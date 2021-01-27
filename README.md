# Thinkpad-E570-Hackintosh

This laptop is having the following specs:

i5-7200U
UHD620
8gb RAM 2400
NVidia 940MX (disabled via wegnoegpu)
512gb Intel NVMe
240gb Patriot Burst 2.5' SSD
1Tb WD Blue
Thinkpad BIOS rev. 2.03 (dvmt locked by OEM)

So, I installed this on the NVMe, and then followed Dortania's guide for making this work with OpenCore 0.6.5.

What works:
QE/CI Metal
Audio (AppleALC @ alcid=15)
USB (using personally-created USBMap.kext)
Built-in en0 (for iMessage, etc)
Camera
FaceTime and such

What doesn't:
WiFi/BT (workaround using HornDis by Joshua Wise)
