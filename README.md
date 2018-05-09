# deepsecurity-facter-ansible
Get Deep Security Agent info by facts with Ansible

Deep Security Agent Facter scripts
====

Runs the facter discovery program (https://github.com/puppetlabs/facter) on the remote system, returning JSON data containing Deep Security Agent information.

## Installation
It is best to use the custom facts in combination with the Deep Security Ansible module which can be found at https://github.com/deep-security/ansible.<br/>
<br/>
$ mkdir -p ansible/files<br/>
$ git clone https://github.com/mawinkler/deepsecurity-facter-ansible.git<br/>
$ cp deepsecurity-facter-ansible/files/*.fact ansible/files<br/>
   
## Usage
Creates two different types of external facts:<br/>
dsa_status - agent component info as JAML<br/>
