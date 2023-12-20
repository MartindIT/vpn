![image](https://github.com/MartindIT/vpn/assets/151476834/4da09b42-298f-4f5f-b4b7-69a565b195a5)

<h1>Changing Locations with a VPN</h1>
This tutorial outlines the differnet uses of a VPN within Azure Virtual Machines




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/MartindIT/vpn/assets/151476834/80ebffc9-a680-4325-979c-e78132334807)

**1.) Firstly we will take note what are IP address is now and compare down the road what our IP Address changes to later**

![image](https://github.com/MartindIT/vpn/assets/151476834/ec90cf7c-c448-49c2-9646-37c738741036)

**2.) Then we will go to azure and make a Virtual Machine in windows 10 with a differnet region than our default** 

![image](https://github.com/MartindIT/vpn/assets/151476834/b5c7d7d2-68c3-424a-8bc2-92d225e746cb)

**3.) Once the VM is done creating just Remote Desktop into it by copying and pasting the Public IP Address and connecting**

![image](https://github.com/MartindIT/vpn/assets/151476834/6596fc83-b0ce-49cc-a33e-ce8087a0d086)

**4.) When you log into the VM go to "whatsmyIPaddress.com" and check IP Address and now it says we are in Hong Kong.**

![image](https://github.com/MartindIT/vpn/assets/151476834/0f736c0b-8479-4797-93fc-6a71c0f6f202)
![image](https://github.com/MartindIT/vpn/assets/151476834/fb744e18-70ef-4272-b287-7c3dc787d269)
![image](https://github.com/MartindIT/vpn/assets/151476834/aef1c9d0-70e5-4633-8043-a1518b135530)

**5.) Then make a Proton VPN account which is free and download the VPN client inside your Virtual Machine and log into VPN Account.**

![image](https://github.com/MartindIT/vpn/assets/151476834/dd49d397-7f57-4db8-998e-0b588fc3fcdd)

![image](https://github.com/MartindIT/vpn/assets/151476834/d875e931-4f05-451a-aa90-9472ce18de6a)

**6.) Now click on quick connect and we will be assigned Japan and we will have currently switched our IP Address to Japan servers.**

![image](https://github.com/MartindIT/vpn/assets/151476834/74815212-1f49-4ce9-a996-029758b5f0e2)

**7.) So if we go back to "whatsmyIpaddress.com" our IP will be different and haved changed locations to Japan and we will now have changed our locations twice.**

![image](https://github.com/MartindIT/vpn/assets/151476834/99cf107e-746d-485a-93fd-9248c3ad33c7)
**8.) Finally we can have a little fun around japan servers and go and look at different websites such as Netflix and see how the UI looks and from the looks of things how a VPN can alter computers local IP Address and give users the ability to switch servers/ IP Addresses.**

