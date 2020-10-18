# Prerequisites

https://www.virtualbox.org/wiki/Downloads


# Start from here

https://www.vagrantup.com/downloads.html

Select your platform button, make sure arch is 64bits
Install the package, say No for the reboot prompt after install (Windows)

# Run the command in a Shell session  (Mac/Linux Terminal, Windows PowerShell)

`mkdir **path/to/your_new_vm_config** `

`cd **path/to/your_new_vm_config** `

`vagrant init generic/alpine312`

`vagrant up`

`vagrant ssh`

# Finish the work

**Ctrl + D**

`vagrant halt`

# Caution! It deletes the VM

`vagrant destroy`
