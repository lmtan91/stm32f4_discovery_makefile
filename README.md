# stm32f4_discovery_makefile

# openocd to download the binary
1. Install **openocd** on Ubuntu, then all scripts will be located in **/usr/share/openocd/scripts/**
2. To install **demo.elf**
```
openocd -f board/stm32f4discovery.cfg -c "program demo.elf verify reset"
```
