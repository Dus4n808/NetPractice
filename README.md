*This project has been created as part of the 42 curriculum by <dufama>.*

## Description

NetPractice is a networking exercise from the 42 curriculum. The goal is to solve 10 levels of network configuration problems using a browser-based training interface. Each level presents a non-functioning network diagram that must be fixed by correctly configuring IP addresses, subnet masks, and routing tables so that devices can communicate with each other.

## Instructions

### Running the training interface

1. Download and extract the project files from the 42 project page.
2. Run the training interface:
   ```
   ./run.sh
   ```
   If `run.sh` does not work, you can start the server manually:
   ```
   python3 -m http.server 49242
   ```

## Resources

### Networking concepts studied

- **TCP/IP addressing** — how IP addresses identify devices on a network
- **Subnet masks** — how to determine network and host portions of an address
- **Default gateways** — how devices route traffic outside their local network
- **Routers and switches** — the role of each in connecting networks and devices
- **OSI model layers** — understanding the layered approach to networking

### Useful references

- [TCP/IP addressing and subnetting basics (Cisco)](https://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13788-3.html)
- [Subnet Calculator](https://www.calculator.net/ip-subnet-calculator.html)
- [OSI Model explained](https://en.wikipedia.org/wiki/OSI_model)

### AI usage

AI was used to assist with drafting this README and to clarify networking concepts (subnetting, routing logic) during the learning process. All configurations were completed and understood manually.
