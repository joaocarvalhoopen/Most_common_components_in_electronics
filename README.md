# Most common components in electronics

A guide to the electronics adventurer!

## Description

In this repository, I will try to maintain a list of the most common components in electronics. Specially, the ones that passed the test of time, the ones that distinguished themselves by having characteristics that are useful in a broad range of projects. The components should also be inexpensive, available and easy to get from several sources. They should be on every electronics designer, engineer, technician or electronics hobbyist stock, near the workbench. I divided this list by category, their main characteristics, is listed and there is a link to the datasheet.

# List of components

## Resistors

* You can buy them in kits with all series values, but the most common values of 1/4 Watts, 5 % or 1 % are:<br>
  **10**   - To limit current at the output of OpAmps.<br>
  **47**   - Generic use.<br>
  **56**   - Some white LEDs at 5V.<br>
  **82**   - Some white LEDs and blue LEDs at 5V.<br>
  **100**  - To limit current in inputs.<br>
  **120**  - Yellow, green and orange LEDs at 5V.<br>
  **150**  - Red LEDs at 5V.<br>
  **220**  - Nice generic value to play safe for a LEDs of any color at 5V, good fot infra-red LEDs at 5V.<br>
  **330**  - Resistor for collector/emitter.<br>
  **390**  - Resistor for collector/emitter.<br>
  **470**  - Resistor for collector/emitter, strong pull-up for I2C lines. And because it limits the current to approximately ~1mA at 5V.<br>
  **560**  - Resistor for collector/emitter, strong pull-up for I2C lines.<br>
  **1K**   - Low current/low bright for LEDs of any color, voltage dividers, inputs protection, if a strong pull-up is needed.<br>
  **1.2K** - Voltage dividers.<br>
  **1.5K** - Voltage dividers.<br>
  **2.2K** - Bias for circuits, voltage dividers.<br>
  **3.3K** - Bias for circuits, voltage dividers.<br>
  **3.9K** - Bias for circuits, voltage dividers.<br>
  **4.7K** - Bias for circuits, voltage dividers. A medium value that with 10K divides a 5V into ~3.3V (and that’s nice for micro-controllers).<br>
  **5.6K** - Bias for circuits, voltage dividers.<br>
  **10K**  - Pull-ups/Pull-downs, resistors for collector.<br>
  **22K**  - Pull-ups/Pull-downs, pull-ups of reset pin in micro-controllers.<br>
  **33K**  - Pull-ups of reset pin in micro-controllers.<br>
  **47K**  - Generic use.<br>
  **100K** - Gain control in OpAmps and discrete amplifiers, pull-downs in analog circuits.<br>
  **330K** - Gain control in OpAmps and discrete amplifiers, pull-downs in analog circuits.<br>
  **470K** - Gain control in OpAmps and discrete amplifiers, pull-downs in analog circuits.<br>
  **1M**   - Gain control in OpAmps and discrete amplifiers, pull-downs in analog circuits, is used in piezo discs (low current speaker).<br>
  **2.2M** - Gain control in OpAmps and discrete amplifiers, pull-downs in analog circuits.<br>
  Note: Many of those resistors application info, come from "Kit Njay de Resistências 1/4W" and is used with permission.


## Capacitors

* The most common values are:<br>
  **100nF**  - Generic bypass.<br>
  **4.7uF**  - Also used as bypass capacitor in parallel with 100nF.<br>
  **10uF**   - Higher capacitance, very common in smd.<br>
  **100uF**  - Polarized, for filtering near voltage regulator.<br>
  **1000uF** - Polarized, to smooth the ripple in mains power supplies.<br>
  **2200uF** - Polarized, to smooth the ripple in mains power supplies.

