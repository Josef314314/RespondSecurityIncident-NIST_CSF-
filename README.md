<h1>Respond to a security incident by using the NIST Cybersecurity Framework</h1>

<h2>Scenario</h2>
This scenario is based on a fictional company: <br/>
<br/>
As a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. The organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved. <br/>

During the attack, the organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. <br/>

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. <br/>

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
- Network monitoring software to detect abnormal traffic patterns
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics
<br/>

<h2>Task</h2>

As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve the company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). I will use the CSF to help navigate through the different steps of analyzing this cybersecurity event and integrate the analysis into a general security strategy.
I have broken the analysis into different parts. You can explore them here:

- Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. <br/>
- Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. <br/>
- Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. <br/>
- Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. <br/>
- Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. <br/>

<h2>Incident report analysis</h2>

[See incident report analysis sheet](https://github.com/Josef314314/RespondSecurityIncident-NIST_CSF-/blob/main/Incident%20report%20analysis.pdf)

</p>
