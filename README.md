
# LG-G6-FRP-BYPASS

_This wiki is for private usage and as a reminder if I will get another LG G6._

This device has been by far the most difficult phone to hack all categories, probably spent over 100 hours to bypass FRP.

*No* wiki's out there actually work the idiots or let us call them scammers (yeah, even dr phone and such programs wont work)  and some tutorials even may brick your device, not even xda forum have legit tutorial for this device so hopefully someone will enjoy this unique and probably only wiki for bypassing FRP protection on LG G6 870 for 100% real.

# HOWTO - ANDROID 7.0 

* If you got Android 8.0 Oreo then you must re-flash your firmware to Android 7.0, it wont  matter what firmware you choose from https://lg-firmwares.com/ until we really hacked the device, just pick one and download the file and flash your device with LGUP tool, go grab the tool + dll file from here: https://www.mylgphones.com/download-lg-up-software.

But before we re-flashing device and you trying to find a way to install the apks since settings is limited to network only let me show you how to install apk files on this firmware since LG techs forgot to set permissions on the email client for install applications outside play store. 

### INSTALL APKS ON ANDROID 8.0 LOCKED BY FRP

##### NOTICE: This is NOT allowed on Android 7.0 so don't bother to try, it will just bring you to the limited settings panel with netowrk settings only and you wont be able to move on to developer settings or overide apps settings: 

1) Start your device

2) On welcome screen press next button

3) Press on skip in lower right corner

4) Turn wifi on and login on your wifi

5) Go back to welcome screen

6) Press on Accessibility

7) Press on settings

8) Press on Switch Access

9) Press on settings in down right corner

10) Press on Help & Feedback

11) Press on About Switch Access for Android

12) Touch the youtube video once

13) Click on the clock icon beside the share icon

14) Youtube is starting quickly and taking you to google chrome browser

15) Now click on Accept & Continue

16) In down left corner click on No Thanks

17) Now browse to https://nr1.nu/i/archive/lg-g6/terminal.apk

18) Click on update permissions

19) Click on Allow