* Others types: <br>
  **For small pF** - You can use a DIY solution, two isolated and twisted wires cut to length.<br>
  **For small variable value** - You can use a trimmer cap.<br>
  **For dynamic value** - You can use a DC bias Varicap diode or use a generic diode as a Varicap.<br>
  [Please see this page on VariCaps](http://ftp.hanssummers.com/varicap.html)<br> 
  **DIY Capacitors** - [Home made capacitors](https://www.youtube.com/watch?v=GveI9gXIsHw&list=PLFsZmHTZL-zmfXxstlxuJgRE9bOGobEVu)

## Inductors

* Those can have air cores or cores from other materials. They are more specific so I don't list more used values of commercial ones here, I will only say that for high frequency application you can make your owns.<br>
  **DIY inductors** - [Home made inductors](https://www.youtube.com/watch?v=awyLYgu6ODM)

## LED’s

* Many colors: **red**, **yellow**, **green**, **orange**, **blue**, **white**, infra-red, Ultra-Violet (not very common), **RGB LEDs**.<br>
  Most common came in 3mm, 5mm and SMD packages. <br>
  Each color has it’s own forward voltage and should always be used with a current limiting resistor.<br>
  [They can also be used as VariCaps diodes](http://www.hanssummers.com/varicap/varicapled.html) 


## Diodes

* **1N4148** - Signal diode, 100V, 200mA. Note: At low voltages 1N5917/8/9 are equivalent to 1N4148, 1N400x.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/1N914-D-1801484.pdf)

* **1N4001** to **1N4007** - Rectifying diodes, 1 A, (1 - 50V, 2 - 100V, 3 - 200V, 4 - 400V, 5 - 600V, 6 - 800V, 7 - 1000V).<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/1N4001-D-1801424.pdf)

* **1N5817** - Schottky diode, 20V, 1A, Fast switching.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/1n5817-1848842.pdf)

* **1N5822** - Can be used as a great range VariCAP, Schottky diode, 40V, 3A. <br>
  [Please see this page on VariCaps](http://ftp.hanssummers.com/varicap.html) <br>
  [Please see the images with the graph and table in this page](http://ftp.hanssummers.com/varicap/varicapdiode.html) <br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/1n5822-1848813.pdf)

* **BAT85S** - Schottky diode, 30V, 200mA. Equivalent to BAT54.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/427/bat85s-1767722.pdf)

* **BZX79B3V3** - Zener diode, 3.3V, 1/2W, 2%.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/395/BZX79B2V4%20SERIES_D1610-1099766.pdf)
 
* **BZX79B5V1** - Zener diode, 5.1V, 1/2W, 2%.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/395/BZX79B2V4%20SERIES_D1610-1099766.pdf)

* **TZX12C** - Zener diode, 12V, 1/2W, 2%.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/427/tzxserie-1767901.pdf)
 
* **CDBV3-40S-G** - Input protection - series diodes, 40V, 200mA.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/80/CDBV3-40_2cS_2cC_2cA-G_RevB731263-1481097.pdf)


## BJT Transistors

* **2N3904** - BJT, **generic**, npn, 40V, 200 mA, bandwidth 300 Mhz, 625 mW, noise figure 5db, signal.<br>
  [2N3904 wikipedia](https://en.wikipedia.org/wiki/2N3904)<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/2N3904-D-1801586.pdf)

* **2N3906** - BJT, **generic**, pnp, -40 V, -200mA, 250 MHz, 625 mW, noise figure 4db,  signal, complementary Pair of the 2N3904.<br>
  [2N3906 wikipedia](https://en.wikipedia.org/wiki/2N3906)<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/2N3906-D-1801672.pdf)

* **BC547** - BJT, npn, noise figure 2 dB, 50V, 100mA, bandwidth 300MHz, 500mW.<br>
  Terminating with x for each beta range: A - 110 to 220, B - 200 to 450, C - 420 to 800.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/BC550-D-1802078.pdf)

* **BC557** - BJT, pnp, noise figure 2 dB, -50V, -100mA, bandwidth 150MHz, 500mW, complementary pair of BC547.<br>
  Terminating with x for each beta range: A - 110 to 220, B - 200 to 450, C - 420 to 800.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/BC556BTA-D-1802030.pdf)

* **BC549C** - BJT, **low noise**, npn, high beta 420 to 800, noise figure 1.2 dB, 30V, 100mA, bandwidth 300MHz, 500mW.<br>
  Terminating with x for each beta range: A - 110 to 220, B - 200 to 450, C - 420 to 800.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/BC550-D-1802078.pdf)

* **BC559C** - BJT, **low noise**, pnp, beta 420 to 800, low noise, noise figure 1.2 dB, -30V, -100mA, bandwidth 150MHz, 500mW, complementary pair of BC549C.<br>
  Terminating with x for each beta range: A - 110 to 220, B - 200 to 450, C - 420 to 800.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/BC556BTA-D-1802030.pdf)

* **BD135** - BJT, npn, **medium power**, beta 100, 45 V, 1.5 A, 1.25 W, audio amplifier.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/bd135-1848980.pdf)

* **BD136** - BJT, pnp, **medium power**, beta 100, -45 V, -1.5 A, 1.25 W, audio amplifier, complementary pair of BD135.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/bd135-1848980.pdf)

* **KSP10** - This is a replacement for the good old **BF199**. <br> 
  BJT, npn, **RF transistor**, bandwidth 650 MHz to 1GHz, 25V, beta 60,  60 mA, 350 mW.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/KSP10-D-1810572.pdf)

