# HP-29E_JulianDate

A Gregorian Date to Julian Date converter. Adapted from the HP-41 Solutions Book, "Calendars".

This must be the most marginal program I've ever made. If there is one other
person in the whole universe that will use this, color me surprised.

To make use of this program, you will need an HP-25E (LP) from
[Panamatik](http://www.panamatik.de/html/hp_calculator_repair_kit.html)
and set it up to be an HP-29.

Enter the program into the calculator.

Then set the calculator in GPS mode for it to capture the current UTC time.
While in GPS mode, press "f STO 0" to make the calculator continually store
the current UTC time into register 0. Exit GPS mode, enter the current date as
DD.MMYYYY. Then press "GSB 0" to run the program. It will then convert the
current date to the Julian Date, add the current time and dispay that for two
seconds before it will recalculate the Julian Date again with the updated UTC
time continually captured by the GPS chip into register 0.

Have the calculator beside your telescope to have it continually present the
current Julian Date for you to jot down on your observation notes.

The reason you would use this calculator to do this conversion is because the
red LED display is kind to your night vision.

Enjoy the skies.

PS: The reason that the program file has the extension ".25" is for the
program to be displayed nicely in VIM using my [HP-25 VIM
plugin](https://www.vim.org/scripts/script.php?script_id=5523).
