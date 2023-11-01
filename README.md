# cyberoperations
### Overview 
Your team has received management buy-in and have two weeks to complete the IRP.  You have gathered your team and are ready to go. Our company is fictional but is based on various components of Motorola Solutions (MSI) and information that is readily available through public research. MSI is a publicly traded company and complies with the Sarbanes-Oxley Act (SOX). This act (SOX) is an annual obligation requiring publicly traded companies doing business in the U.S. to establish financial reporting standards. The standard also includes safeguarding data, tracking attempted breaches, logging electronic records for auditing, and proving compliance. No company confidential data was used in the development of this assignment.       
### Planning
Motorola Solutions is widely recognized as a “global leader in public safety and enterprise security. Our solutions in land mobile radio communications, video security & access control and command center, bolstered by managed & support services, create an integrated technology ecosystem to help make communities safer and help businesses stay productive and secure. At Motorola Solutions, we’re ushering in a new era in public safety and security.” Over our 95-year company history, we have acquired and divested from numerous business segments from semiconductors, cellular, government electronics, and television. But one constant at Motorola Solutions has and continues to be the Public Safety communications business. To this day, the Public Safety business segment is the core of the company and its culture. With just over 20,000 employees, the company develops products and services for State, Local, and Federal government agencies throughout the world to “ensure the protection of citizens, persons in their territory, organizations and institutions against threats such as crimes, revolt, political turmoil, natural and man-made disasters, and so on.” 
Most people associate Public Safety with first responders and while this is a good starting point, public safety agencies encompass much more. They include law enforcement at the federal, state, and local level, fire departments and agencies, emergency medical personnel, 911 Dispatchers, and public works departments and utilities just to mention a few. If you take a moment, we all probably know someone serving in this capacity and arguably one of the most important tools they use during the moments that matter most is the ability to communicate.  It is often their lifeline for backup and support in critical moments.
These networks, for all practical purposes, have flown under the radar from cybersecurity attacks for many years. In the summer of 2018, the Federal Government created the Cybersecurity and Infrastructure Security Agency (CISA). Just another indicator about the increased threats of Cybersecurity and the need for companies to prepare accordingly to deal with this critical area of expertise. With the creation of CISA, there were “16 critical infrastructure sectors whose assets, systems, and networks, whether physical or virtual, are considered so vital to the United States that their incapacitation or destruction would have a debilitating effect on security, national economic security, national public health or safety, or any combination thereof.” One of the 16 critical infrastructure sectors identified was the Communications sector: MSI’s core business. However, one key component absent from MSI’s Products and Services offerings was providing advanced security monitoring, detection, and remediation capabilities for Customer communications networks. 
To face the challenge of providing incident response services to our Public Safety Customers, management has tasked our team to develop recommendations for implementing this critical service. We formed a Computer Security Incident Response Team (CSIRT) made up of key members of our Human Resources (HR), Finance, Development Engineering, Managed & Support Services (M&SS), Sales and Legal teams. The CSIRT concluded that we lacked the internal resources and expertise to bring cybersecurity services such as Security Monitoring and Incident Response to the marketplace. However, we had many critical infrastructure components in place serving more than 500 Customer networks such as Network Monitoring, Dispatching of Partners to respond to system alarms (with Service Level Agreements established), and Security Patching Services of Windows and Linux devices. The CSIRT decided to recommend a hybrid solution would be the fastest and most efficient way to bring security monitoring and IR services to our customers. By outsourcing these two components to an established Managed Security Service Provider (MSPP) and coupling this with our existing Network Monitoring, Security Patching and Dispatch service capabilities, we could quickly establish MSI as a full-service Public Safety provider of missing critical communications and Cyber Security services. The CSIRT also recommended MSI consider acquiring our recommended MSPP (Lunar Line) as part of a long-term strategy.  

### Lunar Line attributes:
•	24 x 7 Security Monitoring
•	Threat Intelligence gathering for proactive monitoring, detection, and response.
•	IR professionals to engage with Customers during a Cyber-attack.
•	Centralized Security Monitoring - Note: special provisions made to place key Lunar Line personnel working directly in MSI’s existing Network Monitoring team. 

