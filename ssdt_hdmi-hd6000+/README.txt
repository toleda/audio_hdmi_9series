audio_hdmi_9series/ssdt_hdmi-hd6000+
============
OS X Broadwell/9 Series/Socket 1150 - HD5500/HD600+ ssdt

ssdt_hdmi-hd5500+
Supports Mobile/HD5500
Injects BDW/framebuffer: 0x02001616 (LVDS DP DP  GT2 34MB)

ssdt_hdmi-hd6000+
Supports Mobile/HD6000/HD6100/HD6200
Injects BDW/framebuffer: 0x06002616 (LVDS DP DP  GT3 34MB)

ssdt_hdmi-hd6100
Supports Mobile/HD6000/HD6100/HD6200
Injects BDW/framebuffer: 0x04002B16 (LVDS DP DP  GT3 34MB)

ssdt_hdmi-hd6200
Supports Mobile/HD6000/HD6100/HD6200
Injects BDW/framebuffer: 0x02002216 (LVDS DP DP  GT3 34MB)

HD 5500/6000+/6100/6200 HDMI audio
OS X/Mobile/5500/6000 audio is native, see
tba
https://github.com/toleda/audio_hdmi_9series

Patch:
1. DP audio is native
2. HDMI/DVI audio requires AppleIntelBDWGraphicsFramebuffer.kext patch.
   Find: 01050B000004000007050000
   Rplc: 01050B000008000082000000
   Cmmt: 10.10-BDW6000-Port_0x5-DP2HDMI

Installation (included in download)
1. [Guide]-OSX_ssdt-installation

Problem Reporting: see https://github.com/toleda/audio_hdmi_9series README.txt

toleda
https://github.com/toleda/audio_hdmi_9series/ssdt_hdmi-hd6000+
README.txt