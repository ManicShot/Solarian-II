### Welcome to the Solarian II github!
![Startup splash crop alpha](https://github.com/user-attachments/assets/cfa272de-dc9a-48ff-8f1a-53179c3995ab)


For those who want to play the classic 1990 space shooter game Solarian II 
developed by Ben Haller of [Stick Software](http://sticksoftware.com/) 


![001_Splash_start_auto_splitter](https://github.com/user-attachments/assets/a4559bd9-b165-4782-8a1b-e317cc507277)


Solarian II runs on classic Macintosh systems, so to play today you'll need to download ![multiplier 3x](https://github.com/user-attachments/assets/f573fa08-7430-4aaa-9107-43ff0e61ef5b) items:

1) Emulation software
2) A ROM file
3) A MacOS disk image
   
Links for each below, with further instructions to follow:

### 1. Emulator

There a few different ways to emulate the Macintosh system. For this guide we're recommending **Basilisk II**.

Head to one of the following links at the emaculation.com forums to download the latest version

* Basilisk II for **Windows**

  ⁃ download the latest version - https://www.emaculation.com/forum/viewtopic.php?t=5282
 
* Basilisk II for **OSX/macOS**

  ⁃ download the latest version - https://www.emaculation.com/forum/viewtopic.php?f=6&t=7361
    
* Basilisk II for **Linux**

  ⁃ download the latest version - https://www.emaculation.com/forum/viewtopic.php?t=6580



### 2. ROM file

For this guide we're using a **Quadra ROM** from 1997. You can use other ROMs but this works as good as any other.

`Quadra.rom`

https://github.com/Solarian-II/Solarian-II/blob/main/Quadra.rom

or [direct download](https://github.com/c864488b-9467-4c21-b471-019d4dbfbe9d) - (1 MB)

### 3. Disk Image

Normally you would have to setup and install a system yourself, but this takes all the work out of that

Head here to download a disk image of a **System 7.5.3** minimal install (it has a copy of Solarian II v1.04 pre-installed):

`MacOS753_mini10.dsk`

https://github.com/Solarian-II/Solarian-II/blob/main/MacOS753_mini10.dsk

or [direct download](https://github.com/c5ca7ae6-29f3-4c44-b3a3-7538520c6964) - (10.5 MB)


Now that you have the ![multiplier 3x](https://github.com/user-attachments/assets/f573fa08-7430-4aaa-9107-43ff0e61ef5b) items downloaded, you can proceed

![supply stork](https://github.com/user-attachments/assets/fc6caf23-a31c-4ade-915f-b0d36500dfd2)

## INSTRUCTIONS TO INSTALL

1. Start BasiliskIIGUI

2. Configure Volumes

    In the 'Volumes' tab click 'Add...' to browse for `MacOS753_mini10.dsk` and add to the list

3. Configure System:

#### ROM File
  
Click 'Browse' and navigate to `Quadra.rom`

  ⁃   The path to the rom file should now appear in the text field.

The rest of the settings should be set by default, but in case not, here are the recommendations:

#### MaOS RAM Size (MB)
  
  ⁃   The amount of memory to assign to Basilisk. Set it to 128 or 256.

#### Mac Model ID
  
  ⁃   Set the `Model ID` to “Quadra 900”.

#### CPU Type
  
  ⁃   Set `CPU type` to “68040”

#### CPU idolatry and memory access
  
  ⁃   Don't use CPU when idle and Ignore Illegal Memory Accesses
  
  ⁃   Make sure both options are checked.

#### JIT
  
   ⁃   Do not enable JIT compiler. 
   
   ⁃   Note this might be in a tab of its own, depending on the version installed

#### Keyboard
  
   ⁃   For US keyboards you can ignore this step. 
   
   ⁃   For non-US and non-standard keyboards you may need a keycodes file. If you need assistance with this, see the setup guides in the final section below


You can now save the GUI preferences and start Basilisk II

You should have a screen that looks something like this:

![Mini753_2](https://github.com/user-attachments/assets/795b22dc-5d0d-4141-8271-542578d82aa2)


## Get that game running

Go ahead and double click Solarian II to play

![Startup splash](https://github.com/user-attachments/assets/1da8beca-01d9-4266-8eb2-fe3bc74f7bb6)

________________
## HAVE FUN 👾
________________

![vlcsnap-2024-08-25-12h57m38s672_15](https://github.com/user-attachments/assets/5986db04-318f-4309-90ae-56aadc34487d)



## Tip on scaling for larger displays

For the crispiest of crispy pixels, it is recommend to double the screen size and use integer scaling

One way to do this is set the emulator dimensions to half that of the actual display, and then ensure fullscreen is ticked

for example if you have a 1920x1080 display, set the emulator to 960x540 with fullscreen enabled

Next add some custom lines of text to your preferences file. Open the file in a text editor and append the following code to the end:

          `scale_nearest true`
          
          `scale_integer true`

The preferences file will be called 

  ⁃  "BasiliskII_prefs" (Windows)
    
  ⁃  ".basilisk_ii_prefs" (Mac). It's hidden by default on Mac so press `cmd`+`shift`+`.` to show hidden items, and look in your home directory
    
This scaling uses NN sampling (nearest neighbour, or "neighbor" for all you freedom spellers out there) to get those extra crispy pixels, and makes it clearer to view on retina displays.


## Setup guides

In case you run into any issues, here are Setup Guides for each system:

  * Windows           https://www.emaculation.com/doku.php/basilisk_ii_setup
  * OSX/macOS         https://www.emaculation.com/doku.php/basiliskii_osx_setup
  * Linux             https://www.emaculation.com/doku.php/sheepshaver_basiliskii_linux


Lastly if anyone has recommendations to streamline this process or improve this guide, please get in touch or submit an issue. Thanks!

![Peace](https://github.com/user-attachments/assets/75e6cbb5-d618-41a0-9434-206024f04f65)