### Detection and Analysis
##### Detection tools and methodologies:
Lunar Line’s Managed Security Service Provider offers 24/7 security monitoring and threat intelligence gathering capabilities. These services involve use of various tools and methodologies to detect and respond to cybersecurity threats. Some of the popular tools that might be used are intrusion detection systems/prevention systems (IDS/IPS). (IDS/IPS) watches your network, identifies possible incidents, logs information on incidents, stops the incident, and reports them to security administrators (Juniper Networks). Also, Lunar Line can use security information and event management systems (SIEM), vulnerability scanners, and endpoint detection and response tools (EDR). SIEM offers real-time monitoring and analysis of incidents.
SIEM can provide tracking and logging of security data for compliance (IBM). Vulnerability scanning involves regularly scanning the network for vulnerabilities and potential security threats. EDR is an endpoint security solution that continuously monitors devices to detect and respond to threats like ransomware, malware, Trojans, etc. (Aarness). This approach can help detect potential security threats or attacks before they are exploited. As a result, these tools can be placed throughout the customer’s network to monitor traffic and identify suspicious activity (IBM).
In addition to the tools, Lunar Line may use methodologies such as signature-based detection, behavioral analysis, and machine learning algorithms to identify and respond to threats. Signature-based detection involves matching known patterns with the incoming traffic and malicious activity (Cyberwire). Behavioral analysis looks for anomalies in network traffic to identify potential threats (VMWare). Machine learning algorithms are used to analyze large amounts of data to detect patterns and trends to detect a cybersecurity threat (Crowdstrike).
#### Types of tools and placement:
There are many types of tools and methodologies that can be used for detecting and analyzing security incidents at Lunar Line. Some of the most common types of tools and their placements include:
1.	Network Monitoring Tools: These tools are placed at various points on the network such as routers, switches, and firewalls. Network monitoring tools are used to monitor traffic and detect anomalies and security events (Bertucci).
1.	Examples of network monitoring tools include Wireshark, Nagios, and SolarWinds. These tools allow users to capture and view network traffic, filter packets, based on specific criteria, and analyze network data. The tools support TCP, UDP, IP, HTTP, DNS, etc. Network engineers, security analysts, and other network professionals use these tools to understand their company’s network (Bertucci).
2.	Host-based Monitoring Tools: These tools are installed on individual computers, devices, or servers to monitor on the host and detect unauthorized access (Tour Tech Diet).
1.	Examples of host-based monitoring tools include antivirus software, intrusion detections/prevention systems, and endpoint detection and response solutions. These tools are signature-base and behavior-based systems that look for known patterns of known threats, while behavior-based systems analyze traffic to detect abnormal behavior that could indicate a potential cyber-attack (Tour Tech Diet).
3.	Security Information and Event Management (SIEM) Tools: These tools are used to aggregate, correlate, and analyze log data from various sources to detect security events and incidents. SIEM tools can be used for threat intelligence reporting (Exabeam).
1.	Examples of SIEM tools include Splunk, ArcSight, and IBM QRadar. These tools are known for their log management capabilities. It can collect and index logs from sources and make it searchable real-time. These tools can be used for security monitoring. As a result, it can detect and respond to security incidents by analyzing event data from different sources. In addition, these tools can integrate with vulnerability management tools. Vulnerability management tools can track and remediate security vulnerabilities, or with incident response tools to automate the response to security incidents (Exabeam).
4.	Vulnerability Scanning Tools: These tools are used to scan for vulnerabilities in software and systems, which can be exploited by cyber criminals (Kime).
1.	Examples of vulnerability scanning tools include Nessus, OpenVAS, and Qualys. These tools can be used to scan a wide variety of systems, including servers, workstations, network devices, and cellular devices. It can detect a wide range of vulnerabilities, including misconfigured software, outdated software, and known security vulnerabilities in software applications. These tools include a large database of known vulnerabilities and can perform both authenticated and unauthenticated scans (Kime).
### Reporting Procedures:
When a security incident is detected, it is important for Lunar Line to have a reporting procedure in place. Therefore, the procedure ensures that the incident is documented and escalated to the appropriate parties. Key components of a reporting procedure include:
1.	Who to report to: The reporting procedure should define who should be notified in the event of a security incident, including internal stakeholders such as CSIRT, IT, and legal teams. In addition, Lunar Line should inform external stakeholders such as law enforcement and regulatory authorities.
2.	How to report: The reporting procedure should outline the steps to be taken. This can be communicated through email, phone web portal, chat systems. The information that should be provided would be date/time of incident, affected systems, and type of incident.
3.	Incident classification: The reporting procedure should define how incidents are classified based on severity and impact. As a result, this can help prioritize incident response activities and allocate resources accordingly.
4.	Response procedures: The reporting procedure should outline the steps for the security incident. This includes containment, investigation, remediation, and recovery. For example, this should have detailed response plans for different types of incidents such as malware infection or data breach.
5.	Reporting template: The reporting procedure should include a template for documenting security incidents. This can be used by incident responders to ensure that all relevant information is captured. The template should include fields for incident classification, incident description, impact assessment, containment measures, investigative findings, remediation activities, and lessons learned.
Therefore, detection tools, methodologies, tool placements, and reporting procedures are critical components of a successful incident response program. By having a well-defined and tested incident response plan. Organizations like Motorola Solutions can respond quickly and effectively to cybersecurity incidents. As a result, minimizing the impact of a breach, and improving their overall cybersecurity.
## Response - Containment, Eradication and Recovery 
Based on the information provided, Motorola Solutions’ Security Operations Center (SOC) is equipped to monitor networks, applications, and devices for potential security threats 24/7. The SOC uses ActiveEye to prioritize alerts and focus on those that are more likely to result in a security incident or risk. The SOC management team regularly monitors internal SLAs and has established internal KPIs to ensure alerts are investigated in a timely manner.
In the event of a potential incident, the SOC will use data available in ActiveEye and access your system to determine the extent of malicious activity. If needed, the SOC will add more detection policies to your service modules. With the EDR service module, the SOC can take mitigating actions on remote host systems based on a pre-approved response plan or, if they determine it to be necessary for a specific case. When needed, the SOC will recommend mitigating actions that you can take to address a threat.

