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
![1](https://github.com/sivaram-R/ARP-Attack-and-Network-Sniffing/assets/121165794/8e0f79aa-cc76-42cf-8950-8de98c8bb393)
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/sivaram-R/ARP-Attack-and-Network-Sniffing/assets/121165794/066c8990-8a0b-4b78-acc3-fe347a7b9003)
 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/sivaram-R/ARP-Attack-and-Network-Sniffing/assets/121165794/f0961dc5-6bb7-4ea8-b39a-08c43d66c1c6)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![4](https://github.com/sivaram-R/ARP-Attack-and-Network-Sniffing/assets/121165794/e8a96c2d-6bac-41c7-82fc-da9d4a18ab36)

Invoke the wireshark and examine the various menus  and controls of the tool:
![5](https://github.com/sivaram-R/ARP-Attack-and-Network-Sniffing/assets/121165794/af5bcf30-1216-4ed6-977f-343571a2adc9)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
