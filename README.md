# terraform
for terraform codes

#Installing terraform on ubuntu
#just download and extract terraform executable and add location to env variables.
sudo curl -O https://releases.hashicorp.com/terraform/0.11.5/terraform_0.11.5_linux_amd64.zip
sudo apt-get install unzip
sudo mkdir /bin/terraform 
sudo unzip terraform_0.11.5_linux_amd64.zip -d /usr/local/bin/

#Providers
A provider is responsible for understanding API interactions and exposing resources(ex: AWS, GCP, Consul etc) usually IaaS/ SaaS. 

