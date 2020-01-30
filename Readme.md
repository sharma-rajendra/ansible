ansible-playbook -i /etc/ansible/hosts /path/of/restart_container.yml --extra-vars "**hostgroup**=web-server **container_name**=nginx **seconds**=20"
