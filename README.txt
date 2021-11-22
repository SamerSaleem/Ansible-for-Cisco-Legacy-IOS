This is an ansible playbook that will get some facts like:
1. Software version
2. Serial number
3. CDP neigbors of each interface
4. Ansible keys that can be used on the device
5. This is for the legacy Cisco IOS switches like Cisco CAT2960S
6. You need to have your hosts file ready with IP addresses of the inventory
7. You need to make sure ansible.cfg configured to accept the SSH key
8. in my case the password and user name already configured inside the hosts file so I dont have to enter the username and password.


