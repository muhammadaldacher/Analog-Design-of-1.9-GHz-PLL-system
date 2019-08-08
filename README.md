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
####   1- LC VCO:
Refer to: https://github.com/muhammadaldacher/RF-design-of-1.9-GHz-Rx-frontend/tree/master/%5B2%5D%20VCO%20design <br/>
![VCO_LC](https://user-images.githubusercontent.com/27668656/62666459-611b5880-b938-11e9-8581-81349e223dcd.png) <br/>
![lc](https://user-images.githubusercontent.com/27668656/62667160-4eeee980-b93b-11e9-91f0-90585d671192.png) <br/>
####   2- Current-Starved Ring VCO:
![VCO_ring](https://user-images.githubusercontent.com/27668656/62667249-b147ea00-b93b-11e9-9828-5e5c48a859f0.png) <br/>
![rg](https://user-images.githubusercontent.com/27668656/62667287-dccad480-b93b-11e9-8be8-604a056441ac.png) <br/>
### E) Divider:
![Divider](https://user-images.githubusercontent.com/27668656/62671403-9c735280-b94b-11e9-9dae-725af9e789dd.png) <br/>
####   1- TSPC Flipflop: (for high-speed-input stages)
![Divider](https://user-images.githubusercontent.com/27668656/62671736-ddb83200-b94c-11e9-936c-c4115550a676.png) <br/>
####   2- CMOS Flipflop: (for lower-speed-input stages)
![Divider](https://user-images.githubusercontent.com/27668656/62671766-f9233d00-b94c-11e9-9f22-335821989829.png) <br/><br/>
### => System Simulations:

*****************
### References:
-> VerilogA References:<br/>
https://github.com/muhammadaldacher/Analog-Design-of-1.9-GHz-PLL-system/tree/master/%5B1%5D%20PLL%20System%20Level%20(VerilogAMS%20-%20Matlab)/VerilogA%20References%20(for%20PLLs) <br/>
-> PLL Design References: <br/>
https://github.com/muhammadaldacher/Analog-Design-of-1.9-GHz-PLL-system/tree/master/%5B2%5D%20PLL%20Circuit%20Design/References <br/>
My project on google drive:<br/>
https://drive.google.com/drive/folders/1TUYCLbdZC5S4dQVAxZmoUjMQPiLFntPe <br/>
EE230 Lecture Notes:<br/>
https://drive.google.com/open?id=1WcP2svOrAle0cEzlL1oexYeuDEQjH5j9 <br/>
