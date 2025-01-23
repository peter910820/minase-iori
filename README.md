# MinaseIori
## a linebot to query the ranking of MLTD current event
 
伊織醬喵喵小公主Bot(名字不是我取的)

此LINEBOT可用來查詢MLTD榜線，使用說明參見下方指令集。

* 2024/10/5 重構部分程式碼並架設到自己的VPS上(API暫時使用v1)

* 9/12: 
  1. 修正bug，簡化程式碼。
  2. 建立指定排名查詢。
  3. 架設到koyeb(正式版)
* 9/11: 建立榜線查詢
* 9/10: 測試koyeb

## LineBot URL
![URL](https://github.com/peter910820/ioribot/blob/main/QRcode.png)

## 指令集

跟bot聊天時輸入:
```console
event-pt-{名次}
event-hs-{名次}
event-lp-{名次}
```
分別用來查詢當前活動的pt榜以及HighScore榜，若沒有加上 `-{名次}` 會使用預設方式輸出:  
pt榜預設為: 1,2,3,100,2500,5000,10000,25000,50000,100000名  
HighScore榜預設為: 1,2,3,100,2000,5000,10000,20000,100000名  
寮榜預設為: 1,2,3,10,100,250,500,1000名

## 聯繫我

Twitter: https://twitter.com/seaotterMS