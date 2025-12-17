# Task 4: Setup and Use a Firewall

## Objective
Configure and test basic firewall rules to allow or block network traffic.

## Tool Used
- Windows Defender Firewall / UFW (Linux)

## Steps Performed
1. Listed existing firewall rules.
2. Blocked inbound traffic on port 23 (Telnet).
3. Tested the rule using telnet command.
4. Allowed SSH traffic on port 22 (Linux).
5. Removed the test block rule to restore original state.

## Result
The firewall successfully blocked unauthorized access on port 23 while allowing required services. This demonstrates how firewalls filter traffic based on predefined rules.

## Key Learning
Firewalls improve network security by controlling inbound and outbound traffic using port-based rules.
