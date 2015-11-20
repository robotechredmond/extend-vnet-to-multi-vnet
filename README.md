# Extend an existing Azure VNET to a Multi-VNET Configuration

This template allows you to extend an existing single VNET environment to a Multi-VNET environment that extends across two datacenter regions using VNET-to-VNET gateways

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frobotechredmond%2Fextend-vnet-to-multi-vnet%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template extends an existing single VNET environment to a Multi-VNET environment by deploying these Azure resources:

+ Second VNET in a different Azure datacenter region
+ VNET gateways on existing and second VNET
+ VNET gateway connections to establish a routable VNET-to-VNET connection between existing and second VNET 

Modify parameters file to change default values.