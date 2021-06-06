# Basil

Basil is an LFS based operating system. It will pretty much follow the LFS Program By The channel "Write your own Operating System" until a some very early things in BLFS. In the future I hope to add some automation scripts in Python, A customised XFCE environment and maybe even its own lightweight shell aimed for beginners.

Use at your own risk.

How to Format Your Drive.
  1. Use sudo fdisk -l to find the name of your USB drive eg.sdb.
  2. in lfs.sh, change the variable "LFS_DISK" to the name of your drive.
  3. Save file
  4. Run with bash lfs.sh. Note, do not run as root.

Current Features:
  * Automatic Disk partitioning script.
