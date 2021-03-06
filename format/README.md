# 格式

編輯格式的設計，將焦點放在「簡潔易用」與「易讀性」。

GitBook 使用 Markdown 這種輕量級標記語法作為編輯格式的設計基礎。

在包含實際內容的檔案之外，GitBook 添加了一些額外的參照檔：

* [README](format/introduction.md)：一本書的介紹文字。
* [SUMMARY](format/chapters.md)：定義章節的架構與順序。
* [LANGS](format/languages.md)：多種翻譯版本的設定。
* [GLOSSARY](format/glossary.md)：詞彙表與定義描述。

除了內容檔案外，一本書至少需要添加 `README` 與 `SUMMARY` 這兩個檔案。


## 譯者補充說明

### 關於 Git 與 GitHub

這是一種目前程式開發者很習慣的「版本管理系統」，簡單的說就是會儲存你的內容修改與編輯歷程，讓你有機會比較甚至回復到之前修改過的某個時間點，但原則上你必須在修改到一定程度後明確的「儲存」並讓系統知道這是一個需要紀錄的過程版本。[GitHub](https://github.com) 則是目前全世界最大、被程式設計師廣泛使用的 Git 線上服務。

GitBook 支援兩種模式：使用 GitBook 自己的倉儲系統，或是導入你擺在 GitHub 上面的專案。對一般不熟悉 Git 系統的用戶來說，直接在 GitBook 上開啟一個書籍專案，持續使用它提供的編輯器書寫與編輯，就不用太在意這個在背後持續保護你的內容的底層機制，只要記得儲存就好。

### 關於目錄與檔案

GitBook 可以作為一種「持續出版」的工具，因為你可以在專案目錄下，擺放各種狀態的文件：研究資料、參考書摘，以及章節還在進行中的草稿，只要不將這些檔案對應寫進 SUMMARY.md 文件中，GitBook 就不會在轉製時包含進去。

你可以在寫完前言、第一章時，就先修改 SUMMARY.md 檔案讓它只包含這些完成的部分，製作出來的書籍就很像是「試讀本」。你也可以用上面的格式預先展示目錄（書籍的架構與未來會撰寫的章節計畫），但不要賦予實際的檔案連結（畢竟你還沒有寫完對嗎？）。
