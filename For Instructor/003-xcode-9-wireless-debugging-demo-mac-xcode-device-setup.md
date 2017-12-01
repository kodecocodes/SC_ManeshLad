*This section should be de displaying mac screen*

**Launch Xcode**
Ensure your Mac, iOS and Apple TV share on the same network for wireless debugging to work properly.
Launch Xcode 9 or higher
Got to Window > Devices & Simulators, click on the devices tab

**Setup iOS device for wireless debugging**
Make sure your Mac and iOS device are on the same network, WIFI or ethernet
Connect your iOS device to your mac using a usb cable, iPhone or iPad
If its your first time connecting this device to this mac, wait until xcode prepares debugger support for your connected device.
Check the option for Connect via network
Disconnect your device
Once xcode connect's to your device wirelessly the network icon will show up
Once you see the network icon next to your device name your are ready for wireless debugging.

**Setup Apple TV for wireless debugging**
Make sure your Mac and Apple TV device are on the same network, WIFI or ethernet
One your Apple TV, opening up the setting app and go to Remotes and Devices > Remote App and Devices
On the Mac, on the Devices & Simulators window, click the plus icon and select the Apple TV you want to setup.
Now in the devices pane, select the Apple TV and enter verification code to pair the Apple TV with your Mac.
Once you see the network icon next to your device name your are ready for wireless debugging.

**Wireless Connection Discovery**
*Home & Small Business*
The steps above will work fine for most home and small business network - no configuration is required.

*Enterprise Wireless Networks*
If the above steps do not work or you have a compplex network you can alternatively connect directly to the device by IP address.  Redirect the viewer to Apple's documentation do do a quick demo.

**Additional information can be found here:**
Pair a wireless device with Xcode (iOS, tvOS) - https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj#/devbc48d1bad
WWDC 2017 Session. Debugging with Xcode 9 - https://developer.apple.com/videos/play/wwdc2017/404/
