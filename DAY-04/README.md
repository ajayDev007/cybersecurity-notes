## Networking commands & tools
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
* __Wireshark:__![wireshark](https://github.com/user-attachments/assets/37f24ca4-c6a0-4c89-a66a-a78ec85cdc2a)

  * Wireshark is a widely used network protocol analyzer, often referred to as a packet sniffer. It allows you to capture and interactively browse the traffic running on a computer network in real-time. Wireshark is an essential tool for network administrators, security professionals, and anyone interested in learning more about how networks operate.
 > Wireshark is a powerful tool, but it's important to use it responsibly, particularly in environments where monitoring traffic could breach privacy or legal agreements.
  * 
 
