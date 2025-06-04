Run the playbook:
	`ansible-playbook -i inventories/production/hosts playbooks/install_configure_harbor.yaml`
	`ansible-playbook -i inventories/production/hosts playbooks/install_configure_build_server.yaml`

• Variables in roles/deploy_script/vars/main.yml let you configure cron hour/minute, the script name, and paths.

