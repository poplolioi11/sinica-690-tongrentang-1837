# 同仁堂徵信錄 — 全140幅 AI 校訂版 v0.2.0

## 摘要 / Abstract

本資料集以牛津大學Bodleian Libraries藏Sinica 690、清道光十七年（1837）《同仁堂徵信錄》原圖為底本，提供全140幅的AI校訂資料，供清代慈善史料定位、檢索與後續校訂。v0.2.0完成初錄、獨立AI來源讀錄、逐段比較及回圖裁定，保留原字、單元ID、欄序、讀序、疑字候選、未知長度缺損與訂正歷史；公開JSON、TXT、TEI及相關紀錄。人工及專家覆核尚未執行，有限標點層亦未獨立覆核，故不構成人工學術定本或已測量逐字準確率的版本。

This dataset provides AI-corrected transcription data for all 140 images of Bodleian Libraries Sinica 690, the 1837 《同仁堂徵信錄》, for locating, retrieving and further correcting historical charity records. Version 0.2.0 completes initial transcription, independent AI source reading, passage comparison and source-image adjudication. Public JSON, TXT, TEI and supporting records retain original characters, unit IDs, column and reading order, uncertain candidates, unknown-length damage and revision history. Human and expert review have not been performed, and the limited punctuation layer remains independently unreviewed. This is therefore not a human-reviewed scholarly definitive edition or a version with measured character accuracy.

1837年本堂編刊本，Bodleian Libraries, University of Oxford 藏 Sinica 690。全140幅來源畫布均有初錄及獨立AI來源讀錄、逐段比較與影像裁定；human/expert review: not-run。這是 AI 輔助校訂成果，仍保留疑字候選，未經人類專家覆核，不能視為人工學術定本。歷史編者同仁堂司事與現代編輯 poplolioi11 身份不同；館藏不表示館方背書。

範圍為140個IIIF canvases，包括封面、襯頁、空白及正文，不等於140葉。本次固定快照：`2026-10-21T04:26:15.997888+00:00`。保留1518個單元、4144個segments、570筆UNC及947筆REV。校讀覆蓋率不是逐字準確率，兩次一致亦不是字形證據。

`□`可表示一個字位或未知長度片段；`extent=unknown`不能當作恰缺一字。候選不是確讀，不能用文意、金額算術或頁序補字。現有segments含743個□位置；278筆有效UNC標為unknown extent，兩數均不等於未識別歷史字數。詳 `COLLATION.md`。

`transcription.json`保留原字序、ID、雙行右後左界線及完整裝置；`transcription-diplomatic.txt`只輸出in_txt=true單元，以U+000C分頁。TEI為有原ID、來源參照及unknown-extent標記的文字投影；更完整的座標、候選與改訂理由在JSON。`uncertainties.json`、`revisions.json`保留現行與歷史讀法，歷史提案不能當作現行定讀。

`transcription-punctuated.json`／`.txt`僅涵蓋明列的c005–c021序文、條約單元；現代標點仍unreviewed，並非全書標點本。

`source-index.json`列全部140幅來源URL、SHA-256、實際JPEG尺寸及manifest尺寸。註記座標依其原有frame解讀；c001/c002歷史縮圖與原生JPEG的映射未建立，不得自行換算。p069原segment ID保留，文本定位於c071。來源：[Bodleian IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/8c7b5553-81f3-43b5-9d58-e8a61509e6fb.json)。本包不含來源影像、裁圖、程式或操作紀錄。

版本日期：2026-10-22。本版 DOI：[10.5281/zenodo.23524909](https://doi.org/10.5281/zenodo.23524909)；[Zenodo 本版記錄](https://zenodo.org/records/23524909)。此 DOI 在製包時已為 v0.2.0 預留，註冊於 Zenodo 公開發布時生效；這是製包當時的 metadata 狀態，實際公開與登記狀態以記錄頁為準。引用時請列本書名、版本 v0.2.0、現代編輯 poplolioi11、本版 DOI 及 canvas/segment ID；完整資訊見 `CITATION.cff`。

先前初錄 v0.1.0 的 DOI 為 [10.5281/zenodo.23523642](https://doi.org/10.5281/zenodo.23523642)，只識別該初錄版本（140幅初錄、41幅獨立AI校讀），不識別本版。[既有儲存庫](https://github.com/poplolioi11/sinica-690-tongrentang-1837)；GitHub v0.2.0 release 在製包時尚未發布。

歷史原文公有領域；具著作權的原創編輯文檔採CC BY 4.0。Bodleian來源影像另有CC BY-NC 4.0條款且未收入包內，詳 `LICENSE.md`。格式驗證不構成人工專家認證。

製包沿用已核驗 r2 文字快照；該次修訂僅修順44處版面說明殘句，正文、疑字、讀字候選、來源定位及校讀範圍不變。本次正式化僅更新版本與 DOI 等公開 metadata。
