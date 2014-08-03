title: PTT Efficient Poster
date: 2007-11-06
tags:
- programming
- software
---

![screenshot](https://raw.githubusercontent.com/changyuheng/ptt-efficient-poster/master/screenshot.png)


在PTT上發表文章，會依文章長度得到相當的稿酬；而稿酬的單位就是所謂的 P 幣。然而，PTT 判斷一篇文章值多少 P 幣，不只看總字數，還會計算使用者輸入的次數。現在公認的稿酬計算公式是，每 2 秒輸入 2 個中文字獲得 1 元，某些特殊字元或重複字不列入計算。因此，使用新注音等一次輸入好幾個字的輸入法輸入文字，相較於其他逐字輸入的輸入法，PTT 偵測到的輸入次數會少很多，換句話說稿酬也少很多。

這套軟體可以幫您把一整篇文章，在背景逐字輸入到 PCMan 視窗中。在字與字之間，會自動加入經過計算的最佳延遲時間並取消重複字之間的延遲，讓您的文章能得到該文所能得到的最高稿酬。網路上有好幾種不同的軟體能自動輸入文章，但是這些軟體多半不能在「背景運行」，也不能支援控制碼或雙色字。

※所謂的「背景運行」，係指 PCMan 視窗不必在最上層，軟體也能自動輸入文章；亦即貼文時，還可以做其他的事。


**特色**

1. 支援 BBS 控制碼。
2. 支援雙色全形字（一字雙色）。
3. 支援 Big-5 擴充字集（支援 Unicode 補完計畫內的日文字）。
4. 支援背景運行。
5. 支援暫停。


**使用方式**

1. 修改 PTT 設定
    <pre>
    ‧ 修改 PTT 站台設定如下：
    　　(U)ser 【 個人設定區 】
    　　　(U)Customize 個人化設定
    　　　　i. DBCS 自動偵測雙位元字集(如全型中文)　　　　：是
    　　　　j. DBCS 忽略連線程式為雙位元字集送出的重複按鍵：是
    　　　　k. DBCS 禁止在雙位元中使用色碼(去除一字雙色)　：否
    </pre>
2. 複製欲張貼的文章到剪貼簿。（可在記事本中先排版好再複製，也可複製 PCMan 的 ANSI 編輯器中的彩色文字。）
3. 進入發文狀態。
4. 按下 Shift + F10 開始張貼。

* * *

* 開始張貼後，可以切換到別的視窗做其他事，唯獨不可以在 PCMan 中另開新分頁。
* 張貼完成後程式會自動彈出提示視窗。
* 欲暫停張貼，請按 Shift + F11。在工作列圖示的選單中取消暫停即可繼續貼文。
* 欲取消張貼，請按 Shift + F12 重新載入本程式，或關閉本程式


[**[下載](https://raw.githubusercontent.com/changyuheng/ptt-efficient-poster/master/PTTEfficientPoster.exe)**]
[**[原始碼](https://github.com/changyuheng/ptt-efficient-poster)**]

作業系統：Windows 2000 / XP / Vista / 7 32-bit & 64-bit
※ 只能在 PCMan 使用
