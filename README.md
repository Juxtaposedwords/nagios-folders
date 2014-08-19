nagios-folders
==============
This project exists more as a guide to any who wish to set up Nagios in a sane manner. I have arranged and formatted the folders to be consistent with others in Ubuntu. 

Notes on example config files:
  1. I have used the domain bash.org for my top level domain.
  2. Any IPs herein provided are nothing short of random ips, and should be replaced if you want to use them. 
  3. This is not a guide to install Nagios (thought i'd like to do one in the futureA
    3a. This is a guide to the folder configuration
  4. These are the files I have organized, but not the entire Nagios etc folder

An important part of this folder's configuration is that the nagios.cfg file. This file tells nagios what order to load objects in sequential order.
  TLDR; - config files are loaded in the order they are declared.

Services which point to nowhere:
  Some services you won't have or need. As a non-barbarian I use SNMP with Nagios. I have included my calls to NetSNMP, as I believe that Nagios is only as good as how you check.. 
