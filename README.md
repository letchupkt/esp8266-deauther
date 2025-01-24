# ESP8266 Deauther By Letchu pkt

<img src='https://deauther.com/img/logo.png' alt='Deauther Logo' width='200' />

**Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi scanners.**


## Password

The password for `pwned` is `deauther`



## 💻 Installation

### Step 1: Download the Firmware

1. Go to the official GitHub repository to download the `.bin` file for your ESP8266 board:
   - [Download the latest firmware from this GitHub repo](https://github.com/letchupkt/esp8266-deauther/)

### Step 2: Open the Flashing Tool

1. Open [espwebtool](https://espwebtool.netlify.app) in your web browser (Chrome is recommended).
   
### Step 3: Connect Your ESP8266

1. Plug your **ESP8266** board into your computer via USB.
   
### Step 4: Connect to the Flashing Tool

1. Click **Connect** in the web interface.
2. Select the **serial port** of your ESP8266 device from the list of available ports.

### Step 5: Upload the Firmware

1. Once connected, click the **"Choose File"** button to select the `.bin` file you downloaded earlier.
2. After selecting the file, click **Program** to start flashing the firmware onto your ESP8266.

### Step 6: Wait for the Flashing to Complete

1. The flashing process will take a few moments. Wait for the process to complete successfully.
2. Once completed, your ESP8266 is now ready to use with the Deauther firmware installed!

---

## 🛠️ Usage

Once the firmware is installed, follow these steps to use the tool:

1. **Power on your ESP8266**: After flashing, your ESP8266 should boot up and start running the Deauther software.
2. **Connect to the device**: You can connect to the ESP8266 via WiFi or using a serial terminal.
3. **OLED Display**: If you have an OLED display connected to your ESP8266, the real-time information will be shown directly on the screen.
4. **Scan for WiFi Networks**: Use the interface to scan available networks.
5. **Perform Attacks**: You can select a target device or network and perform actions such as deauthentication attacks, blocking devices, or creating fake networks.

Refer to the on-screen instructions for specific options and commands available through the web interface.

---


## About this Project

This firmware allows you to easily perform a variety of actions to test 802.11 networks using an [ESP8266](https://www.espressif.com/en/products/socs/esp8266). It's also a great project for learning about WiFi, microcontrollers, Arduino, hacking and electronics/programming in general.  

The deauthentication attack is the main feature, which can be used to disconnect devices from their WiFi network.  
Although this denial-of-service attack is nothing new, a lot of devices are still vulnerable to it. Luckily this is slowly changing with more WiFi 6 enabled devices being used. But a lot of outdated WiFi devices remain in place, for example in cheap IoT hardware.
With an ESP8266 Deauther, you can easily test this attack on your 2.4GHz WiFi network/devices and see whether it's successful or not. And if it is, you know you should upgrade your network.

## Disclaimer

This project is a proof of concept for testing and educational purposes.  
Neither the ESP8266, nor its SDK was meant or built for such purposes. **Bugs can occur!**  

**Use it only against your own networks and devices!**  
Please check the legal regulations in your country before using it.  
We don't take any responsibility for what you do with this program.  
