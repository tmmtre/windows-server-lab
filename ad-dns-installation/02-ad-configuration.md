# Configure AD Domain Services - Windows Server

## Objective
Configure AD Domain Services post-deployment.

## Steps

1. Go to the flag icon and click Promote this server to a domain controller
2. Select Add a new forest and give it a domain name
3. Click Next and set a password for the restore
4. Next until Prerequisites Check and Install

## Result
Root domain name: home.lab

The warning shown in the Active Directory Domain Services configuration wizard is normal in a home lab environment. 
It appears because there is no parent DNS zone called "lab" on the local network or on the public Internet.
In this setup, the Domain Controller manages the entire internal DNS infrastructure for the home.lab domain. Since the environment is isolated and self-contained, no external DNS delegation is required.
The configuration has been completed successfully and the Domain Controller is now responsible for both Active Directory and DNS services within the lab.

## Screenshot

<img width="1023" height="853" alt="4" src="https://github.com/user-attachments/assets/99c5f670-e876-4e3f-8052-bc5526a6ac9e" />

<img width="1022" height="850" alt="5" src="https://github.com/user-attachments/assets/f096c4bc-cc1d-413c-b5f2-e6621055a9b2" />

<img width="1019" height="850" alt="6" src="https://github.com/user-attachments/assets/b807f6ed-2866-49ce-b235-647d481509a0" />

<img width="1023" height="851" alt="7" src="https://github.com/user-attachments/assets/cdd27550-6201-401b-8d6b-7db8d93b4087" />
