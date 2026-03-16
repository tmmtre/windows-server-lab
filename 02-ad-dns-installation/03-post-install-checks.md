# Post Installation Checks - Windows Server

## Objective
After installing Active Directory Domain Services and DNS, some basic checks were performed to ensure the environment works correctly.

## Steps

1. Go to Tools and select DNS
2. Right click on the DNS Server DC01 and click on Properties
3. In the tab Forwarders click Edit and add a DNS to resolve external domains
4. Now in the terminal you can use the command nslookup to verify the DNS
5. And dcdiag to verify that Active Directory services are functioning correctly  
   
1. If it was not created automatically, you can manually create a Reverse Lookup Zone
2. In DNS Manager, right-click Reverse Lookup Zones
3. Follow the wizard and configure the PTR records as shown in the screenshots

## Configuration used in the lab
Forwarder configured: 8.8.8.8

## Screenshot

<img width="1022" height="850" alt="9" src="https://github.com/user-attachments/assets/55a1f393-d4cb-4a69-aa01-996840f3ab3a" />

<img width="1022" height="850" alt="10" src="https://github.com/user-attachments/assets/c6ee3a74-116c-4a15-adb9-78c4143386f8" />
