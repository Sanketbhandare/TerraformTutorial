# Terraform Tutorial



### Basic Installation Steps on RHEL / CentOS System

	sudo yum install -y yum-utils 
	sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo 
	pkill yum                     # To kill any running processes of yum before installting terraform 
	sudo yum -y install terraform 

---------------------------------------------------------------------------------------------------------
