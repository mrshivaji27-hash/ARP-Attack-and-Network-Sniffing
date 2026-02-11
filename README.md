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

<img width="1114" height="889" alt="image" src="https://github.com/user-attachments/assets/54de562b-ef36-49cd-9dea-12765ba04dbd" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="938" height="865" alt="image" src="https://github.com/user-attachments/assets/ebb739cb-8b21-4382-932d-9b66c5d2a220" />

## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="650" height="553" alt="image" src="https://github.com/user-attachments/assets/b64cf2a1-5893-49c5-b5f6-55f8f1e19cea" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="315" height="102" alt="image" src="https://github.com/user-attachments/assets/a88adf10-fcc0-42ca-a7c0-46fa68a5bbc6" />

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1694" height="919" alt="image" src="https://github.com/user-attachments/assets/089c6c48-9d47-4643-be17-fc1d2fa3135d" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