* **TIP31CG** - BJT, **high power**, npn, 100 V, 3 A, 40 W, 3 MHz, beta 20.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/TIP31A-D-1814956.pdf)

* **TIP32CG** - BJT, **high power**, pnp, -100 V, -3 A, 40 W, 3 MHz, beta 20, complementary pair of TIP31CG.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/TIP31A-D-1814956.pdf)

* **TIP41CG** - BJT, **high power**, npn, 100 V, 6 A, 65 W, 3 MHz, beta 20.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/TIP41A-D-1815006.pdf)

* **TIP42CG** - BJT, **high power**, pnp, -100 V, -6 A, 65 W, 3 MHz, beta 20, complementary pair of TIP41CG.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/TIP41A-D-1815006.pdf)

* **TIP122** - BJT, **darlington high power**, npn, 100 V, 5 A, 65 W, beta min 1000, TO220. <br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/tip120-1852367.pdf)

* **TIP127** - BJT, **darlington high power**, pnp, -100 V, -5 A, 65 W, beta min 1000, TO220, complementary pair of TIP122.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/tip120-1852367.pdf)

* **2N6027** - This is a replacement for the good old **2N26469**. <br> 
  **PUT - Programmable Unijunction Transistor**, 40 V, 300 mW.<br>
  This is a component that has a "negative resistance" zone. The 2N2646 was used in oscillators with output having "low impedance", that is, only with one "transistor", you could make an oscillator that drives directly a low power speaker. <br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/2N6027-D-1801510.pdf)

* **ULN2003A** - chip, seven darlington arrays, output current 500 mA, output voltage 50 V, integrated suppression diodes for inductive loads, TTL/CMOS compatible inputs. <br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/uln2001-1852702.pdf)

* **ULN2803A** - chip, eight darlington transistors with common emitters, output current to 500 mA, output voltage 50 V, integral suppression diodes, TTL/CMOS compatible inputs.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/uln2801a-1852595.pdf) 



## JFet Transistors 

* **J111** - Type n, -35V, 50mA, 625mW, 30 Ohms, signal.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/MMBFJ113-D-1811481.pdf)
 
* **J175** - Type p, 30V, 50mA, 350mW, 125 Ohms  signal.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/J175-D-1810249.pdf)


## MOSFET Transistors

* **BS170** - N-MOS, 60v, 500mA, input capacitance 60pf, switching 4ns.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/BS170-D-1803008.pdf)

* **BS250** - P-MOS, -45 V, -230 mA, 700mW.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/115/BS250P-36302.pdf)

* **DMG1012UW-7** - MOSFET N-Channel, 20V, 1A, SOT-323, SMD.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/115/ds31859-90313.pdf)
 
* **IRF3205PBF** - N-MOS, Power MOSFET 150 W, 55V, 110A, 8mOhm, 97.3nC.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/196/irf3205pbf-1732530.pdf)


## IGBT Transistors

* **STGF5H60DF** - 600 V, 5 A, 24 W.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/stgb5h60df-1850797.pdf)
 
* **STGP7NC60HD** - 600 V, 14 A, 25 W.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/stgb7nc60hd-1850860.pdf)

* **STGP40V60F** - 600 V, 40 A, 62.5 W.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/stgb40v60f-1850655.pdf)

* **IHW25N120E1** - 1200 V, 25 A, 231 W.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/196/Infineon-IHW25N120E1-DataSheet-v02_01-EN-1731566.pdf)

* **FGH80N60FD2** - 600 V, 40 A, 290 W.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/308/FGH80N60FD2-D-1808869.pdf)


## Thyristors

* **P0102DA** - SCR, 400 V, 0.8A, TO-92.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/p0102da-1480544.pdf)

* **2N6507G** - SCR, 400 V, 25A, TO220-AB.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/240/Littelfuse_Thyristor_2N6504_D_Datasheet.pdf-1317268.pdf)

* **Z0409NF0AA2** - TRIAC, 600V, 4 A.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/z04-1852640.pdf)

* **T1620T-8I** - TRIAC, 600V, 16A.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/t1620t-8i-1852350.pdf)  


## OpAmps - Operational Amplifiers

* **LM358** - Double, cheap, 3V to 36V, Bandwidth 1.2 MHz, Voffset 3mV, noise figure 40nV/sqrt Hz, not rail to rail.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm358.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591004748869)

* **TL072** - Double, JFET inputs, cheap, low THD - Total Harmonic Distortion 0.003%, Low noise 18 nV/sqrt Hz, not rail to rail, used in high quality audio.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/tl072.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591005562273)

