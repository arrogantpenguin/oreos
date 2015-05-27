// Decide whether to keep it straight AMD64 or include ARM64 code
// Decide on hardware support and start looking at developing code in hardware/<vendor>/ directories
// Decide on basic kernel model (minimal, yet functional, possibly POSIX compatible) develop code in sys/ directory

<FOR PROCESSOR ARCHITECTURE>
// Code in hardware/AMD64 and hardware/ARM64
// Build kernel with full multicore processor capabilities
// Design bootloader to detect architecture at boot, to allow for removable OSes via thumbdrive/memorycard

<FOR HARDWARE SUPPORT>
// Research and build support for multiple hardware capabilities
// Design kernel to detect and load new hardware loadouts on boot
// Give the software as much low-level exposure to the hardware as is possible
