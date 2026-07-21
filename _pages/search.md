---
layout: page
title: Search
permalink: /search/
description: Site search
nav: false
nav_order: 11
pagefind: false
---

<div id="search"></div>

<link href="/pagefind/pagefind-ui.css" rel="stylesheet">

<script>
  window.addEventListener("DOMContentLoaded", () => {
    import("{{ '/pagefind/pagefind-ui.js' | relative_url }}")
      .then(() => {
        new PagefindUI({
          element: "#search",          // 這裡要對應上面的 div id
          bundlePath: "{{ '/pagefind/' | relative_url }}", // 指向索引資料庫的路徑
          showImages: true,            // 是否在搜尋結果顯示圖片
          showSubResults: true,        // 是否顯示內文的小標題結果
          exact: false,                 // 啟用精確匹配
          // mergeIndex: ["en", "zh"],    // 合併多個語言索引

          // ⭐ 只在「超過一個單字」時自動轉為短語搜尋
          processTerm: (term) => {

            const trimmed = term.trim();

            // 空字串不處理
            if (!trimmed) return trimmed;

            // 若使用者已自行加上雙引號 → 不處理
            if (/^".*"$/.test(trimmed)) {
              return trimmed;
            }

            // 若包含進階搜尋語法 → 不處理
            if (
              trimmed.includes(" OR ") ||
              trimmed.includes("-")
            ) {
              return trimmed;
            }

            // 若超過一個單字 → 自動加引號
            const wordCount = trimmed.split(/\s+/).length;

            if (wordCount > 1) {
              return `"${trimmed}"`;
            }

            return trimmed;
          },

          translations: {
            placeholder: "輸入關鍵字進行搜尋...",
            clear_search: "清除",
            load_more: "載入更多結果",
            search_label: "站內搜尋",
            filters_label: "篩選",
            zero_results: "找不到與 [SEARCH_TERM] 相關的內容",
            many_results: "找到 [COUNT] 筆關於 [SEARCH_TERM] 的結果",
            one_result: "找到 1 筆關於 [SEARCH_TERM] 的結果",
            alt_search: "找不到 [SEARCH_TERM] 的結果。改為顯示 [DIFFERENT_TERM] 的結果",
            search_suggestion: "找不到 [SEARCH_TERM] 的結果。試試看搜尋以下詞彙：[SUGGESTIONS]",
            searching: "搜尋 [SEARCH_TERM] 中..."
          }
        });  
      });

  });
</script>

<style>
  /* ===== 搜尋容器 ===== */
  #search {
    min-height: 400px;
    margin-top: 1rem;
  }

  /* ===== 整體 UI 繼承 al-folio ===== */
  .pagefind-ui {
    --pagefind-ui-font: var(--global-font-family);
    --pagefind-ui-primary: var(--global-theme-color);
    --pagefind-ui-text: var(--global-text-color);
    --pagefind-ui-background: var(--global-bg-color);
    --pagefind-ui-border: var(--global-divider-color);

    font-family: var(--global-font-family);
    color: var(--global-text-color);
  }

  /* ===== 搜尋輸入框 ===== */
  .pagefind-ui__search-input {
    background-color: var(--global-bg-color);
    color: var(--global-text-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 0;
    padding: 0.6rem 0.75rem;
    font-size: 1rem;
  }

  .pagefind-ui__search-input:focus {
    outline: none;
    border-color: var(--global-theme-color);
    box-shadow: none;
  }

  /* ===== 結果統計文字（找到 X 筆） ===== */
  .pagefind-ui__message {
    color: var(--global-text-color);
    font-size: 0.95rem;
    margin-bottom: 1rem;
  }

  /* ===== 單筆結果區塊 ===== */
  .pagefind-ui__result {
    padding: 1rem 0;
    border-bottom: 1px solid var(--global-divider-color);
  }

  /* ===== 結果標題 ===== */
  .pagefind-ui__result-link {
    color: var(--global-theme-color) !important;
    font-weight: 600;
    font-size: 1.1rem;
    text-decoration: none;
  }

  .pagefind-ui__result-link:hover {
    text-decoration: underline;
    opacity: 0.85;
  }

  /* ===== 結果摘要內文 ===== */
  .pagefind-ui__result-excerpt {
    color: var(--global-text-color);
    font-size: 0.95rem;
    line-height: 1.6;
    margin-top: 0.3rem;
  }

  /* ===== 搜尋關鍵字高亮 ===== */
  .pagefind-ui mark {
    background-color: var(--global-theme-color);
    color: var(--global-bg-color);
    padding: 0 0.2rem;
  }

  /* ===== 載入更多按鈕 ===== */
  .pagefind-ui__button {
    background: transparent;
    color: var(--global-theme-color);
    border: 1px solid var(--global-theme-color);
    padding: 0.4rem 0.9rem;
    border-radius: 0;
    font-size: 0.9rem;
  }

  .pagefind-ui__button:hover {
    background-color: var(--global-theme-color);
    color: var(--global-bg-color);
  }

  /* ===== 移除 Pagefind 預設圓角卡片風格 ===== */
  .pagefind-ui__result,
  .pagefind-ui__search-input,
  .pagefind-ui__button {
    box-shadow: none;
  }
</style>
