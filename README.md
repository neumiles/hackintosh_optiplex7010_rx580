# hackintosh_optiplex7010_rx580
opencore 9.0 with legacy patcher for Ventura. 98% good.
Dell optiplex 7010 BIOS:A29
CPU: i7 3770
GPU: rx580 8G 

working:
almost everthing(still testing)

not working:
nothing till now.

how to use?
normal hackintosh installation steps(to be added).
1. add -amd_no_dgpu_accel in boot-args, otherwise you will see blackscreen after booted into Ventura. 
2. run OpenCore Patcher , click 'Post-Install Root Patch', click 'Start root patching' .
3. remove -amd_no_dgpu_accel in boot-args. then reboot, enjoy Ventura with your Optiplex 7010.

