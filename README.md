# 約瑟夫《駁阿比安》希臘文–中文對照本
# Flavius Josephus, *Against Apion* — Greek Text with Chinese Translation

一個單檔網頁閱讀器，並排呈現弗拉維奧．約瑟夫《駁阿比安》（*Contra Apionem*）的希臘原文（Niese 校勘本）與完整中文譯文。
A single-file web reader presenting the Greek text of Josephus' *Against Apion* (Niese edition) side by side with a complete Chinese translation.

## 功能 Features

- **希臘文與中文逐節對照**：以尼斯（Niese）節數為單位並排顯示；窄螢幕上中文置於希臘文之下，每段均標示節數。
  Greek and Chinese aligned section by section (Niese numbering); on narrow screens the Chinese follows the Greek, each paragraph carrying its section number.
- **雙重編號導覽**：可按卷、尼斯編號及惠斯頓（Whiston）分段選擇，並以 ‹ › 前後翻閱；版面仿照 [PACE](https://pace.biblico.it/) 的《駁阿比安》頁面。
  Navigation by book, Niese section and Whiston section, with previous/next buttons; layout modelled on the PACE *Against Apion* page.
- **詞形連結**：點擊任何希臘文（或拉丁文）字詞，即在 [Perseus Digital Library](https://www.perseus.tufts.edu/) 開啟該詞的詞形分析及詞典釋義。
  Every Greek (or Latin) word links to its morphological analysis and lexicon entry at Perseus.
- **匯出 txt**：可匯出本段、本卷、全書或自訂尼斯範圍；內容可選希臘文、中文或兩者。
  Export the current passage, a whole book, the whole work, or a custom Niese range as a `.txt` file — Greek, Chinese, or both.
- **可分享的連結**：每個惠斯頓分段有獨立網址，例如 `index.html#b1-w8`、`index.html#b2-w17`。
  Each Whiston section has its own link, e.g. `index.html#b1-w8`.
- **淺色／深色模式**：自動跟隨系統設定。
  Light and dark themes follow the system setting.

## 使用方法 Usage

此專案為單一靜態 HTML 檔，無需建置步驟。
The project is a single static HTML file; no build step is needed.

1. 將 `index.html` 與 `README.md` 放入 GitHub 儲存庫。
   Put `index.html` and `README.md` in a GitHub repository.
2. 於儲存庫的 **Settings → Pages** 中，選擇 **Deploy from a branch**，分支選 `main`，資料夾選 `/ (root)`。
   In **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. 數分鐘後即可於 `https://<用戶名>.github.io/<儲存庫名>/` 瀏覽。
   After a few minutes the page is live at `https://<username>.github.io/<repository>/`.

亦可直接在瀏覽器中開啟本機的 `index.html`。頁面需要網絡連線以載入 Google Fonts（Noto Serif TC、Gentium Book Plus）及開啟 Perseus 連結；離線時會使用系統字型。
You can also open `index.html` locally. An internet connection is used for Google Fonts and the Perseus links; offline, system fonts are used.

## 文本來源 Sources

- **希臘文 Greek**：Benedikt Niese, *Flavii Iosephi opera*, vol. 5 (Berlin: Weidmann, 1889)。數碼文本取自 Perseus Digital Library 的 [PerseusDL/canonical-greekLit](https://github.com/PerseusDL/canonical-greekLit)（`tlg0526.tlg003.perseus-grc2.xml`），以 CC BY-SA 4.0 授權發佈。
  Digital text from PerseusDL canonical-greekLit, licensed CC BY-SA 4.0.
- **拉丁文 Latin**：第二卷第51節後半至第113節前半的希臘原文已佚，Niese 本以古拉丁譯本補足；本頁照錄，並以斜體標示。
  Book 2 §51b–§113a survive only in the old Latin version, reproduced as in Niese and shown in italics.
- **中文譯文 Chinese**：據上述 Niese 希臘文本（拉丁部分據古拉丁譯本）逐節直接譯出。
  Translated section by section directly from Niese's Greek (and from the Latin for the Latin-only portion).

## 翻譯說明 Translation Notes

- 譯文力求貼近原文；方括號［］內為 Niese 所標示的存疑文字，或譯者對訛誤、脫漏之處的說明。
  The translation stays close to the original; square brackets ［］ mark words Niese brackets as doubtful, or the translator's notes on corruptions and lacunae.
- 聖經人物及地名採用《和合本修訂版》（和合本2010）譯名。
  Biblical names of persons and places follow the Revised Chinese Union Version (RCUV, 2010).
- 除少數常見名詞（如摩西、耶路撒冷、埃及、希臘人等）外，專名及術語在譯文中每次出現均附英文，例如：伊西斯 (Isis)。
  Apart from a few common names (Moses, Jerusalem, Egypt, Greeks, etc.), proper names and technical terms carry their English form in brackets at each occurrence, e.g. 伊西斯 (Isis).
- 卷首的希臘文書名保留原文，不另附中文。
  The Greek book headings are kept in Greek without a Chinese rendering.

## 授權 License

本頁所含希臘文數碼文本源自 Perseus Digital Library，以 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 授權。由於本作品包含並改編該文本，整體內容（希臘文、中文譯文及頁面）亦以 **CC BY-SA 4.0** 授權發佈：可自由分享及改編，但須註明出處，並以相同授權方式分享。
The Greek digital text comes from the Perseus Digital Library under CC BY-SA 4.0. Because this work incorporates and adapts that text, the whole (Greek text, Chinese translation and page) is released under **CC BY-SA 4.0**: you may share and adapt it with attribution, under the same license.

建議引用格式 Suggested attribution：

> 弗拉維奧．約瑟夫《駁阿比安》希臘文–中文對照本。希臘文：B. Niese (1889)，Perseus Digital Library（CC BY-SA 4.0）。中文譯文：［譯者／整理者姓名］。CC BY-SA 4.0。

## 致謝 Acknowledgements

- Perseus Digital Library, Tufts University — 希臘文數碼文本及詞形分析工具 / Greek digital text and morphology tools.
- PACE (Project on Ancient Cultural Engagement) — 版面參考 / layout reference.
- 中文譯文在 Claude（Anthropic）協助下完成。/ The Chinese translation was prepared with the assistance of Claude (Anthropic).

## 檔案結構 Files

```
index.html   閱讀器（單一檔案，含全部希臘文、拉丁文及中文）/ the reader (single file with all texts)
README.md    本說明 / this file
```
