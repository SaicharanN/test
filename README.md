# Extention of DHCPv4 implementation in ns-3 to support more options

## Course Code:  CO300

### Overview

Dynamic Host Configuration Protocol (DHCP) is a client/server protocol that automatically provides an Internet Protocol (IP) host
with its IP address and other related configuration information such as the subnet mask and default gateway.

RFC 2132 defines DHCP Options for dynamic configuration of IPv addresses on hosts. 
While DHCPv4 has been implemented in ns3, Some of the options are still unavailable in the implemented version.
The following Options are implemented here:
* Option 28- Broadcast Address Option
* Option 56- Message
* Option 57- Maximum DHCP message size
  
### References

[1] RFC 2132: DHCP Options and BOOTP Vendor Extensions
https://tools.ietf.org/html/rfc2132

[2] DHCP module for IPv4 in ns-3 (src/internet-apps/model)
