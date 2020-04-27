# landtray
Playing with a system tray icon on golang

## How to build
```
echo "one;two;three;four" >> /tmp/results.txt
apt-get install libgtk-3-dev libappindicator3-dev libwebkit2gtk-4.0-dev upx
git clone https://github.com/oprietop/landtray.git
cd landtray
go get .
go build -ldflags="-s" && upx -9 landtray
```
## Thanks
https://github.com/getlantern/systray   
https://github.com/marcsauter/single
