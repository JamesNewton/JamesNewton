## Robotics Firmware Engineer

- Loves to collaborate. email JamesNewton at MassMind.org
- Many years experience in making things move.
- Has been VERY lucky to be involved with brilliant people (and learn all their secrets 🤫)
- Currently available for work, please check my <a href="https://docs.google.com/document/d/19SGMbVQtF7QBo8nATcOUQLo_2o9t4nHPgO0AcBHvORA/edit?usp=sharing">resume</a>.

### In-Work

- Simplifying the implementation of the [1 Million CPR Encoder](https://github.com/HaddingtonDynamics/Dexter/wiki/Encoders) used on the Haddington Dynamics Dexter Robot to avoid the need for an FPGA and allow simple RasPi Pico or other microcontroller to provide precise (and somewhat accurate) position feedback. [That's done with the HybridEncoder](https://github.com/JamesNewton/HybridDiskEncoder). Next is adding Single Track Grey Code (STGC) operation via an inner track for absolute position to a slot. Since the analog reading of an individual slot gives absolute position inside that slot, the combination should provide 1MCPR _absolute_ position reporting with something you can 3D print or laser cut for $10.

- Continued improvements on the super easy to use [Arduino Controller including optional Stepper Motor and Dynamixel Servos](https://github.com/JamesNewton/Arduino_Dynamixel_Stepper_Controller) a simple Arduino script to set pins high, low, input, pull up, or analog/servo, clock out data with timing, and read all or a single pin back via serial IO (e.g. USB). It also (optionally) supports Dynamixel Servos given a sheild and Stepper Motors given a standard step / direction driver. Instead of binary commands, it uses human readable byte codes. e.g. `13H` turns on the LED. `13,60A` PWMs it. 

### History
- Contributed to the Insight Mars Helecopter... :cough: by correcting the spelling of ONE word in the documentation of the OpenCV.js project. (so... pretty much ignore that tag please? LOL)

- Provided the electronics for the very first cement house 3D printer in the USA in 2013/14 [<sup>1</sup>](https://hackaday.com/2014/05/29/man-builds-concrete-3d-printer-in-his-garage/) [<sup>2</sup>](https://3dprint.com/12933/3d-printed-castle-complete/) [<sup>3</sup>](http://web.archive.org/web/20170328064604/http://americankabuki.blogspot.com/2014/09/minnesotan-man-builds-worlds-first-3d.html) [<sup>4</sup>](https://www.youtube.com/watch?v=aSJXaPGLmIk)

<img alt="Cement 3D printer drivers" width="49%" src="https://github.com/user-attachments/assets/a6195d92-6e6a-486f-bc16-8013e1b4a43c"> <img alt="Andrey3DCementCastle" width="44%" src="https://github.com/user-attachments/assets/a8e1144f-eec2-4d65-8c2c-cb8793ccc69d">

Then Alex Le Roux and his team at VestPrint purchased the same electronics, printed an outhouse, and managed to get purchased by Icon forming Icon Builds which does most of the house printing you see today. Proud to have gotten them started. 

- Developed a basic, very low cost, useful PID controller: The [BOB PID](https://github.com/JamesNewton/BOBPID/). Accepts step / direction or serial input, and drives standard DC or other high power motors, allowing replacement of stepper motors for truly massive 3D printers or CNC machines. Combined with PCBs for a [DC motor driver](https://hackaday.io/project/11419-massmindorg-40-v-18-a-output-dc-motor-drive), and [hall effect array encoder](https://hackaday.io/project/11418-massmindorg-abosoluteincremental-rotary-encoder) which came together (along with some fabrication help from friends) to make the MONSTER servo: 1 foot square, 5000 oz/in of torque, runs on power tool batteries, WiFi enabled. Like an RC servo but massive. [first video](https://www.youtube.com/watch?v=EHmwiAFREVE) [second, with smoother motion](https://www.youtube.com/shorts/ekbzLTYLiSY). Cheap DC motors from salvage, encoders, and the [BOB PID](https://github.com/JamesNewton/BOBPID/?tab=readme-ov-file) can make massive monsters move. 

- Joined Haddington Dynamics the year before they [won the the Hackaday Prize in 2018](https://hackaday.com/2018/11/03/dexter-robotic-arm-wins-the-2018-hackaday-prize/) (:cough: a co-worker put us in for it, but [I got to give the acceptance speech](https://www.youtube.com/live/Mbg8jMhSEIY?si=4Bx6bzOGXUUd0AJf&t=1503) ). I've done gobs of work on the firmware for that project, implementing real time monitoring and control including jerk limited playback, fast dh IK (based on a method developed by a co-worker) and extensive servo control, debugging, etc... As well as a web based UI, which allows editing and execution of onboard scripts, direct "chat" based control, and troubleshooting. 

- Extended the basic design of an educational robot by JMalins which uses an ESP to provide a WiFi AP and is controlled by the web page served into a connected cell phone browser, to add a web editor which allows the files on the robot to be changed, implemented recording / playback of movements, support for onboard sensors, etc... the [SDMG Bot](https://github.com/JamesNewton/SDMG-Web-Bot?tab=readme-ov-file)



<!--
**JamesNewton/JamesNewton** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
