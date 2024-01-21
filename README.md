osg202@osg202-virtual-machine:~$ sudo apt install apcalc
[sudo] password for osg202: 
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  calc calc-common
The following NEW packages will be installed:
  apcalc calc calc-common
0 upgraded, 3 newly installed, 0 to remove and 55 not upgraded.
Need to get 799 kB of archives.
After this operation, 4.716 kB of additional disk space will be used.
Do you want to continue? [Y/n] y  
Get:1 http://vn.archive.ubuntu.com/ubuntu jammy/universe amd64 calc-common all 2.12.7.2-4 [471 kB]
Get:2 http://vn.archive.ubuntu.com/ubuntu jammy/universe amd64 calc amd64 2.12.7.2-4 [327 kB]
Get:3 http://vn.archive.ubuntu.com/ubuntu jammy/universe amd64 apcalc all 2.12.7.2-4 [928 B]
Fetched 799 kB in 2s (510 kB/s)
Selecting previously unselected package calc-common.
(Reading database ... 199411 files and directories currently installed
.)
Preparing to unpack .../calc-common_2.12.7.2-4_all.deb ...
Unpacking calc-common (2.12.7.2-4) ...
Selecting previously unselected package calc.
Preparing to unpack .../calc_2.12.7.2-4_amd64.deb ...
Unpacking calc (2.12.7.2-4) ...
Selecting previously unselected package apcalc.
Preparing to unpack .../apcalc_2.12.7.2-4_all.deb ...
Unpacking apcalc (2.12.7.2-4) ...
Setting up calc-common (2.12.7.2-4) ...
Setting up calc (2.12.7.2-4) ...
Setting up apcalc (2.12.7.2-4) ...
Processing triggers for gnome-menus (3.36.0-1ubuntu3) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for mailcap (3.70+nmu1ubuntu1) ...
Processing triggers for desktop-file-utils (0.26-1ubuntu3) ...

osg202@osg202-virtual-machine:~$ calc
C-style arbitrary precision calculator (version 2.12.7.2)
Calc is open software. For license details type:  help copyright
[Type "exit" to exit, or "help" for help.]

; 1*2*3
	6
; 5*2/4+5
	7.5
; 6/9-(1*2.5)
	~-1.83333333333333333333
; 

