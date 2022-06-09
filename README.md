# Experiment--10-Programmable-logic-devices-
 
### AIM: To implement PROM using verilog and validate its output 
### HARDWARE REQUIRED:  – PC, Cyclone II , USB flasher
### SOFTWARE REQUIRED:   Quartus prime
### THEORY 

 
PROM (Programmable Read-Only Memory) is a type of ROM that is written only. It was meant to fulfill the requirement of a group of ROMs which may contain a selected memory content. It’s memory is written just the once and programmed electrically by the user at the time or when the initial chip fabrication. the required content file is equipped by the user and inserted within the machine referred to as storage coder. There exist a fuse at every programmable association and it’s blown once the association isn’t required.
PROM is primarily meant for smaller productions that require some initial programming. With PROM, the memory chips cannot be improved when they become obsolete. That, plus other limitations, has made PROM a somewhat phased-out type of product and technology in the catalogs of some of today's vendors. In many cases, PROM has been replaced by other methods that involve more flexibility, such as Electronically Erasable Programmable Read-Only Memory (EEPROM).

A process known as "burning the PROM" blows fuses for bit settings, rendering them unchangeable.

![image](https://user-images.githubusercontent.com/36288975/172760743-04a59275-862b-4c42-8d08-8ecbca668c75.png)
Figure -01 PROM 
 
 
### Procedure
/* write all the steps invloved */



### PROGRAM 
~~~
/*
Program for PROM 
Developed by: u.srinivas
RegisterNumber:  212221230108

module ten(out,addr,clk);
output[15:0] out;
input[3:0] addr;
input clk;
reg [15:0] out;
reg [15:0] Rom [15:0];
always @ (negedge clk)
begin 
Rom [0] = 16'h 5601;
Rom [1] = 16'h 5602;
Rom [2] = 16'h 5603;
Rom [3] = 16'h 5604;
Rom [4] = 16'h 5605;
Rom [5] = 16'h 5606;
Rom [6] = 16'h 5607;
Rom [7] = 16'h 5608;
Rom [8] = 16'h 5609;
Rom [9] = 16'h 5610;
Rom [10] = 16'h 5611;
Rom [11] = 16'h 5612;
Rom [12] = 16'h 5613;
Rom [13] = 16'h 5614;
Rom [14] = 16'h 5615;
Rom [15] = 16'h 5616;
out = Rom[addr];
end
endmodule


*/
~~~





### RTL LOGIC  



![172762382-729e3353-62ff-47ab-8c5f-1164905a4e0f](https://user-images.githubusercontent.com/93427183/172842469-ee19b903-dfe4-4a50-824d-24f68d5d0d50.png)






### TIMING DIGRAMS  



![172762396-83fccc73-5360-4b79-9ef0-22fc9154b44b](https://user-images.githubusercontent.com/93427183/172842483-cb3e63b4-c46f-43b8-aa80-b07129fc206d.png)


 





### RESULTS 
Thus the program to design a programmable logical device is done successul.
