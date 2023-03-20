# g36-ahu-faults

## This project is under development to eventually be a Pypi package to use with the `open-fdd` project for ASHRAE G36 FDD:
https://github.com/bbartling/open-fdd

###### Fault equations expect a float between 0.0 and 1.0 for a control system analog output that is typically expressed in industry HVAC controls as a percentage between 0 and 100% of command. 
Examples of a analog output could a heating valve, air damper, or fan VFD speed. For sensor input data these can be either float or integer based. Boolean on or off data for control system 
binary commands the fault equation expects an integer of 0 for Off and 1 for On.

## Reference AHU fault equations here:
https://github.com/bbartling/open-fdd/tree/master/air_handling_unit/images
