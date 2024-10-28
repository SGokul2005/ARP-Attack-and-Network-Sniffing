# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
## Gokul S

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
![image](https://github.com/user-attachments/assets/d33a918f-ff28-4a9c-8113-95f7e4f0e2d2)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-10-07 155224](https://github.com/user-attachments/assets/5378a9bd-b66c-4457-9632-1f2b8e7f35b7)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2024-10-07 155307](https://github.com/user-attachments/assets/cbfcefb4-c2c6-411c-8b7b-5fbadca45d16)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2024-10-07 155320](https://github.com/user-attachments/assets/f467417b-d701-48ca-a8b8-64958c0c42a3)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
