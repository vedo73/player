# [Hola Media Player API](https://hola.org/player)
An HTML5 Media Player that instantly streams http, torrents and magnets to the browser.

[Live demo](http://jsbin.com/faceyu/8/)
```html
<script src="//hola.org/play_page.js"></script>
<div class="hola-embedded-player"
  v="http://distribution.bbb3d.renderfarming.net/video/mp4/bbb_sunflower_1080p_30fps_normal.mp4.torrent">
</div> 
```

## Features
* instant streaming
* protocols: http, torrent files and magnet links
* embeddable as div, iframe, script or simple link to video
* video formats: mp4, mkv and avi
* browsers: Chrome, Firefox. coming soon: IE.
* mobile: coming soon: Android App.
* seek/reposition
* subtitles

## Example: &lt;a&gt; link
```html
<a href="http://hola.org/play#v=http%3A%2F%2Fdistribution.bbb3d.renderfarming.net%2Fvideo%2Fmp4%2Fbbb_sunflower_1080p_30fps_normal.mp4.torrent">
  Watch SunFlower Movie
</a>
```
[Live demo](http://hola.org/play#v=http%3A%2F%2Fdistribution.bbb3d.renderfarming.net%2Fvideo%2Fmp4%2Fbbb_sunflower_1080p_30fps_normal.mp4.torrent)

## Example: &lt;script&gt; and &lt;div&gt;
```html
<script src="//hola.org/play_page.js"></script>
<div class="hola-embedded-player"
  v="http://distribution.bbb3d.renderfarming.net/video/mp4/bbb_sunflower_1080p_30fps_normal.mp4.torrent">
</div> 
```
[Live demo](http://jsbin.com/faceyu/8/)

## Example: &lt;iframe&gt;
```html
<iframe width="770" height="500" frameborder="0" allowfullscreen
  src="//hola.org/play_embed#v=http%3A%2F%2Fdistribution.bbb3d.renderfarming.net%2Fvideo%2Fmp4%2Fbbb_sunflower_1080p_30fps_normal.mp4.torrent">
</iframe>
```
[Live demo](http://jsbin.com/faceyu/6/)

## Example: make all torrent and magnet links pop up a media player upon hover
```html
<script src="//hola.org/play_page.js"></script>
<script>window.hola_player.init({links: 'hover'});</script>
```
[Live demo](http://jsbin.com/faceyu/9/)
