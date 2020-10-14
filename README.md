# wired-802.1x-spreadsheet

## Updated - 10/14/2020

Added additional Aruba-CX configurations. h/t to Aaron Smith at Aruba, as always!

## Updated - 04/14/2020

Added Aruba-CX configuration - h/t Aaron Smith at Aruba!

##

This spreadsheet will help deploy wired 802.1X on Cisco, Juniper, Extreme, an HPE platforms<br>

To get started, fill out the "Start Here" tab. On this tab, you can fill out the following information:<br>
  - ClearPass / Radius Server IP addresses<br>
  - RADIUS / TACACS+ Shared Secret <br>
  - RADIUS / TACACS+ Source VLAN <br>
  - RADIUS / TACACS+ Source IP address <br>
  - Interface ranges for Cisco and Juniper configurations<br>
  
  The data that you enter here will populate throughout the tabs of the spreadsheet. You can then select the platform and copy and paste the relevant data into the manufacturer switch of choice.

The "Advanced Cisco Switch Config" tab provides the following:<br>
  - The commands for a wired Guest Portal Redirection<br>
  - Advanced Device Sensor configuration for IOS 15+<br>
  
The "Cisco Switch Config" code has been tested on IOS 12.2.55-SE5 - IOS 15.1<br>

The "Juniper EX Config" code has been tested on JUNOS 12.x - JUNOS 15.x<br>

The "HPE Provision Config" has been tested on legacy Provision and ArubaOS-Switch 16.x images<br>

The "Aruba S-Series Config" was tested through Aruba S-Series code 7.4.x<br>

The "Extreme EXOS 15- Config" was tested on Extreme EXOS 15 and 14, hence the "-" minus sign<br>

The "Extreme EXOS 16+ Config" was tested on Extreme EXOS 16<br>

