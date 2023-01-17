# dhcpD
## dhcp server only for tr-069 protocol

DhcpD will assign only 2 IPs, one for PC and one for DGA/MODEM<BR>
This program uses macaddresses to detect who is PC and who is DGA<BR>
and it will assign the right IP to them<BR>
At the beginning you can select who is PC and who is DGA from the macaddr list<BR>
PC/ACS ip will be always assigned to 58.162.0.1 (and cannot be changed for now).<BR>
MODEM/DGA ip will be always assigned to 58.162.0.12 (and cannot be changed for now).<BR>
<BR>
when PC ip has been set to 58.162.0.1, program shows PC=1<BR>
when DGA ip has been set to 58.162.0.12, program shows DGA=1<BR>
When both PC and DGA =1 then they can communicate<BR>
<BR>  
dhcpD.exe _option43.txt _macaddr.txt MUST be in the same folder<BR>
_option43.txt: change first line to your domain<BR>
_macaddr.txt:  add all your macaddresses in your LAN<BR>
This way you will see the name of the other devices<BR>
requesting dhcp services in your LAN (they are ignored)<BR>
