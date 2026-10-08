MEGURI SEO 更新版（以 Pasted text(7).txt 為基礎）

上載 index.html 同整個 images 資料夾到現有 GitHub Pages 網站目錄。
本檔案包沒有 thank-you.html：請保留你現有的確認頁及該頁的廣告追蹤程式。

本次修改：
- 搜尋標題、描述及分享文字。
- 七款服務補充文字及四條常見問題；沒有虛構客戶、價格或案例。
- Organization 資料：MEGURI、電話 +85284826854、Instagram meguri.ad。
- 圖片使用完整構圖的 WebP 多尺寸版本，原始 JPEG 保留作後備。
- 修正頁尾無障礙電話標籤。
- 表格成功後以相對路徑前往 thank-you.html，適用 GitHub Pages 子目錄。
- 保留 Formspree mwlpjdjw、Google Ads AW-18497496047 及 WhatsApp 轉換事件；加入點擊跳轉後備機制。

仍待確認：
1. 完整正式網站網址。未加入猜測的 canonical、og:url、og:image、Organization url/logo 或 sitemap。
2. 請在現有 thank-you.html 的 head 加入：
   <meta name="robots" content="noindex">
   不要把 noindex 放到首頁，也不要用 robots.txt 阻止 Google 讀取 thank-you.html。
3. Search Console 擁有權驗證及收錄檢查需在你的帳戶進行。
4. 上載後以手機檢查圖片，並測試表格及 WhatsApp，確認收件與追蹤。

圖片替換：原圖仍使用原來檔名，但新圖需要同時重新產生對應的 WebP 版本。
如果只換 JPEG，請先移除相應 picture 中的 source，否則支援 WebP 的瀏覽器會繼續顯示舊版本。

採用的官方參考：
https://developers.google.com/search/docs/fundamentals/seo-starter-guide
https://developers.google.com/search/docs/appearance/google-images
https://developers.google.com/search/docs/appearance/structured-data/organization
https://developers.google.com/search/docs/crawling-indexing/block-indexing

圖片修正：所有 WebP 已重新產生及逐張解碼驗證；載入失敗時自動回退原始 JPEG。請上載新版 index.html 同整個 images 資料夾。

版面修改：電腦首屏隱藏 MEGURI · VEHICLE ADVERTISING 同首屏兩個查詢按鈕；頂部查詢入口保留。輪播高度跟隨左側文字高度。七款服務改為橫向滑動，支援電腦箭頭、鍵盤及手機觸控。手機首屏保留原有查詢按鈕。
