                                       
################################################################################################
####                            PROPERTY OF LA CUEVA HS                                     
####
####                                       & ROWAN HART                                     
####
####                            ---------DO NOT DISTRIBUTE--------                          
####
####                           [Except me because I made the thing]                         
####
################################################################################################

Licensed under GNU Public License Version 3.0
This script package was put together by Rowan Hart for the purpose of 
competition.

How to use this script
1. Run the CyberSetup.sh script from the same directory the MACHARIEL 
and SAPHARIEL scripts are in. This will set them up and run the 
machariel script.
2. The machariel script is user-friendly interactive. Each process will 
prompt for options that will allow the user to easily pick with number 
keys.
3. Before running the machariel script, make sure to set automatic 
updates with the GUI to avoid interoperability problems.

Version History
1.0 - Base import and cleanup of old scripts, consolidation from python 
to BASH, addition of system scanning processes for common items.
1.1 - Addition of in-place runs of Crontab, added multi-system 
sources.list updates, added some changes to password policy that make it 
consistent with useability standards.

Known Bugs
1. Not a script bug, but a PAM bug: if you do not set passwords in the 
password block that comply with the password policy, it is very possible 
to lock yourself out.
   For safety, maybe set one admin password beforehand so you can get in 
and fix it.
   

