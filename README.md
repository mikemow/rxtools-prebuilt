prebuilt rxtools: http://github.com/roxas75/rxtools

Note: you don't have to have firmware.bin and rxtools.dat,it is outdated.

FIRM is already downloaded.

Other folder contain HTML you have to launch on your 3ds browser to acces code.bin and launcher.dat.

To install this,you can just copy prebuilt/release/rxTools and slot0x25KeyX.bin folder in your SD card and launch other/dukesrg.no-ip.org in your 3DS browser.For the FIRM,pick the one for your model (New3DS or 0ld3DS),rename it firm, and put it in your SD in: /rxTools/ folder you just copied.

You can also go to the real URL:

http://dukesrg.no-ip.org/3ds/cakes/?rxTools/sys/code.bin

http://go.gateway-3ds.com/

If slot0x25KeyX.bin do not work,copy/past this in a file you created and renamed slot0x25KeyX.bin:

CEE7D8AB30C00DAE850EF5E382AC5AF3

Finally,to use dukesrg.no-ip.org,you have to loacalhost by using "Hosting" step and then,redirect your 3ds browser like this:<

http://yourinternalip/dukersg.no-ip.org/?file/to/load/on/sd

(you have to put the ? before file path)

An example:

https://192.168.15.22:2343/dukersg.no-ip.org/?rxinstaller.bin

#### Hosting ####

On Windows:

Follow the great Bullywiiplaza's video [here](https://www.youtube.com/watch?feature=player_embedded&v=b-ztG3JmyE8).

On Linux/Mac OS X:

You can create a simple server using these commands:

`cd path/to/homebrew/`

`python -mSimpleHTTPServer 2343`

Put on your Wii U browser: http://yourinternalip:2343/

To find your IP address, do the command: `ifconfig` and look at the `wlan0/inet adr:` connection.


