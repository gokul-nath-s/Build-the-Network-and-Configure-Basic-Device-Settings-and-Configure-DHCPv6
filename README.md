# Build-the-Network-and-Configure-Basic-Device-Settings-and-Configure-DHCPv6

## Overview

This project involved building and configuring a network to ensure smooth and efficient device communication using DHCPv6, all implemented in a CISCO Packet Tracer file. The exercise was divided into several parts, each focusing on different aspects of network setup, configuration, and verification.

## Project Breakdown

### Part 1: Network Setup and Basic Configuration
1. **Cabling the Network:** The network was cabled according to the provided topology.
2. **Switch Configuration:** Basic settings were configured for each switch.
3. **Router Configuration:** Basic settings were configured for each router.
4. **Interfaces and Routing:** Configured interfaces and routing on both routers to establish proper communication across the network.

### Part 2: Verifying SLAAC Address Assignment from R1
- Verified that Stateless Address Auto Configuration (SLAAC) was properly assigned and confirmed connectivity and IP address assignment.

### Part 3: Configuring and Verifying DHCPv6 on R1
1. **PC-A Configuration:** Ensured that PC-A was correctly configured.
2. **DHCPv6 Services on R1:** Configured R1 to provide stateless DHCPv6 services to PC-A.

### Part 4: Configuring a Stateful DHCPv6 Server on R1
- Configured R1 to dynamically manage IPv6 addresses and verified all settings for accuracy.

### Part 5: Configuring and Verifying DHCPv6 Relay on R2
1. **SLAAC Address Examination:** Examined the SLAAC address.
2. **DHCPv6 Relay Configuration on R2:** Configured R2 as a DHCP relay agent for the LAN on G0/0/1.
3. **Verification on PC-B:** Tested and successfully acquired an IPv6 address from DHCPv6 on PC-B.

## Installation and Usage

To replicate this setup:

1. **Open the Packet Tracer File:** Load the provided CISCO Packet Tracer file.
2. **Cable the Network:** Follow the setup as per the provided topology in the file.
3. **Configure Devices:** Implement the switch and router configurations as detailed.
4. **Verify Configurations:** Use Packet Tracer's simulation mode to verify SLAAC, DHCPv6, and routing.

## Contributing

Contributions to this project are welcome. Please ensure that any proposed changes are well-documented and tested within the CISCO Packet Tracer environment.



## Contact

For any questions or feedback, please contact [Your Name] at [Your Email Address].