The SOC team operates from secure, redundant locations in the U.S. Analysts complete regular training on customer data management and privacy to protect sensitive customer data. The SOC team routinely participates in red team and purple team exercises and uses sophisticated training platforms to ensure their skills are up to date. The senior analysts develop and perform real-world exercises, simulating modern threat actor activity and security breaches for SOC analyst training.
To further strengthen the SOC's capabilities, the following measures can be taken:
•	Regular reviews and updates of the SOC's policies, procedures, and response plans to ensure that they align with best practices and industry standards.
•	Regular vulnerability assessments and penetration testing to identify weaknesses in the SOC's systems and processes.
•	Integration of threat intelligence feeds to enhance the SOC's ability to detect and respond to emerging threats.
•	Collaboration with external stakeholders, such as law enforcement agencies and industry peers, to share threat intelligence and best practices and to coordinate responses to major security incidents.
•	Regular tabletop exercises and incident simulations to test the SOC's response capabilities and identify areas for improvement.
## Develop categorization of incidents: 
Incidents can be categorized into various levels based on their severity and impact on the organization. One commonly used categorization is:
1.	Level 1 - Low impact incidents that can be resolved quickly and without significant disruption to business operations. Examples include minor system issues, routine access requests, and minor security incidents.
2.	Level 2 - Medium impact incidents that require more resources and attention to resolve. These incidents may cause some disruption to business operations but are not critical. Examples include moderate system issues, significant security incidents that do not result in data loss or theft, and access requests that require additional approval.
3.	Level 3 - High impact incidents that require immediate attention and significant resources to resolve. These incidents can cause major disruption to business operations and may result in data loss or theft. Examples include major system outages, significant security incidents with data loss or theft, and access requests for sensitive information.
The escalation process for incidents typically involves moving the incident from one level to the next if it cannot be resolved at the current level. For example, if a Level 1 incident cannot be resolved within a certain period, it may be escalated to Level 2. Similarly, if a Level 2 incident becomes more severe or cannot be resolved within a certain period, it may be escalated to Level 3.
The escalation process may also involve notifying higher-level personnel or departments within the organization, such as management or the IT department, to ensure that the incident is receiving the necessary attention and resources to be resolved in a timely and effective manner. Communication and collaboration between different departments and personnel is essential for effective incident management and resolution.
## Incident Event Procedures and Response: 
Sure, I can provide some responses and procedures to three different incidents, one of which will be a natural disaster. Here are some examples:
### Incident 1. Phishing attack:
Categorization: Medium
Response:
Procedure:
1.	Designate a response team to manage the incident and coordinate with relevant stakeholders.
2.	Collect and preserve evidence related to the phishing attack for future reference.
3.	Assess the impact of the attack on the organization's operations and infrastructure.
4.	Notify law enforcement agencies and regulatory authorities, if necessary.
5.	Prepare a detailed incident report that includes the root cause of the attack, the extent of the damage, the response actions taken, and the lessons learned.
6.	Conduct a post-incident review to identify areas for improvement and update the incident response plan accordingly.
### Incident 2: Ransomware Attack
Categorization: High
Ransomware is a type of malicious software that blocks access to a system or data until a ransom is paid. It is a prevalent threat that can cause significant harm to an organization. Here is a response and procedure for a ransomware attack:
#### Response:
1.	Immediately disconnect the affected systems from the network to prevent the spread of the ransomware.
2.	Notify the incident response team, and they will activate the ransomware response plan.
3.	Determine the scope of the attack and identify the type of ransomware used.
4.	Contact law enforcement if necessary.
5.	Restore data from backups and ensure they are clean and free from ransomware.
6.	Clean and rebuild infected systems and devices.
7.	Update the organization's security systems and software to prevent future attacks.
8.	Monitor the network for any unusual activities.
#### Procedure:
1.	The incident response team should be notified immediately when a ransomware attack is suspected.
2.	The team should identify the type of ransomware and its scope.
3.	The affected systems should be immediately disconnected from the network to prevent the spread of the ransomware.
4.	The team should assess the damage and determine the impact on the organization's data and systems.
5.	If necessary, law enforcement should be contacted to investigate the attack.
6.	The team should restore the affected systems and devices from clean backups.
7.	Infected systems and devices should be cleaned and rebuilt, and all security patches and updates should be applied.
8.	The team should conduct a post-incident review to identify any weaknesses in the organization's security systems and procedures and implement any necessary changes.
### Incident 3: Natural Disaster (Hurricane)
Categorization: High
Natural disasters such as hurricanes can cause widespread damage to an organization's infrastructure and affect its ability to operate. Here is a response and procedure for a natural disaster:
#### Response:
1.	Ensure the safety of all employees and evacuate the affected areas if necessary.
2.	Notify the incident response team and activate the disaster recovery plan.
3.	Assess the damage caused by the hurricane to the organization's infrastructure and facilities.
4.	Prioritize the restoration of critical systems and services.
5.	Work with local authorities and emergency services to coordinate recovery efforts.
6.	Provide regular updates to employees, customers, and stakeholders on the status of the organization's recovery efforts.
7.	Conduct a post-incident review to identify any weaknesses in the organization's disaster recovery plan and implement any necessary changes.
#### Procedure:
1.	The safety of all employees should be the priority, and evacuation should be carried out if necessary.
2.	The incident response team should be notified immediately, and the disaster recovery plan should be activated.
3.	The team should assess the damage caused by the hurricane and prioritize the restoration of critical systems and services.
4.	Local authorities and emergency services should be contacted and coordinated with to aid in the recovery efforts.
5.	Regular updates should be provided to employees, customers, and stakeholders on the organization's recovery progress.
6.	Once the recovery efforts have been completed, a post-incident review should be conducted to identify any weaknesses in the disaster recovery plan and to implement any necessary changes.

