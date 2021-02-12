## Barebones Template for Longan Nano 

This is meant as a starting point template and doesn't have any value by itself.

Important commands:
- ~/riscv-binutils-gdb/binutils/objcopy -O binary output firmware.bin
- dfu-util -a 0 -s 0x08000000:leave -D firmware.bin