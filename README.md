# ion-content-scroll-issue
Repo to demonstrate an issue with on-scroll-complete.

# Run

  `cordova platform add ios@3 && cordova run ios`
  
# Native scrolling
  
  Set ion-content's `overflow-scroll="true"` in https://github.com/blefebvre/ion-content-scroll-issue/blob/master/www/index.html#L32 to observe the on-scroll-complete function fail to fire when the page is scrolled.
