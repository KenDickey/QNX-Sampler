# QNX-Sampler
Exploratory code

Get QNX free licence and directions at qnx.com/getqnx

- Install QNX software dev tools.  
- in a Bash shell, `source sourceMe.sh`
- Compile as per instructions in top of each file

_qnxDisplayTest.c_ -- Opens a display-sized window and draws balloon images [see Balloon.h]. Setup window + buffer; fill region; draw individual pixels

_qnxScreenTest.c_ -- As above, but adds code to sample Keyboard and Mouse Pointer events.



Tested on Raspberry Pi 4 + QNX 8.0
