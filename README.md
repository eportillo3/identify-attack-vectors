<h1>Identify the attack vectors of a USB drive</h1>

In this activity, you will assess the attack vectors of a USB drive. You will consider a scenario of finding a USB drive in a parking lot from both the perspective of an attacker and a target.

USBs, or flash drives, are commonly used for storing and transporting data. However, some characteristics of these small, convenient devices can also introduce security risks. Threat actors frequently use USBs to deliver malicious software, damage other hardware, or even take control of devices. USB baiting is an attack in which a threat actor strategically leaves a malware USB stick for an employee to find and install to unknowingly infect a network. It relies on curious people to plug in an unfamiliar flash drive that they find.

<h2>Scenario</h2>

You are part of the security team at Rhetorical Hospital and arrive to work one morning. On the ground of the parking lot, you find a USB stick with the hospital's logo printed on it. There’s no one else around who might have dropped it, so you decide to pick it up out of curiosity.

You bring the USB drive back to your office where the team has virtualization software installed on a workstation. Virtualization software can be used for this very purpose because it’s one of the only ways to safely investigate an unfamiliar USB stick. The  software works by running a simulated instance of the computer on the same workstation. This simulation isn’t connected to other files or networks, so the USB drive can’t affect other systems if it happens to be infected with malicious software.

<h2>Contents</h2>

You create a virtual environment and plug the USB drive into the workstation. The contents of the device appear to belong to Jorge Bailey, the human resource manager at Rhetorical Hospital.

<img src="https://i.imgur.com/FxKuKBg.png" height="80%" width="80%"/>

Jorge's USB drive contains personal info like family and pet photos. The USB drive also seems to contain sensitive work files like Shift schedules, new hires and employee budgets. Personal files and works files should never be together in the same USB drive. 

<h2>Attacker mindset</h2>

The USB drive contains shift schedules and employee budgets where the attacker can use this information against them. Since there is personal files included such as family photos, the attack could target family members. The files in the drive could provide the attacker access to the business. 

<h2>Risk analysis</h2>

Raising employee awareness about these types of attacks and providing guidance on how to handle suspicious USB drives is a managerial control that can help mitigate the risk of security incidents. Implementing routine antivirus scans serves as an operational control. Additionally, a technical control, such as disabling AutoPlay on company computers, can act as a further defense by preventing the automatic execution of malicious code when a USB drive is inserted.
