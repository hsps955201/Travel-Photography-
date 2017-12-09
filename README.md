# Travel-Photography
### 目的:
* 一開始會想做這個網站的原因是因為本身喜歡攝影，加上常常在fb社團裡看到別人分享的美照卻沒標清楚所在位置或是如何拍攝的技巧。
  為了改善此點，找了一些同樣有攝影興趣的同儕開始著手開發這個網站。

### 構想:
* 前端利用 Bootstrap結合google map，搭配node.js及mongodb，讓地圖上呈現出使用者目前po熱門照片的景點，或是使用者想要分享的攝影技巧。
* 當使用者一登入網站後，會顯現出附近的熱門照片
 而目前規劃是將使用者照片以限時照片或作品集儲存，仍持續開發中，最終會開發成手機app。

### 網頁開發簡介
>* 目前是設計讓使用者用fb登入，在index.html頁面會顯示目前熱門景點，旁邊拉條有其他連結功能，也可點擊左上角上傳照片。
>
>![](https://i.imgur.com/lwRlxkv.png)
>
>(index.html頁面)

>* 在upload頁面，使用者選擇照片，填入欄位所需資訊。在這裡最重要的地方就是選擇是”即時影像”或是”作品集”。
即時影像目前設計會讓他在24小時內消失，會有這種設計是因為有些景色(如日出，星空…等)諸如此類有時效性的景色，可能不久就消失了，所以特別分類出來。
>
>![](https://i.imgur.com/MVSLwB8.png)
>(upload.html頁面)

* 在map.html上可看到其他使用者分享的攝影點。
>
>![](https://i.imgur.com/rF3zm6t.png)
>(map.html頁面)

>* 可從map.html頁面看到其他使用者分享的攝影點，目前測試中，故尚未加上照片。
>
>![](https://i.imgur.com/qjxtVf8.png)
>(map.html頁面)

>* 進入mongodb可以查詢使用者照片資訊
>
>![](https://i.imgur.com/yBTb1yr.png)
>(mongodb所存之使用者相片資訊，分Live及Your_story)

