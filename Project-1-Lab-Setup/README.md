Project 1: Isolated Security Lab Setup

**The Goal**: To build a secure and isolated virtualization lab to perform 
any vulnerability assessments without impacting production networks or the public internet.

**Technical Implementation**

- Virtualization: Deployed Oracle VirtualBox as the virtualization layer. I chose this one for its ease of use and online support.

- Attacker Node: installed and configured Kali Linux as the dedicated security testing platform, which also came with additional tools such as Nmap, Wireshark, etc.

- Target Node: Obtained a Windows 11 Enterprise Evaluation instance to serve as the target of choice to simulate an enterprise environment.

- Network Architecture: Configured a Host-Only Virtual Network Adapter to ensure an 100% network isolated enviroment. This is to prevent leaks during security scans while allowing connectivity between lab assets.

**Results**

- Connectivity: Successfully established an ICMP(Internet Control Message Protocol) ping between both the Linux and Windows nodes.

- Security Status: verified that the environment is isolated from the host machine's Wi-Fi connection, making it good for future safe testing practices. 

**Skills Learned**

- Virtualization and resource allocation
- Network protocol analysis(ICMP, TCP/IP)
- System administration (Linux and Windows setup)
- Secure architecture design

![Network Ping Test](Proof_Of_Ping.png)
![Virtual machines of kali Linux and Windows 11](VirtualMachines.png)
