# QEMU-overhead
QEMU preallocates memory regions for device emulation. This patch, generated using qemu-4.2.1 needed to be applied to memory.c, is used to compute the qemu emulation overhead.

The patch generates a log, which is stored in /tmp/log.txt file in the following format: [Current Total][Size of the region][Name of the region]
