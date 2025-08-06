# cubemx-h5-simple-led-sample
A very simple CubeMX-based project for demonstrating a potential GPIO issue with the STM32H5 nucleo board in Renode.

The files used to create the CubeMX-based ELF can be found in the CubeMXProject directory.

The files used in the Renode simulation can be found in the RenodeFiles directory. Please note these are based heavily on the blinky files at https://designer.antmicro.com/library/devices/nucleo_h563zi?software=zephyr%7Cnucleo_h563zi%7Cblinky. 

The ELF files can be found in the ELF_Files directory. H5-LED-Sample.elf is created using STM32 CubeMX tools and CMake/GCC. The blinky elf is from the link provided above. Both have been observed to work on real hardware.
