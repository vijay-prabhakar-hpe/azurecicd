# bootstapping

This ARM template creates a VNet with 3 Subnets

- Frontend Subnet
- App Subnet
- Database subnet.

It creates three Network Security groups one per each subnet. It creates DMZ rules for the App Subnet to expose endpoints to the Internet.
It secures the App Subnet and the DB subnet with appropriate rules.
It blocks Outbound Internet access to VMs in App and DBSubnets. It opens up DB Subnet only on the DB port to App Subnet.

- In Frontend Subnet
It deploys Jenkins Master


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvijay-prabhakar-hpe%2Fazurecicd%2Fmaster%2Fbootstrapping%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fvijay-prabhakar-hpe%2Fazurecicd%2Fmaster%2Fbootstrapping%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
