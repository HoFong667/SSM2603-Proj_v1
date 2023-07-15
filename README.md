# SSM2603-Proj_v1

Target device: SSM2603 from Analog Device, Audio Codec
Target board: Zybo Z7, Zynq-7000 ARM/FPGA SoC Development Board

Description: Direct input and output of audio including ADC and DAC operation. The audio codec is initialized using I2C and 
once the SW0 switch is turned on, I2S will be preformed for data capture or placement. All is done by VHDL.
To facilitate these operations, two clocks need to be generated: one at 24.576MHz for I2S and another at 5MHz for I2C.

Line IN: Audio in
HPH Out: Audio out
SW0: Direct input/output activation
BTN3: Reset, re-initialize
