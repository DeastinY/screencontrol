## Manual setup
- Install [ddcutil](http://www.ddcutil.com/#introduction)
- Detect screens `sudo ddcutil detect`
- Check for the display capabilities `sudo ddcutil capabilities --display X`
- Note the brightness feature and use `sudo ddcutil setvcp BRIGHTNESS_FEATURE BRIGHTNESS_VALUE --display X`
