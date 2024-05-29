SSHD CONFIGURATIONS
=========

This role configure and hardening sshd service.
Parameters to modify:
MACs
Ciphers
LogLevel 
PermitRootLogin 
MaxAuthTries 
HostbasedAuthentication 
IgnoreRhosts 
PermitEmptyPasswords 
PasswordAuthentication 
AllowTcpForwarding 
GatewayPorts 
X11Forwarding 
ClientAliveInterval 
ClientAliveCountMax 
UseDNS 
Banner 
	AllowTcpForwarding 


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      gather_facts: yes
      gather_subset: min
      roles:
         - role: roles/sshd-configurations

License
-------

BSD

Author Information
------------------

Developed by Rolando Antonio https://www.linkedin.com/in/rolando-ant-j/
