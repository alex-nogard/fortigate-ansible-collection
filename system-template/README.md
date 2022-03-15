# System Template

## Aim :
The objective is to create a system template, to have the exact same config on all firewall.

## How it works :
1 / Configure the system global parameters :
-> Console timeout
-> Language
-> Fortigate Alias

2 / Configure the Firewall DNS

3 / Configure the Firewall NTP Server

4 / Configure the Firewall SNMP

5 / Configure the SMTP part.

## Command :
Enter the command : ansible-playbook global-template.yml
