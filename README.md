# Create 2 Ubuntu Server VMs behind an external Load Balancer with inbound NAT rules for SSH

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/mikepfeiffer/ubuntu-arm-template/raw/master/azuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://github.com/mikepfeiffer/ubuntu-arm-template/raw/master/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to create 2 Virtual Machines in an Availability Set with configure NAT rules for SSH through an external load balancer. This template also deploys a Storage Account, Virtual Network, Public IP address and Network Interfaces. Resource loops are used to create the network interfaces and virtual machines.

