## Contributing Guide

* Maintain proper nomenclature and comment structure in fonts.css file.
* After adding the font correctly add another paragraph in the ```index.html``` file into ```ul``` tag as shown below.
```html
    <p class="fNUmber-fontWeight-fontStyle">Welcome to My Page : 'FONT-NAME'</p>
```
##### Examples:
```html
    <!-- Start Lato Font -->

            <li>
                <p class="f11-regular">Lato</p>
                    <ul class="sublist">
                        <li><p class="f11-thin">Lato Thin</p></li>
                        <li><p class="f11-thin-italic">Lato Thin Italic</p></li>
                        <li><p class="f11-light">Lato Light</p></li>
                        <li><p class="f11-light-italic">Lato Light Italic</p></li>
                        <li><p class="f11-regular">Lato Regular</p></li>
                        <li><p class="f11-regular-italic">Lato Regular Italic</p></li>
                        <li><p class="f11-bold">Lato Bold</p></li>
                        <li><p class="f11-bold-italic">Lato Bold Italic</p></li>
                        <li><p class="f11-black">Lato Black</p></li>
                        <li><p class="f11-black-italic">Lato Black Italic</p></li>
                    </ul>
            </li>

    <!-- End Lato Font -->

```
* In ```style.css``` file set the paragraph to use the new font.
```css
.f11-thin-italic {
    font-family: 'Lato';
    font-weight: 100;
    font-style: italic;
}

.f11-light{
    font-family: 'Lato';
    font-weight: 300;
}

.f11-light-italic {
    font-family: 'Lato';
    font-weight: 300;
    font-style: italic;
}

.f11-regular {
    font-family: 'Lato';
    font-weight: 400;
}

.f11-regular-italic {
    font-family: 'Lato';
    font-style: italic;
}

.f11-bold {
    font-family: 'Lato';
    font-weight: 700;
}

.f11-bold-italic {
    font-family: 'Lato';
    font-weight: 700;
    font-style: italic;
}

.f11-black {
    font-family: 'Lato';
    font-weight: 900;
}

.f11-black-italic {
    font-family: 'Lato';
    font-weight: 900;
    font-style: italic;
}
```
* Add your font at ```fonts.css``` file with this format.
```css
/* 
#
#   Lato
#
*/

/* Thin */

@font-face {
    font-family: 'Lato';
    font-weight: 100;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-Thin.ttf) format('truetype');
}

/* Thin Italic */

@font-face {
    font-family: 'Lato';
    font-style: italic;
    font-weight: 100;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-ThinItalic.ttf) format('truetype');
}

/* Light */

@font-face {
    font-family: 'Lato';
    font-weight: 300;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-Light.ttf) format('truetype');
}

/* Light Italic */

@font-face {
    font-family: 'Lato';
    font-style: italic;
    font-weight: 300;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-LightItalic.ttf) format('truetype');
}

/* Regular */

@font-face {
    font-family: 'Lato';
    font-weight: 400;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-Regular.ttf) format('truetype');
}

/* Regular Italic */

@font-face {
    font-family: 'Lato';
    font-style: italic;
    font-weight: 400;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-Italic.ttf) format('truetype');
}

/* Bold */

@font-face {
    font-family: 'Lato';
    font-weight: 700;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-Bold.ttf) format('truetype');
}

/* Bold Italic */

@font-face {
    font-family: 'Lato';
    font-style: italic;
    font-weight: 700;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-BoldItalic.ttf) format('truetype');
}

/* Black */

@font-face {
    font-family: 'Lato';
    font-weight: 900;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-Black.ttf) format('truetype');
}

/* Black Italic */

@font-face {
    font-family: 'Lato';
    font-style: italic;
    font-weight: 900;
    font-display:swap;
    src: url(../webfonts/Lato/Lato-BlackItalic.ttf) format('truetype');
}
```
* Update the list of available fonts in ```README.md```. You can add a screenshot with your styles fonts in ``` \screenshots\screenshotFontName.png```. Use gimp for with the ```template.png``` file and the screnshot tool of firefox browser.
