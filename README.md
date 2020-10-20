## Prerequisites

If you didn't install VirtualBox yet and don't have the analogue like VMWare, Hyper-V, etc.
Download and install

https://www.virtualbox.org/wiki/Downloads

## For Windows 7 only

Open the  PowerShell terminal and type

`Get-Host | Select-Object Version`

If the version of PowerShell you see is lower than 3.0 you may install it from here http://www.microsoft.com/en-us/download/details.aspx?id=34595

**or** use this information:

https://stackoverflow.com/questions/19902239/how-to-upgrade-powershell-version-from-2-0-to-3-0

# Start from here

https://www.vagrantup.com/downloads.html

Select your platform button, make sure architecture selected is 64-bits, press **Download** button.
Install the package, say **No** for the reboot prompt after install (Windows)

# Run the command in a Shell session  (Mac/Linux Terminal, Windows PowerShell)

`mkdir some_temp_directory` For example: `mkdir vagrant_temp_machine_config`

`cd some_temp_directory`

`vagrant init generic/alpine312`

`vagrant up`

`vagrant ssh`

You're inside your Linux box. Enjoy!

# Finish the work

**Ctrl + D**

`vagrant halt`

## Caution! It deletes this new virtual machine, all its files (HDD image, settings, logs, etc). No other VMs, neither the VirtualBox itself is not deleted.

`vagrant destroy`

Now you can delete your `some_temp_directory` with the configuration
