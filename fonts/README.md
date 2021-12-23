## Fonts
These fonts are avalible for anyone to use.
### Font Usage
Each font has a catogary and they link to a css file you can import in your page and then use the ```font-family``` css property and use the font names provided; eg.: ```font-family:  comfortaa;```.

There are also links to the page that the fonts are taken from.

another trick is fallback fonts on other system, simply add the line bellow after the desired font in the font-family property
```css
... ,-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
```
### Font api versions
There are diffrent version of accsesing fonts. These usally relased in chronological order.
- V1:
  - All the fonts from the catogary are put in one css file.
- V2:
  - these seperate each font individualy to their own files.
### Serif
**V1 font api**
these are serif fonts avalible at:
```
https://eureka-imagineee-server.github.io/cdn/fonts/serif/serif.css
# one url for all
```
Avalible fonts:
- [fredoka](https://fonts.google.com/specimen/Fredoka+One)
- [comfortaa](https://fonts.google.com/specimen/Comfortaa)
- [abril-fatface](https://fonts.google.com/specimen/Abril+Fatface)

### Sans-Serif
**V2 font api**
These are sans serif fonts (seperated to each css file to reduce download on page load)
<br>
Avalible Font:
- [Raleway](https://fonts.google.com/specimen/Raleway) [(import url)](https://eureka-imagineee-server.github.io/cdn/fonts/sans-serif/raleway.css)
- [Work Sans](https://fonts.google.com/specimen/Work+Sans) [(import url)](https://eureka-imagineee-server.github.io/cdn/fonts/sans-serif/work-sans.css)
### IBM Plex
**V1, V2 hybrid font api**
*coming soon*
