# CKAN contribution

## Issue
- “Good for Contribution” 可以看見所有值得貢獻開發的點子
- 不適用詢問使用問題
- 回報錯誤（Bug Report）
    - 明確描述遇到的問題。
    - 附上錯誤訊息、步驟、瀏覽器環境、系統版本等重現條件。
    - 建議附上 log 或截圖。
- 提出新功能建議（Feature Request）
    - 說明你需要什麼功能，以及它的用途或解決了什麼問題。
    - 若為大型架構修改，應轉往 ckan/ideas-and-roadmap。
- 文件錯誤或不清楚的地方
    - 例如某段教學說明不完整或有誤。
    - 可簡要說明想改進的地方或提出補充。

## Pull Request
- 你已經完成一項明確的更動
    - 如：修復 bug、新增功能、改進文件。
    - 更動要與某個已知 Issue 對應（若有的話）— PR 標題或 commit message 中要標記 Issue 編號。
- 每次 PR 只做一件事
    - 一個功能修補、一份文件改進、一個設定新增。
    - 保持 PR 聚焦且易於審查。
- 你完成以下所有前置準備：
    - 已更新對應測試（或新增測試）。
    - 已更新對應文件（如果功能變動）。
    - 所有測試通過。
    - 遵守 CKAN 的 commit message 規範與程式碼風格。
- 目標分支為 master
    - 除非 maintainer 指定要送到特定版本分支。

## Else
- Commit message
    - 用 祈使句（imperative mood），例如：
        - Add tutorial for custom plugins
        - Fix broken Solr query in search page
    - 若有對應 issue，必須加上如 [#123] 的標示。
        - [#456] Update API docs for search endpoint
- Document writing
    - Overview：為什麼有這功能？用途？背景概念。
    - Tutorials：怎麼設定？怎麼用？步驟導引。
    - Reference：有什麼參數？API 方法？設定檔選項。
    - Troubleshooting：出錯怎麼辦？FAQ 有什麼？
- 寫作風格
    - 長度、被動主動語句的規範、一致性(用「command line」而不是「command-line」)