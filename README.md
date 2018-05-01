# grub-prober-switch
Bash script to switch OS PROBER on or off

This script switches Grub to prober for other OS (like Windows) or not to

Disabled prober is protected on three levels
1 - immutable attribute on grub file
2 - Prober is turned on/off in grub file
3 - executable in /etc/grub.d is set on/off
