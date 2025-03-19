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
<img src="https://github.com/user-attachments/assets/cd3c9d46-92d0-4fcf-a4eb-148562193f3a" width=600>

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img src="https://github.com/user-attachments/assets/14423345-cb52-4c85-86c3-e8e8c31877cb" width=600>

dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img src="https://github.com/user-attachments/assets/2dd88d7e-84dd-4251-9421-3aa2c4f20758" width=600>

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img src="https://github.com/user-attachments/assets/25bfc872-2de3-4ba6-8931-f456a333e6f6" width=600>

Invoke the wireshark and examine the various menus  and controls of the tool:
<img src="https://github.com/user-attachments/assets/35e8d51d-076e-4ac1-aa52-918801e40ff4" width=600>

## ettercap :
ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.

<img src="https://github.com/user-attachments/assets/3ab8439e-49fd-47fc-b666-9e4016a40d7f" width=600>



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
