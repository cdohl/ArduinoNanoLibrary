# Create junction for Windows.

mklink /j src     C:\arduino\hardware\arduino\cores\arduino
mklink /j include C:\arduino\hardware\arduino\variants\standard
mklink /j lib     C:\arduino\libraries


# Create link for Linux.

ln -s /usr/share/arduino/hardware/arduino/cores/arduino     src
ln -s /usr/share/arduino/hardware/arduino/variants/standard include
ln -s /usr/share/arduino/libraries                          lib


# Change Eclipse compiler option with reference of following.

http://playground.arduino.cc/Code/Eclipse