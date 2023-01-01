# Remove-inbuilt-app-from-Android
This module contains instructions for removing bloatware and system apps installed by the mobile company.


Here, I'll outline the procedures needed to get rid of unwanted system programmes and bloatware.
This tutorial is now divided into three parts:

                          1. Prerequisites in mobile phone,
                          
                          2. Opening the command prompt in PC,
                          
                          3. Removal of system apps.
                          
                          
## 1. Prerequisites in Mobile Phone:
 
  Step 1 : Open Playstore and install the app named **Package name viewer**.

  Step 2 : Then, enable the `developer options` in your android mobile. _(Refer google for your current device model )_
 
  Step 3 : In developer options, toggle on the **USB Debugging** option.
 
  Step 4 : Connect the mobile device to the computer using usb cable and click allow to the following popup.
 
 ## 2. Opening the Command Prompt in PC:
 
  Step 1 : Download this repository as a zip and extract in your local directory.
 
  Step 2 : Now, run the `Command Prompt` in that extracted folder.
 
 
## 3. Removal of System Apps :

  Step 1 : In the command prompt, type `adb devices`.

  Step 2 : Your device name will be shown there or again reconnect the mobile phone .

  Step 3 : Now type `adb shell`.

  Step 4 : 
