# First

## Convert MOV into GIF


The first one has been converted via the following:
```
ffmpeg -i mvn-clean.mov -s 600x400 -pix_fmt rgb8 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > mvn-clean.gif
```

![Gif](/docs/resources/mvn-clean.gif)

The next GIF has been converted via the following command:

```
ffmpeg -i mvn-clean.mov -s 300x200 -pix_fmt rgb8 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > mvn-clean.gif
```
![Gif](/docs/resources/mvn-clean-300x200.gif)

```
ffmpeg -i rust-example.mov -s 300x200 -pix_fmt rgb8 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > rust-example.gif
```
![Gif](/docs/resources/rust-example.gif)

