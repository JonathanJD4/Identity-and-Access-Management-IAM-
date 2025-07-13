# Setup/Configurations

#### Steps to Enable Microsoft Entra Internet Access
1.	Enable the Microsoft Traffic Forwarding Profile:
o	Microsoft Entra Internet Access captures traffic going to Microsoft services like Exchange Online and SharePoint Online.
2.	Install the Global Secure Access Client on End-User Devices:
o	Download and install the client app to manage and control access from user devices.
3.	Enable Tenant Restrictions:
o	Configure which tenants or organizations are allowed or blocked for access.
4.	Enable Enhanced Global Secure Access Signaling and Conditional Access:
o	Use Conditional Access and Global Secure Access to prevent potential attacks.

#### Steps for Configuring Microsoft Entra Private Access
1.	Configure a Microsoft Entra Private Network Connector and Connector Group:
o	Establish a connection between your on-premises server and Global Secure Access.
2.	Configure Quick Access to Your Private Resources:
o	Define specific fully qualified domain names (FQDNs) or IP addresses of private resources for inclusion in Microsoft Entra Private Access.
3.	Enable the Private Access Traffic Forwarding Profile:
o	Activate Private Access and link it from the on-premises router to remote networks.
4.	Install and Configure the Global Secure Access Client on End-User Devices:
o	Deploy the client software on devices to manage traffic flow access.

### Conditional Access Checks Overview
1.	Compliant Network Check:
Ensures users are connecting from a verified, compliant network based on the organization's security policies.
2.	Private Access Apps:
Applies Conditional Access policies to Microsoft Entra Private Access apps, enforcing security policies for internal, private resources.
3.	Source IP Restoration:
Restores the original user Source IP in Global Secure Access to maintain backward compatibility when using a cloud-based network proxy.
Global Secure Access snapshot – provides summary of users, devices, & workloads secured through the service.
