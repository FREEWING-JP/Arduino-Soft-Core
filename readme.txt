FPGAに AVRを実装して Arduino Soft Coreを動かす方法、FPGAを Arduino IDEで開発する
http://www.neko.ne.jp/~freewing/fpga/fpga_avr_arduino_soft_core/  

GadgetFactory/Papilio-Arcade FPGA board用の実装を ALINX AX309 cloneで動く様に改変したものです。

Xilinx FPGA Spartan-6 XC6SLX16 in ALINX AX309 clone  

Please use file "scripts/XilinxISE/AX309_AVR8_LX16.xise" .  

Development Environment:  
* Xilinx ISE WebPack 14.7  
* Windows 10 Pro 64bit 21H2  

---

The Arduino Soft Core is the combination of the AVR8 Soft Processor and the Arduino IDE modified to run on the Open Source Papilio FPGA development board.

For more information visit http://papilio.cc

The AVR8 Soft processor was originally downloaded from [OpenCores.com](http://opencores.com/project,avr_core).

The Arduino IDE is modified to merge sketches into the AVR8 processor and load the processor and sketch the the Papilio One FPGA dev board.

Please use file "Papilio_AVR8_500K.xise" and not "Papilio_AVR8-500K.xise" - this can create problems.

----
To synthesize using Xilinx Webpack navigate to the scripts/XilinxISE directory.

