# DHCP Dynamic Host Configuration Protocol

DHCP API to support DHCP server application for creating, destroying, receiving and releasing IP addresses to hosts in the network.

## Functionality includes:
* GetAddress: returns a new IP address to assign to host
* ReleaseAddress: releases a given IP address and returns it to the pool
* RenewAddress: renews a lease of IP address of a client 

## DHCP implemintation consist 3 files:
* [dhcp.h](https://github.com/itay-adi/DHCP/blob/main/dhcp.h): a header file
* [dhcp.c](https://github.com/itay-adi/DHCP/blob/main/dhcp.c): functions implemintation
* [dhcp_test.c](https://github.com/itay-adi/DHCP/blob/main/dhcp_test.c): for a functionality testing
