# Bootstrap To Material
## Overview
This extension will turn any page made with Bootstrap 4 into one that uses Material Design.

**Disclaimer:** this extension is still in really early development, so I would consider only keeping it enabled for testing, as it may (and it will) cause unexpected behaviors on websites. For example, it prevents scrolling in [Material Design guidelines](https://material.io/guidelines/) itself...

## Credits
This extension was made using:
* AngularJS (Angular ≤ 1.6.9)
* AngularJS Material
* Material Design Icons

## Changelog
### 0.2.1 (current)
* Changed the way the framework is loaded: started using programmatic injection instead of content scripts
* I had actually forgotten to update to 0.2.0 in the extension manifest... <img style="transform: scale(1.5);" height="16px" alt="Man facepalming emoji" src="https://emojipedia-us.s3.amazonaws.com/thumbs/120/google/119/man-facepalming_1f926-200d-2642-fe0f.png">
* I neither fixed issues, nor added features (however now by disabling the extension from the popup you can actually avoid the scroll prevention)

### 0.2.0
* Forgot to mention, the extension also kinda converts typography
* Added the ability to change primary and secondary colors in the settings popup (again, still nothing in advanced...)
* Made code a bit fresher and easier to understand
#### Known issues
* Still, some attributes of the original elements aren't copied through
* I don't have to remind you the disclamer, do I?

### 0.1.0
* The extension now _fully_ supports buttons!
* Added a master switch in the settings popup (still nothing in the advanced settings...)
#### Known issues
* Some attributes of the original button might not be copied on the Material Design one
* For some arcane reason, enabling the extension works well, but you have to click twice on the master checkbox to disable it

### 0.0.2
* The extension now converts buttons!

### 0.0.1
* First release
* Added a blank settings page

## License:
[![CC BY-NC-SA License Button](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).