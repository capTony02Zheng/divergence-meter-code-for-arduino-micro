# divergence-meter-code-for-arduino-micro
// This is a project use for creating an divergence meter.

// Code are well written but need the user to update the IRdata to match the 1838IR remote control. Also the ds3231 module need to be updated with
other code, which is not provided here.

// The PCB is developed with kiCAD.

// To start up from nothing, here's the few steps you need to follow:

// 1: Get all the component you need, which includes:

// An arduino micro board;
// A pcb that is printed with the file provided;
// A ds3231 time module;
// An IR1838 module with corresponding remote control;
// One or two 5v to 170v boost module;
// multiple resistors of 10k and 100k;
// four hv5523pg-g chips; you can buy some here: https://www.microchip.com/en-us/product/hv5522#document-table;

//Features of the divergence meter:
There are 6 mode for the divergence meter, the first one displays current time; the second one displays current date; the third one
displays Celsius temperature recorded by ds3231; the fourth mode displays displays worldline; the fifth mode displays the number you entered;
the sixth one diplays number from 0 to 9 to protect the tubes;