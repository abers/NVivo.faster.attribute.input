# NVivo Faster Attribute Input Script
AuotHotKey script that enables the ability to input attribute values using the numpad on the keyboard. Helps to dramatically speed up data input when working with a lot of attributes.

## Starting the script 
Script can be run either by opening the exe file or, if AutoHotKey is installed, by opening the script with AHK. 

## Using the script
On starting a help message will display giving an overview of how to use the script. It can be accessed again at any time whilst the script is running by pressing F12.

To enable the hotkeys please press the Windows key and 'p' together.

Once active, rather than right-clicking on a source or node and selecting source or node properties, please left-click on it once so it is selected then press win+p again.

Please wait for the first part of the script to run, and importantly, please don't press any additional keys during this time. The script will open the node properties, shift to the attributes tab, and select the value field for the first variable. 

Each number on the numpad will select the corresponding attribute value. For example, if after 'Not Applicable' and 'Unassigned' the second value is "Turner" then numpad 2 will set the value to "Turner" and move the selection to the next attribute value field 

Pressing enter on the numpad will skip back up one attribute, handy if you accidently chose a wrong value. Additionally, pressing the plus on the numpad will skip to the next attribute. Pressing star on the numpad will set the attribute value to Not Applicable. Finally, pressing subtract on the numpad will return the attribute value back to unassigned.

NVivo for boolean attributes places the No value before the Yes value meaning that they are the opposite way around than you might expect. 

For age and other integer values, please use the number keys on the top of the keyboard to enter the participant's age then press the plus on the numpad to move to the next attribute and resume using the numbers on the numpad- using the keys on the numpad for trying to input age will result in the script selecting a random age from those already inputted.  

## Changing the default sleep timer and number of attributes to skip
Pressing the Windows key and 'o' together will bring up an options menu that can be used to set the sleep timer and the number of attributes to skip. The first is useful if NVivo is running slow to allow a wait period inbetween opening the node properties and moving  the selection focus to the attribute values. The second is useful if, for example, you are adding attributes for a second or third wave of interviews and you would like to skip all the attributes from the first wave so that the focus moves straight-away to where the second wave attributes start.

## Exiting, pausing, and quitting
Pressing the Windows key and enter on the Numpad together will exit the faster attribute input mode. 

Pressing 'pause' at any time (located top right of the keyboard) will pause the script and stop the hotkeys from working and pressing it again will reactivate the script.  Pressing the Windows key and 'q' together at any time (when the keys are not paused) will force the script to close and will need to be double-clicked to run again.
