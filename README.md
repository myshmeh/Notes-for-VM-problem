# Notes-for-VM-problem
This is a note in for the case VM not working properly

##Problems
VM is not running guest OS (showing dead black screen forever).

##Solutions
###BIOS settings problem
"Intel Virtualization Technology" (VT) might be "disabled" in the BIOS settings of your computer.
1. Enter into your BIOS settings
1. Go to Advanced settings
1. Find something like "Intel Virtualization Technology" for Intel processors
1. Set it to "Enabled"
1. Save and exit BIOS
