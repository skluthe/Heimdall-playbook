# Heimdall-playbook
An ansible playbook that will deploy Heimdall and configure it as well as Nginx


# Install Instructions
Update to the latest software avaliable
```sudo apt update -y && sudo apt upgrade -y```

Install Ansible
```sudo apt install ansible```

Clone the github repo
```git clone https://github.com/skluthe/Heimdall-playbook```

Move to the Heimdall-playbook directory
```cd Heimdall-playbook```

Run the installer
```sudo sh install.sh```

When it's finished visit the IP of your server in a browser and you should have a working Heimdall installation.