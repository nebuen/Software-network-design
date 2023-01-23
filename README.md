# 🧑‍💻Software-network-design

- <b>Business continuity</b>
- <b>Evaluating existing network problems and potential threats</b>
- <b>Secure architecture based on industry best practices</b>

<h2>Summary</h2>
<b>This project that aimed to address network security and infrastructure problems within a fictitious company, specifically Company A and Company B, which were planning to merge. The project involved:</b><br /><br />

- <b>Identifying vulnerabilities and risks within the networks.<b/>
- <b>Implementing solutions to mitigate those risks.<b/>
- <b>Ensuring that the merged company's IT systems were aligned with the business needs.<b/><br />


<b>Solutions implemented included:</b>
- <b>Multi-factor authentication<b/>
- <b>Regular updates and upgrades<b/>
- <b>Strong password policies<b/>
- <b>Use of technologies such as Zenmap and OpenVAS<b/>
- <b>Hiring security professionals<b/>

<b>Additionally, the project aimed to optimize the IT budget and implement cost-saving measures while ensuring compliance with industry best practices and regulatory requirements. The project also aimed to improve incident response capabilities and provide ongoing employee training to raise awareness of security risks and best practices.<b/><br /><br />



<h2>📝📝📝Problem📝📝📝</h2><br />

- <b>Remote Desktop Protocol opens ports 88-93, making it easy for threat actors to gain access to resources, create accounts, and move laterally to maintain persistence and privilege escalation.</b>
- <b>Old user accounts no longer required are not removed, leaving the company open to attacks.</b>
- <b>Full access privileges are granted to every employee, with the exception of the payroll system, increasing the risk of misconfigurations, privilege escalation, and accidental data loss.</b>
- <b>Regular password changes are not enforced, leaving the company open to brute force attacks and cracking password hashes.</b>
- <b>Outdated hardware in the Cisco PIX 515E Firewall increases the risk of exploitation by bad actors as it does not receive patches or updates.</b>
- <b>Missing critical personnel in the form of security professionals who can help mitigate network security problems.</b>
- <b>Company B outsources IT-related needs to a consultant, resulting in a lack of IT infrastructure documentation and security and integration issues.</b>
- <b>Company B uses Windows Server 2008 IP address 192.168.25.4 SMB server, which is missing critical patches, increasing the risk of remote execution, denial of service, and bypassing the authentication mechanism.</b>
- <b>Company B uses default usernames and passwords, which can be easily exploited by bad actors, leading to information disclosure and unauthorized access.</b>
- <b>Company B uses Telnet which is open on port 23 and doesn't have encryption, making it easy for malicious actors to intercept and read sensitive data.</b>

<h2>📝📝📝Solution📝📝📝</h2> <br />


- <b>Implemented multi-factor authentication and access duration monitoring to secure Remote Desktop Protocol</b>
- <b>Implemented regular updates and upgrades and regular monitoring logs to mitigate the problems like remote execution, bypassing the authentication</b>


- <b>Addressed the credentials that Company B was using, which were default credentials, changed them, and implemented stronger passwords that consist of standardized length and combination, limit password attempts, password change every 90 days, and use multi-factor authentication.</b>
- <b>Implemented solutions to address the vulnerabilities in Company B, such as disabling Telnet, closing open ports, and strengthening cyber posture before the merger</b>
- <b>Collaborated with cross-functional teams to ensure seamless integration of IT systems and alignment with the business needs of the post-merger organization</b>
- <b>Utilized technologies such as Zenmap, OpenVAS, and Microsoft Visio</b>
- <b>Implemented least privilege for more manageable sessions</b>
- <b>Enforced necessary least privilege, just-in-time (JIT) access</b>
- <b>Implemented regular password changes to mitigate brute force attacks and cracking password hashes</b>
- <b>Upgraded Cisco PIX 515E Firewall to a more secure and updated version</b>
- <b>Hired security professionals to oversee day-to-day security and information usage of the company</b>
- <b>Regularly monitored logs and implemented incident response plan to identify and quickly address any security breaches quickly.</b>
- <b>Implemented secure communication channels and addressed relevant regulatory compliance</b>
- <b>Implemented automation initiatives to enhance analyst capabilities and workflows while eliminating monotonous tasks</b>
- <b>Implemented threat hunting to detect and prevent malicious activity</b>
- <b>Implemented cutting-edge detection content aligned with ATT&CK, Cyber Kill Chain, and various other cyber security frameworks</b>
- <b>Implemented cost-saving measures to optimize the IT budget</b>
- <b>Created comprehensive IT infrastructure documentation for Company B to ensure compliance with industry best practices and secure design principles</b>
- <b>Provided ongoing training and development for all employees to ensure they were aware of the latest security risks and best practices to mitigate them.</b>
