# sd-mux

sd-mux stands for Secure Digital Multiplexer.

This is SD card switcher (multiplexer) designed to help automatic testing.

This project is sd-mux controller - binary for controlling sd-mux device.

Requirements:
  1. libftdi1 1.4 - development library
  2. popt - development library
  3. cmake - binary tool

Build:
 - enter into project directory
 - create 'build' directory
 - enter into "build" directory
 - run 'cmake ..'
 - run 'make'

Install:
 - enter into 'build' directory
 - run 'sudo make install' to install binary into '/usr/local/bin' (the default one) directory

Note:
If you want to install files into different directory then add argument to cmake command:
 cmake -DCMAKE_INSTALL_PREFIX=/usr ..
Then again run:
 make
 make install
