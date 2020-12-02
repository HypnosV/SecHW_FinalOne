# SecHW_FinalOne

## 助教批改回覆 (2020-11-28)

以下提供一些修改建議:

HTML:

- img 標籤記得補上後方的 alt 的敘述哦，這樣當圖片無法正常載入時，才會有替代的文字顯示，讓使用者知道這裡原本圖片的意義
- 「個人資料」的結構建議改為

```
<ul>
  <li>
   <p>陳久安...<br>1997...<br>應屆畢業生</p>
  </li>
  <li>
   <p>UI 設計...<br>獨立接案...<br>品牌規劃...</p>
  </li>
</ul>
```
-「學歷」建議使用 ul>li 的結構
-「工作經驗」的每一項建議用 h3 標籤來包住
-「聯絡方式」的信箱和電話，可以使用 emmet 語法，讓使用者點擊便可寄送 email 或撥打電話

```(ex: a:mail -> <a href="mailto:"> 和 a:tel -> <a href="tel:+">)```

-最下方的三個 icon 建議使用 ul>li>a>img 的結構哦

CSS:
- 各大區塊的間距是 72px ，可以再調整哦
    
----

2020-11-28 已同步程式碼至 Copepen

----

## 助教批改回覆 (2020-11-30)

1. .contact 的信箱、電話、地址、作品連結這邊也建議使用 ul>li 的結構。
2. 作品連結也可以再用 a 標籤包住，讓他有連結的效果。
3. 相似的 CSS 設定，建議可以用逗號將 class 名稱隔開，並統一做設定 (ex: .profile, .education, .experience {margin-bottom: ...})，可以讓程式碼更簡潔。

---
以上建議已調整同步至 [GitHub Repo](https://github.com/KS-VC/SecHW_FinalOne)，並建立 [GitHub Pages](https://ks-vc.github.io/SecHW_FinalOne/)。

---
