```
pi@scout:~ $ grep '/dev/' klipper_config/printer.cfg  
# Obtain definition by "ls -l /dev/serial/by-id/"  
serial: /dev/ttyACM0
```


1. sudo service klipper stop
1. cd ~/klipper
1. git pull
1. make clean
1. make menuconfig
1. make
1. ./scripts/flash-sdcard.sh /dev/ttyACM0 btt-skr-mini-e3-v2
1. sudo service klipper start
