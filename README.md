# Prerequisites

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

`mkdir **path/to/your_new_vm_config** `

`cd **path/to/your_new_vm_config** `

`vagrant init generic/alpine312`

`vagrant up`

`vagrant ssh`

You're inside your Linux box. Enjoy!

# Finish the work

**Ctrl + D**

`vagrant halt`

## Caution! It deletes the VM

`vagrant destroy`
