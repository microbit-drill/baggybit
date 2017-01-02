# baggybit
!![img](media/collection.png)

A picture paints a thousand words, but some words are needed.

- on the left and right hand side of the green pcb, as many big holes/connectors for crocodile clips for safe connection to i/o 
- the green area should have place for i2c and connections to left and right side big holes
- the bottom part of the green area should have the normal micro:bit connection to expansion except
 - big holes are not plated thru, ie the two sides are not connected
 - the black small connector to allow rerouting of i/o: may need two parrallel connectors with more space than jumpers
- the coin battery should be replaceable without removal of micro:bit
- the small black rectangle is a 3.5 jack for mic/speaker 
 - with routing p0: left p1: right p2: mic
 - it should be possible to disable the connections so available on outside big hole connections
- the orange area is the horizontal part of the expansion to allow for "cool things" that are not already on green board
- Kitronik buggy
 - the green board should allow rerouting of i/o so that the buggy is using digital i/o and not valuable analog i/o
 - the expansion pins on the Kitronik motor kit will be accecable for "cool things" as there is rerouting for i/o pins to the otherwise inactive backside of the motor kit
 - it is such that if the micro:bit is reversed on the motor controller, the pins are active, the green board allows for the micro:bit to be freely placed, front or back facing
- The right angled connector is optional, the green board should have big holes for "standard" bolt/nut/spacer for electrical contact of p0-2/vcc/gnd
 - The green pcb should have the possibility of mounting the right angled connector when wished

 ## Kitronik Motor Driver
 !![img](media/motordriver.png)