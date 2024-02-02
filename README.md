Don't like the new Firefox look regarding tabs and the url/toolbar?
This css slims it down insanely:

![Final look](https://github.com/ittykeys/slimlined-firefox/assets/157688550/80869ac3-cfa5-4e3b-bb16-ca9be6358f49)

Go to about:config , look at "Root Directory" for the profile you wish to change.
In that directory create a folder named "chrome". Place userChrome.css inside that.
Go to about:config , change "toolkit.legacyUserProfileCustomizations.stylesheets" to True.
Restart Firefox.

(Don't forget to customize the toolbar to remove empty spaces etc)
