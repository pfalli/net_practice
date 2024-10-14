# Network Practice Exercise

This project is a network practice exercise from 42 School. The goal is to complete three exercises of varying difficulty levels by adjusting the networks shown.

## Project Overview

In this project, you will work on configuring network settings for different scenarios. You will need to take care of the following:

1. **IP Addresses**: Assign appropriate IP addresses to devices in the network.
2. **Switches**: Represent a single network segment where all connected devices are on the same subnet.
3. **Routers**: Connect different networks and route traffic between them.
4. **Routing Channels**: Define the destination and the next hop for routing traffic.

## Exercises

### Level 1
- Basic network configuration with a single switch and multiple hosts.

### Level 2
- Introduction of a router to connect two different networks.

### Level 3
- More complex network with multiple routers and switches.

## Key Concepts

### IP Address Calculation
To calculate an IP address, you need to understand the structure of an IP address, which consists of four octets. Each octet can range from 0 to 255. For example, `192.168.1.1` is a valid IP address.

### Netmask Calculation
A netmask is used to divide an IP address into subnets and specify the network's available hosts. For example, a netmask of `255.255.255.0` means that the first three octets are the network part, and the last octet is the host part.

### Routing
Routers use routing tables to determine the best path for forwarding packets. Each entry in the routing table includes a destination network and the next hop (the next router or device to which the packet should be sent).

## Example Code

Here are some functions from the project that help with IP and netmask calculations:

### How to calculate the IP addresses Range

We have to take in consideration the range of IP addresses looking at the Network address in which the devices are connected.

### If we have only the Net Mask

We can add any IP address we want, but taking in consideration that theaddresses 192..../172..../10.... cannot be connected to Internet because they are exclusivily Private IP addresses.
