audio_hdmi_9series
============
OS X Haswell/9 Series/Socket 1150 - HD4600/AMD/Nvidia HDMI Audio
OS X Haswell/9 Series/Socket 1150 - 9series LPC
With or Without DSDT Edits

Update: v2.2 - 2/3/2015  9series ssdt update; do not use DropOEM
Update: v2.1 - 12/22/2014  9series LPC
Update: v2 - 8/15/2014

Update: 10.9.4 requires new AppleHDA patch for OS X Haswell/HD4600 HDMI audio. The v2 patch supports 10.9 and newer. Credit TimeWalker75a

HDMI audio for OS X 9 Series HD4600 systems with either: 1. HDMI audio edited dsdt or 2. the HDMI audio ssdt.  HD4600 HDMI audio is not native; AppleHDA.kext and AppleIntelFramebufferAzul.kext require edits.  Credit: PikeRAlpha for both fixes.

Details
[Guide]_HD4600-hdmi_audio_(dsdt_or_ssdt)_v2.1.pdf, see https://github.com/toleda/audio_hdmi_8series
[Guide]_OS_X_hdmi_audio-dsdt_v2, see https://github.com/toleda/audio_hdmi_guides
[Guide]_OS_X_hdmi_audio-ssdt_v2, see https://github.com/toleda/audio_hdmi_guides

OS X 9 Series HD4600/AMD/Nvidia HDMI Audio (Audio ID: 1 = patch-A1 = filename-1, etc.)

9series LPC
dsdt/LPC edit: MaciASL/Patch/AMI-Enable_LPC-9series
1. Configure MaciASL/Preferences/Sources/+ with URL:  (copy/paste URL below)
2. https://raw.github.com/toleda/audio_hdmi_9series/master
ssdt/LPC: 9series_ssdt/ssdt-ami-9series_lpc

Problem Reporting
1. Required info:
   1. [Guide]_HD4600-hdmi_audio_(dsdt_or_ssdt)_v2.1.pdf
2. Post to:
   1. http://www.insanelymac.com/forum/topic/292999-mavericks-applehda-hdmi-audio/
   2. http://www.tonymacx86.com/hdmi-audio/112469-mavericks-hdmi-audio-applehda.html

Credit:
PikeRAlpha https://pikeralpha.wordpress.com/2013/09/19/haswell-hdau-solution/
bcc9 Post #11 - http://www.insanelymac.com/forum/topic/290783-intel-hd-graphics-4600-haswell-working-displayport/?p=1934889
TimeWalker75a Post #118, http://www.insanelymac.com/forum/topic/290783-intel-hd-graphics-4600-haswell-working-displayport/?p=1949558

toleda
https://github.com/toleda/audio_hdmi_9series
README.txt