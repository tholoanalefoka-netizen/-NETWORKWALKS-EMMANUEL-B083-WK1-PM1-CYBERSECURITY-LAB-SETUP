The week 1 content is about lab setup. Because I already had virtualbox, it made my work easier as the only requirement was now installing Kali Linux. I was already using red hat and learned that they are two Linux distributions with different focus tasks.

The main objectives of this project are to:

Install and configure VirtualBox.
Install/import Kali Linux as a virtual machine.
Create a private NAT Network for the cybersecurity lab.
Configure network connectivity for Kali Linux.
Assign a consistent IP address to the Kali VM.
Verify network connectivity and DNS resolution.
Take a clean VM snapshot for recovery.
troubleshoot the internet connection.
Prepare the environment for future cybersecurity projects.

From Nat Network configurations, kali exportation and setup, vm snapshots to writing documentation. The step by step guide made my work very easy and understandable.

step 1: Install Virtualbox as a Configuration: Network Name: NatNetwork IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled IPv6: Disabledhypervisor. 

step 2: Create the Nat Network using the configuration: Network Name: NatNetwork IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled IPv6: Disabled.  

step 3: I downloaded the Kali Linux virtual machine from the official Kali Linux website and imported into VirtualBox.  

step 4: I checked the Kali Linux network configuration and configured with a consistent IPv4 address.  

step 5: after the setup, I created a snapshot and named it my clean kali linux.      

step 6: I verified the connection and Ip addresses using commands including; Ip addr, Ip route and ping 8.8.8.8.                   

The network settings were a challenge because they were different from the already existing settings, but I managed to find a work-around it and added another NatNetwork and wrote the required network settings

The challenge i faced was turning off the machine to come back to a diconnected internet. After a tiny research, i learned that the network was static and therefore needed to be refreshed. 
The lab verification included pings to google.com and the gateway and both were successful. Although I did not see the difference that the snapshot made, I learned that it "provides a known-good recovery point for future cybersecurity exercises" that i am yet to discover.

Author: Tholoana Jeanet Lefoka
Program Name: Cybersecurity at Networkwalks | Week: 01 | Project: Cybersecurity & Pentesting Lab Setup 
