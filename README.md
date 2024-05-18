# Lenovo IdeaPad 3 (14ARE05) Hackintosh based on Opencore 1.0.0
## Currently tested on Ventura, anything above or below has not been tested.
&nbsp;
<h1 align="center">What's working?</h1>

* Graphics Acceleration
* Battery
* USB Ports
* Audio
* Ethernet - requires seperate hub (QCA/QCOM WIFI+BT Combo not supported.)
* Trackpad
* Brightness control
* Audio
* HDMI Output
* External hub
* Possibly other things which I have forgotten to add here.        
&nbsp;

<h1 align="center">What isn't working?</h1>

* Native WiFi & Bluetooth (qcom moment)

&nbsp;

<h1 align="center">Ready to try?</h1>

Requirements:
* Must have [genSMBIOS](https://github.com/corpnewt/GenSMBIOS)
* Must have [properTree](https://github.com/corpnewt/ProperTree)

Instructions:

* Open up genSMBIOS, and run the .bat file or whatever extension is suitable.
* Select option 1.
* Then, select option 2.
* Drag and drop your config.plist.
* Then, select option 3.
* Use a suitable SMBIOS.
* After it spits out the generated information, double check the serial number against apple database.
* If it comes back valid, regen.
* If it comes back false, open the config.plist and check if the variables was set properly. (you can use propertree)

Awesome! You are ready to install.         
&nbsp;

<h1 align="center">Screenshots</h1>

[TO BE ADDED]      
&nbsp;

<h1 align="center">Credits & Thank yous</h1>

Thanks to:
* Dortania for the awesome guide
* AMD OS-X
* corpnewt
* r/hackintosh
* the hackintosh community!
* Visual & NootedRed for their extremely valuable help.
* NootedRed community (some awesome people, go check them out!)