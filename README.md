HOST_KEY_CHECKING=false ansible-playbook -i hosts main.yml --ask-sudo-pass --ask-pass -u ${username} -c paramiko
