## Networking commands & tool
### DAY-04(9/8/24)
#### Linux provides a range of powerful networking commands that are essential for configuring, monitoring, and troubleshooting network connections. Here's an overview of some commonly used Linux networking commands:

#### __Basic Networking commands__
* **`ping`**: Test the network connection between the host and a destination computer. 
  * Example: ping google.com 
* **`ifconfig`** (or ip a): Display or configure a network interface. 
* **`netstat`**: Display network connections, routing tables, interface statistics, etc. 
  * Example: netstat -tuln (Displays listening ports) 
* **`traceroute`**: Display the route and transit delays of packets across a network. 
  * Example: traceroute google.com 
* **`nslookup`**: Query the DNS to obtain domain name or IP address mapping. 
  * Example: nslookup example.com 
* **`dig`**: DNS lookup utility. 
  * Example: dig example.com 
* **`route`**: Show or manipulate the IP routing table. 
  * Example: route -n 
* **`ss`**: Utility to investigate sockets. 
  * Example: ss -tuln 
* **`iwconfig`**: Configure a wireless network interface.

#### __Networking tools__
* __Wireshark:__

  * Wireshark is a widely used network protocol analyzer, often referred to as a packet sniffer. It allows you to capture and interactively browse the traffic running on a computer network in real-time. Wireshark is an essential tool for network administrators, security professionals, and anyone interested in learning more about how networks operate.
  * Visit [Wireshark's documentation](https://www.wireshark.org/docs/) to learn more about the tool.
  * A tipical Wireshark Interface ![Wireshark-Interface](https://github.com/user-attachments/assets/88184080-33e7-42f3-a995-7754dd99da28)

 > Wireshark is a powerful tool, but it's important to use it responsibly, particularly in environments where monitoring traffic could breach privacy or legal agreements.
* __Common use cases of Wireshark:__
* Network Troubleshooting: Identifying and resolving network performance issues or connectivity problems.
* Security Analysis: Detecting and investigating security threats, such as unauthorized access or malware activity.
* Protocol Analysis: Understanding the behavior of network protocols and developing new applications or services.
* Education and Training: Learning about network concepts and how different protocols work.

#### Other networking tools include __*Nmap*__, __*Aircrack-ng*__, __*John the ripper*__, __*Hydra*__, __*Metasploit Framework*__, __*Burp suite*__ etc, which we will be learning in the upcoming sessions.
------------------------------------------------------------------------------------------------------------------------------------------

#### __Virtual Private Network (VPN)__
A Virtual Private Network (VPN) is a technology that creates a secure, encrypted connection over a less secure network, such as the internet. It allows users to send and receive data as if their devices were directly connected to a private network, providing several key benefits.
> VPNs are powerful tools for enhancing privacy, security, and freedom online, but it’s important to choose a reputable provider and understand the implications of using one.
> 

 
 
