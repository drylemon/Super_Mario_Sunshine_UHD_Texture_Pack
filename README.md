# Super_Mario_Sunshine_UHD_Texture_Pack
[DDS DOWNLOAD](https://drive.google.com/open?id=183ptyXZvE27mZfo0LvxuqTJzYOcqPdkb)
![](https://raw.githubusercontent.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/master/GMS/gui/title/tex1_490x270_8173791dd11cea7c_5.png)
### TLDR: Upscales and retextures of the whole game.  Check "Prefetch Custom Textures" in the "Advanced" tab of the Graphics settings on the 5.0 build of Dolphin to prevent stuttering.

[Click here to see comparisons!](../../wiki)

### -About the pack-

I've been using [waifu2x](https://github.com/nagadomi/waifu2x),  a free, web-based upscaler that uses deep convolutional neural networks, and I've gotten some incredible results out of it for certain textures, most notably the goo textures.  I manually ran each texture through waifu2x, and inspected them, testing settings to see what looked best.  I used [Bighead's Custom Texture Powershell script](https://forums.dolphin-emu.org/Thread-dolphin-custom-textures-info) to make the goo and other seamless textures, big thanks to him!  A few original textures are too low-res for waifu2x to make good upscales from.  Using Gimp, I manually upscaled a few textures: low-res banners, letters, text, and small character maps.  I also manually retextured certain textures that I felt required more than just upscaling to be acceptable in a UHD pack.  Most notably the main menu A, B, and C save blocks were retextured.  For the wanted poster, I edited a screenshot from an in-game cutscene that shows the poster at a higher resolution.

### -Recommended Settings-

Make sure to check "Prefetch Custom Textures" in the "Advanced" tab of the Graphics settings on the 5.0 build of Dolphin, this will cache the custom textures to RAM when Dolphin loads the game. This will prevent all stuttering caused by using custom textures. This texture pack should only load less than 2 GB to RAM (without the goo maps) which shouldn't be a problem for computers capable of playing the game at UHD smoothly anyway.

Look at the [Dolphin wiki page for Super Mario Sunshine](https://wiki.dolphin-emu.org/index.php?title=Super_Mario_Sunshine) and follow the graphics settings configurations.  One deviation I make from that configuration is to enable Scaled EFB Copy because it makes bodies of water look way better.  I also highly recommend using V-Sync to avoid tearing.  I do not use the widescreen code on the wiki because it causes problems for me, although I've heard it works fine for others.  These are the only Gecko codes that I use:  
$60FPS (Region-Free)  
F6000002 80008180  
BF800000 3F000000  
00000000 43300000  
14000004 3F800000  
E0000000 80008000  
F6000002 80008180  
801E0074 901E0038  
801E007C 901E0078  
14000014 60000000  
E0000000 80008000  
F6000001 80008180  
40800034 C03F00D0  
D2000004 00000002  
3DC03F80 91DF00D0  
C03F00D0 00000000  
E0000000 80008000  
$16:9 Aspect Ratio (Widescreen) [NTSC-U]  
04416B74 3F9A7643  
$Remove Heatwave Effect Code NTSC-U:  
0419F83C 4E800020

Enjoy!

### -Resources-

If anyone reading this wants to make their own texture pack, here's some links to the websites, apps, and other resources I used:<br>

This is the web version:<br>
http://waifu2x.udp.jp/

Here's a web version that can do batches of textures:<br>
http://waifu2x.me/

Here's the desktop version I used, scroll down to the zip which contains the precompiled exe (not the source zip) and download it:<br>
https://github.com/lltcggie/waifu2x-caffe/releases

CUDA download, you will have to make an account:<br>
https://developer.nvidia.com/cuda-downloads

Of course check out Bighead's custom textures post and his custom texture tool which is very good for creating seamless textures, doing file conversions, optimizing png files, and other things that would be quite awful to do manually:<br>
https://forums.dolphin-emu.org/Thread-dolphin-custom-textures-info

I would test some textures using the waifu2x web version and the desktop version to see which will be faster for you. If you don't have an NVIDIA graphics card and CUDA acceleration you might want to just stick with the web version, however if your internet speed isn't that good definitely use the desktop version even if it's just using your CPU.

### -Community Requests-

tree shadows : Some of the original tree shadows create a white box around the trees, does anyone know how to fix this?<br>
miscellaneous fixes/improvements : If you think certain textures look bad and want to fix/improve any of the textures I've already made, post your edits on the forum and I can add them to the github.<br>

### Donate!

Bitcoin:
1562cPDAqTCtF1oX6RPMy1n8Rx6jvzYTvN

Ethereum:
0xb4355179da353f1BA4AA0BB5a7E3Ba4FdC7128ea

Patreon:
[https://www.patreon.com/qashto](https://www.patreon.com/qashto)

Paypal:
[https://www.paypal.me/qashto/5](https://www.paypal.me/qashto/5)
