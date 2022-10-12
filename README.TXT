sudo apt install ansible
sudo vim  /etc/ansible/hosts
ansible-inventory --list -y
make password less login


ansible-playbook kill-app.yml
ansible-playbook change-id.yml
ansible-playbook start-app.yml

