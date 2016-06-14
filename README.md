## Wind River Rocket [**Arduino-lite**](https://github.com/Wind-River/rocket-arduino-lite) API

# Arduino-lite Digital Sensor I/O Sketch  
A digtal input (**Button** or **Touch** sensor) controls a digital output (to **Relay**, **Buzzer**, or **LED**)    

*** 
  
##  Required Hardware
 * [**Intel Galileo Gen 2**](http://www.intel.com/content/www/us/en/embedded/products/galileo/galileo-overview.html) or [**NXP FRDM-K64F**](http://www.nxp.com/products/software-and-tools/hardware-development-tools/freedom-development-boards/freedom-development-platform-for-kinetis-k64-k63-and-k24-mcus:FRDM-K64F)  
 * [**Grove Starter Kit**](http://www.seeedstudio.com/deled/Grove-Starter-Kit-for-Arduino-p-1855.html)
   * Input sensor (connected to **D3**).  Choose one of **Button** or **Touch** sensor.  
   * Output sensor (connected to **D6**).  Choose One of **Relay**, **Buzzer**, or **LED Socket Kit with LED**
 
## Hardware Configuration

1. Power off the **Intel Galileo Gen 2** or **NXP FRDM-K64F** before connecting shield or sensors  

2. Ensure that the **VCC** switch on the **Grove Shield** is appropriate for the device:  
* **5V** for the **Intel Galileo Gen 2**; or   
* **3.3V** for the **NXP FRDM-K64F**.

3. Choose one of the 2 input sensors (**Button** or **Touch** sensor) and insert one end of a 4-pin cable into the connector

4. On the Grove Shield, locate the connector labeled **D3** and insert the other end of the 4-pin cable.

5. Choose one of the 3 output sensors (**Relay**, **Buzzer**, or **LED Socket Kit**) and insert one end of a 4-pin cable into the connector.

6. If you are using the **LED Socket Kit**, choose one of the LEDs and insert the two wires into the socket of the **LED Socket Kit** sensor ensuring that the  **anode (long wire)** is in the **positive (+)** socket.

7. On the Grove Shield, locate the connector labeled **D6** and insert the other end of the 4-pin cable.


## Control and Output
### Input
1. Press and release **Button**; or  
2. Touch and release **Touch** sensor.

### Output
1. **Relay**: The relay switches on for two second (red LED illuminated) then turns off (an audible click is heard when it switches); or  
2. **Buzzer**: The buzzer turns on for two seconds then turns off; or  
3. **LED Socket Kit**: The LED turns on for two seconds the:1


