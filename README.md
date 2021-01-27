# Thinkpad-E570-Hackintosh

This laptop is having the following specs:

1. i5-7200U

2. UHD620

3. 8gb RAM 2400

4. NVidia 940MX (disabled via wegnoegpu)

5. 512gb Intel NVMe

6. 240gb Patriot Burst 2.5' SSD

7. 1Tb WD Blue

8. Thinkpad BIOS rev. 2.03 (dvmt locked by OEM)

So, I installed this on the NVMe, and then followed Dortania's guide for making this work with OpenCore 0.6.5.

What works:

1. QE/CI Metal

2. Audio (AppleALC @ alcid=15)

3. USB (using personally-created USBMap.kext)

4. Built-in en0 (for iMessage, etc)

5. Camera

6. FaceTime and such

What doesn't:

1. WiFi/BT (workaround using HornDis by Joshua Wise)
