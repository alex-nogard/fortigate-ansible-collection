# Admin Access with LDAP

## How it works ?
1 / The script will create a new ldap server, dont forget to modify your parameters
2 / The script will create a new group, linkt to LDAP server. Please put the CN of your group name
3 / Create the admin, linkt to the group previously created.

## Command :
Enter the command :  ansible-playbook admin-access-with-ldap.yml
