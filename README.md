# Terraform Tutorial



## Basic Installation Steps on RHEL / CentOS System

sudo yum install -y yum-utils \n
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo \n
pkill yum                     # To kill any running processes of yum before installting terraform \n
sudo yum -y install terraform

---------------------------------------------------------------------------------------------------------
