# Famous Font Families

> Latest Version: 1.3.0

[![download][download-image]][download-url]
[![license][license-image]][license-url]
[![changelog][changelog-image]][changelog-url]

Famous Font Families (further just **FFF**) is a small lib of widely used font families nowadays in Web Development. There is only usage of **WOFF** font format in **FFF** which is the recommended format of the font by **W3C** and fully supported in all modern browsers (**IE9+**). At this initial version, **FFF** contains 7 popular font families with their different types.
Feel free to use **FFF** in your projects.

&nbsp;
## Installation
Use this GitHub repo to clone or download the **FFF**

&nbsp;
## Usage
It assumed that your **fonts** folder is placed in the **assets** folder at the same level as **styles** folder. Soo, if you are using **SCSS** you can just move all structure of **FFF's SCSS** folder for example in your **base** folder from your own SCSS files structure and make **@import base/typography** to your **MAIN scss file**. Folders as **partials** and **modules** can be placed in another way as convenient for you and your files structure, just keep in mind to do simple change in **_typography.scss** file, where you will need to change only the **@import paths** for **partials** and **modules** files, a small job for you :). Otherwise, if you are using basic **CSS** you will need to copy and paste the @font-face rules from **typography.css** file to your **MAIN CSS** stylesheet file before any styles. Useless fonts for your project can be managed by yourself, by deleting or just shifting out from your project.

&nbsp;
## Contributing
Pull requests are welcome.

&nbsp;
## Contributors
- Karen Kharatyan <karenkharatyan1@gmail.com>

&nbsp;
## License & Copyrights
**FFF** has no license. This is **public**, **open** and **free** to use\
© Karen Kharatyan, Web Developer



[download-image]: https://img.shields.io/badge/download-v1.3.0-blueviolet.svg
[download-url]: https://github.com/KarenKharatyan/famous-font-families/archive/master.zip
[changelog-image]: https://img.shields.io/badge/changelog-md-informational.svg
[changelog-url]: CHANGELOG.md
[license-image]: https://img.shields.io/badge/license-none-success.svg
[license-url]: https://github.com/KarenKharatyan/famous-font-families