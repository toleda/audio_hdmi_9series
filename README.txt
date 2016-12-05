audio_hdmi_9series
============
OS X Haswell/9 Series/Socket 1150 - HD6000+/AMD/Nvidia HDMI Audio
OS X Haswell/9 Series/Socket 1150 - 9series LPC
With or Without DSDT Edits

v4: 12/2/16 - Clover ssdt rename, cloverHDMI support
v3: 8/10/15 - New ssdt method/credit RehabMan, initial 10.11 support, native 
    CPU/GPU PM and Nvidia Maxwell support
v2.2: 2/3/15  9series ssdt update; do not use DropOEM
v2.1: 12/22/214  9series LPC
v2: 8/15/14

Update: 10.9.4 requires new AppleHDA patch for OS X Haswell/HD6000+ HDMI audio. The v2 patch supports 10.9 and newer. Credit TimeWalker75a

HDMI audio for OS X 9 Series HD6000+ systems with either: 1. HDMI audio edited dsdt or 2. the HDMI audio ssdt.  HD6000+ HDMI audio is not native; AppleHDA.kext and AppleIntelFramebufferAzul.kext require edits.

Details
[Guide]_HD4600-hdmi_audio_(dsdt_or_ssdt)_v3, see https://github.com/toleda/audio_hdmi_8series
[Guide]-OSX-hdmi_audio-hdef_audio-dsdt_v3, see https://github.com/toleda/audio_hdmi_guides
[Guide]-OSX-hdmi_audio-hdef_audio-ssdt_v3, see https://github.com/toleda/audio_hdmi_guides

OS X 9 Series HD6000+/AMD/Nvidia HDMI Audio (Audio ID: 1 = patch-A1 = filename-1, etc.)

9series LPC
dsdt/LPC edit: MaciASL/Patch/AMI-Enable_LPC-9series
1. Configure MaciASL/Preferences/Sources/+ with URL:  (copy/paste URL below)
2. https://raw.github.com/toleda/audio_hdmi_9series/master
ssdt/LPC: 9series_ssdt/ssdt-ami-9series_lpc

Problem Reporting
1. https://github.com/toleda/audio_ALC_guides/blob/master/Problem%20Reporting.md

Credit:
PikeRAlpha https://pikeralpha.wordpress.com/2013/09/19/haswell-hdau-solution/
bcc9 Post #11 - http://www.insanelymac.com/forum/topic/290783-intel-hd-graphics-4600-haswell-working-displayport/?p=1934889
TimeWalker75a Post #118, http://www.insanelymac.com/forum/topic/290783-intel-hd-graphics-4600-haswell-working-displayport/?p=1949558

toleda
https://github.com/toleda/audio_hdmi_9series
README.txt