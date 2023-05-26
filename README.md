# gulp-start

<pre>
#Add images on html
Example based integration AVIF
<div class="highlight highlight-text-html-basic notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">&lt;</span><span class="pl-ent">picture</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">source</span> <span class="pl-c1">type</span>="<span class="pl-s">image/avif</span>" <span class="pl-c1">srcset</span>="<span class="pl-s">./to/show.avif</span>" /&gt;
    <span class="pl-kos">&lt;</span><span class="pl-ent">source</span> <span class="pl-c1">type</span>="<span class="pl-s">image/webp</span>" <span class="pl-c1">srcset</span>="<span class="pl-s">./to/show.webp</span>" /&gt;
    <span class="pl-kos">&lt;</span><span class="pl-ent">img</span> <span class="pl-c1">src</span>="<span class="pl-s">./to/show.png</span>"<span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">picture</span><span class="pl-kos">&gt;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
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
