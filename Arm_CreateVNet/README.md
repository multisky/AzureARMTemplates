## 가상 네트워크를 만드는 ARM 템플릿
- 매개변수는 VNet 이름
- 내부적으로 Subnet 2개 생성
  - Virtual Network CIDR : 10.0.0.0/16
  - 서브넷 1 : Frontend-Subnet(10.0.1.0/24)
  - 서브넷 2 : Middle-Subnet(10.0.2.0/24)

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ftaeyo%2FAzureARMTemplates%2Fmaster%2FArm_CreateVNet%2FTemplates%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Ftaeyo%2FAzureARMTemplates%2Fmaster%2FArm_CreateVNet%2FTemplates%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>