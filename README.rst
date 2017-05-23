.. image:: https://travis-ci.org/DeastinY/screencontrol.svg?branch=master
    :target: https://travis-ci.org/DeastinY/screencontrol

Manual setup
============

- Install https://www.ddcutil.com
- Detect screens `sudo ddcutil detect`
- Check for the display capabilities `sudo ddcutil capabilities --display X`
- Note the brightness feature and use `sudo ddcutil setvcp BRIGHTNESS_FEATURE BRIGHTNESS_VALUE --display X`
