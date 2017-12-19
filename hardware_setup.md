# My machine
I am use an NVIDIA Titan Xp (2017 Jedi edition) for training.

# First time setup
1. I installed Ubuntu 16.04 LTS desktop edition from a USB onto a clean hard disk.
   1. I had to connect a keyboard and monitor to my machine for this initial installation.
   1. I saw a boot error after the first boot and had to physically remove the USB drive. My BIOS might have had USB booting prioritized.
1. The computer restarts and boots into Ubuntu. Open the terminal from the desktop.
1. Install ssh, to enable remotely connecting to the machine.
   `sudo apt-get install openssh-server`
   1. The monitor and keyboard can now be disconnected.
