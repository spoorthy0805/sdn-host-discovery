# SDN Host Discovery Service using Ryu

This project implements a Host Discovery Service in an SDN network using Ryu controller and Mininet.

## Features
- Detects hosts dynamically using PacketIn events
- Stores MAC address, IP address, switch ID, and port number
- Maintains a host database
- Displays host details in real time
- Supports packet forwarding for successful connectivity

## Topology
- 1 OpenFlow switch
- 3 hosts
- Ryu remote controller

## How to Run

Activate Ryu environment:

```bash
source ~/ryu39/bin/activate
