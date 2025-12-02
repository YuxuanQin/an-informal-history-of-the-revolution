# 《解放別錄》重排本

## 讀 pdf 請[點我](./an-informal-history-of-the-revolution.pdf)！

本自述文件只記錄重排的技術細節，至於本書之內容與價值，敬請參看本書之“重排者前言”。

- 排版引擎：Typst；
- 流程：
  + 首先，從[安娜的檔案館（Anna's Archive）](https://annas-archive.li)處搜索本影印本並下載；
  + 其次，使用開源的 [pdftk](https://gitlab.com/pdftk-java/pdftk) 軟件對原影印本裁剪（命令爲 `pdftk 文件名 cat 頁碼範圍 output 輸出名`），十頁一份，共裁得四份。（十頁一份，乃是因爲下文的免費 OCR 服務只支持一次十頁。）
  + 再次，使用網上好心人搭設的[豎排書 OCR 服務](https://ocr.wdku.net/index_shupai)提取文本。
  + 最後，開始校讀！
