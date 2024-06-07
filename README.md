今日複習的 SCSS 用法為：

（共同）變數的使用：前面先宣告 $變數名稱: 值; 後面直接這樣使用 $變數名稱 。
拆多個 .scss 檔，讓 CSS 更加容易管理及閱讀：
  1.將 CSS 內容依據功能，拆成多支 _檔名.scss 檔案
  2.create 一個 all.scss (也可以叫別的名稱)，裡面寫 @import "檔名";
  3.(須與第一點的檔名一致)

存檔後，Prepros 即會在 css 資料夾產生一個 all.css 的檔案

note:
Prepros 我是用 watch scss 展開