# MIG-TelldusTellstick interface
HomeGenie / MIG interface driver for TellStick. Tested on TellStick Duo.

<h3>Installation</h3>
<b>Install telldus-core</b><br />
This interface requires telldus-core libraries. To install these in Windows, Mac or Linux download telldus center from http://www.telldus.se/products/nativesoftware.
For raspberry pi follow step 4 - 7 in this tutorial (please note last comment): https://blogg.itslav.nu/?p=875. Here is another more official tutorial I haven't tried myself: http://elinux.org/R-Pi_Tellstick_core.

<b>Install interface to homegenie</b><br />
When the telldus-core libraries are installed you can install the interface in homegenie: <br />
<ol>
<li>Download the zip file located in the root directory <a href="https://github.com/swaner/HomeGenieTelldusInterface/raw/master/Tellstick_0_9.zip">here</a>.</li>
<li>Open HomeGenie and goto Configure->Interfaces.</li>
<li>Press Import Interface Driver and locate the file downloaded in step 1.</li>
</ol>

<h3>Features</h3>
Currently the interface supports the following:
* Turning lights on/off
* Dimming lights
* Reading temperature values
* Simulated two way communication (remote triggers homegenie status)
