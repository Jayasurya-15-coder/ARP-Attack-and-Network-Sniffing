# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

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
<img width="953" height="838" alt="image" src="https://github.com/user-attachments/assets/63c13c63-7403-4f40-9bd5-f973d1341ccd" />



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="910" height="435" alt="image" src="https://github.com/user-attachments/assets/8cc605a6-579a-49f6-8e3e-4c16a38c4a51" />


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="847" height="162" alt="image" src="https://github.com/user-attachments/assets/3aeed820-363d-4bbd-af26-9e287cd0553a" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="1662" height="985" alt="image" src="https://github.com/user-attachments/assets/b4e5dab6-898d-4f5c-b83f-7f691fac484c" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
