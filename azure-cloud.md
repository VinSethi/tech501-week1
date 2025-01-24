# Azure Cloud steps:

1. Create 2 keys
2. Create Vnet
3. Create Virtual Machine 
4. Login- to login need to connect the virtual machine by using the private key and inputting the name of the file it into the Native SSH after clicking on connect. Then copy the clipboard thing into git bash and then it should allow to input commands. Adding  ~/.ssh/  will allow specific path and allow to login into virtual machine from any directory.

* ssh -i ~/.ssh/tech501-vineet-az-key  adminuser@20.26.236.242 will allow you to login on git bash for the virtual machine


## Git bash section:
* "**cd .ssh**" to go into section with two keys (public and private) from the local
* "**ls**" to bring up the two keys from the local
* "**cat tech501-vineet-az-key.pub**" to bring the public key up and copy it to input it into Azure
* "." represents the current directory
* "cd /" takes you to the root directory



## To create Virtual machine select these options:
* Our virtual machine:
* Name: tech501-your_name-first-vm
* Region: UK South
* Security: standard
* Image (i.e. the OS that will go onto the machine): Ubuntu Pro 18.04 LTS Gen 2 [LTS means long term support for ~7 years]
* Size: Standard_B1s — 1 vcpu, 1 GiB [very important to set correctly because this impacts pricing]
* Administrator account: adminuser
* Use existing key pair stored in Azure (use the one with your name)
* Select inbound ports: allow HTTP and SSH traffic
* Disks tab:
* OS disk type: Standard SSD
* Networking tab:
* Virtual network: your named version
* Subnet: public-subnet
* Choose Delete public IP and NIC when VM is deleted option