## 一對一視訊通話
[鐵人賽](https://ithelp.ithome.com.tw/users/20130062/ironman/3918)

## 啟動方式
```
git clone https://github.com/tc3oliver/1-on-1-webrtc.git
docker build . -t 1-on-1-webrtc
docker run -d --name webrtc  -p 8088:8088 1-on-1-webrtc
```