# HomeAssist / Robo-Owen
A weekend project to enable our friend Owen to more easily interact with his home devices, such as a mechanical door and smart outlets. This project also served as an exploration to try various alternative input methods, such as using EMG to detect subtle hand motions.

Project completed in March 2017.

Technical components:
- Arduino: Embedded firmware development
- Eagle: Electronics hardware design
- Electomyography (EMG): Detect slight hand movement via electrical signals from the nervous system
- Particle Photon: WiFi-enabled microcontroller
- Fusion 360: 3D printable design

This project won the Autodesk Design Award at the TOM:Berkeley Make-a-Thon held at UC Berkeley in March 2017. For this project, we worked with our friend Owen Kent whose physical disability makes it difficult to interact with the world via conventional input methods. He currently has a single joystick attached to his wheelchair through which he uses his computer and other devices that can take a mouse as input. Prior to this Make-a-Thon, we observed a few key problems that we aimed to solve with our invention.
Specifically, Owen previously had to interface with a very buggy RFID system that was synchronized with a wall-mounted button in order to open his home door. When physically pressed (by rolling his wheelchair into contact with the wall), the button can open the door from the outside, but he has to time it exactly with his buggy RFID transmitter, and it often takes him multiple tries to open his door (rolling into the wall, repeatedly). Moreover, Owen is severly constrained by his assistive mouse, which is only mounted on his wheelchair. Unless he is seated in his wheelchair, he has no way to connect with any device. He has been wanting to design a system to allow him to use his tablet while lying down in bed.

We created a new joystick USB mouse that will allow Owen to talk to the various devices in his home that he currently has no means of controlling (this includes his door, lights, heater, speaker, etc.). In a little more detail, this new mouse project enables him to have a more efficient interaction with his devices while also promoting bodily movement that he previously had no motivation to do. The mouse was built with an Arduino-like microcontroller with Electromyographic (EMG) sensors that can detect and process slight muscle movements in each of his hands and a 3-axis accelerometer that can detect stomach inflation/deflation. I programmed the device to be able to left-click and drag when Owen flexed his left hand and to right-click when he flexed his right hand. His stomach movement could easily be mapped to small functions, such as taking a screenshot. This solution works around his existing problematic setup where all clicks are sensed in software with timers, which can be difficult to operate, let alone much slower to use (must stall above an object for a certain time period in order to click, or nudge the joystick in a particular way). This EMG clicking mechanism also provides Owen with the motivation to engage in physical training of his existing hand muscles.
This solution provides Owen with a device that not only allows him to control his door with ease (not to mention allowing him to control various appliances like bedroom lights), but it lets him do so from his bed! We designed multiple mounts that could be placed near hes bed so that his tablet and our mouse could be operated without ever having to get up. Our invention gives Owen the freedom to interact with his house, especially when opening his door, while also giving him the freedom to connect to the world when he is not in hiw wheelchair. The mouse can virtually work with any PC or tablet available.

The whole system was developed in 40 hours for a hack-a-thon.
Video demo of controlling Owen's mechanical door from a custom tablet app (now he can open/close his door from anywhere in his home): https://youtu.be/9umRvlkxGAE

![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-0.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-1.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-2.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-3.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-4.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-5.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-6.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-7.gif)
![alt text](https://github.com/cortensinger/HomeAssist/blob/main/pics/robowen-8.gif)
