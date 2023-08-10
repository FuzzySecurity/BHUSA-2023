## Close Encounters of the Advanced Persistent Kind: Leveraging Rootkits for Post-Exploitation

#### Speakers

[Valentina Palmiotti](https://twitter.com/chompie1337) & [Ruben Boonen](https://twitter.com/FuzzySec)

#### BlackHat Abstract

Our team specializes in conducting advanced Red Team engagements in highly secure environments with complex security measures. These environments demand constant innovation and the development of novel tools, techniques, and procedures to bypass critical endpoint security controls. We have created a versatile kernel rootkit that neutralizes various endpoint sensors providing an effective solution when traditional methods are impossible or cost-prohibitive. Additionally, we have developed novel tradecraft to establish various persistence and data collection channels.

Our presentation will explore a full-chain Windows kernel post-exploitation scenario, where we discovered and weaponized a Windows 0-day vulnerability to load our kernel rootkit. Once loaded, we will demonstrate how Direct Kernel Object Manipulation (DKOM) can be utilized to dynamically alter OS telemetry/sensor visibility, thereby rendering endpoint security solutions ineffective. Additionally, we will showcase a number of advanced attacks, such as employing Network Driver Interface Specification (NDIS) modules to disrupt EDR cloud telemetry or establish covert persistence channels or directly read memory-resident keyboard states in the Kernel for high-performance global keylogging.

Furthermore, we will examine several Windows platform mitigation technologies and their impact on our rootkit's operation, while offering guidance that attendees can apply to fortify their corporate networks. Kernel rootkits have been predominantly associated with nation-state actors; however, this perception is changing. Increasingly, capable groups can leverage such TTPs, and even commodity attackers have demonstrated the ability to employ basic kernel post-exploitation capabilities, e.g., Bring Your Own Vulnerable Driver (BYOVD). As these attacks grow in frequency and sophistication, it is essential for companies to configure their systems and networks to provide as many obstacles for potential attackers as possible.