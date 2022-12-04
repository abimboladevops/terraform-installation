# terraform-installation
Terraform installation on ubuntu Before starting the installation, get the download link from the Terraform website. 
Navigate to https://www.terraform.io/downloads.html and move to the specific OS version
Log in to the Ubuntu system. Make sure Wget and Unzip are installed. If not, install the same:
sudo apt-get install wget unzip
Download the Terraform zip file by running the following command. 
Put the URL copied earlier in the command for download {wget https://releases.hashicorp.com/terraform/1.1.0/terraform_1.1.0_linux_amd64.zip}
Unzip the zip file in the current folder -the Terraform executable should get unzipped in the current folder
Move the Terraform executable file to /usr/bin folder --{sudo mv terraform /usr/local/bin/}
That should complete the Terraform installation. Verify the installation by verifying the version {terraform --version}
