# gulp-start


# gulp --tasks
exports.styles = styles;<br>
exports.scripts = scripts;<br>
exports.images = images;<br>
exports.sprite = sprite;<br>
exports.fonts = fonts;<br>
exports.pages = pages;<br>
exports.watching = watching;<br>
<br>
exports.imgsp = series(images, sprite);<br>
exports.build = series(building, cleanDist, building);<br>
exports.watch = parallel(styles, scripts, pages, watching);<br>
