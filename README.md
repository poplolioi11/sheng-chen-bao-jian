# 升沉寶鑑（DRS 428685410） / Sheng chen bao jian: Transcription Dataset

底本為哈佛燕京圖書館藏本 DRS 428685410，索書號 RAREB TA 1980.2/2470.4。內題葉並列光緒十六年與西曆一千八百九十年，刊記為山東濟南府藏板。 [館目](https://id.lib.harvard.edu/alma/990094320560203941/catalog) · [固定掃描](https://commons.wikimedia.org/w/index.php?oldid=1293876346) · [館藏 IIIF](https://iiif.lib.harvard.edu/manifests/view/drs:428685410)

《升沉寶鑑》是秀華陽著的一卷晚清漢文基督教勸世書，底本為光緒十六年（1890）山東濟南府藏板刊本。原書從安然辭世、敬酬帝恩與修求真福談起，繼而以賞善罰惡說明天道，分節論述上帝的能力、知識、公義與仁愛。末節徵引《書》《易》，並列中國與西方著述，藉以申論作者所理解的天道。這些段落呈現晚清漢文基督教著述如何借用既有經典語彙，討論信仰、道德行為與人的終局。

本資料集以哈佛燕京藏本 DRS 428685410 為底本，共取 34 幅固定影像，其中 27 幅用於轉錄正文，提供 JSON、TXT、TEI 和逐項覆核紀錄。此版為 AI 校讀稿，421 項比對中保留 125 項未解。補充覆核另留 1 處疑讀。人工全文二校待完成。

Sheng chen bao jian (Mirror of Progress & Ruin, as annotated on the cover) is a one-volume late Qing Chinese Christian tract by Xiu Huayang (Francis Huberty James). The source edition was printed in Jinan Prefecture, Shandong, in 1890. The work opens with dying in peace, responding gratefully to God’s grace, and cultivating true blessings. It treats the rewarding of good and the punishment of evil as evidence of the Way of Heaven, then discusses God’s power, knowledge, justice, and benevolence. The closing section cites the Book of Documents and the Book of Changes and draws on Chinese and Western writings to make the author’s case about the Way of Heaven. The tract shows how late Qing Christian writers in Chinese could use the vocabulary of the classics to discuss faith, moral conduct, and human destiny.

This dataset uses 34 fixed images from Harvard-Yenching Library DRS 428685410. The main text is transcribed from 27 pages. The AI-reviewed JSON, TXT and TEI transcription retains 125 unresolved comparison items. A further 1 reading(s) flagged in supplemental review remain open. Full human collation is outstanding.

序文首幅明印「秀華陽著」。封面後加手題為 “Mirror of Progress & Ruin”。 [日文研究所收館藏書目第 220 筆](https://www2.kansai-u.ac.jp/shkky/wakumon/no-07/wakumon7_3_li%20xiaojie.pdf)

## 資料與校讀

- data/document.json 保留歷史文字、原圖位置、疑讀與缺口。
- data/text.txt 與 data/text.tei.xml 為全文與 TEI，附文字單位的對應檔。
- data/review.json 保留 421 項比對、125 項未解及採用紀錄。
- data/manifest.json 與 PACKAGE-SHA256SUMS.txt 記錄固定發行的檔案雜湊。

底本34幅。p002扉頁，p003–p004為序，p005–p031為正文，p003–p032保存可見版心葉碼。後加館記、透印與末尾無正文幅按實見範圍記錄。

The 34 fixed images include the title leaf, preface in p003–p004, and body in p005–p031. Visible original folio numbers in p003–p032 have a separate layer.

初錄與第二路讀稿各以同一批固定原圖為據。Claude 完成第 1–34 幅初錄與第 1–34 幅第二路讀稿。Claude 依原圖覆核 421 項比對。程式列出的 421 項比對均有逐項紀錄。採入 22 項有影像依據的更正，保留未解位置與候選。另有 21 項異讀保留原讀及候選。程式驗收確認公開 JSON、TXT 和 TEI 的逐欄內容一致。TEI 通過 P5 4.12.0 Relax NG。人工全文二校、專家審定和準確率量測待完成。

The two independent readings used the same fixed source images. Claude produced the first reading for images 1–34 and the second reading for images 1–34. Claude reviewed 421 comparison items against the images. The dataset records 421 comparison items. The edition incorporates 22 corrections supported by the images. The initial readings and alternatives remain recorded for 21 further proposed changes. Automated validation confirmed that the transcription content agrees column by column across JSON, TXT and TEI. The TEI passed P5 4.12.0 Relax NG validation. Full human collation, expert assessment and accuracy measurement are outstanding.

## 權利與引用

歷史原文及忠實轉錄按公有領域狀態提供。新增且受著作權保護的說明與整理編排採 CC BY 4.0。 [權利說明](LICENSE.md)

曲宸宇（Chu, Chen-Yu）。2026。升沉寶鑑（DRS 428685410） / Sheng chen bao jian: Transcription Dataset。v0.2.0。資料集。 [固定發行](https://github.com/poplolioi11/sheng-chen-bao-jian/releases/tag/v0.2.0) · [ORCID](https://orcid.org/0009-0003-9738-6914)
