# gulp-start

#Add images on html<br>
<br>
Example based integration AVIF<br>
<picture><br>
    <source type="image/avif" srcset="./to/show.avif" /><br>
    <source type="image/webp" srcset="./to/show.webp" /><br>
    <img src="./to/show.png"><br>
</picture>

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
