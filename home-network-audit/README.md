# Home Network Security Audit

## Objective
Assess the security of a home network to identify potential vulnerabilities and recommend improvements.

## Scenario
Personal home networks can be misconfigured or lack proper security controls, making them vulnerable to unauthorized access and potential cyber threats.

## Hypothesis
If a home network uses weak security configurations (such as default credentials or outdated encryption), then it will present identifiable vulnerabilities that could be exploited.

## Tools Used
- Router Admin Interface
- Command Prompt (ipconfig, netstat)
- Network Settings
- Wireshark

## Steps Taken
1. Accessed router settings via default gateway (e.g., 192.168.1.1).
2. Reviewed Wi-Fi security settings (encryption type, password strength).
3. Checked for use of default credentials.
4. Identified connected devices on the network.
5. Reviewed firewall and security settings.
6. Observed network traffic (optional, using Wireshark).

## Findings
- Wi-Fi encryption: (e.g., WPA2 enabled)
- Password strength: (weak/strong)
- Connected devices: (list or general description)
- Firewall status: (enabled/disabled)

## Risks Identified
- Weak passwords may allow unauthorized access.
- Outdated encryption protocols increase vulnerability.
- Unknown devices could indicate unauthorized network usage.

## Recommendations
- Use a strong, unique Wi-Fi password.
- Enable WPA3 or WPA2 encryption.
- Disable unused network features (e.g., WPS).
- Regularly monitor connected devices.
- Ensure firewall is enabled.

## Conclusion
This audit highlights the importance of properly configuring home network security settings to reduce vulnerabilities and protect connected devices from potential threats.
