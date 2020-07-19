# Firefox Dark Homepage

On Linux, simply copy the .css file into `~/.mozilla/firefox/`*`XXX`*`/chrome/` where XXX is your profile folder.  
On Windows, the path can be found following this:  https://superuser.com/questions/318912/how-can-i-override-the-css-of-a-site-in-firefox-with-usercontent-css  

If `chrome` directory does not exist, create it.
Usually, your profile folder should be the biggest in size.  

Finally, visit about:config and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
