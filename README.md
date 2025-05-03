## AZ84

First editing in file for testing


https://us06web.zoom.us/j/81103813397#success
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