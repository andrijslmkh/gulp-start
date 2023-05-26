# gulp-start

#Add images on html<br>
<br>
Example based integration AVIF<br>
<pre>
<picture>
    <source type="image/avif" srcset="./to/show.avif" />
    <source type="image/webp" srcset="./to/show.webp" />
    <img src="./to/show.png">
</picture>
</pre>

# gulp --tasks
<pre>
exports.styles = styles;
exports.scripts = scripts;
exports.images = images;
exports.sprite = sprite;
exports.fonts = fonts;
exports.pages = pages;
exports.watching = watching;

exports.imgsp = series(images, sprite);
exports.build = series(building, cleanDist, building);
exports.watch = parallel(styles, scripts, pages, watching);
</pre>
