## AZ84

https://us06web.zoom.us/j/81103813397#success
87941171596
anilkumar.mallavarapu429@gmail.com
Azure public IP Creation with CLI
az login
az network public-ip create --resource-group project-1 --name workstation --version IPv4 --sku Basic --allocation-method Dynamic

sudo dnf list all | grep ansible
sudo dnf install python3.12 python3.12-pip -y
sudo pip3.12 install ansible

Azure VM delete from CLI
az vm delete --name <VM_NAME> --resource-group <RESOURCE_GROUP> --yes
az vm delete --name frontend-dev --resource-group project-1 --yes

#vault Installation
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
sudo yum -y install vault
sudo pip3.12 install hvac

https://helm.sh/docs/intro/install/
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | sudo bash

https://external-secrets.io/latest/introduction/getting-started/ - getting secrets to kubernetes from vault.