20) Wait until file has been downloaded
-)  Now to the problem, you won't be able to install this application
    since the settings and hiddenmenu are disabled and you will just
    get redirected to the limited settings, it wont help to use
    quickshortcutmaker or similiar tools for launch development settings, why?`Duh! Cause it's not even installed! And cause selinux you wont be able to overide the current settings neither so you are stuck, just give up!
    
21) Go back to the youtube screen by pressing arrow back

22) Start a video, choose the share button

23) Choose E-mail application provided by LG the white icon with a blue E

24) Allow the permissions for access contacts + E-Mail address

25) Choose to sign in with your email (NOT A GMAIL ACCOUNT IT IS NOT VALID AND WONT WORK AND WILL REDIRECT YOU TO THE LOGIN SCREEN WERE YOU MUST LOGIN WITH THE OLD MAIL ACCOUNT)

26) Wait until you get's connected and just hit next followed by done

27) Now you are on "Send Message" in your e-mail application

28) Choose the the add file button, upper right behind your e-mail address

30) Now press on the terminal.apk file that you added

31) You will now be allowed to install the application without enabling any permissions since they forgot to add permission denied on this one

32) After you installed the application, you can choose to open terminal in lower down corner

33) Now you will notice EVERYTHING is locked due to selinux enforcing and you wont even be allowed to list applications by pm list applications

34) What you wanna do now is to browse back to youtube screen in accessibility screen and press on the clock to start google chrome again and feel free to download and install ALMOST any apk file.

34) It wont help to install lgsetupwizard.apk, luckypatcher.apk, settings.apk or any other applications since you wont be able to turn permissions ON for the required features. You are not even allowed to use UUSD for open hidden menu on 8.0, BUT this will work on Android 7.0 so you must downgrade to Android 7.0, all applications that you have installed before you downgrading will be wiped so don't spend to much time for install your apps since it's a waste of time.

# FOR BYPASS FRP

If you're on Android 8.0 and need reflash your device you can browse to lg's homepage and see how this can be done, since this is another process I wont go deeper in this topic but the main process is: 
 - 1) Start LGUP Tool
 - 2) Reboot your device to recovery mode by:
 - 3) Power off device and enter recovery mode by hold VOLUME UP while you plug in the usb cable while its still off
 - 4) Now choose your firmware file in LGUP tool and flash the firmware. Thats it.

Just for saying, when you downgrading from android 8.0 to android 7.0 your device will be wiped and if you installed any apks by above method you wont be able to use the applications on android 7.0 since its fully erased. If you are on Android 7.0 and upgrading to 8.0 instead your device wont be erased but this does not really matter since you wont be allowed to install applciations the same way as on android 8.0 cause this bug is only on android 8.0 AFAIK! Howerver, let us bypassing FRP now: 

1) Start your device after you installed Android 7.0

2) On welcome screen press next button

3) Press on skip in lower right corner

4) Turn wifi on and login on your wifi

5) Go back to welcome screen

6) Press on Accessibility

7) Press on settings

8) Press on Switch Access

9) Press on settings in down right corner

10) Press on Help & Feedback

11) Press on About Switch Access for Android

12) Touch the youtube video once

13) Click on the clock icon beside the share icon

14) Youtube is starting quickly and taking you to google chrome browser

15) Now click on Accept & Continue

16) In down left corner click on No Thanks

- If you don't trust me and want to explore things by your own, you can do:
    Now browse to https://nr1.nu/i/archive/lg-g6/terminal.apk
    Click on update permissions
    Click on Allow
    Press install when done, now I wish you luck for bypassing the permissions! :-)
   
17) Once google chrome has been started, go to a page that allowing you to press on a phone number, for example on Telia.se - You can press ![here](https://www.telia.se/privat/kontakt/butikerochaterforsaljare/borlange) for get redirected to telia.se and here you can press on a phone number, your phone application will be started.

18) Enter UUSD: *#546368#*870# where 870 is the device model, since we have a LG G6 870 we entering 870, you are now in HiddenMenu

### Don't get panic! If USB Debugging is inactive and you are not allowed to enable usb debugging! (users that not have this issue can jump over part)

   - Turn off your LG device
   - Re-do the flash process with LGUP
   - Once the installation is complete and your device is erasing itself with the white background and the android logo on screen saying "DO NOT TURN OFF YOUR DEVICE" - That's exactly what you must do so turn off device by hold POWER + VOLUME DOWN (if you will be to late first time, you will succeed second time just press the buttons ~2-3 seconds before you know the screen will popup so you will poweroff the device during installation) - Now let the device be powered off for ~1 minute and then turn it on again and redo the process from step 1 until 22 and you will be enable to enable usb debugging if you wasn't to late when powering off the device, IF it's still inactive then just try again and try again until it will work, actually I figure out this after my third attempt and now I have tried this several times and you must turn it off while it's between 0% and 100% and since POWER + VOL DOWN takes ~7 seconds to power off device and the screen appears for around 4 seconds you must press the buttons few seconds before to turn it off exactly when it's needed.

19) Once you got into Hidden Menu, press on:
     - Device Menu 
     - LDB
     - USB Debugging - Turn on debug mode when usb is connected


20) You are now allowed enter USB Debugging but this wont help much due to the permissions issues BUT now you are allowed to list application wich means you are allowed to uninstall them aswell (still not allowed to start any application or do anything almost since / is mounted as ro): Now do exactly as below and don't install other apps if you don't know exactly what you doing then you might be stuck and have a softbricked device, just follow this and you're safe!

![Screenshot](https://nr1.nu/archive/lg-g6/lg-remove-apps.gif)

     adb shell pm uninstall --user 0 com.android.google.gms
     adb shell pm uninstall --user 0 com.lge.setupwizard
     adb shell pm uninstall --user 0 com.lge.hiddenmenu
     adb shell pm uninstall --user 0 com.google.android.setupwizard
     adb shell pm uninstall --user 0 com.lge.easyhome
     adb shell am broadcast -a android.intent.action.MASTER_CLEAR
     adb reboot 
     
* Once device rebooted after you ran reboot, turn off the device while its installing with the white background and android logo on screen and let the device be turned off for ~1 minute and then powering off your device - When you are back back to welcome screen (It's safe to turn off device during install, did it several times for trying)

21) Press on next button 
22) On wifi settings do NOT have a sim card or connect to a wifi
23) Just press skip down in right corner, and just move on until you enter HOME SCREEN and your done! Google can't connect to their servers due we removed the gms package and lgsetupwizard is gone so frp protection can't be triggered, reinstall applications from /system application and enjoy your fully unlocked LG G6 870S device!

Enjoy your fully unlocked LG G6 870 - If you're smart, download LG Bridge and put your device into download mode and upgrade your device to a proper firmware for you country.

Mission complete. 

### Other bugs I found while trying bypassing the FRP

When you are at wifi settings and the next button is inactive because you are forced to connect to a network then do as following to move further, exactly the same second as you turning off the wifi then press on next button before the button getting inactive/grayed out and you will be asked if you wanna continue to the next step, you will now be allowed to take over the pin code and erase the old owners lock setting, but don't be to excited once this step is done and when you was allowed to enter the username you will be redirected back to the wifi screen and you wont be able to go further until you are connected to the wifi (you can still turn off wifi and press next the same second but you will be sent back to wifi settings again no matter if you trying 20 times or 1 time, did it myself). In some tutorials out there some claims you can take over lockscreen settings by entering the phone application and go to settings and setup new certificates and then be allowed to install your own fingerprint, this is waste of time and it's much easier to use this bug to take over the pin code (this is just for saying and has nothing todo with the frp bypassing even if some wikis say so)

#### This was a challenge and I bet other ppl that is still trying to break this device that hasn't seen this wiki will agree with 100%! Thanks LG.

### Life's Good ! // wuseman

### UUSD CODES LG

     *#546368#*870# 
     LG secret codes

    *#*#34971539#*#* - This code is used to get information about phone camera. It shows following 4 menus:
    * Update camera firmware in image (Don't try this option)
    * Update camera firmware in SD card
    * Get camera firmware version in LG G6
    * Get firmware update count

    WARNING: Never use the first option otherwise your phone camera will stop working and you'll need to take LG G6 to service center to reinstall camera firmware.

    *#*#7594#*#* - This one is favorite one. This code can be used to change the "End Call / Power" button action in your phone. Be default, if you long press the button, it shows a screen asking you to select any option from Silent mode, Airplane mode and Power off.

    You can change this action using this code. You can enable direct power off on this button so you don't need to waste your time in selecting the option.

    *#*#225#*#* - Events calendar.

    *#*#426#*#* - Debug information for Google Play service.Google Play Services first appeared in 2012. In its initial version, it provided a way to access the Google+ API and OAuth 2.0. From those humble beginnings, it has spread to work with a variety of different Google services, allowing apps to communicate with them. Google Play Services is how other apps can access all the different Google APIs.

    *#*#759#*#* - Access Google Partner setup (Rlz debug interface).
    *#872564# - USB logging control
    *#9900# - System dump mode LG G6
    *#*#97#*#* - Language and Keyboard settings in LG G6
    *#*#46*#*# - Reset Sim in LG G6

    *#301279# - HSDPAHSDPA means “High Speed Downlink Packet Access” and is a technique used in the UMTS mobile communication system, the download speeds of currently 3.6 Mbit/s to 7.2 Mbit/s. HSUPA is developed commercially since 2007 in Germany. High Speed Downlink Packet Access (HSDPA, 3.5G, 3G + or UMTS broadband) is a data transmission method of the cellular standards UMTS, which was defined by the 3rd Generation Partnership Project. The method enables DSL-like data rates in mobile networks. HSDPA is available in Germany, among others by the network operators Vodafone, E-Plus, O2, and telecom and in Switzerland by Swisscom, Sunrise and Orange. In Austria operate the A1, T-Mobile, Orange and Three HSDPA networks./HSUPAHSUPA means “High Speed Uplink Packet Access” and is a technique used in the UMTS mobile communication system, the upload speeds up to 5.8 Mbit/s. High Speed Uplink Packet Access (HSUPA) is a transmission method of the UMTS mobile radio standard that allows higher data rates in the uplink and reduces the round trip time (often referred to as ping). HSUPA Category 6 were up to 5.76 Mbit / s and category 9 (Release 9) up to 23 Mbit / s can be achieved. HSUPA is part of Release 9 of UMTS. Control Menu

    *#7465625# - View phone lock status
    *7465625*638*Code# = Enables Network lock 
    #7465625*638*Code# = Disables Network lock
    *7465625*782*Code# = Enables Subset lock
    #7465625*782*Code# = Disables Subset lock
    *7465625*77*Code# = Enables SP lock
    #7465625*77*Code# = Disables SP lock
    *7465625*27*Code# = Enables CP lock
    #7465625*27*Code# = Disables CP lock
    *7465625*746*Code# = Enables SIM lock
    #7465625*746*Code# = Disables SIM lock
    *7465625*228# = Activa lock ON
    #7465625*228# = Activa lock OFF
    *7465625*28638# = Auto Network lock ON
    #7465625*28638# = Auto Network lock OFF
    *7465625*28782# = Auto subset lock ON
    #7465625*28782# = Auto subset lock OFF 
    *7465625*2877# = Auto SP lock ON
    #7465625*2877# = Auto SP lock OFF
    *7465625*2827# = Auto CP lock ON
    #7465625*2827# = Auto CP lock OFF
    *7465625*28746# = Auto SIM lock ON
    #7465625*28746# = Auto SIM lock OFF

    *#*#273283*255*663282*#*#* - This code opens a File copy screen where you can backup your media files e.g. Images, Sound, Video and Voice memo.

    *#*#197328640#*#* - This code can be used to enter into Service mode. You can run various tests and change settings in the service mode.

 
    WLAN, GPS and Bluetooth Test Codes:

    *#*#232339#*#* OR *#*#526#*#* OR *#*#528#*#* - WLAN test (Use "Menu" button to start various tests)

    *#*#232338#*#* - Shows WiFi MAC address MAC (Media Access Control), address is a globally unique identifier assigned to network devices, and therefore it is often referred to as hardware or physical address. MAC addresses are 6-byte (48-bits) in length, and are written in MM:MM:MM:SS:SS:SS format. The first 3-bytes are ID number of the manufacturer, which is assigned by an Internet standards body. The second 3-bytes are serial number assigned by the manufacturer.

    *#*#1472365#*#* - GPSThe Global Positioning System (GPS) is a satellite-based radio navigation system developed and operated by the U.S. Department of Defense. GPS permits land, sea, and airborne users to determine their position, velocity and the time 24 hours a day, in all weather, anywhere in the world. test

    *#*#1575#*#* - For a more advanced GPS test

    *#*#232331#*#* - Bluetooth test Bluetooth is a wireless technology standard for exchanging data over short distances (using short-wavelength UHF radio waves in the ISM band from 2.4 to 2.485 GHz) from fixed and mobile devices, and building personal area networks (PANs). Invented by telecom vendor Ericsson in 1994, it was originally conceived as a wireless alternative to RS-232 data cables. It can connect several devices, overcoming problems of synchronization.

    *#*#232337#*# - Shows Bluetooth device address in LG G6

    *#*#8255#*#* - This code can be used to launch GTalk Service Monitor. Gtalk Service Monitor and play services monitor are developer options to let you examine and debug the push connections to google talk and google play services. Below these, the "restore default heartbeats" button lets you bring back the original heartbeat exchange settings if you have to. The final button is about making a donation to the developer of this convenient app. and that is it! now, you are left to experiment with the data and wi-fi settings until you land the most comfortable intervals for you.

    *#*#36245#*#* - Access email debug information.

    Codes to get Firmware version information:

    *#*#4986*2650468#*#* - PDA, Phone, H/W, RFCallDate

    *#*#1234#*#* OR *#1234# - PDA and Phone firmware information

    *#*#1111#*#* - FTA SW Version (1234 in the same code will give PDA and firmware version)

    *#12580*369# - Software and hardware info

    *#9090# - Diagnostic configuration in LG G6

    *#*#2222#*#* - FTA HW Version

    *#*#44336#*#* - PDA, Phone, CSCThe Customer Service Code (CSC) plays an important role in the operation of your mobile device. Different countries have different standards for both voice and data communications to a cell phone tower. Although most countries follow the international standard for WiFi connects, there are variations from the standard. The CSC code ensures that your mobile device complies with the standards for your country, and your cell phone operator. The CSC code also determines the source for firmware updates via FOTA or Samsung Kies., Build Time, Changelist number

# Codes to launch various Factory Tests:

    *#*#0283#*#* - Packet Loopback

    *#*#0*#*#* - LCD display test

    *#*#0673#*#* OR *#*#0289#*#* - Melody test

    *#*#0842#*#* - Device test (Vibration test and BackLight test)

    *#*#2663#*#* - Touch screen version LG G6

    *#*#2664#*#* - Touch screen test

    *#*#0588#*#* - Proximity sensor test

    *#*#3264#*#* - RAM version LG G6

 


    GSM codes for LG G6

Change PIN For security, you can require a PIN code in order to use your SIM card in any device. This PIN code follows the SIM card from one device to another. A personal unblocking code (PUC), also known as a PIN unlock key (PUK), is used in 3GPP mobile phones to reset a personal identification number (PIN) that has been lost or forgotten. - ** 04 *, then enter the PIN old, and twice a new PIN.
Change PIN2 - ** 042 *, then enter the old The PIN2, and twice the new PIN2.
Unlock SIM-card (PIN) - ** 05 * then enter the PUK and new PIN twice
Unlock SIM-card (PIN2) - ** 052 *, then enter the PUK2 and new PIN2 twice

    Call Forwarding (you have to order the service from the operator)
    ##002# - Cancel all diverts
    ##004# - Cancel all conditional call forwarding
    **004* phone number # - Activate all conditional call forwarding

    Unconditional call forwarding (Call Forward All)
    ###21 - Switch off and deactivate
    #21# - Deactivate
    **21*phone number# - Enable and Activate
    *21# - Activate
    *#21# - Check the condition

    Diversion in case of "no answer"
    ###61 - Switch off and deactivate
    #61# - Deactivate
    **61* phone number# - Enable and Activate
    *61# - Activate
    *#61# - Check the condition

Setting the call time until the call forwarding option "no answer"
When installing forwarding on "no answer" you can set the time in seconds that the system allows you to hook. If during this time you have not picked up the phone, the incoming call will be diverted.
Example: - ** 61 * + ** 709576617601234 # 30 - set the waiting time of 30 seconds
Set timeout - ** 61 * Phone Number ** N #, N = 5..30 (seconds)
Remove the previous installation - ## 61 #

    Diversion in case of "not available"
    # ## 62 - Switch off and deactivate
    # 62 # - Deactivate
    ** 62 *phone number# - Enable and Activate
    * 62 # - Activate
    * # 62 # - Check the condition

### Diversion in case of "busy"
    ###67 - Switch off and deactivate
    #67# - Deactivate
    **67*phone number# - Enable and Activate
    *67# - Activate
    *#67# - Check the condition

### Call Barring (you have to order the service from the operator)
### Change the password for all bans (default - 0000)
    - ** 03 * 330 * old password * new password * new password #




### Barring of all outgoing calls
    **33*password# - Activate
    #33*password# - Deactivate
    *#33# - Check the condition

### Barring of all calls
**330*password# - Activate
#330*password# - Deactivate
*#330# - Check the condition

### Barring of all outgoing international calls
    **331*password# - Activate
    #331*password# - Deactivate
    *#331# - Check the condition

### Barring of all outgoing calls
    **333*password# - Activate
    #333*password# - Deactivate
    *#333# - Check the condition

### Barring of all incoming calls
    **353*password# - Activate
    #353*password# - Deactivate
    *#353# - Check the condition

### Barring all incoming calls when roaming
    **351*password# - Activate
    #351*password# - Deactivate
    *#351# - Check the condition

### Call waiting (you have to order the service from the operator)
    *43# - Activate
    #43# - Deactivate
    *#43# - Check the condition

### Transfer your phone number (Anti ANI)
    #30#phone number - Block
    *30#phone number - Allow
    *#30# - Check the condition

### Show phone number of the caller you (ANI)
    #77# - Block
    *77# - Allow
    *#77# - Check the condition

### Smart menu
    GP - *111#
    Rob - *140#
    Banglalink - *789#


#### REQUIREMENTS

A LG G6 870S Europe Model - Probably same method work on G7 and other devices from LG that has limited settings after a factory reset from distance by owner

#### CONTACT 

If you have problems, questions, ideas or suggestions please contact
us by posting to wuseman@nr1.nu

#### WEB SITE

Visit our homepage for the latest info and updated tools

https://github.com/wuseman

#### END!

