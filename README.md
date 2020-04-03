# Famous Font Families
### Version 1.0.1  -  [Changelog](CHANGELOG.md)

Famous Font Families (further just **FFF**) is a small lib of widely used font families nowadays in Web Development. There is only usage of only **WOFF** font format in **FFF** which is the recommended format of the font by **W3C** and fully supported in all modern browsers (**IE9+**). At this initial version, **FFF** contains 7 popular font families with their different types.
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
**FFF** is open and free to use\
© Karen Kharatyan, Web Developer