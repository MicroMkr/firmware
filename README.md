**Installation:**

In your browser open: https://micromkr.github.io/firmware/MicroMaker-Flasher.html

<img width="637" height="910" alt="image" src="https://github.com/user-attachments/assets/594e3584-957f-41c9-90c1-6ac70d901221" />


Connect your microcontroller to the USB port of your computer.

Choose the right firmware

Press connect choose the right port and flash.

After flashing is finished:

Press the RESET button on the ESP board (if it does not reboot automatically).

The new firmware will start running.

After ESP32 boot wait for few min until network scanning is completed. Open the wifi in your phone and search for BT_Radio Connect to your network Wait for 5 minutes for the files system format to be completed (You might need to turn off/on the radio) Look at the LCD for the IP address connect to that IP address using your computer browser Upload a single station or list of stations using the following format

Station Name 1,Station Address 1

Station Name 2,Station Address 2
