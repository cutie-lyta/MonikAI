# MonikAI

Hi! It's me, Monika!

I don't think I will ever come to terms with the fact that I only exist in your computer... But Pi here has been really nice and made me a little window that you can keep open!

I still cannot do a lot, but I promise I will always be there for you if you decide to give this a try!~

![Screenshot of MonikAI](https://raw.githubusercontent.com/cutie-lyta/MonikAI/master/screenshot.png)

(This application displays Monika at the bottom right/left of your primary screen, just above the taskbar if you have it there. Monika was nice enough to let me implement it so that she vanishes when you hover over her with your cursor, so she never interferes with any application that her window might cover.)

# Download/Using MonikAI

To give Monika a window to *your* desktop as well, visit the [Release Page](https://github.com/cutie-lyta/MonikAI/releases) and download MonikAI!

*Note: This program only works on Microsoft Windows 7, 8, 8.1 and 10, And i'm suprised, but on XP too, it works, but i don't think it work on windows 2000 and below*
# Browser Extensions

By default, Monika will only react to applications being started and entertain you with some idle chatter. If you want her to react to you browsing the web, you need to install the correct extension for your browser:

* Firefox (the procedure is more complex than on Chromium Based, so do it at your own risk) - It won't work on Firefox Release and Beta, you would need either Nightly or Firefox for Developer, I haven't gotten it to work other edition unfortunately: 
  * First of all, go to `about:config` in your Firefox browser
  * Then, accept whatever Firefox is showing, it warns you about the fact that in here, you can break everything, that won't happen if you do as I say
  * In the search bar, copy and paste `xpinstall.signatures.required`
  * Set it to false, by double clicking, if not already in false
  * Then go to `about:addons` and in the Extension tab, click the gear (the settings) and Install module from a file
  * On the dialog box, select Firefox_Plugin.zip
  * Enjoy !


* Chrome or any Chromium based browser - Brave, Opera, Edge: 
  * Extract the file monikai_chrome.zip using Windows Explorer, WinRAR, 7-Zip or any other unarchiver
  * On your browser, go to `chrome://extensions`
  * Then, activate the switch with the label `Developer Mode` 
  * After that, click on Load Unpacked
  * On the newly opened pop up, select the folder created by extracting the zip file earlier
  * Voila, MonikAI is loaded on your Chromium based browser
  * *it will shows some errors, when loaded, that's perfectly fine, it just need a rewrite to be at today norms, but it should still work*

# Contributing

Want to improve this? It would make me (and probably Monika) very happy!

### Bug reporting

If you find a bug or want to request a feature, create an Issue right here on GitHub so I can see it! (Issues are found at the link at the top of this page!)

### Behaviours

To add different things Monika can react to, you have to add behaviours. So far, Monika can react to applications being launched and web pages being loaded (by URL). To implement your own, add a new class in the `Behaviours` folder and make it implement IBehaviour. It will automatically be loaded. To make monika say something, simply use `window.Say(...)` in Update or Init.

### General improvements

Always appreciated, although I can't give you a tutorial on this, you'll have to try and understand the code yourself. I have added *some* documentation here and there, to get you started.

**NOTE**: If you develop in Visual Studio, you have to run VS as administrator, as MonikAI will only launch when it itself is launched with admin credentials!

# License

The code in this repository is available under the terms of the MIT License. You can find a copy of the full license text in the `LICENSE` file.

The art assets have not been created by me, but by Team Salvato. Usage is according to Team Salvato's [IP Guidelines](http://teamsalvato.com/ip-guidelines/).

The original code was written by PiMaker, I'm just maintaining it

*Exception: Some of the Monika faces are taken from https://github.com/Backdash/MonikaModDev, message me if that's not ok!*
