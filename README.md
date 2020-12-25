# TOC Project--Billboard hot
*Access Music More Easily!!*
## Introduction
* A Line chat bot based on a finite state machine.
* 由於Billboard音樂排行在音樂的評比中算是最具指標性的排行，所以透過傳送Billboard當週Hot 100相關音樂及資訊來讓人們可以接近音樂及了解現在的音樂潮流，並去除掉上瀏覽器搜尋的步驟，使得音樂更輕易接近
## Join Billboad Hot
掃描QR Code或是輸入ID
![](https://i.imgur.com/xcZj1G7.png)
## How to Use
1. **輸入"help"**
    顯示使用提示
    ![](https://i.imgur.com/YX5WlcU.jpg)
2. **輸入"hotlist"**
    傳送當週Billboard the Hot 100 Chart的連結
3. **輸入"recomendation"**
    傳送小編本週私心推薦歌曲連結
    ![](https://i.imgur.com/VGxXWEF.jpg)
4. **輸入"hot num"**
    傳送Billboard當週該排行的歌曲
    ![](https://i.imgur.com/1TBScEd.jpg)
4. **輸入"introduction"**
    傳送Billboard當週排行冠軍的歌曲相關介紹
    ![](https://i.imgur.com/rFErfEV.jpg)
## FSM
![](https://i.imgur.com/V5JndOj.png)
## Explain on Code
* **app.py** 
    main program
* **fsm.py** 
    建構FSM，各state的進入條件及state內要完成的動作
* **utils.py**    
    line message API
* **drawing.py**    
    用來獨立畫出此FSM的Graph
    


    



