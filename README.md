# CANalystII-SocketCAN

Linux SocketCAN kernel module for the CANalyst II USB CAN adapter, an
affordable Chinese 2-channel adapter having USB ID 04d8:0053.

What documentation I have on this adapter can be found at
[my wiki](https://nick-black.com/dankwiki/index.php/CANalyst_II). For now,
[python-can](https://python-can.readthedocs.io/en/master/) exports a userspace
driver that operates directly on the USB device, and `slcand` can bind to
ttyUSB interfaces created via the `usbserial` kernel module.
