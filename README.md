Usage:
* copy hosts.yml.template to hosts.yml (or create a new one)
* ansible-playbook -i hosts.yml playbook.yml

Additional notes:
* As a security rpecaution, will enable ufw and only allow ssh port (TODO: make additional ports configurable)
* Installs kubectl and docker-machine-driver-kvm2 as part of the playbook
* Starts minikube, if ansible detects minikube is not currently running
