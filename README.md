# SOHO Router Simulator — Fixed LAN Validation

Open `index.html` in a browser or publish the folder with GitHub Pages.

## Correct LAN answer

- Router IP: `192.168.1.1`
- Subnet mask: `255.255.255.0`
- DHCP enabled
- DHCP start: `192.168.1.100`
- DHCP end: `192.168.1.150`

The validator now accepts this range and provides separate feedback for invalid IPv4 values, invalid masks, wrong subnets, reversed ranges, network/broadcast addresses, and a pool containing the router address.
