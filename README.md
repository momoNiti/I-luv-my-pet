# I-luv-my-pet
Computer Programing Project
---
### Introduction
> Nowadays, people are feeding a variety of animals, such as cats, dogs, rabbits, etc., and may face the problem of feeding animals. Especially when you have to go to work or go to the provinces or abroad. Cause concerns about eating time of pets. Usually, the owner will feed on time, so the device must be invented to facilitate the owner. Developers recognize this problem and have developed and produced automatic feeding machines that can be ordered from a mobile phone so they can be fed anytime, anywhere.
---
### Library
* [Servo library](https://github.com/arduino-libraries/Servo)
* [Blynk library](https://github.com/blynkkk/blynk-library/releases/tag/v0.5.2)
* [Time library](https://github.com/PaulStoffregen/Time)
---
### Installation
1. Download arduino ide: https://www.arduino.cc/en/Main/Software
2. Add board
   * File -> Preference -> add this url: http://arduino.esp8266.com/stable/package_esp8266com_index.json to Additional Boards Manager URLs -> OK
   * Tools -> Board -> Boards Manager
   * Type esp8266 in search -> install
   * Tools -> Board -> Wemos D1 R1
3. Download and Install Library
   * Sketch -> Include library -> Add.Zip Library...
   * Select all Zip file
---
### Use
#### In Application
1. Download application Blynk to your phone
2. Select New Project
3. Set your project name and device then create project
4. Add 4 button to your project
   * First button select OUTPUT as V3 and MODE as PUSH  \# control value food
   * Second button select OUTPUT as V4 and MODE as SWITCH  \# autometic food
   * Third button select OUTPUT as V5 and MODE as PUSH  \# control value snack
   * Fourth button select OUTPUT as V6 and MODE as SWITCH  \# autometic snack
5. Add 1 notification <br>
[![blynk.jpg](https://s17.postimg.cc/hmmuh92in/blynk.jpg)](https://postimg.cc/image/ic5mtm323/)
#### In arduino ide
1. Change auth token \# You can find your auth token in Blynk app.
2. Change ssid and password \# It is your ssid and password of your wifi. <br>
[![config.png](https://s7.postimg.cc/rsxefus8r/config.png)](https://postimg.cc/image/qqn7xb9fb/)
3. Upload code to your board
---
### Assistant Teacher
* Asst.Prof.Dr. Panwit Tuwanut
* Asst.Prof.Dr. Kitsuchart Pasupa
---
### Author
* 60070004 Kunyarat Inta
* 60070035 Teeraphon Jirachanchai
* 60070040 Nantasiri Maungthong
* 60070041 Niti Jirakarnwuttikrai
---
Faculty of Information Technology <br>
King Mongkut's Institute of Technology Ladkrabang
