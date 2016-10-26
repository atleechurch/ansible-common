This is a modified version of the common role found at: https://github.com/arbabnazar/ansible-roles
It has been modified to add some tasks specific to Atlee Church.

Many thanks to the original author.

Common Ansible Role for Ubuntu Server:
---
 With this role you can prepare your machine to do the following tasks:
  
 - Install the minimum essential packages
     - build-essential
     - python-software-properties
     - git
 - Setting Hostname 
 - Add the additional sudo user and it's ssh key with passwordless sudo option
 - Enable the Multiverse repository
 - OpenNTPD Installation
 - Timezone Configuration
 - VIM-nox Installation
 - SSMTP Installation and Configuration with GMail for Sending System Alerts
 - Automatic Security Updates Installation
 - Disable the Default UFW
 - Fail2Ban Installation and Configuration

