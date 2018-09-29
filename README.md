## Prerequisite

> Install Ansible: ```sudo apt-get install ansible```

> Godaddy domain and API key

# Set up email server with user accounts

> Step 1. Create a VPS in Digital ocean with ssh key, assign a Godaddy's domain as the VPS's name

> Step 2. Update server IP address and assigned domain in hosts file

> Step 3. Run Ansible Playbook

```shell
ansible-playbook main.yml
```

> Default account: username@<domain>

> Default password: 123password123