Everything needs to be cleaned up, but I'm slowly starting to implement version control and get a better understanding of a workflow that suits me and is sane for any end user.

The code in main has a few minor tweaks to get the code to compile and to test adding raytac dongle support to my own branch. Currently used only for refrence.

The code in RAYTACDONGLE has a working config for the dongle that uses slicemk fork of zmk that has added RAYTAC support. Use this currently for dongle.

The code in theDbranch is the one used currently for the two halves of the peripherals. Your firmware should read lily58d for dongle.
Main hasnt been renamed so when it compiles the left half it pulls the default config for lily58 automatically. This makes the left central instead of another peripheral.

ToDo: Clean up the main branch adding support for studio if possible, rename lily58 to lily58d or something similar. 
