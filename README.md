Here is where the dongle is made. Pointed at the slicemk fork of zmk main repo and combining configs from the ergodox dongle with the lily58 config,
I have successfully paired my raytac dongle with a nice nano or rather, my nice nanos with the raytac dongle.
I do not recommend going this route, the raytac dongles are expensive and usually dont come pre-flashed with a bootloader.

ToDo: add the complicated instructions of flashing the bootloader the only way I was successful. Directly to the gpio of an rpi 4 with openOCD. Use the native package from apt, dont
waste your time compiling. Briefly tried on a raspberry pi 5 and propmptly went back to the 4.

For refrence in case you want to use pi pico:
https://mcuoneclipse.com/2023/10/22/debug-probes-for-rp2040-with-vs-code/
https://mcuoneclipse.com/2023/04/08/open-source-picolink-raspberry-pi-rp2040-cmsis-dap-debug-probe/
https://github.com/raspberrypi/debugprobe
