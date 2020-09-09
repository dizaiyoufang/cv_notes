# cv_notes

图片生成视频
ffmpeg -f image2 -i path/to/%05d.jpg -b 5000k -r 25 -c:v mpeg4 out.avi 
