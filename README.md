# PlayVideoOnAndroidWeb
Play video on android web

jsmpeg通过canvas播放视频,解决了video标签在安卓浏览器上层级最高的问题,同时实现了视频的自动播放。

网页示例:https://demo.crazyming.cn/?link=PlayVideoOnAndroidWeb

jsmpeg插件:https://github.com/phoboslab/jsmpeg

使用插件前需要将视频转换成ts格式

推荐使用ffmpeg转换:http://ffmpeg.org/

转ts的参数：

ffmpeg -i video.mp4 -f mpegts -codec:v mpeg1video -codec:a mp2 out.ts
