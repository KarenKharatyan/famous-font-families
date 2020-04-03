# Changelog
All notable changes to this project will be documented in this file.

&nbsp;
&nbsp;
## [1.3.0] - 2020-04-03
### Changed:
- content of first **@mixin newFont**. $name -> $font.
- **@mixin newFont** was made more dynamic for declaration. **Format** and **font-display** values can be changed by argument passing to that @mixin very easily. Note that they have default values **'woff'** and **'swap'** as well.

### Added:
- new **@mixin font-family** which allows you super-fast declare your font-family sequence with, 3 fallback fonts  **Lato, Poppins, Roboto** and a generic family **sans-serif** by default. Easy can be modified by you.
- comments in **modules/mixins.scss** file for describing SCSS @mixins
- new parameter in **@mixin newFont** called **$display** with default value **swap**
- new parameter in **@mixin newFont** called **$format** with default value **'woff'**

&nbsp;
&nbsp;
&nbsp;
## [1.2.0] - 2020-04-03
### Added:
- **font-display** property with a **swap** value is added to all fonts. This value is my recommendation.

&nbsp;
&nbsp;
&nbsp;
## [1.0.1] - 2020-04-03
### Changed:
- src property for all @font-face rules declarations by adding **format('woff')** value

&nbsp;
&nbsp;
&nbsp;
## [1.0.0] - 2020-04-02
Initial release

### Added:
- Lato (**10**)
- Roboto (**12**)
- Ubuntu (**8**)
- Poppins (**18**)
- Montserrat (**18**)
- Proxima Nova (**6**)
- Operaator Mono (**10**)
- Font families above with their several types of fonts
- CSS/SCSS @font-face rules
- README.md
- CHANGELOG.md