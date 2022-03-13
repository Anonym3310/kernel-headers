# kernel-headers
With the help of this repository, the headers are packed into a deb package.
Just move the header files to the kernel headers folder and run the command:
sudo dpkg-deb --build kernel-headers kernel-headers.deb
