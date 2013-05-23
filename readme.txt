Preview: http://guides.lib.jjay.cuny.edu/ 

A more modern look for your LibGuides:

1. If you’re an admin, get to the Admin stuff » Customize » Look & Feel page (admin_lookfeel.php)
2. Choose “Square” for the tab and box shape; ignore the color swatches
3. Banner options:
--A static image, 985px wide, that will automatically link to your main library page
--Custom Header Code in HTML: use if you have multiple images, a menu bar, or other complex items. Note that this code doesn’t actually go within <header>
--Both: not recommended, looks messy. Note that the System Banner will appear after the Custom Header Code. (See ‘before’ image above.)

4. Custom JS/CSS code: this is where you can customize how the whole page looks, as it overrides the system CSS. Paste the .css file into this textbox.

Things this code will do:

--Take out all references to Verdana and replace with Helvetica; make all text easier to read with increased size and fewer instances of bolded font

--Where you see display:none, that’s mostly where we’re hiding all references to comments and overriding the circa 2002 gradient look of which LibGuides is so fond. Gradients can be gorgeous, but use them wisely, everyone.

--The colors in this custom code are blue and grey — be sure to color-match to your library site. For easier color-matching, refer to screenshots and find/replace these hex codes:
#012d6b is navy blue (border of buttons)
#3c5e8e is medium blue (buttons and box titles)
#00a7e5 is bright blue (active and hover buttons)
#eaeaea is light grey (band where search bar is)
#ffffff is white (button and box title text)

--Make the tabs at the top of the page into buttons with rounded corners (flat color). Guides with multiple tabs may find that by default the tabs stack up on top of each other unattractively; buttons make slightly more sense and look better.

________________
More info: http://emerging.commons.gc.cuny.edu/2013/03/easy-libguides-makeover/

Robin (@robincamille)

Take this CSS and make it your own! 