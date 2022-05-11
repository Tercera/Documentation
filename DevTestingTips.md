# Dev Testing Tips

1. Generally when you're testing the device for responsiveness you need to test on devices that vary in _width_ and _height_ to ensure that your designs are going to work for _most_ users.
2. You'll want to try to run the app on the simulator/emulator, but _also_ on a device whenever possible. There are often crashes that happen on devices that may not happen on the simulator/emulator.
3. Try the devices on wifi, on cellular, and with no wifi. 
4. Press buttons as fast as you can on both simulator/emulator and device, sometimes this can cause unforseen crashes; do the same with changing screens.
5. Close the app in a middle of an API call to see what happens
6. Get a phone call when you're using the app on device or a push notification, does the app crash or still work?
7. On device, use the app as you would others -- switching between different apps -- make sure it stands up to this kind of usage.

### iOS
- iPhone 8
- iPhone 8 Plus is a good _wide_ device
- iPhone 8 SE is a good _short_ device
- iPhone X
- iPhone 12 Pro Max
- iPhone 13

### Android
- You'll want to test on the latest Pixel and perhaps that last 2/3 models
- You'll want to test on some Samsung devices
- You'll want to test on some LG devices
