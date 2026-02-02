# c64upgrade

Documentation + links for the C64 upgrade project.

## Files
- STLs live in Google Drive (links below).
- Source files (Tinkercad) are linked below.

## Parts index

| Part | Purpose | Tinkercad | STL (Google Drive) | Notes |
|---|---|---|---|---|
| (example) | | | | |
| C64 screen adapter (legacy?) | Additional screen-related parts (possibly deprecated) | https://www.tinkercad.com/things/g175seyIrYO-c64-screen-adapter | (see Drive folder) | May be deprecated by newer models |
| C64 short neck adapter | Adapter for the C64 screen holder (short neck) | https://www.tinkercad.com/things/jXZNhlvi3aB-c64-short-neck | (see Drive folder) | Pairs with the screen holder upgrade |
| C64 screen holder upgrade | External screen holder matching C64 aesthetics | https://www.tinkercad.com/things/6Brm0crgzTa-c64-screen-holder-upgrade | (see Drive folder) | External screen matching C64 aesthetics |
| C64 Raspberry Pi inner upgrade (set) | Inside-case parts + C64 case reference model | https://www.tinkercad.com/things/hRkwhY43SIk-c64-raspberry-pi-inner-upgrade | (see Drive folder) | Contains internal parts + model of C64 case |

## Drive folder
- https://drive.google.com/drive/folders/1eSIGOz6_u6HjV1szIJh4CBuaD-XmflCE?usp=sharing

## Build notes
- (add notes)
Here is the consolidated inventory of your DIY ribbon cable parts.

I have grouped similar items together and matched them with their likely **Adafruit Product IDs** (PID). Please double-check the cable lengths, as I assumed "mm" was likely a typo for "cm" given standard ribbon sizes (e.g., 30mm is only 3cm, which is unusually short).

### **HDMI Adapters**