* **NE5532** - Low noise, cheap, supply min +-5V to +-15V, not rail to rail, 10 MHz, Voffset 4mV, 5 nV/sqrt Hz, low THD - Total Harmonic Distortion, used in high quality audio.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/ne5532a.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591006447562)

* **MCP6004-I-P** - Microchip, quad, cheap, rail-to-rail, single supply 3.3V to 5V, bandwidth 1MHz, offset voltage = 4.5 mV, noise figure 28nV/sqrt Hz.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/268/21733j-740845.pdf)

* **MCP6024-E/P** - Microchip, quad, rail-to-rail, single supply 3.3V to 5V, bandwidth 10MHz, offset voltage = +-0.250 mV, extended temperature, noise figure 8.7nV/sqrt Hz.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/268/21685b-25979.pdf)

* **MCP6072T-E/SN** - Microchip, double, cheap, bandwidth 1.2 MHz, offset voltage =  150 uV, SOIC-8 SMD, 19nV/sqrt Hz.<br>
  [Datasheet](https://pt.mouser.com/ProductDetail/Microchip-Technology/MCP6072T-E-SN?qs=WqWCsLCZBkqxem6AyHcpJg%3D%3D)
 
* **TC7650CPA** - single, chopper, single-supply or dual supply 5V, not rail to rail + 0.3V lower limit  - 0.3V upper limit, zero offset chopper stabilized operational amplifier, low input  noise offset voltage 2.0 uV pp bandwidth 2MHz.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/268/21463b-40504.pdf)


## Comparators

* **LM393** - Double comparator up to 38V, 1uS.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm393.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591005754950)

* **LM339** - Quad comparator, single supply 2 V to 36 V, double supply ±1 V to ±18 V, output current 20 mA.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm339a.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591005916821)


## 555 Timer

* **NE555** - Timer from microseconds to hours, astable and monostable, adjustable duty cycle, TTL output compatible, can sink or source 200 mA.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/ne555.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591006555392)


## Voltage regulators

* **LD1117V33** - Voltage regulator ST, 3.3 V, 0.8A, TO-220-3, input voltage has to be min 1V upper.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/ld1117-1849389.pdf)

* **LD1117V50** - Voltage regulator ST, 5 V, 0.8A, TO-220-3, input voltage has to be min 1V upper.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/ld1117-1849389.pdf)

* **LD1117** - Adjustable voltage regulator ST, 0.8A TO-220-3, input voltage has to be min 1V upper.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/ld1117-1849389.pdf)

* **LD1117S33CTR** - Voltage regulator LDO 3.3V, 0.8A, positive, SMD, package SOT-223-3.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/ld1117-1849389.pdf)
 
* **LM78xx ICs**, 1.5 A, including 7805 (5 V), 7806 (6 V), 7808 (8 V), 7809 (9 V), 7810 (10 V), 7812 (12 V), 7815 (15 V), 7818 (18 V), and 7824 (24 V).<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm340.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591007597872)

* **LM79xx IC's** "part number" to "voltage output" scheme, 1.5 A, but their outputs are negative voltage, for example 7905 is −5 V and 7912 is −12 V.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm79.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591007662512)

* **LM317** - Adjustable voltage regulator, 1.5 A. <br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm317-n.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591007747243)


## Special components

* **LM35DZ** - Temperature sensor, linear + 10-mV/C scale factor, 0.5 C ensured accuracy, −55 C to 150 C range.<br>
 [Datasheet](http://www.ti.com/lit/ds/symlink/lm35.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591007837552)

* **L293D** - Two H bridges, supply up to 36 V, 600 mA, 1.2A peak.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/l293d-1849134.pdf)

* **TL431ACZ** - Voltage reference, adjustable output voltage 2.5 to 36 V, sink from 1 to 100mA, 1% and 2% voltage precision.<br>
  [Datasheet](https://pt.mouser.com/datasheet/2/389/tl431-1852462.pdf)

* **LM386** - Audio amplifier class A-B, wide supply voltage range 4 V–12 V or 5 V–18 V, low distortion 0.2%, voltage gains from 20 to 200, 20 to 700 mW.<br>
  [Datasheet](http://www.ti.com/lit/ds/symlink/lm386.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&ts=1591008261226)
 
* **Ferrite bead 1-1624117-6**, 600R@100MHz +/-25% 200mA  package 0805

## Disclaimer
Please, before choosing a component or using it, always check the specifications of each part against the datasheet of the manufacturer of your specific part. I collect the characteristics of the parts with great diligence, but I don't assume any responsibility for any error or mistake that I could have made in this list. So always check your part specific datasheet before using the part.

## License
This document is under the Creative Commons license.

## Have fun!
Best regards, <br>
Joao Nuno Carvalho

