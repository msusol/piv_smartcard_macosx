piv_smartcard_macosx
====================

PIV smart card reader on Mac OS X Mountain Lion v10.8

purchased:  SCM SCR3500 Smart Card Reader (amazon.com)

Suggestion:  purchase a PIV reader on a usb cable or you'll need a usb hub to connect all your devices as the smartfold reader blocks both usb ports.

STEPS REQUIRED TO USE:.
1) Need Apple support for smartcards in OSX 10.7+, install the "Tokend" module from here:
http://smartcardservices.macosforge.org/trac/wiki/installers

2) Download the drivers for the reader itself from the manufacturer's website:
http://www.identive-group.com/products-and-solutions/identification-products/mobility-solutions/mobile-readers/scr3500-smart-fold

3) Download Citrix Receiver for mac (CitrixReceiverWeb.dmg) from
http://receiver.citrix.com

4) Use the smartcard to log into sites from SAFARI (OS X Keychain restriction).
When you've got it working, you should see your smartcard appear in the OS X Keychain Access as a "keychain".

5) Browse to https://connect.#####.### and select "Login from Other Device".
a citrix viewer launch file (launch.ica) will appear in your downloads directory, click it to load the citrix viewer.

6) Your PIV card reader should be working, login..voila!

DOWNLOADS used are provided with this repos.
1) SmartCardServices_2.0.b2_(MtLion)
2) scmccid_5.0.27_mac_rel
3) CitrixReceiverWeb.dmg