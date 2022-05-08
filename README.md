# How-to-get-the-max-performace-in-Minecraft-on-Chromebook
This is a guide with all the commands on how to run minecraft much faster than you are right now



Okay so you installed minecraft with crostini and it runs really slow or you want it to run better.
Or you installed it with crouton and runs really fast but you think that is the max your chromebook can do.

Well actually NO you can run it way faster than you think.

I have a Hp chromebook 14 BLOOG
Specs:
4gb ram 
Intel n4000 2.8 ghz


But STILL WITH ALL THE SETTINGS I have it runs minecraft at above two hundred always in a discord call



# So you are ready, lets Begin

So f you think you have a chroot desktop you are good to go. Well no you need this specific chroot i am about to give you for this to work becuase this has a specific x server.

1. Enable Developer mode if not akready
2. Download [crouton](goo.gl/fd3zc)
3. Press ctrl + alt + t 
4. Type Shell
5. Type sudo install -Dt /usr/local/bin -m 755 ~/Downloads/crouton
6. Type this command and wait till it is done (YOU WILL HAVE TO INTERACT MID PROCCES FOR A USERNAME AND PASSWORD): sudo /bin/bash -c "$(curl -fsSL https://git.io/JfSPp)"
7. After it is done start the desktop using sudo startplasma
8. Download this  deb file for your device in Firefox in the  crouton/linux desktop: [https://github.com/TheAssassin/AppImageLauncher/releases](url)https://github.com/TheAssassin/AppImageLauncher/releases 
9. Name the file App.deb
10. Go to terminal and type the following command: cd Downloads, sudo dpkg -i App.deb
11. It will download the app now go install the latest version of linux lunar client on their website
12.After download Double click on the file to open with AppImageLaucnher
13. After install open the app atleast once and then close it
14. After that right click on the app then click details
15. After that click on commad and then copy the command of the application mine looks lie this "/home/sudham/Applications/Lunar Client-2.10.1_d89016e3fcbc71e73fb16d46b384fc83.AppImage" --no-sandbox %U
16. after copying create a file called .xinitrc
17. type this vblank_mode=0 exec and then the apllication commad you copied and press ctrl + s to save
18. Now exit out of the dekstop back to chrome os 
19. now, while staying in Shell, type this sudo enter-chroot neon 
20. after taking you in the chroot you type xinit
21.  HAVE FUN!!!!!!



# Now you have it but still want MOre.......


 You get a ton more FPS but you still want more performace out your device ????????????


Dont worry there is still a way but it reqires a sacrifice, you have to lose a bit of quality but it wont matter that much (I personally do it)

Okay startoing off 
1. Press ctrl + alt + t 
2. type shell
3. Then type sudo enter-chroot neon
4. do sudo nano .xinitrc
5. Move the first sentence to the second sentence by pressing enter at the start
6. Type the following in the first sentence : xrandr -s 1280x720 &
7. Press ctrl + o to save 
8. Press ctrl + x to exit
9. Then press sudo enter-chroot *IF* you left the chroot shell
10. type xinit now 

# Now you are all set with device settings moving on to minecraft settings (If you still want more fps)


You still want more fps and you dont know what minecraft and lunar cleint setttings are the best for you?

Dont worry i am going to give you two files that are going to automatically chnage all the settings and give more fps.




First of all, go to .minecraft in the kde neon desktop (sudo startplasma)

You should see three .txt documents called : options.txt , optionsof.txt and optionsLC.txt  

1.  Download these three modified files : [options.txt](https://github.com/Sudham6/How-to-get-the-max-performace-in-Minecraft-on-Chromebook/files/8647317/options.txt) 
                                         [optionsof.txt](https://github.com/Sudham6/How-to-get-the-max-performace-in-Minecraft-on-Chromebook/files/8647327/optionsof.txt)
                                          [optionsLC.txt](https://github.com/Sudham6/How-to-get-the-max-performace-in-Minecraft-on-Chromebook/files/8647328/optionsLC.txt)
2. after downloading all these files delete your  options.txt , optionsof.txt and optionsLC.txt   and paste these there and restart your minecraft and you will have these settings 







## Just in case these do not work you have to mannualy change these settings yourself



Copy down these in minecraft video settings 

                
