# IBM-Project-54620-1662359380
Gas Leakage monitoring &amp; Alerting system for Industries
PROJECT OBJECTIVES

ABSTRACT 
 
The  Internet  of  things  (IoT)  is  the  system  of  gadgets, vehicles,  and home  machines  that  contain  hardware, 
programming,  actuators,  and  network  which  enables  these  things  to  interface,  collaborate  and  trade 
information.  IoT  includes  broadening  Internet  network  past  standard  device,  for  example,  work  areas, 
workstations, cell phones and tablets, to any scope of generally stupid or non-web empowered physical device 
and ordinary articles. Installed  with  innovation, these gadgets can  convey and connect over the Internet, and 
they can be remotely observed and controlled [1]. The meaning of the Internet of things has advanced because 
of  union  of  numerous  innovations,  ongoing  examination,  AI,  ware  sensors,  and  implanted  frameworks. 
Conventional  fields  of  installed  frameworks,  remote  sensor  systems,  control  frameworks  computerization 
(counting home and building mechanization), and others all add to  empowering the Internet of  things. A gas 
spill alludes to a hole of petroleum gas or different vaporous item from a pipeline or other regulation into any 
territory where the gas ought not be available. Since a little hole may steadily develop a hazardous convergence 
of  gas,  spills  are  perilous.  Notwithstanding  causing  flame  and  blast  dangers, holes  can  slaughter  vegetation, 
including huge trees, and may discharge amazing ozone harming substances to the environment. 
Keywords:  IOT, MQ5 sensor, Arduino module, GSM networks. 


 
 
I.INTRODUCTION

The  Internet  of  Things  is  a  developing  theme  of specialized,  social,  and  monetary  centrality.
Customer  items,  tough  goods,  cars  and  trucks, modern  and  utility  segments,  sensors,  and  other
regular  articles  are  being  joined  with  Internet availability  and  amazing  information  systematic
capacities  that  guarantee  to  change  the  manner  in which  we  work,  live,  and  play.  Projections  for  the effect  of  IoT  on  the  Internet  and  economy  are amazing, with some foreseeing upwards of 100 billion
associated  IoT  gadgets  and  a  worldwide  financial effect of more than $11 trillion by 2025. The Internet
of  Things  (IoT)  is an  essential  theme  in  innovation industry,  strategy,  and  designing  circles  [1].  This 
innovation  is  encapsulated  in  a  wide  range  of arranged  items,  frameworks,  and  sensors,  which 
exploit  headways  in  processing  power,  gadgets scaling down, and organize interconnections to offer 
new  capacities.  The  expansive  scale  usage  of  IoT gadgets  guarantees to  change numerous  parts of  the 
manner  in  which  we  live.  For  shoppers,  new  IoT items  like  Internet-empowered  machines,  home 
mechanization  parts,  and  vitality  the  executive’s gadgets are pushing us toward a dream of  the  "savvy 
home'',  offering  greater  security  and  vitality effectiveness. IoT frameworks like arranged vehicles, 
savvy  traffic  frameworks,  and  sensors  implanted  in streets  and  scaffolds  draw  us  nearer  to  "brilliant 
urban  areas'',  which  help  limit  clog  and  vitality utilization.  

II.  METHODS AND MATERIAL 
 
System: Input, Output, Function, Success, Failure Input:  Sensor  data  signal  which  is  not  regular  or 
Change in Signal 	
Output: End User get informed with alert buzzer and 
Display to LCD  
Functions: 
1.  Access ():-  In this module  we are  going to  access the  feature  provided  by  the  module  which  Will 
include Sensor data access. 
2.  Control ():-In  this  module we  are  controlling the Alert System by using System which  is connected to 
hardware or sensor data. 
3.  Broadcast  ():-In  this  module  we  are  going  to broadcast the alert Display to LCD. 
4. Success Conditions: 
1. If such data which is received through sensors are not stable  or  are more  than threshold it  will predict 
that there is leakage situation 
5. Failure Conditions: Desired output is not generated due to following failures. 
1. Software Failure 
2. Hardware Failure 
3. Network Connection Failure 
 
