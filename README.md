# debianims
Scripts to run after Debian 9+ installation.

swapoff -a

and still thrashing

https://unix.stackexchange.com/questions/499485/how-do-i-use-swap-space-for-emergencies-only

# Make sudo work

echo "%sudo ALL=(ALL) ALL" > /etc/sudoers.d/10-installer
