
# VPN and IP Address Verification

## Overview
This document provides evidence of VPN usage and IP address verification before and after connecting to a VPN service.

## Steps and Observations

### 1. SSL Certificate Verification
- Accessed `google.com` via Brave browser.
- Verified that the connection is secure (HTTPS) with a valid SSL certificate.

### 2. VPN Connection (ProtonVPN)
- Connected to ProtonVPN using the **Fastest Free Server** located in the Netherlands (Server: NL-FREE#217).
- VPN protocol: **WireGuard (UDP)**.
- VPN assigned IP: **185.165.240.48**.

### 3. IP Verification After VPN Connection
- Visited `whatismyipaddress.com` to verify the IP.
- Detected IP: **185.165.240.48** (Netherlands - WorldStream B.V., Public Proxy Server).
- Location: Naaldwijk, Zuid-Holland, Netherlands.

### 4. IP Verification Without VPN
- Disconnected VPN and checked IP again.
- Detected IPv6: **2401:4900:78fe:64f0:69a2:9484:609b:3848**
- Detected IPv4: **106.194.78.xxx** (original ISP location).

## Conclusion
The VPN successfully masked the original IP address by assigning a Netherlands-based IP. SSL certificate verification ensured secure communication between the client and server.
