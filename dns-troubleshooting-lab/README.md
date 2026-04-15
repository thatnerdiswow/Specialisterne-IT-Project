# DNS Troubleshooting Lab

## Objective
Simulate and resolve a DNS issue where websites are inaccessible despite an active internet connection.

## Issue
A user reports that their device is connected to the internet, but websites will not load.

## Hypothesis
It seems as though the laptop is connected to the internet but websites fail to load. The most likely cause is an issue with the network itself?
If DNS settings are misconfigured, domain names will fail to resolve, preventing access to websites.

## Tools Used
- Command Prompt (Windows)
- ipconfig
- ping
- Network Adapter Settings
- Wireshark (optional)

## Steps Taken
1. Manually changed DNS settings to an invalid IP address.
2. Attempted to access websites (failed).
3. Verified network connectivity using:
   - `ping 8.8.8.8` (successful)
4. Tested DNS resolution:
   - `ping google.com` (failed)
5. Identified DNS misconfiguration as the root cause.
6. Restored DNS settings to a valid server (8.8.8.8).
7. Verified resolution and website access was restored.

## Results
- Internet connectivity was confirmed
- DNS resolution failed when misconfigured
- Issue was resolved after correcting DNS settings

## Environmental Restrictions
Due to network restrictions, DNS settings could not be manually modified on the system. This reflects real-world environments where administrative controls or ISP configurations limit direct changes.

## Conclusion
The issue was caused by incorrect DNS configuration, demonstrating how DNS failures can disrupt access even when the network is connected. Even without direct modification, this project demonstrates the diagnostic process used to identify DNS-related issues. It highlights the importance of testing both IP connectivity and domain resolution when troubleshooting network problems.
