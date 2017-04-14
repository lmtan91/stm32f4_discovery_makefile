# stm32f4_discovery_makefile

# openocd to download the binary
openocd -f openocd_config/stm32f4discovery.cfg -c "program demo.elf verify reset"
