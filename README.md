# Youtube video failed to play in Ubuntu

<img src="https://github.com/jonhan8352/youtube-video-cannot-play-in-ubuntu/blob/main/screenshot202109172100.jpg">

If you experiencing difficulty to watch or play the Youtube video in Firefox under Ubuntu. You might need to do following steps to install some codec in order to fix the issue.
1. Open terminal and enter following command to install ffmpeg codec.
```
sudo apt install ffmpeg
```
2. Then Ubuntu Restricted Extras with following command.
```
sudo apt install ubuntu-restricted-extras
```
3. Finally install the libavcodec-extra with following command.
```
sudo apt install libavcodec-extra
````
Now you can watch your favourite Youtube videos in Firefox for Ubuntu.