HARDWARE INFORMATION:  
1.Arduino Uno  
The Arduino Uno is a microcontroller board based on the  ATmega328  (datasheet).  It  has  14  digital 
input/output pins  (of  which 6  can  be used  as  PWM outputs),  6  analog  inputs,  a  16  MHz  ceramic 
resonator, a  USB  connection, a  power jack,  an  ICSP header,  and  a  reset  button.  It  contains  everything 
needed  to  support  the  microcontroller;  simply connect it to a computer with a USB cable or power it 
with  a  AC-to-DC  adapter  or  battery  to  get  started. The Uno  differs from  all preceding  boards  in  that  it 
does  not  use  the  FTDI  USB-to-serial  driver  chip. Instead, it  features  the Atmega16U2 (Atmega8U2 up 
to  version  R2)  programmed  as  a  USB-to-serial converter. 
 
2.LCD (Liquid Crystal Display) 
 LCD stands for Liquid Crystal Display. LCD is finding wide spread use replacing LEDs (seven segment LEDs 
or  other  multi  segment  LEDs)  because  of  the 
following reasons: 
1. The declining prices of LCDs. 
2.  The  ability  to  display  numbers,  characters  and graphics.  This  is  in  contrast  to  LEDs,  which  are 
limited to numbers and a few characters. 
3.  Incorporation  of  a  refreshing  controller  into  the LCD,  thereby  relieving  the  CPU  of  the  task  of 
refreshing  the  LCD.  In  contrast,  the  LED  must  be refreshed by the CPU to keep displaying the data. 
 
3.BUZZER 
A buzzer or beeper is  an audio signalling  device, which  may  be mechanical, electromechanical, 
or piezoelectric. Typical  uses of  buzzers  and beepers include alarm  devices, timers and  confirmation  of 
user  input  such  as  a mouse  click or  keystroke. The first electric  buzzer  was  invented  in  1831 by Joseph 
Henry.  They  were  mainly  used  in  early  doorbells until they were phased out in the early 1930s in favor 
of  musical  chimes,  which  had  a  softer  tone. Piezoelectric buzzers,  or  piezo  buzzers,  as  they  are 
sometimes  called,  were  invented  by  Japanese manufacturers  and  fitted  into  a  wide  array  of 
products  during  the  1970s  to  1980s.  This advancement  mainly  came  about  because  of 
cooperative  efforts  by  Japanese  manufacturing companies.  In  1951,  they  established  the  Barium 
Titanate  Application  Research  Committee,  which allowed  the  companies  to  be  "competitively 

4.Bluetooth Module: 
SIM900  GSM  Module –  This  means  the  module supports  communication  in  900MHz  band.  We  are 
from India and most of the mobile network providers in this  country operate  in the  900MHz band.  If you 
are  from  another  country,  you  have  to  check  the mobile  network  band  in  your  area.  A  majority  of 
United  States  mobile  networks  operate  in  850MHz band  (the  band  is  either  850MHz  or  1900MHz). 
Canada operates primarily on 1900 MHz band. 
 
IV. PROPOSED SYSTEM 
 
We  design  and  develop  an  propose  system  which include some safety factors. A safety has been a major 
issue  in  today’s  day  to  day  life.  LPG  and  CNG  i.e. petroleum  gas  and  compressed  natural  gas  are  most 
commonly used in residential and commercial places for  cooking  purpose  and  in  various  vehicles  as  a 
replacement  for  costly  fuels  like  diesel,  petrol  [7]. These  gases  are  filled  in  cylinders which  are  easily 
un-damageable.  But  leakage  can  take  place through pipes  or  regulators  or  knobs  which  may  cause 
accidents  like  suffocation,  uneasiness  or  sometimes .
 
V. CONCLUSION 
 
The  advantage of  this  simple gas  leak  detector is  its simplicity and its ability to warn about the leakage of 
the LPG gas [11]. This system uses GSM technique to send  alert  massage  to respective  person  if  no one  is 
there  in  the  house  and  then  gas  leaks  occurs,  GSM module  is  there  to send  immediate messages  to the 
respective  person  regarding  the  gas  leak  [13].  The main  advantage  of  this  system  is  that  it  off  the 
regulator  knob  of  the  cylinder  automatically  when gas leakage detected.


![image](https://user-images.githubusercontent.com/116338304/197356421-8bc6bf38-1f6a-4bca-99ca-a99047c08a84.png)
