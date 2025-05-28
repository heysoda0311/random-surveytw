# random-survey
會隨機派發問卷（或你想要的網址們）的入口

## 介紹
有些時候，我們會有需要隨機派發不同版本問卷的需求，或是要讓使用者隨機前往其中一個網址。這時候就可以讓這個小專案來幫忙。

## 使用方式
在 [`url.js`](url.js) 中填入自己想要隨機派發的問卷網址們（注意頁面上提示的規則），其他檔案不須更動。

之後將 `index.html` 作為入口發布，當使用者進入時就會由程式隨機抽出其中一個網址並將使用者重新導向過去。

### 教學文
不才寫的一篇簡單教學文──[〈隨機分配問卷？讓 Github Pages 幫你吧！〉](https://hms5232.medium.com/%E9%9A%A8%E6%A9%9F%E5%88%86%E9%85%8D%E5%95%8F%E5%8D%B7-%E8%AE%93-github-pages-%E5%B9%AB%E4%BD%A0%E5%90%A7-764372f26cd9)，懇請各方斧正。

### 有問題？

請先看[常見問題](https://github.com/hms5232/random-survey/discussions/9)一文，如果沒辦法解決問題的話，可以至本專案的 [discussions Q&A 分類](https://github.com/hms5232/random-survey/discussions/categories/q-a)底下看看是否有人碰過相同問題。

如果上述步驟都無法解決，請至本專案的 [discussions](https://github.com/hms5232/random-survey/discussions) 新增一則 Q&A 發問，問題得到解答後也請記得把答案 `mark as answer` 讓其他有相同問題的人後來可以找到答案。

### 範例
![GitHub deployments](https://img.shields.io/github/deployments/hms5232/random-survey/github-pages)

本儲存庫的 Github Pages 將會依照 `url.js` 隨機將使用者導向本人的 Github 或 GitLab 等地方。👇  
https://hms5232.github.io/random-survey/

## 鳴謝
本專案係參考[〈【html javascript】隨機分配問卷〉](http://g23988.blogspot.com/2015/08/html-javascript.html)之概念改寫而成。感謝前人大大的無私分享。

## 其他版本
### GitLab 🦊
如果比較喜歡 GitLab 或有什麼原因偏好 GitLab，也可以參考 GitLab Pages 的版本：https://gitlab.com/hms5232/bird-screen-url

## LICNESE
See [LICENSE file](LICENSE).
