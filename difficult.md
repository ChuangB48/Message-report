# 過程中遇到的困難
## login
### username的輸入框不知道如何美化
* 最後用淡淡的藍色影子解決，低調一點。
### username can't be empty出現與消失單用css無法控制
* 使用javascript控制。
### 煙火置中
* 把煙火放在`<div>`裡面定位。
## message
### 判斷是否為自己的訊息
* 記住名字和打的訊息，兩個都符合就判定為自己的訊息。
### 傳送照片
* 讀成base64格式。
### 影片檔案太長，讀成base64後傳不出去
* 每次傳十萬左右個字，分好幾次傳。
### 光傳字串沒辦法包含這麼多資訊
* 傳json格式，再轉成字串。
## server
### 一切都很順利。。。

[返回](lobby.md)