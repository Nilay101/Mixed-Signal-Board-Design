## Project Overview
This following project is a design of a Mixed Signal board design which consist of multipler perhiperals and communication protocols which is used by the microcontroller, with built in ADC and microhpone peripherals. In this project I have provided a design for Central Controller Board design. This can be used for multiple applications such as controller board for autonomous vehicals, Robotics, Defense mechanism, Industrial Machines etc.

## Key specifications
> [Technical specification]

* `Microcontroller and Debugger: 
STM32F407 Controller with Debugger on STM32F103.`
* `Communication Interfaces:
Ethernet (Transfer Speed: 2MB/s) 
USB 2.0, CAN Bus (Transfer Speed:
1MB/s), UARTs`
* `ADC
24-bit ADC: ADS122C04IPW with external
reference and clock, PGA 128, Sample Rate: 100SPS`
* `Motor Drivers
DRV8701 motor Driver with Mosfet Bridge with ability to run 2 bi-directional motor with a power rating of 36W (12V, 3A)`

> [Physical specification]
> Dimensions:
> 75.00mm X 70.00mm
> ![](https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/cea92cd5136b66ddd60f3f0f14ad82e4e045e4f8/Images/PhysicalDim.png)

## 2.Block Diagram
![](https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/6f48fad0da92dc2ec3374a7bc96cafcb16f029bb/Images/Schematic%20Block.PNG)

## 3.Power Budget
![](https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/6f48fad0da92dc2ec3374a7bc96cafcb16f029bb/Images/Power%20Budget.PNG)

## 4. Layer Stack
![](https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/74ef40a205442ae5d97af97179a7f0ddcca79347/Images/Stackups.png)
`Layer 1 (Signal): Top routing and component placement`

`Layer 2 (GND): Solid ground plane for return paths`

`Layer 3 (VCC): Internal Power VCC Plane`

`Layer 4 (Signal): Bottom Signal routing`
<table>
  <tr>
    <td><img src="https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/bab1862c16ad35a5d6e8c263587db0406e25521a/Images/Layer1.png"/></td>
    <td><img src="https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/bab1862c16ad35a5d6e8c263587db0406e25521a/Images/Layer2.png"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/bab1862c16ad35a5d6e8c263587db0406e25521a/Images/Layer3.png"/></td>
    <td><img src="https://github.com/Nilay101/Mixed-Signal-Board-Design/blob/bab1862c16ad35a5d6e8c263587db0406e25521a/Images/Layer4.png"/></td>
  </tr>
</table>
