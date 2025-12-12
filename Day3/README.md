**1. What is vulnerability scanning?**

Vulnerability scanning is an automated check that looks for weaknesses in a system—like outdated software, open ports, or misconfigurations—that attackers could use.

**2. Difference between vulnerability scanning and penetration testing?**

Vulnerability scanning: Automated, finds weaknesses but doesn’t exploit them.

Penetration testing: Manual + skilled testing, actually tries to exploit vulnerabilities to see what damage is possible.

Think of scanning as “finding the doors” and pentesting as “checking if you can break through them.”

**3. What are some common vulnerabilities in personal computers?**

Outdated Windows or software

Weak passwords

Enabled SMB/NetBIOS ports (like 445, 139)

Unpatched browsers

Unsafe extensions

Disabled antivirus or firewall

Misconfigured services running in the background

**4. How do scanners detect vulnerabilities?**

They use:

A database of known vulnerabilities

Port scans to see exposed services

Version checks (e.g., old Apache, outdated OS)

Misconfiguration checks

Weak-password tests (in some tools)

They compare what they find against known security issues.

**5. What is CVSS?**

CVSS (Common Vulnerability Scoring System) is a standard way to rate how severe a vulnerability is.
Scores range from 0 to 10, where:

0–3 is low

4–6 is medium

7–8.9 is high

9–10 is critical

6. How often should vulnerability scans be performed?

For personal systems: monthly or after major changes.
For organizations: weekly, daily, or continuous depending on risk.

**7. What is a false positive in vulnerability scanning?**

A false positive is when the scanner reports a vulnerability that isn’t actually present.
It’s like a smoke alarm going off when there’s no fire.

**8. How do you prioritize vulnerabilities?**

You usually sort them by:

Severity score (CVSS)

How easily they can be exploited

Whether the system is exposed to the internet

Importance of the affected device

Whether an active exploit exists in the wild

Critical and easily exploitable issues get fixed first.
