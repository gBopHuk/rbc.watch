# rbc.watch
Shell script for watching rbc.tv - https://www.rbc.ru

* Needed a player that supports .m3u8 file format as mplayer, mpv etc.
* Supported only 2 resolution formats: 224p and 448p

## Install
1. git clone https://github.com/gBopHuk/rbc.watch
2. chmod +x rbc.watch
3. Copy to your $PATH

## Run
* Run without args showing help
 
* `$ rbc.watch 2` runs `mpv http://online-video.rbc.ru/online/rbctv_224p/index.m3u8`



## Customize

You can set your own player with $PLAYER variable a the top of the script. Mpv is set by defualt
