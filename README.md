# The dataloo blog font
This is the official dataloo.de blog font.

Download the [latest release](https://github.com/dataloo/font/releases).

Contains dataloo regular files - webfont ready:

* ttf
* eof
* woff
* woff2
* svg

Place in your web root assets folder, add this to your css file and adjust paths to the font files:

```css
@font-face {
  font-family: 'dataloo';
  src: url("../fonts/dataloo.eot");
  src: url("../fonts/dataloo.eot?#iefix") format("embedded-opentype"), 
  url("../fonts/dataloo.woff2?v=0.1.4") format("woff2"), 
  url("../fonts/dataloo.woff?v=0.1.4") format("woff"), 
  url("../fonts/dataloo.ttf?v=0.1.4") format("truetype"), 
  url("../fonts/dataloo.svg?v=0.1.4#datalooregular") format("svg");
  font-weight: normal;
  font-style: normal; }
```

# Build with

* [Adobe Capture](https://www.adobe.com/products/capture.html)
* [Adobe Illustrator](https://www.adobe.com/products/illustrator.html)
* [BirdFont](http://birdfont.org/)

# Licence
Published under

<!--SIL Open Font License-->
<a rel="license" href="https://scripts.sil.org/OFL">
<img alt="Open Font License" border="0"
src="https://scripts.sil.org/cms/sites/nrsi/media/OFL_logo_rect_color.png"/></a>
<br />
<a rel="license" href="https://scripts.sil.org/OFL">Open Font License </a>
<!--/SIL Open Font License-->
