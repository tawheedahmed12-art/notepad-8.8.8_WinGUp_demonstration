# CVE-2025-15556
# Notepad-8.8.8_WinGUp_Demonstration
Demonstration of how the WinGUp service had been exploited after an APT gained access to a cloud instance hosting the WinGup backend and update files.

# WinGUp

WinGUp (Windows General Updater) was developed by Don Ho for the Notepad++ as their updater and was later released under the LGPL license. A vulnerability was disclosed February of 2026 that an APT had been persistent for 6 months primarily targeting government infrastructure in south east asia by.

Attackers gained access to the primary NP++ updater instance serving an update.exe file and handling the WinGup backend, once in the APT could steer select IP's from the main site to a malicious webserver, based on the way the WinGup service is architected the attacker need only serve a file named updater.exe and client instances would identify it as a genuine update pushing it to the machine and executing it. 

| CVE | Date | Payload | Details |
|------|------|--------|--------|
| CVE-2025-15556| February 3rd 2026 | Chrysalis Backdoor | Between June and December 2025, a supply chain compromise on the official Notepad++ hosting infrastructure delivered two primary types of malicious payloads via hijacked software updates |

This demonstration was made in a local environment of how the attack would have looked to the victim the attacker and the server minus the Chrysalis payload.


