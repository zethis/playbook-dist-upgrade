# playbook-dist-upgrade
Upgrade all your server and wait for reboot if needed

1. Clone the repo
2. Install ansible
3. Modify file in inventory/prod with your own server(s)
4. Launch with this command: ansible-playbook -i inventories/prod playbooks/upgrade.yml
