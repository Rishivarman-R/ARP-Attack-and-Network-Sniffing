# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks.

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot 2025-05-02 132924](https://github.com/user-attachments/assets/eabfe2e6-6e63-4362-8f4e-23ff23afd3b9)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2025-05-02 132939](https://github.com/user-attachments/assets/80c08278-d5a8-444b-9869-04023ad09dbb)

 dsniff:

![Screenshot 2025-05-02 134105](https://github.com/user-attachments/assets/e903a2ea-5446-4815-abe4-fe3f8af020be)





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![WhatsApp Image 2025-05-02 at 14 07 12_5c451943](https://github.com/user-attachments/assets/ecbec34d-ac5f-44fd-8263-e7353c02e28c)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![WhatsApp Image 2025-05-02 at 14 12 21_b73cf85c](https://github.com/user-attachments/assets/fc8167fb-64d8-4f96-b5d6-f25f315c36d5)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
