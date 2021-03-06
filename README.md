<pre>
##############################################################################
#                                                                            #
#                 Carliv Image Kitchen for Android v1.1                      #
#              for android phones copyright(c)2016 carliv@xda                #
#             including support for MTK powered phones images                #
#                              LINUX version                                 #
#                                                                            #
##############################################################################	
</pre>	
To use this Android images kitchen is very easy. First, place your image files in corresponding folders: boot images in [boot-resources] and recovery images in [recovery-resources].

Start the kitchen by double click on { carliv } file, then choose [Run in Terminal] and follow the informations on the screen - it's easy. All menu letters are case Insensitive and you can type how you want [B or b, etc.], and the numbers... are just numbers :). If the "carliv" script doesn't run with double click, or if you don't see the dialog for Run in Terminal, Display, Run etc, but instead it opens in a text window, check the executable permission, because maybe your system changed that after unpack. If still don't see that dialog box after you checked the permissions, open a terminal window in the Kitchen folder and type [ ./carliv ] then enter, to start it manually.

ATTENTION again! When you unpack the archive, it is better to not use the fancy file-roller or whatever archive GUI application you have: use the terminal commands.

If your phone is MTK powered, the built binaries and the scripts will handle these images automatically. 

After you finished your modding job, to repack the image do the same, but this time select the repack menu items. NOTE: If you have unpacked more than one image, to repack select that image again from boot or recovery images list section, and the script will know to find corresponding folder for repacking (if you have deleted that folder it will display an error on process). To go to boot or recovery list selection menu, just type [E] - Go Back to select from unpack/repack scripts menu, then select the image you worked on and want to repack it back. 

The new image will have original name with a time stamp appended to it and will be saved in [output] folder. NOTE: These scripts and binaries are dependent on type of image integrated in name: boot for boot images and recovery for recovery images. If your image has a different name (let's say a recovery named twrp.img), the script will append automatically the type on it's name, based on the folder you select the image from (in that example it will be recovery-twrp.img), and the repacked image will have that name plus the time stamp.

If you don't want to unpack the image but only to see or to check it's informations (offsets, sizes, addresses, cmdline, etc.) for various reasons, just select the { image info menu } and you will see all these on terminal. Also a text file with all informations will be saved in utility's root folder.

ATTENTION! This Image Kitchen is built to work on any path, but to avoid any possible breackage, please don't use folders or images with spaces or special characters in name; use only letters [a-Z], numbers [0-9] and usual signs [- or _], and stay away from [!@~`%$#*&(){}[]<>\/....] or other like these.
	
My tool doesn't have restrictions on placement. For me it worked in last partition, in sub-subfolder, without problems.

Please respect my work and if you use it don't forget to hit the THANKS button in my thread or to make a donation to buy me a coffee. And if you take it and share it on other sites, or integrate it in other tools, give proper credits for my work.
	
I built from source every working module, and the lz4 binary. For everything to work well you need to have installed in your system these (my example is for ubuntu):

- sudo apt-get install bzip2
- sudo apt-get install lzop
- sudo apt-get install xz-utils
- sudo apt-get install liblz4-tool
<pre>	
##############################################################################
#                                CREDITS                                     #
#  * michfood from xda.developers for the initial starting ideea;            #
#  * osm0sis from xda.developers for his Android Image Kitchen, which gave   #
#  me some hints;                                                            #
#  * Cyanogenmod Project and Omnirom for the initial source code             #
#  of binaries;                                                              #
##############################################################################		
</pre>	
