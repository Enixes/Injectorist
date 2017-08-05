# Injectorist :: Is Your Wireless Card capable of Packet Injection? 
Injectorist is a simple bash script to check Packet Injection capabilities in all connected wireless cards
# Dependencies
1) aircrack-ng::: Install it by executing following command as root in terminal
>apt install aircrack-ng
2) awk ::: Install it by running following comand as root in terminal
> apt install gawk

Note : gawk is already installed on most linux distributions

Supported distros--> All Debian based, Ubuntu, Fedora, Kali, Arch, OpenSUSE.
# Installation

1) Download the master zip and extract all files to any location.

2) Open terminal and navigate to extracted folder
> cd /location/of/extraction

3) Gain root access
> su 
Enter root password:____

4) Make the script InjectionCheck executable by-
> chmod +x InjectionCheck

5) Run the script
> ./InjectionCheck

6) Now, Injectorist will scan all wireless cards connected for packet injection.

# Future Perspective
Adding features such as 

~ Checking Monitor Mode support

~ Enabling Monitor Mode

~ Many more...

