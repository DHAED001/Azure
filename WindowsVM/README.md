# Windows VM with Availability Set
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/DHAED001/Azure/master/WindowsVM/azuredeploy.json?token=Ao3VJeSAyG0f5wBnPukBQcr3fxuGYh4oks5ccFirwA%3D%3D" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/DHAED001/Azure/master/WindowsVM/azuredeploy.json?token=Ao3VJRi3_z2HrWy8WhXiPnFSjlCjF0YVks5ccFjWwA%3D%3D" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>


This template creates a new VM with two NICs which connect to two different subnets within the same VNet.

## Tips
1. If running under PowerShell you may update the **azuredeploy.parameters** file with the **allowedValues** for the subnet name of the Primary NIC and Secondary NIC for a nice dropdown list.
2. Customize parameters in **azuredeploy.parameters** as you see appropriate, at the very least the **adminPassword**.

Feel free to post qeustions and enjoy!
