<!-- Improved compatibility of back to top link: See: https://github.com/bmcsilva/zeropad-customizer-app/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the zeropad-customizer-app. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<div align="center">
         <img src="https://img.shields.io/github/stars/bmcsilva/zeropad-customizer-app.svg?style=for-the-badge">
         <img src="https://img.shields.io/github/issues/bmcsilva/zeropad-customizer-app.svg?style=for-the-badge">
         <br />
         <img src="https://img.shields.io/github/downloads/bmcsilva/zeropad-customizer-app/total">
         <img src="https://img.shields.io/github/watchers/bmcsilva/zeropad-customizer-app">  
         <img src="https://img.shields.io/github/v/release/bmcsilva/zeropad-customizer-app">
         <img src="https://img.shields.io/github/release-date/bmcsilva/zeropad-customizer-app">
</div>
    <div align="right"><b><i>Download is here</i></b> ➡️</div> 
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/bmcsilva/zeropad-customizer-app/assets/logo.png">
    <img src="assets/logo.png" alt="Logo" width="80" height="80">
  </a>
<h3 align="center">ZeroPad Customizer: A free program that allows us to configure a PIM551 keypad and a Raspberry Pi Pico W to execute keybinds on our computer</h3>

  <p align="center">
    <a href="https://github.com/bmcsilva/zeropad-customizer-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/bmcsilva/zeropad-customizer-app/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#todo-list">Todo list</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<br />

This project was born out of my aspiration to showcase my coding abilities. The initial concept was to create a keypad capable of simulating keypresses on a connected device, such as my PC. As I explored similar projects, I came across numerous individuals building their own 'stream decks,' and I thought to myself, 'I can do this too.' And so, I set out to prove just that.

I embarked on this journey, leveraging Python examples from the CircuitPython libraries to bring my vision to life. This project consisted of two essential components:

* Developing the necessary code for the Raspberry Pi to execute the desired functions.
* Creating a PC program that would enable me to customize the keypad's colors and key bindings to my liking.

The Configurator app was easy to create, thanks to my proficiency in C and GTK, which are like my comfort zone. However, the python part posed a challenge because I had never coded in that language before.

<br />
Here's a glimpse of the application:
<br />

<br />
<div align="center">
    <p><i>After the first boot of the application</i></p>
    <img src="https://github.com/bmcsilva/zeropad-customizer-app/blob/main/assets/zero_pad_ss_1.png" alt="screen_1" />
</div>

<br />
<div align="center">
    <p><i>A sample of some customized buttons</i></p>
    <img src="https://github.com/bmcsilva/zeropad-customizer-app/blob/main/assets/zero_pad_ss_2.png" alt="screen_3" />
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With
<a href="">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/>
</a>

<a href="https://www.gtk.org/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/GTK_logo.svg" alt="gtk" width="40" height="40"/>
</a>
<a href="https://www.sqlite.org/index.html">
     <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> 
</a>
<a href="https://circuitpython.org/">
     <img src="https://circuitpython.org/assets/images/logo.png" height="40"/> 
</a>

<br />
<div align="left">
         <p>All the assetts (images, backgrounds, etc...) are made by Freepik can be found on <a href="https://www.freepik.com/">their website</a></p>
         <a href="https://www.freepik.com/">
              <img src="https://cdn-teams-slug.flaticon.com/freepik.jpg" height="40"/> 
         </a>
</div>


  
<!-- GETTING STARTED -->
## Getting Started
* Heres a  <a href="https://www.youtube.com/playlist?list=PLLO5uk2SobPw9637IQluF0fxr4MJ_0fyl"> youtube playlist</a> showcasing the features
  
### Prerequisites

This application is compatible with the following operating systems
* Windows 7 or later
* Ubuntu 20.04 or later
* <div align="left">
    <p>A Raspberry Pi Pico W (At this date, this will <b>not work on non W devices</b>)</p>
    <img align="Center" src="https://github.com/bmcsilva/zeropad-customizer-app/blob/main/assets/pi_pico_w.jpeg" alt="pi_pico_w" height="300"/>
    <br />
* <div align="left">
    <p>A Pico RGB Keypad Base (PIM551) </p>
    <img align="Center" src="https://github.com/bmcsilva/zeropad-customizer-app/blob/main/assets/pim551.jpg" alt="pi_pico_w" height="300"/>
    <br />
</div>

* An accessible 2.4Ghz WiFi connection to reach the host (needed for the Raspberry)

### Installation
<b>Warning:</b> this will wipe your device. If you have stuff inside, do a backup now.

0. Required files on the releases:
    - Download the ZeroPad-Customizer-raspberry-vx.x.x.zip
    - Download the ZeroPad-Customizer for your Operating System

1. Wipe the entire Raspberry
    - Remove the USB cord from the raspberry
    - Press the white button on the raspberry (<b><i>BOOOTSEL</b></i>) and plugin to your computer
    - Download this file https://datasheets.raspberrypi.com/soft/flash_nuke.uf2
    - Copy the file into inside the raspberry
    - Wait for the raspberry to boot
    
