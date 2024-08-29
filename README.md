# parolla_scrolling_arduino

Use the Parola library to scroll text on the display

Demonstrates the use of the scrolling function to display text received from the serial interface
User can enter text on the serial monitor and this will display as a scrolling message on the display.
Speed for the display is controlled by a pot on SPEED_IN analog in.
Scrolling direction is controlled by a switch on DIRECTION_SET digital in.
Invert ON/OFF is set by a switch on INVERT_SET digital in.
UISwitch library can be found at https://github.com/MajicDesigns/MD_UISwitch
MD_MAX72XX library can be found at https://github.com/MajicDesigns/MD_MAX72XX
