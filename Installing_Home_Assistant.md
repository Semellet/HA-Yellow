There are 2 ways to install Home Assistant on the Raspberry-Pi.  I will try and get both sets of instructions for you but the USB-drive method is the best.

<h2>The USB-drive method: </h2>

Step 1: Get a USB stick and put it in your computer.

Step 2: Go to https://www.raspberrypi.com/software/ and download the windows version.

Step 3: Run the file and from the main screen click "Choose OS" 
  Scroll down and select "Other specific-purpose OS" 
  And then select "Home Assistants and Home Automation"
  Then select "Home Assistant"
  Finally select "Home Assistant OS Installer for Yellow"

Step 4: Click on "Choose Storage" and select the USB drive. - if you arent 100% sure dont choose anything and then we can take this step together - some USBs have weird names that look like hard drives.

Step 5: Select "Write" and then "Yes" if you are sure that the USB is selected.

Step 6: Move the jumper to select "UART":
<img width="800" height="814" alt="UART" src="https://github.com/user-attachments/assets/54022fa0-bf6a-40fd-97ea-cd12388772f4" />

Step 7: Remove the USB from your computer and put it into the HA-Yellow, and plug in an ethernet cable - Internet is needed for installation.

Step 8: Plug in power.  If everything is going well you will get solid red and green LEDS, and then the green and yellow lights will start flashing.  Let it do its thing.

Step 9: Eventually the yellow and green lights will stop flashing, leaving a solid red.  This is telling you the install is done.

Step 10: Remove the power and ethernet cable and install the mainboard in the plastic case.

Step 11: Plug in the ethernet and power again.  You should get lights of all colours.

Step 12: On your PC go to http://homeassistant.local:8123 You should get the Home Assisstant start screen.

Step 13: Setup an account for your machine - choose a <b><i><u>REALLY</b></i></u> good password - you do not want outsiders hacking your security cams.
