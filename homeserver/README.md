# Configuration for my homeserver (tested on bare metal, no GUI)

## Config

- Motherboard: AsRock Taichi B550
- CPU: AMD Ryzen 5950x (16 cores 32 threads)
- GPU: NVIDIA GTX 1050

## Kernel configuration

Wi-Fi and Ethernet drivers: only the interfaces on the mobo have built in kernel support. Support for any other driver has been removed.

Boot: I used efistub to boot the system so the builtin kernel command line must be changed with the right PARTUUID (the one that is corresponding to the system's root partition).