### Post-incident Activity:
An after-action report or lessons learned document is a critical component of post-incident activities. It provides an opportunity to review the incident, analyze the response, and identify areas for improvement. Some key items to capture in an after-action report or lessons learned document include:
1.  	Incident summary: a brief description of the incident, including the date, time, and duration.
2.  	Impact analysis: a description of the impact of the incident, including the systems and services affected, the number of users impacted, and the monetary impact.
3.  	Response timeline: a detailed timeline of the response to the incident, including the initial detection, escalation, containment, and resolution.
4.  	Root cause analysis: a detailed analysis of the root cause of the incident, including any vulnerabilities or gaps in the security controls.
5.  	Response effectiveness: an assessment of the effectiveness of the response, including the identification of any gaps or areas for improvement.
6.  	Communication effectiveness: an assessment of the effectiveness of communication during the incident, including any gaps or areas for improvement.
7.  	Lessons learned: a list of the key lessons learned from the incident, including any improvements that could be made to processes, procedures, or technology.
8.  	Action plan: a list of action items to address the gaps or areas for improvement identified in the after-action report.
9.  	Follow-up: a plan for follow-up and review to ensure that the action items are completed and that the improvements are implemented.
10.  Recommendations: any additional recommendations for improving the incident response process, including training or awareness programs, technology upgrades, or process improvements.
Capturing these items in an after-action report or lessons learned document can help an organization improve its incident response capabilities and reduce the risk of future incidents.



