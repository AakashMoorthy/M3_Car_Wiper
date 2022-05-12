# PROJECT TITTLE - WIPER CONTROL SYSTEM

# INTRDUCTION
Wiper system is the utility project. It is used to clean the wind shield of the car at the front and rear. Wiper works by removing oil,dust,rain water and dirt.That get struck to the wind shield and the arm is provided by the motor.The warm gear is able to generate the force required to move the wipers as fast as they need to move. now a days we have an automatic wiper control when ever we stop wiping in between the process it will automatically comes to initial position this is the new wiper system as behined in the wiper arm.The car wipers that have been available in the present day market are manual systems that work on the principle of manual switching.Our proposed system proposes an automatic wiper system that automatically switches ON the wiper on detection of rain and stops the wiper action when rain stops. This system eases the work of driver by eliminating the manual human intervention for initiating the wiper action, thereby contributing to the comfort driving.
This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen. Because driving a vehicle in the rain is quite difficult, we will use wipers to clear the front screen of the vehicle, which is a mirror, so that we may drive the vehicle even in the rain.

# WORKING 
* The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED keeps continuously glowing until the stop of the engine signifying the engine condition to be turned ON.
* On press of the user input push button, the other three Blue, Green and Orange LEDs come ON one at a time with the set frequency. The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz.
* The LED glow pattern stops on the 4th press; the wiper action starts with the next press.
* If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine is turned OFF.

# REQUIREMENTS FOR THE PROJECTS ARE :
## STM32Cube IDE :
* STM32Cube software ecosystem. STM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors. It is based on the Eclipse®/CDT™ framework and GCC toolchain for the development, and GDB for the debugging. It allows the integration of the hundreds of existing plugins that complete the features of the Eclipse® IDE.

## Xpack Packages :

### Windows Build Tools:
* The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.

### OpenOCD :
* Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.

### QEMU :
* The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.

# 5WS AND 1H
## WHAT
It is Wiper Control system which is generally deployed in all the automobiles in order to ensure safety for the passengers and drivers during rainy conditions.

## WHERE
It is an element which is present in the windshield of the automobile.

## WHO
It is highly useful for drivers of any kind of automobile who needs clear vision of the road in case of dust or rain.

## WHEN
It is recommended to operate during dust or rain

## WHY
To get a clear vision of the road.

## HOW
It is implemented with the help of STM32 with the desired operation of turning on the engine, changing of speeds and turning off with the help of Embedded c Programming.



# SWOT Analysis 
## Strength
* Visibility
* The wiper does not stop in the middle of the window during drive.
* Safety

## Weakness 
* High cost
* Not automatic

## Opportunities
* Rain sensing and automatic operation can be implemented as further enhancement.


## Threats 
* Once the board repaired cannot be replaced quickly

# REQUIREMENTS
## High level requirements
| ID | Description | Status |
| --- | --- | --- | 
| HR_01 | ACC Mode Operation |	Implemented |
| HR_02 |	Wiper ON |	Implemented |
| HR_03 |	Wiper Speed Change |	Implemented |
| HR_04 |	Wiper OFF |	Implemented |
## Low level requirements
| ID |	Description | Operation |	Status |
| --- | --- | --- | --- |
| LR_01 |	Button pressed once for 2 secs | Red LED ON |	Implemented |
| LR_02 |	Button pressed second time | 1 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_03	|Button pressed third time | 4 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_04	|Button pressed fourth time | 8 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_05 |	Button pressed again for two seconds |Turn Off all LEDs |	Implemented |



