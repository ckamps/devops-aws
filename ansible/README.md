# Testing Ansible Playbooks with Test Kitchen

## Set Up KitchenCI on Amazon Linux to Test Playbooks

See `Gemfile`

## Set Up .kitchen.yml

...

## Execute Kithcen Tests

    $ kitchen verify

# Manually Running Ansible Playbooks

## Install Ansible

    $ sudo pip install ansible

## Manually Execute a Playbook

Execute the following command on a target node to apply the playbook:

    $ sudo /usr/local/bin/ansible-playbook -i "localhost," -c local realm-servers.yml
    
# Listing All Ansible Facts on Local Node

    $ ansible localhost -m setup
