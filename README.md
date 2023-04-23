# Screen Distribution

## Requirement

* ffmpeg: http://ffmpeg.org/
  * Assumes ${PROJECT_HOME}/ffmpeg/bin contains ffmpeg binaries

## Note

* ffprobe can get video info like resolution, fps 
* ffmpeg -i myVideo.mp4 -r 24 images_%04d.jpg
  * r = frame per sec
  * let's try with 24 