# gulp-start
<hr>
<span>https://www.npmjs.com/package/gulp-include</span>
<pre>
#Example based integration INCLUDE in HTML 
<div class="highlight highlight-text-html-basic notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">&lt;!--=include _exemple.html --&gt;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
</pre>
<span>Work only folder pages</span>
<hr>
<hr>
<span>https://www.npmjs.com/package/gulp-avif</span>
<pre>
#Example based integration AVIF in HTML
<div class="highlight highlight-text-html-basic notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">&lt;</span><span class="pl-ent">picture</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">source</span> <span class="pl-c1">type</span>="<span class="pl-s">image/avif</span>" <span class="pl-c1">srcset</span>="<span class="pl-s">folder/show.avif</span>" /&gt;
    <span class="pl-kos">&lt;</span><span class="pl-ent">source</span> <span class="pl-c1">type</span>="<span class="pl-s">image/webp</span>" <span class="pl-c1">srcset</span>="<span class="pl-s">folder/show.webp</span>" /&gt;
    <span class="pl-kos">&lt;</span><span class="pl-ent">img</span> <span class="pl-c1">src</span>="<span class="pl-s">folder/show.png</span>"<span class="pl-kos">&gt;</span>
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
exports.building = building;
exports.watching = watching;

exports.imgsp = series(images, sprite);
exports.build = series(building, cleanDist, building);
exports.watch = parallel(styles, scripts, pages, watching);
</pre>
