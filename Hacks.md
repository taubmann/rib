## Hacks 

This Version of RIB is hacked to address following Requirements

* include + zip additional Files in Export 
* include actual versions of jQuery/jQueryMobile

### Files added

* lib/jquery.js (the actual jQuery)
* lib/jquery.mobile.js (the actual jQuery-Mobile)
* src/css/jquery.mobile.structure.css (the actual jQuery-Mobile-CSS)
* src/css/jquery.mobile.theme.css (an empty File to put some custom CSS)
* inc/* (a new Folder with additional Files to Export)

### Files hacked 

**(just search for "hack")**

* src/js/serialize.js (Function createZipAndExport)
* src/js/widgets.js

