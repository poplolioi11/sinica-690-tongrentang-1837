# 同仁堂徵信錄 — 初錄 v0.1.0

1837 年本堂編刊本，Bodleian Libraries, University of Oxford 藏 Sinica 690。這是一份含部分 AI 獨立校讀的初錄資料，並非完整學術定本。現代編輯署名：poplolioi11；歷史編者「同仁堂司事」與現代編輯分屬不同身份。藏有底本不代表館方審核或背書。

初錄涵蓋 140/140 IIIF canvases（包括封面、襯頁和空白，不等於 140 葉）。已整合獨立 AI 校讀 41/140：c001–c034、c071、c115–c119、c138。其餘 99 幅尚未整合獨立覆核；human/expert review: not-run。格式驗證通過不代表逐字正確，也不代表模型一致即正確。

`□` 表示未解字或片段；extent=unknown 時不能當作恰好缺一字。候選不是確讀，不按葉序、語意或算術補字。部分題名、版心和葉碼只剩部件，請連同 certainty、visibility 和疑字證據使用。

檔案：`transcription.json` 保留全部單元、段落、原字序、雙行右後左邊界及位置；`transcription-diplomatic.txt` 只含 in_txt=true 單元，以換頁字元 U+000C 分頁；`transcription.tei.xml` 是 TEI P5 文字投影；`uncertainties.json` 和 `revisions.json` 保留疑字及改訂結果。`transcription-punctuated.json`／`.txt` 僅涵蓋明列序文、條約單元（c005–c021），現代標點為 AI 編輯層，unreviewed，並非全書標點本。

`source-index.json` 列出全部 140 幅來源 URL、雜湊及實際 JPEG 尺寸。註記座標必須依各頁的 annotation frame 解讀；c001、c002 使用歷史縮圖座標，尚無原生像素映射。其他舊註記或四數區域若無已確認映射，明示限制並保留數值，不自行換算。既有 p069 段落 ID 保留；其文本核對後定位於 canvas c071。

底本來源：[Bodleian IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/8c7b5553-81f3-43b5-9d58-e8a61509e6fb.json)。本包不含影像。影像權利為 Photo © Bodleian Libraries, University of Oxford / CC BY-NC 4.0；本包沒有重新授權影像。1837 年原文屬公有領域，不新增使用限制；具著作權的原創編排說明依 CC BY 4.0，詳 LICENSE.md。

版本日期：2026-10-21。本版固定資料快照為 `2026-10-21T01:43:00Z`；後續校訂不在此版。建議引用本書名、版本 v0.1.0、現代編輯 poplolioi11、[本版 DOI：10.5281/zenodo.23523642](https://doi.org/10.5281/zenodo.23523642) 及具體 canvas/seg ID；完整引文資訊見 CITATION.cff。

[Zenodo 本版記錄](https://zenodo.org/records/23523642)；[預定原始資料儲存庫](https://github.com/poplolioi11/sinica-690-tongrentang-1837)。DOI 已為此版預留，將於 Zenodo 發布時註冊；預定儲存庫連結不表示本包已核實其建立狀態。此 DOI 僅識別上述固定初錄版本，不能表示全書已完成獨立校訂。
