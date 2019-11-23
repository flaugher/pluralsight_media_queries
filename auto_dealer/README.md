# README

## Folders

This project came with these folders:
- css
- images
- scss

The css folder didn't contain any files (but we will tell Koala to put our styles.css file there).

The images folder contained the car image files.

The scss folder contained the following partial (i.e. _name) files:
_large.scss was empty.
_medium.scss was empty.
_reset.scss contained the default reset rules.
_small-default.scss contained the html and "*" rules we include in every responsive site.
_variables.scss was empty.
styles.scss contained the @import statements with media queries around the medium and large imports.

## Files

The project also came with a top-level index.html file.

## Set up CSS preprocessing

To use CSS pre-processing,
1. Open the koala app.
2. Drag the top-level auto_dealer folder from Mac Finder to the left pane in the koala window.
3. Right-click the SCSS icon that appears in the right pane and select Set Output Path.
4. Set the output path to a styles.css file in the css folder.  Also, deselect the Source Map option
   and ensure the Auto Compile checkbox is checked.
5. Click the Compile button.

Note that you can also delete the initial styles.css and styles.css.map files in the scss folder if
they're present.  You only need the styles.css file in the output path you just set.

## References

[Choosing great variable names](http://thesassway.com/beginner/variable-naming)
[(S)CSS Best Practices That You Have Not Yet Known](https://medium.com/@mciastek/s-css-best-practices-that-you-have-not-yet-known-ba2f6329b5dd)