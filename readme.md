# PLEASE NOTE: As of 2015, this code is outdated! It discusses customization for LibGuides 1.0, which is no longer supported! If you have LibGuides, you should be on LibGuides 2.0, and this post is not useful to you. #

Preview: https://web.archive.org/web/20140128004104/http://guides.lib.jjay.cuny.edu/dh

## How to customize LibGuides 
1. If you’re an admin, get to the Admin stuff » Customize » Look & Feel page (admin_lookfeel.php)
2. Ignore tab shapes and the color swatches
3. Banner options:
  * Banner: a static image, 985px wide and however much you want high, that will automatically link to your main library page
  * Custom Header Code in HTML: use if you have multiple images, a menu bar, or other complex items
  * Both: not recommended, looks messy. Note that Banner will appear after the Custom Header Code
4. Custom JS/CSS code: this is where you can customize how the whole page looks, as it overrides the system CSS. Paste the .css file into this textbox within style tags.

## template.css 
A fill-in-the-blank CSS template with identifiers and classes you'll probably want to change, commented with descriptions of what they are. Many aren't listed, but you can find them using *Inspect Element* in Chrome/Firefox or examining a libguide's source code.

## custom.css 
Things custom.css will do:
* Take out all references to Verdana and replace with Helvetica; make all text easier to read with increased size and fewer instances of bolded font
* Make the tabs at the top of the page into buttons with rounded corners (flat color). Guides with multiple tabs may find that by default the tabs stack up on top of each other unattractively; buttons make slightly more sense and look better.
* Where you see display:none, that’s mostly where we’re hiding all references to comments and overriding the circa 2002 gradient look of which LibGuides is so fond. Gradients can be gorgeous, but use them wisely, everyone.

The colors in this custom code are blue and grey — be sure to color-match to your library site. For easier color-matching, refer to screenshots and find/replace these hex codes:
  * 012d6b is navy blue (border of buttons)
  * 3c5e8e is medium blue (buttons and box titles)
  * 00a7e5 is bright blue (active and hover buttons)
  * eaeaea is light grey (band where search bar is)
  * ffffff is white (button and box title text)


---
More info: 
* http://emerging.commons.gc.cuny.edu/2013/10/libguides-customization-tutorial-css-template/
* http://emerging.commons.gc.cuny.edu/2013/03/easy-libguides-makeover/

Robin (@robincamille)

Take this CSS and make it your own! 
