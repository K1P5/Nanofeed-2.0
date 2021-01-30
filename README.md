# Nanofeed-2.0
Miniature Micro-controlled Feed Auger with Tank 

THIS IS A WORK IN PROGRESS! Thingiverse link: https://www.thingiverse.com/thing:4743999
------------------------------------------------------------------------------------------------------
Historic link to the orginal design, the Feederpi! 
https://www.thingiverse.com/thing:2947556

------------------------------------------------------------------------------------------------------------------------
I will continue to support this design based on user feedback; this means if no one is particularly interested, I will update only as I create new revisions to meet my personal project needs. If you have any questions, concerns, comments please feel free to message me and I will get back to you!

Remaining Uploads:

BOM
Assembly Instructions
PCB Schematic (Via Github link^^^)
Arduino Code (^^^)
Reference Build Images (^^^)

------------------------------------------------------------------------------------------------------------------------

This is the updated and improved miniature all-in-one material auger with integrated storage tank. Better torque, RTC (real time clock) control, Github hosted design/resource files, script(s), PCB files, etc! Based on an Arduino Nano, DRV8825 stepper driver, and a DS3231 RTC breakout, this unit is intended to be a low cost, fun, and DIY solution to automating your low-scale material handling (feeding) needs! 

Operation is simple; Fill the integrated tank with the material of choice (flake/granular material ~3-5mm Dia. MAX). Mount the unit in the location/orientation of choice, and provide 12V DC power via the rear power port. The Nanofeed will await a button press, upon which the auger will perform an adjustable feed cycle (adjustable via IDE). When the cycle is complete, the RTC module will begin a twenty-four (24) hour delay cycle (adjustable via IDE). After the elapsed time has passed, the Nanofeed will dispense an additional feed volume, resetting the RTC timer once again to continue your established, timed feed cycle. 

This design is the latest revision of my earlier Feederpi, the Pi Zero controlled feed system, with many improved features. 

-Arduino Nano powered; allows for a simple, low-cost microcontroller to handle automation, no need to waste a much more valuable and resource-intensive Pi.
 
-The belt path has been revised, ensuring sufficient torque transfer even when dispensing tough materials. 

-The original continuous-servo was replaced with a 4-wire miniature stepper motor, controlled via the onboard DRV8825. 

-Critical components are now mounted and assembled via "mounting cards"; Easy to print, assemble and disassemble the cards allow easy access and transfer of critical components. 

-Simplified and easy-to-print design ensures most if not all home printer solutions will have no issue reproducing the design in your own corner of the world. 

------------------------------------------------------------------------------------------------------------------------
Please Note!

This design utilizes a prototyped PCB, check the included images to understand the scope of development work involved. There "should" be sufficient interior volume within the PCB containment area, so it may be possible to revise the PCB mounting card to instead utilize a prototyping breadboard and related hardware. Check the related Parasolid file(s) to revise as needed.

I will release my original bare PCB, which will be available off of PCBWay for those that would like a more accessible option. The schematic, Gerber files and BOM will also be uploaded to Github, as I continue distributing this design. Please either check back here for the Github link or message me directly!
