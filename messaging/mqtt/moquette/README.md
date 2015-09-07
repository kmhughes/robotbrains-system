The startup/ directory contains startup scripts for Linux systems.

# System-V Startup

moquette is the System-V init script and should be placed in your /etc/init.d
folder. This is what you would typically use on a Debian system.

To make the startup script work, you will need to run the command

```
sudo /usr/sbin/update-rc.d moquette defaults
```

# Upstart

moquette.conf is the Upstart init script and should be placed in your 
/etc/init folder.
