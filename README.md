# octopuslab
octopusLAB - for devBoard ESP8266/32 - NodeMcu (LoLin) and octopus ESP-interface-board 


<br />
<hr />
oeLABpins:<br />
<pre>
     -----------   (GPIO)
 A0 -           - D0(16)     PIEZZO 1k 
  G -           - D1(05)   > I2C-CLK
 VU -           - D2(04)  <> I2C-DATA
 S3 -           - D3(00)   < FLASH/BTN
 S2 -  NodeMcu  - D4(02)  <> DIN-ONEWIRE/LED
 S1 -           - 3V         +
 SC -  (Lolin)  - G          x/GND
 S0 -           - D5(14)   > SPI-CLK
 SK -           - D6(12)     CS2/PIEZZO2  
  G -           - D7(13)  <> SPI-DATA
 3V -           - D8(15)   > SPI-CS1
 EN -           - RX(03)   > RX
RST -           - TX(01)   < TX
  G -           - G          GND
VIN -           - 3V         +
     -----------
</pre>
