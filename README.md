# 讯飞-语音-合成
### 启动访问流程
第一：拉下代码<br>
第二：安装ffmpeg（解压版就可以了），在FfmpegUtil类中，把ffmpeg.exe这个路径改为自己安装的路径（ffmpeg.exe在ffmpeg的bin目录下）<br>
第三：在XunfeiConvert类中更改生成的mp3文件的位置（这里我设置的是是放在桌面/mp3/xxx.mp3），你也可以不用更改！<br>
第四：运行tomcat,访问：http://localhost:8080/yuyin/<br>
然后输入文字，点击合成，生成的生成的MP3文件我设置的是放在桌面/mp3/xxx.mp3，打开此文件即可！<br>
