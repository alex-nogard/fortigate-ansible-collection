# Fortigate massive import

## How it works :
Prerequisite : create a 2 columns CSV, with a name column and IP column

1 / The script will read the CSV defined in the command line arg, and create all hosts
2 / The script will populate the created hosts in a group, defined in the command line arg

## Command :
Enter the command : ansible-playbook massive-import.yml -e loadcsv=import.csv -e addgrp=test099
