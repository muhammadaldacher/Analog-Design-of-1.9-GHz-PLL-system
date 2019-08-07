# Analog-Design-of-1.9-GHz-PLL-system
This project shows the design of a frequency synthesizer PLL system that produces a 1.92 GHz signal with a reference input of 30 MHz, with a comparison between using an LC VCO and using a Ring VCO.

# [1] PLL System Design
* PLL block diagram: <br/> <br/>
![block diagram](https://user-images.githubusercontent.com/27668656/62658668-2ad0df80-b91e-11e9-8d4a-d3cc765fffe7.png) <br/>
* Typical CP PLL system: <br/>
![block diagram](https://user-images.githubusercontent.com/27668656/62659007-1b05cb00-b91f-11e9-99c5-b8b5a7ae3843.png) <br/> <br/>
* System Parameters: <br/>
![param](https://user-images.githubusercontent.com/27668656/62659490-5fde3180-b920-11e9-979b-c036057acc3d.png) <br/> <br/>
* System Stability: <br/>
![block diagram](https://user-images.githubusercontent.com/27668656/62659548-856b3b00-b920-11e9-99d6-d49adb1be322.png) <br/> <br/>
![block diagram](https://user-images.githubusercontent.com/27668656/62659921-910b3180-b921-11e9-9eb4-502424ebd28e.png) <br/> <br/>
* Open-Loop & Closed-Loop Parameters: <br/>
![param](https://user-images.githubusercontent.com/27668656/62660296-8c934880-b922-11e9-9ba5-f65a7b2fa860.png) <br/> <br/>
* VerilogA System Simulation: <br/><br/>
![param](https://user-images.githubusercontent.com/27668656/62660466-f4499380-b922-11e9-8538-fb5a1e3818ac.png) <br/> <br/>
![param](https://user-images.githubusercontent.com/27668656/62660653-86ea3280-b923-11e9-9664-5af6d84cb73a.png) <br/> <br/>

# [2] PLL Circuit Design
### A) PFD:
![pfd](https://user-images.githubusercontent.com/27668656/62662760-f19e6c80-b929-11e9-8c0b-2270e22c45dc.png)
### B) Charge Pump:
![cp](https://user-images.githubusercontent.com/27668656/62663121-3c6cb400-b92b-11e9-98e2-5690f9dfe831.png) <br/>
![cp](https://user-images.githubusercontent.com/27668656/62663200-7473f700-b92b-11e9-957d-f16e4593238d.png) <br/>
### C) Loop Filter:
![LPF](https://user-images.githubusercontent.com/27668656/62663915-480daa00-b92e-11e9-84de-11f998679c88.png) <br/>
### D) VCO:



*****************
### References:
My project on google drive:<br/>
https://drive.google.com/drive/folders/1TUYCLbdZC5S4dQVAxZmoUjMQPiLFntPe <br/>
EE230 Lecture Notes:<br/>
https://drive.google.com/open?id=1WcP2svOrAle0cEzlL1oexYeuDEQjH5j9 <br/>