| Item Name | Total Count | Adafruit Part # | Notes |
| --- | --- | --- | --- |
| **HDMI Male Plug (Straight)** | **4** | [PID 3548](https://www.adafruit.com/product/3548) | (2 in Box 1, 2 in Box 3) |
| **HDMI Female Socket (Straight)** | **4** | [PID 3551](https://www.adafruit.com/product/3551) | (1 in Box 1, 1 in Box 2, 1 in Box 3) |
| **Micro HDMI Male Plug** | **3** | [PID 3556](https://www.adafruit.com/product/3556) | (All 3 in Box 2) |
| **"Bendy" HDMI Male Plug** | **1** | [PID 3549](https://www.adafruit.com/product/3549) | Likely "Right Angle" (R Bend) |

---

### **USB Adapters**

| Item Name | Total Count | Adafruit Part # | Notes |
| --- | --- | --- | --- |
| **USB Type A Male Plug** | **3** | [PID 4109](https://www.adafruit.com/product/4109) | (1 in Box 1, 2 in Box 3) |
| **USB Type A Female Socket** | **3** | N/A* | *Commonly part of the DIY sets, but check if it's the ["Straight" (PID 3602)*](https://www.adafruit.com/product/3602) |
| **USB Type C Male Plug** | **4** | [PID 4108](https://www.adafruit.com/product/4108) | (All 4 in Box 2) |
| **Micro USB Male (Straight)** | **2** | [PID 4103](https://www.adafruit.com/product/4103) | (1 in Box 1, 1 in Box 3) |
| **Micro USB Male (90° Down)** | **1** | [PID 4105](https://www.adafruit.com/product/4105) | (In Box 2) |
| **Micro USB Female Socket** | **2** | [PID 4104](https://www.adafruit.com/product/4104) | (1 in Box 1, 1 in Box 3) |

---

### **Ribbon Cables (Flex)**

| Item Name | Total Count | Adafruit Part # | Notes |
| --- | --- | --- | --- |
| **10cm Ribbon Cable** | **2** | [PID 3560](https://www.adafruit.com/product/3560) | (Listed as "110mm" in Box 2) |
| **30cm Ribbon Cable** | **5** | [PID 3562](https://www.adafruit.com/product/3562) | (Listed as "30mm" & "430mm"*) |
| **50cm Ribbon Cable** | **3** | [PID 3563](https://www.adafruit.com/product/3563) | (Listed as "150mm" in Box 2) |

**Note: For the cables, I assumed you meant **cm** or standard lengths (e.g., 10cm, 20cm, 50cm). If you actually have 30mm (3cm) cables, those are very rare custom parts!*

Since most of these specific brands (Besign, Talentcell, GeeekPi) are from Amazon/AliExpress rather than Adafruit directly, I have matched them to the **Adafruit Equivalent Product ID** where possible. This gives you a direct link to libraries, drivers, and pinouts that will usually work with these generic parts.

Here is your consolidated inventory:

### **✨ The "Blade Runner" Display Collection**

*Perfect for that retro-futuristic interface you like.*

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **1.28" Round LCD (GC9A01)** | **2** | [PID 5057](https://www.adafruit.com/product/5057) | 1x Bare Module, 1x on Pico Board. Great for "HAL 9000" eyes or gauges. |
|1.8inch LCD Display Module Kit General Screen 128x160 Pixels SPI Interface with Examples for Raspberry Pi/Jetson Nano/Arduino/STM32
| **7" HDMI Display (1024x600)** | **1** | [PID 2353](https://www.adafruit.com/product/2353) | Generic driver board version. |
| **5" HDMI Touchscreen** | **1** | [PID 2232](https://www.adafruit.com/product/2232) | Great dedicated screen for a Pi interface. |
| **3.5" Pi Touchscreen (GPIO)** | **1** | [PID 2441](https://www.adafruit.com/product/2441) | Plugs directly onto Pi GPIO headers. |
| **1.54" LCD "Game Hat"** | **1** | [PID 3531](https://www.adafruit.com/product/3531) | Likely a WaveShare clone. Good for a mini console. |

---

### **📻 Audio & Radio Parts (For BIGTIME235.fm)**

*You can build a killer custom internet radio with these.*

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **Bluetooth 5.0 Receiver Board** | **2** | N/A | Standalone decoder boards (Amazon/Generic). |
| **20W Stereo Amp (XY-AP15H)** | **1** | [PID 1752](https://www.adafruit.com/product/1752) | *Similar capability.* High power class-D amp. |
| **LM3915 VU Meter Kit** | **1** | N/A | Old-school 10-LED audio visualizer. |
| **Ground Loop Isolator** | **1** | N/A | Essential for removing "hum" in car/radio audio. |
| **Headphone Splitter** | **1** | N/A | Standard 3.5mm Y-cable. |

---

### **🍓 Raspberry Pi Utilities**

*Tools to keep your fleet (Tex, Nutty, etc.) running.*

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **Pi 5 RTC Battery Box** | **1** | N/A | Specifically for the new Pi 5 Real Time Clock. |
| **Pi 5 USB-to-UART Cable** | **1** | [PID 954](https://www.adafruit.com/product/954) | *Crucial* for debugging the Pi 5 boot console. |
| **Pi Zero "USB Stem"** | **1** | [PID 2909](https://www.adafruit.com/product/2909) | Converts Pi Zero into a USB dongle. |
| **GPIO T-Type Expansion** | **1** | [PID 2028](https://www.adafruit.com/product/2028) | For breaking out pins to a breadboard. |
| **GeeekPi 4-Ch Power Supply** | **1** | N/A | Rackmount-style 5V power for multiple Pis. |
| **"Eye Contact" Webcam** | **1** | N/A | Center-screen camera for video calls. |

---

### **🛠️ Hardware & Tools (For the Woodshop/3D Printing)**

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **Heat-Set Insert Tip Set** | **1** | N/A | **Essential 3D Print Tool.** Melts brass nuts into plastic. |
| **Threaded Insert Kit (M2-M6)** | **1** | [PID 4255](https://www.adafruit.com/product/4255) | The actual brass nuts for the tool above. |
| **M4 Screw Assortment** | **1** | N/A | Alloy steel bolts (Black Zinc). |
| **M2/M3/M4/M5 Screw Kit** | **1** | [PID 3299](https://www.adafruit.com/product/3299) | Huge mixed set (1760pcs). |
| **CH341A BIOS Programmer** | **1** | N/A | Used to flash EEPROMs/BIOS chips. Very advanced! |
| **Cable Testers (HDMI/USB)** | **2** | N/A | One HDMI breakout, one DT3 USB tester. |
| **Keira V2** | **1** |  

---

### **⚡ Power & Motors**

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **Talentcell 24V Battery** | **1** | [PID 354](https://www.adafruit.com/product/354) | *Similar utility.* Huge capacity for portable projects. |
| **Talentcell 12V Battery** | **1** | N/A | Good for LED strips or the 7" screen. |
| **MG90S Metal Gear Servo** | **1** | [PID 1143](https://www.adafruit.com/product/1143) | Stronger than the standard blue servos. |
| **6V Gear Motor (10RPM)** | **1** | [PID 3777](https://www.adafruit.com/product/3777) | High torque, slow speed. |
| **CR2032 Holder w/ Switch** | **1** | [PID 653](https://www.adafruit.com/product/653) | Great for small wearables or light props. |

---

Raspberry Pi

### **🧠 The Compute Fleet**

*You now have a serious cluster on your hands.*

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **Raspberry Pi 5** | **2** | [PID 5812](https://www.adafruit.com/product/5812) | **The New Beast.** Requires active cooling (fan) & 27W USB-C power. |
| **Raspberry Pi 4 Model B** | **2** | [PID 4296](https://www.adafruit.com/product/4296) | The reliable workhorse. (PID links to 4GB version). |
| **Raspberry Pi 3 Model B** | **1** | [PID 3055](https://www.adafruit.com/product/3055) | Classic. Great for lighter tasks like running the 3D printer webcams. |

*Note: For the Pi 5s, make sure you keep that **"Pi 5 USB-to-UART Cable"** (from the previous box) handy—it's the best way to debug them if they don't boot up perfectly the first time.*

### **⚡ Prototyping**

| Item | Count | Adafruit Equiv. PID | Notes |
| --- | --- | --- | --- |
| **400 Tie-Point Breadboard** | **3** | [PID 64](https://www.adafruit.com/product/64) | Half-size boards. These often snap together to make wider surfaces. |




