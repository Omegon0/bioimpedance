# Bioimpedance

An ESP32-based dev board wtih an onboard MAX30001 sensor. Designed for 4-wire ECG and respiratory monitoring. 

### What even is bioimpedance? 

Bioimpedance is a method that measures the body's resistance to flow of current. It can be used to estimate body composition but it isn't as accurate as other methods. Since it does measure changes over brief time intervals, the MAX30001 sensor can be used to track respiratory rate as well. 

### What's with this board? 

The MAX30001 IC is a 30-bump wafer-level package (WLP) so it was super difficult to fit it onto a two layer board. Reducing clearances to the minimum was necessary to route all traces. A properly functioning MAX30001 is NOT guaranteed with this project! 
How many DRC/ERC errors are there? LOTS!!! Over 100 violations that need to be fixed. This board WILL take some time to polish! However it is technically production ready. 

### Images

![sch](https://github.com/Omegon0/bioimpedance/blob/main/sch.jpg?raw=true)
![pcb](https://github.com/Omegon0/bioimpedance/blob/main/pcb.jpg?raw=true)
![rend1](https://github.com/Omegon0/bioimpedance/blob/main/rend1.jpg?raw=true)
![rend2](https://github.com/Omegon0/bioimpedance/blob/main/rend2.jpg?raw=true)
