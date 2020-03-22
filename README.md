= First

= Convert MOV into GIF


```
ffmpeg -i mvn-clean.mov -s 600x400 -pix_fmt rgb8 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > mvn-clean.gif
```


Test

The first one:
![Gif](/docs/resources/mvn-clean.gif)

the following GIF has been converted via the following command:

```
ffmpeg -i mvn-clean.mov -s 300x200 -pix_fmt rgb8 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > mvn-clean.gif
```
![Gif](/docs/resources/mvn-clean-300x200.gif)