### References

Aarness, Anne. WHAT IS ENDPOINT DETECTION AND RESPONSE (EDR)? 6 February 2023. Website: https://www.crowdstrike.com/cybersecurity-101/endpoint-security/endpoint-detection-and-response-edr/. 10 April 2023.
Bertucci, Destiny. 10 Best Network Monitoring Tools, Compared. 21 January 2022. Website: https://www.auvik.com/franklyit/blog/best-network-monitoring-tools/. 10 April 2023.
CISA. Critical Infrastructure Sectors. 2020. Website: https://www.cisa.gov/topics/critical-infrastructure-security-and-resilience/critical-infrastructure-sectors. 2023 10 April.
Crowdstrike. MACHINE LEARNING (ML) & CYBERSECURITY. 14 September 2022. Website: https://www.crowdstrike.com/cybersecurity-101/machine-learning-cybersecurity/. 10 April 2023.
Cyberwire. signature-based detection definition. 2023. Website: https://thecyberwire.com/glossary/signature-based-detection. 10 April 2023.
Exabeam. Best SIEM Solutions: Top 10 SIEMs and How to Choose. 2022. Website: https://www.exabeam.com/explainers/siem/siem-solutions/. 10 April 2023.
IBM. What is SIEM? . 2023. Website: https://www.ibm.com/topics/siem. 10 April 2023.
Juniper Networks. What is IDS and IPS? 2023. Website: https://www.juniper.net/us/en/research-topics/what-is-ids-ips.html#:~:text=with%20IDS%2FIPS%3F-,Intrusion%20detection%20systems%20(IDS)%20and%20intrusion%20prevention%20systems%20(IPS,reporting%20them%20to%20security%20administrators. 10 April 2023.
Kime, Chad. The 8 Best Vulnerability Scanner Tools for 2023. 8 March 2023. Website: https://www.esecurityplanet.com/networks/vulnerability-scanning-tools/. 10 April 2023.
Market Watch. Public Safety and Security Market Specific Insight Report 2023-2030. 7 April 2023. Website: https://www.marketwatch.com/press-release/public-safety-and-security-market-specific-insight-report-2023-2030-2023-04-07#:~:text=The%20global%20Public%20Safety%20and%20Security%20market%20size%20was%20valued,USD%20768076.01%20million%20by%202027. 10 April 2023.
Motorola. DETECT AND RESPOND TO CYBER THREATS FASTER. 2022. Website: https://www.motorolasolutions.com/en_us/managed-support-services/cybersecurity/activeeye-security-platform.html. 10 April 2023.
Motorola Solutiona. Earnings & SEC Filings. 2022. Website: https://www.motorolasolutions.com/investors/earnings-and-sec-filings.html. 10 April 2023.
Motorola Solutions. ActiveEye Managed Detection & Response. 22 December 2021. Website: https://www.sumtercountyfl.gov/AgendaCenter/ViewFile/Item/19483?fileID=46728. 10 April 2023.
—. Advanced Threat Insight Solutions. 2022. Website: https://www.motorolasolutions.com/content/dam/msi/docs/MSI_Advanced_Threat_Insights_Solution_Brief.pdf. 10 April 2023.
Tour Tech Diet. Top 8 Host-Based Intrusion Detection System Tools. 2022. Website: https://yourtechdiet.com/blogs/host-based-intrusion-detection-system-tools/. 10 April 2023.
VMWare. What is Behavioral Analysis? 2023. Website: https://www.vmware.com/topics/glossary/content/behavioral-analysis.html. 10 April 2023.



