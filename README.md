# Ansible playbook for updating Raspberry Pi and Pi-Hole

## How to basic

1. Create `ansible.cfg` file to the directory, use `ANSIBLE_CONFIG` environment variable or other Ansible supported configuration file settings. https://docs.ansible.com/ansible/latest/reference_appendices/config.html

2. Add your Raspberry Pi('s) to inventory file  

3. Change the `hosts: pihole` for your own groupname if you are using some other naming scheme  

4. Run playbook `update.yml` 

## Todo or "would be nice" 

- If possible, output `pihole -up` to the person running the playbook  