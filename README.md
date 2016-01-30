# 2016 總統大選觀測介面

## 簡介

由於有做政治工作的朋友委託要很細致分析 2016 總統立委大選的資料，於是 fork TonyQ 大大的 crawler，  
然後做一些錯誤校正，製作出這個最小以里為單位的觀測介面，
可以看各個縣市、區、里的總統、立委、政黨票以及投票率分佈，  
比起一堆電視名嘴跟名調公司做的大方向分析，細部的看這些結果意外的有很多趣味喔呵呵～  

一些戲謔的文字敘述是個人愛好呵呵~  
這個介面還會根據朋友的需求慢慢擴大。  

## 環境
node.js  
需安裝 bower(npm 指令：`sudo npm i bower -g`), mongodb(ubuntu 指令：`sudo apt-get install mongodb`)  

## 安裝與執行

以上環境確定 ok 之後，解壓縮 data 的壓縮檔案  
然後 `mongorestore dump/` 把資料輸入到資料庫  
`npm i;bower i` 安裝必要的 package  
`npm start` 啟動 server 並打開瀏覽器 port 3000 來觀看頁面

