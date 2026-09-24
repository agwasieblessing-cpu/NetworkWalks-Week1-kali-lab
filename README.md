NetworkWalks Week 1 – Kali Linux Lab Setup

Project Overview
This project documents my Week 1 hands-on cybersecurity lab setup with Kali Linux using Oracle VirtualBox.

The main objective was to set up the Kali Linux virtual machine, configure its network connection, verify the assigned IP address, and test connectivity with the network gateway.

Tools Used
•	Kali Linux
•	Oracle VirtualBox
•	NAT Network
•	Linux Terminal

Lab Configuration
•	Network: NAT Network
•	Kali Linux IP Address: 10.0.0.2/24
•	Gateway: 10.0.0.1

Tasks Completed
1.	Set up Kali Linux as a virtual machine in VirtualBox.
2.	Configured the virtual machine's network adapter to use a NAT Network.
3.	Verified the network interface and IP address using the ip addr command.
4.	Tested connectivity by pinging the network gateway.
5.	Confirmed successful communication between the Kali Linux machine and the gateway.
6.	Documented the lab setup with screenshots and a demonstration video.

Connectivity Test
The command below was used to test connectivity to the gateway:
ping 10.0.0.1
The ping returned successful replies, confirming that the Kali Linux virtual machine could communicate with the configured gateway.

What I Learned
Through this exercise, I gained practical experience with:
•	Setting up a cybersecurity lab environment using VirtualBox.
•	Configuring a virtual machine's network adapter.
•	Identifying IP addresses and network interfaces in Kali Linux.
•	Understanding the role of a network gateway.
•	Using the ping command to test network connectivity.

Evidence
This repository contains screenshots and a demonstration video showing the completed lab setup and connectivity test.

Conclusion
The Week 1 lab was successfully completed. The Kali Linux virtual machine was configured on the NAT Network, the IP address was verified, and connectivity to the network gateway was successfully tested.

#Cybersecurity #KaliLinux #NetworkWalks #VirtualBox #Networking


