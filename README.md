The command to run the setup: 

```
ansible-playbook --become --user root -i inventory/hosts -l testnet_2_servers  install.yml  --extra-vars "top_dir=$(pwd)"
```