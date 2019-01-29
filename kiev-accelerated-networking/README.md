# VM-Series Beta w/Accelerated Networking Template

This ARM template deploys the beta version of the VM-Series next generation firewall VM into an existing Azure resource group with accelerated networking (SR-IOV). The following resources have to be predefined in the Resource Group:

- A Virtual Network with 4 subnets (Management, Untrust, Trust, and DMZ)
- A Network Security Group

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsuspenceiskillinu%2Fazure%2Fmaster%2Fkiev-accelerated-networking-full%2FAzureDeploy.json)

# Note
This is an unofficial Azure template to deploy VM-Series Next-Generation firewalls from Palo Alto Networks.
