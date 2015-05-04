# configs
A small collection of my most-used configuration files.

## .elintrc
A config file for [ESLint](http://eslint.org), a linting tool for Javascript and JSX that helps detect errors and highlights confusing constructs and violations of stylistic conventions. I use ESLint in preference to [JSLint](http://jslint.com) or [JSHint](http://jshint.com).  
This particular version is intended for use in [Node.js](https://nodejs.org/) but I also use these same settings (minus the 'node' _env_ directive) for browser Javascript.  

## .editorconfig
By placing this config in the root of a repo you can ensure a unified coding style for different editors and IDEs.  
Most modern editors have a plugin available that will read this file and set the default tab style (tabs or spaces), tab size and a few other settings. This ensures that everyone in your team (even if that's just you) maintains a consistent style.
More info and links to the editor plugins can be found at [EditorConfig](http://editorconfig.org/).  

## com.googlecode.iterm2.plist
A config file for [iTerm2](http://iterm2.com/), a Terminal emulator for OSX.  
To try this out with your own copy of iTerm just save this file onto your local drive, open up the iTerm preferences (_iTerm... Preferences_ menu item) and use the _Browse_ button at the bottom of the _General_ settings to locate the folder you placed the settings file in:  
  
![Loading the iTerm preferences file](https://dvolvr.files.wordpress.com/2015/05/iterm_preferences-e1430761329166.png)
  
As you can probably guess from the screenshot, I store mine in a folder that's synced to Google Drive. This lets me share my settings across multiple Macs, gives me an extra backup and lets me restore an old version if something goes wrong when I'm tinkering.
