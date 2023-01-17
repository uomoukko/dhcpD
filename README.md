# dhcpD
## dhcp server only for tr-069 protocol

DhcpD will assign only 2 IPs<BR>
You can select them from the macaddr list<BR>
PC/ACS ip will be always 58.162.0.1 and cannot be changed for now.<BR>
MODEM/DGA ip will be always 58.162.0.12 and cannot be changed for now.<BR>
<BR>
when PC ip has been set to 58.162.0.1, shows PC=1<BR>
when DGA ip has been set to 58.162.0.12, shows DGA=1<BR>
When both PC and DGA =1 then they can communicate<BR>
<BR>  
files _option43.txt and _macaddr.txt must be in the same folder<BR>
change first line of _option43.txt to your domain<BR>
add your macaddresses to _macaddr.txt<BR>
