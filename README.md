# AWS-WEB-APPLICATION
 ## Github Setup
 Having set up my github repositry with the name #AWS-WEB-APPLICATION
I created a readme file a readme file for proper documentation of the project process
### Setting Up Security Group
. I Created a new Security Group, below is an image attached
[!SecGrp](/CrtSecGrp.png)

.  I set an Inbound rule for HTTP and SSH to control incoming traffic to the instaces
[!Inbound](/inbound.png)

. I set Outbound rule to control all outcoming traffic from a resource
[!Outbound](/outbound.png)

### Launching an EC2 Instance
. I launched and named an instance on the North Virgina(N.V), using an already made vpc and subnet by Lita.
. I Selected Amazon Linux 2 as the OS and a t2.micro instance type. below is an image
[!Linux](/AmiSetup.png)

.I went ahead to create a keypair to control login access to EC2 instances

[!Keypair](/KeyPair.png)

### Network Setting
. I selected the LITA VPC created  and also the Public Subnet LITA created
. I ensured the “Auto-assign Public IP” is set to “Enabled”
. I selected the security group i created earlier
### Storage Setting
. I used the default storage 8gb

Below is summary of my running Instance
[!Instance](/LaunchInstance.png)

### Installation Apache Web Server
. I connected the SSH into the instance
[!ConnectInst](/ConnectInstance.png)
. I went ahead to input the commands for installtion
[!InstallApache](/InstallApache.png)
. I proceeded to enabling the already installed Apache Web Server 
[!EnableApache](/EnableApache.png)
. After Enabling the Apache Web server, i copied the ip address to my browser to enusre the Apache is running and low and behold its working fine. Below is the evidence 
[!TestPage](/TestPage.png)

