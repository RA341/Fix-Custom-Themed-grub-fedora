# Prerequisites
* Fedora installation (tested on fedora 36)

# Run Script

* Download ```grub-script```

* run ```sudo ./grub-script``` in terminal

# What this Script is doing
It basically replaces two lines in your grub file in ```/etc/default/grub```

```GRUB_TERMINAL_OUTPUT="console"``` to ```#GRUB_TERMINAL_OUTPUT="console"```

```GRUB_ENABLE_BLSCFG="true"``` to ```GRUB_ENABLE_BLSCFG="false"```

You can manually choose to do this on your own, if you are not comfortable with scripts

And then generates a new grub config file


# Disclaimer/Warning
This script was made by a linux noob, this was made for personal use,This has the potential to mess up your system from booting so use it at your own risk
