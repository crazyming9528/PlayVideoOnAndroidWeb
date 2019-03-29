# PlayVideoOnAndroidWeb
Play video on android web


网页示例:https://crazyming9528.github.io/PlayVideoOnAndroidWeb/

jsmpeg插件:https://github.com/phoboslab/jsmpeg

使用插件前需要将视频转换成ts格式

推荐使用ffmpeg转换:http://ffmpeg.org/

转ts的参数：

ffmpeg -i video.mp4 -f mpegts -codec:v mpeg1video -codec:a mp2 out.ts
