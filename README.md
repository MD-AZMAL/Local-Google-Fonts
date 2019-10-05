# LOCAL GOOGLE FONTS

Use google fonts locally for various frontend development projects.   

## Instructions

* Place the fonts.css in your project's css directory.

```bash 
cp css/fonts.css 'YOUR-PROJECT-CSS-FOLDER'
```
* Make a folder webfonts in your Project's directory at the same place where you have the 'css' directory
(Preferebly put all the static stuff in 'assets' directory).

```bash
cd 'YOUR-PROJECT-DIRECTORY'/assets
mkdir webfonts
```

* Download the required google font and the customisations, extract to folder and place them in webfonts directory. (Make sure to do 'extract to folder', simply extracting and copying wont work).

* Include the fonts.css in your html file, above your custom stylesheet.
```html
    <html>
        <head>
            .
            .
            <link rel="stylesheet" href="css/fonts.css">
            <link rel="stylesheet" href="css/'YOUR-CUSTOM-CSS'.css">
            .
            .
        </head>
        <body>
            .
            .
        </body>
    </html>
```

* In your custom css file use the google font as instructed on fonts.google.com, below are few examples.
```css
.f9 {
    font-family: 'Roboto';
}

.f10 {
    font-family: 'Source Sans Pro'
}
```

## Project Folder Structure

```bash
LOCAL GOOGLE FONTS
├── assets
│   ├── css
│   │   ├── fonts.css
|   |   ├── fonts.css
│   ├── webfonts
│   │   ├──FONT-FOLDER
|   |________|── fonts-files.ttf
|
├── .gitignore   
├── index.html
└── README.md
```

## List of available fonts 
* Abrial fatface
* Armata
* Hind
* Libre-Baskerville
* Lusitana
* Montserrat
* Nunito
* Open-Sans
* Roboto
* Source-Sans-Pro

## Guide to contributing
* Maintain proper nomenclature and comment structure in fonts.css file.
* After adding the font correctly add another paragraph in the index.html file as shown below.
```html
    <p class="f'NUMBER-OF-FONT">Welcome to My Page : 'FONT-NAME'</p>

```
* In style.css file set the paragraph to use the new font.

## Support this Project
* Feel free to add new google gonts to the project.
* Good starting point for newbies in open source.
* Accepting Hacktober fest PR's.

## License
Copyright © 2019, [Md Azmal](https://github.com/md-azmal).
Released under the [MIT License](LICENSE).