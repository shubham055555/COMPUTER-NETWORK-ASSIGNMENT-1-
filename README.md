Assignment 1 – LAN Topology Design using Cisco Packet Tracer

Author Details
Name: Shubham
Roll No: 2301730100
Program: B.Tech CSE (AI & ML)

Course Details
Course Code: ENCS304
Course Name: Computer Networks
Experiment Title: Assignment 1 – Basic Network Topologies
Software Used: Cisco Packet Tracer

------------------------------------------------------------

Objective

The aim of this experiment is to create and analyze different Local Area Network (LAN) topologies using Cisco Packet Tracer. 
The experiment focuses on understanding how network structure influences connectivity, efficiency, and fault tolerance.

------------------------------------------------------------

Network Designs Implemented

1️⃣ Star Topology (Switch-Based)
- One switch connected to four end devices (PCs)
- Each device configured with IPv4 address (192.168.10.1 – 192.168.10.4 /24)
- Connectivity verified using ICMP ping command
- Observed efficient packet forwarding behavior

2️⃣ Hub-Based Topology (Bus-like Layout)
- Switch replaced with a hub
- Same IP addressing maintained
- Observed broadcast transmission of packets
- Noted higher traffic and collision possibility

3️⃣ Ring-Style Topology (Loop Configuration)
- Three switches interconnected in loop form
- Multiple PCs attached to each switch
- Cross-switch communication tested successfully
- Observed path traversal in simulation mode

4️⃣ Fault Analysis Test
- One inter-switch link removed from ring configuration
- Network remained operational through alternate route
- Demonstrated improved fault tolerance compared to star

------------------------------------------------------------

Steps to Execute the Experiment

1. Open Cisco Packet Tracer.
2. Load the file: exp1_topologies.pkt
3. Select Realtime mode for normal operation.
4. Switch to Simulation mode to observe packet movement.
5. Open any PC → Desktop → Command Prompt.
6. Use the "ping" command to test connectivity between devices.
7. For fault testing, disconnect a switch link and repeat ping test.

------------------------------------------------------------

Conclusion

Through this practical assignment, different physical network layouts were designed and tested. 
It was observed that:

- Star topology provides better performance.
- Hub-based topology leads to unnecessary packet broadcasting.
- Ring topology ensures better reliability due to alternative path availability.

This experiment helped in understanding practical LAN planning and topology selection based on performance and reliability requirements.

------------------------------------------------------------
