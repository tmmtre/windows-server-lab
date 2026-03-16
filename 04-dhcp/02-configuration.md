# Configure DHCP Server - Windows Server

## Objective
Configure a DHCP Server and create a scope for the local network.

## Steps

1. Open Server Manager
2. Go to Tools → DHCP
3. Select the server and expand IPv4
4. Right-click IPv4 and select New Scope
5. Click Next, choose a Scope Name, then click Next
6. Configure the IP address range, then click Next
7. Add excluded IP addresses if needed (e.g. for printers or servers), then click Next
8. Configure the Lease Duration, then click Next
9. Configure the Default Gateway, then click Next
10. Click Next to skip optional configuration and Activate the scope
11. To test the configuration, set a Windows client to obtain IP and DNS automatically

## Configuration used in the lab
Scope name: S1  
IP Range: 192.168.10.20/24 - 192.168.10.60/24
Lease duration: 1 hour
Default Gatwway: 192.168.10.1

## Result
The DHCP server successfully assigns IP addresses to clients in the configured range. 

## Screenshot
