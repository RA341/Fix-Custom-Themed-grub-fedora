# About

This script enables custom themes for fedora grub and allows fedora to show up in a custom themed grub.

# Prerequisites
* Fedora installation (tested on fedora 36)

# Run Script

* Download ```grub-script```

* run ```sudo ./grub-script``` in terminal

# What this Script is doing
It basically replaces two lines in your grub file in ```/etc/default/grub```

* To enable custom themes

  ```GRUB_TERMINAL_OUTPUT="console"``` to ```#GRUB_TERMINAL_OUTPUT="console"```

* Allows fedora entry to be seen in custom themed grub

  ```GRUB_ENABLE_BLSCFG="true"``` to ```GRUB_ENABLE_BLSCFG="false"```

You can manually choose to do this on your own, if you are not comfortable with scripts

And then generates a new grub config file

# To-do

check if a grub file already has the changes and skip accordingly 

# Disclaimer/Warning
This script was made by a linux noob, and was made for personal use,This has the potential to mess up your system from booting so use it at your own risk