2. Setup the Raspberry Pi Pico W.
   - Download the "latest stable release of CircuitPython" https://circuitpython.org/board/raspberry_pi_pico_w/
   - Copy the file into inside the raspberry
   - Wait for the raspberry to boot

3. After it boots, go to the ZeroPad-Customizer-raspberry-vx.x.x.zip, and unzip it.
4. Copy the content, and place it inside the raspberry
5. <b><i>THIS STEP WAS MISSING:</b></i> Extract the content of <b><i>lib.zip</b></i> and copy it to the inside of the raspberry

6. Edit the file <i><b>"network.cfg"</b></i> and change the <i><b><your_ssid></b></i> and <i><b><your_password></b></i> to the WiFi network of your desire, and then save.
 - Note: If you dont want to create said file, you can skip this step, and when you reach the <b>#8</b>, come back again here, because, on the first boot, the raspberry will start on AP_Mode. 
    Also, after, if the network you selected isnt reachable, it will also make the raspberry start in AP Mode:
    - If you came back from <b>#9</b>:
      1. Connect to the network called "ZeroPad-RPI" and insert the password "1234567890"
      2. Type this on your browser http://192.168.1.4/rpi/?ssid=<YOUR_SSID>&pwd=<PASSWORD> and press send
      3. On the browser you are going to see a message. If it's OK, just unplug the Raspberry, and plug it again, else, check what you have typed.
         - Note: You can use the command in any time. Just be aware that, any command sent, will need a unplug/plug of the raspberry
         - Theres also the command http://picow/rpi/?whoami=1, that responds with the raspberry address. If for some reason your app is not communicating, try this command.
         - Theres a problem with the DNS on some routers. For that, you need to find the RPI address manually. To do so:
            - On <b><i>Ubuntu</b></i>, type this on the terminal:
             -  <b><i>sudo apt-get install nmap</b></i>
             -  <b><i>ip a</b></i> and search for <b><i>intet</b></i>. It should be an address, for example, <b><i>192.168.1.103/24</b></i>
             - <b><i>sudo nmap -sn 192.168.1.0/24</b></i> change the 192.168.1 to yours. Important to the last digit be the <i>.0</b></i>
          - On <b><i>Windows</b></i>:
            - Use the program Wireless [Network Watcher](http://www.nirsoft.net/utils/wireless_network_watcher.html) to obtain the addresses
         - To test the address, use the command http://<my_address>:80/rpi/?whoami=1, until you see a response on your screen
           <div align="Center">
              <img align="Center" src="https://github.com/bmcsilva/zeropad-customizer-app/blob/main/assets/screen_whoami_1.jpg" alt="screen_whoami" height="300"/>
             <br />
         </div>
7. Unplug the Raspberry and plug it back again.
8. After the Raspberry Pi boots up, the keys will blink in <b>RED</b>, and then they will be lit in <b>YELLOW</b>. This indicates that the Raspberry Pi is in Access Point (AP) mode. If you skipped <b>step 8</b>, now is the time to complete it.
9. Unplug the Raspberry and plug it back again.
9. Unplug the Raspberry Pi, then plug it back in, and wait for the keys to perform one of the following actions:
    - If you have a successful WiFi connection, the keys will blink in <b>GREEN.</b>
    - If the WiFi connection fails, the keys will be lit in <b>RED</b>. Please check your configurations.
11. Start the ZeroPad Customizer app
12. Thats it. Ready to go!
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- TODO LIST -->
## Todo list

- [ ] Create an "About" window.
- [x] Enable customization of button names (e.g., "Mute Microphone," "Run Excel," etc.).
- [x] Enable the keypad to emulate gamepad functions, providing 16 individual keys. <br /> 
      <b><i>Note:</b></i> If no specific key is defined, this feature will operate as the default, resulting in a gamepad key press instead of a keyboard key press.
- [ ] Implement the ability to select new effects.
- [x] Enable button backlighting, with color changes upon pressing.
- [ ] Allow the use of Windows CMD or Ubuntu Terminal to execute custom user-defined commands (e.g., open an app, etc.).
- [ ] Implement the capability to send HTTP requests to a specified target (e.g., send a POST command to turn off a light).
- [ ] Add support for multiple pages within the application.
- [ ] Implement the ability to export and import presets.
- [ ] Enable the export and import of a database.
- [ ] Make it work on non "W" devices
<!-- - [x] Add Changelog -->

See the [open issues](https://github.com/bmcsilva/zeropad-customizer-app/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

<a href="https://linkedin.com/in/bruno-m-c-silva" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="bruno-m-c-silva" height="30" width="40" /></a>
<a href="https://discord.com/users/513401442267037714" target="blank"><img align="center" src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a69f118df70ad7828d4_icon_clyde_blurple_RGB.svg" alt="bruno-m-c-silva" height="30" width="40" /></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
