# buildroot for H3 failsafe rom
## Flash image: 
- Partition_info: 8k: 0x2000@0x0000[0]
- Tee + u-boot: -512k: -0x80000@0x2000[8k]
- Dtb: 512k: 0x80000@0x80000[512k]
- Kernel-emgc: -16M: -0x1000000@0x100000[1m]
- Rootfs-emgc: 16M: 0x1000000@0x1000000[16m]
- Part1-boot/rootfs: xM: xM@0x2000000[32m]
- Part2-system: ...
