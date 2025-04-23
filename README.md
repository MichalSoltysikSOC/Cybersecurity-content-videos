-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Cybersecurity content (in English and Polish):

https://www.youtube.com/playlist?list=PL0RdRWQWldOAAKBqOVEutxKMP-a6CNoLY

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - How Web Protocol Weaknesses Enable Layer 7 DoS Attacks (ENG):


Title of the lecture: How Web Protocol Weaknesses Enable Layer 7 DoS Attacks.

Description of the lecture: This presentation delves into the inherent vulnerabilities within the design of web protocols which indirectly expose web pages to Layer 7 Denial-of-Service (DoS) attacks - regardless of the use of modern transport encryption mechanisms (e.g., WTLS, DTLS, TLS 1.2/1.3, or (G)QUIC). We'll meticulously dissect the specific weaknesses of the Internet Cache Protocol (ICP) and explore how it can be weaponized to circumvent security measures. Our analysis will further delve into the vulnerabilities residing within the handshake processes of DTLS, (G)QUIC, TLS 1.2/1.3, and WTLS. This session will provide valuable insights for security professionals and web developers, highlighting the importance of layered security strategies beyond encryption protocols to defend against DoS attacks.


Content:

Opening words.

Introduction to Layer 7 DoS Attacks.

Weak protocol design in ICP.

Weak protocol design in WTLS.

Weak protocol design in DTLS.

Introduction to QUIC Protocol.

QUIC vs. TLS.

GQUIC vs. IETF QUIC.

Weak protocol design in GQUIC.

Weak protocol design in QUIC.

Weak protocol design in TLS (Pre-1.3).

Weak protocol design in TLS 1.3.

Legitimate vs. illegitimate TLS traffic.

TLS DoS Attacks in practice.

Summary of inherent vulnerabilities in Layer 7 DoS Attacks across protocols.

Conclusions on common weaknesses leading to Layer 7 DoS.

Solutions for the need for a fully secure mechanism.

Executing a Layer 7 TLS 1.3 DoS Attack with OpenSSL and Python on Kali Linux.

Q&A.

Closing words.


URL: https://www.youtube.com/watch?v=_xP7_BnZCts

Click to watch on YouTube:

[![Michał Sołtysik - How Web Protocol Weaknesses Enable Layer 7 DoS Attacks (ENG)](https://github.com/MichalSoltysikSOC/Cybersecurity-content-videos/blob/main/screenshots/ENG_YouTube_avatar_ECC_CyberTalks_Again.png)](https://www.youtube.com/watch?v=_xP7_BnZCts)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - Deep packet inspection analyses - why the typical approach is not enough (ENG):


Title of the lecture: Deep packet inspection analyses: why the typical approach is not enough.

Description of the lecture: There is an unquestionable need to perform regular deep packet inspection analyses, i.e. network edge profiling. Providing standard SOC type services that use tools, such as SIEM, SOAR, IPS, WAF, EDR and others leads to a partial waste of human resources due to the constant dealing with the so-called "false positives". The cybersecurity industry is currently characterized by superficiality, insufficient competence and low cyber awareness. Cybercriminals are in possession of hundreds of mechanisms that they regularly take advantage of to break through firewalls. In this lecture, I will present an advanced view of the realities that teams such as SOC are unable to deal with, and explain why this is the case. I will use extensive knowledge of a variety of threats, based on analysis of 252 different network protocols from the areas of IT, OT and IoT.


Content:

Example number 1 - based on different level monitoring of HTTP traffic through SIEM system vs. DPI analysis on the example of RCE - Unauthorized User Account Creation vulnerability.

Example number 2 - based on File Upload / RCE vulnerability and HTTP traffic.

Example number 3 - based on TCP, FTP, DNS, PNIO, ICMP, RTCP, UDP, ICP, NBNS and SNMP traffic.

Example number 4 - based on RTT Measurements during DoS / DDoS cyber attacks.

Example number 5 - based on Modbus/TCP, WTP, H.225.0 RAS, GTP, RTCP and PFCP traffic.

Example number 6 - based on GTP, TIPC and CIGI traffic.

Example number 7 - based on ADwin and BAT_GW traffic.

Example number 8 - based on RCE vulnerability and MANOLITO and EtherCAT traffic.

20 simple tips - how to be a proficient network traffic analyst performing deep packet inspections.


URL: https://www.youtube.com/watch?v=_ulFvQ1z7j8

Click to watch on YouTube:

[![Michał Sołtysik - Deep packet inspection analyses - why the typical approach is not enough (ENG)](https://i1.ytimg.com/vi/SgrgnwtIT50/mqdefault.jpg)](https://www.youtube.com/embed/_ulFvQ1z7j8)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - Deep Packet Inspection Analysis - Examining One Packet Killers (ENG):


Title of the lecture: Deep Packet Inspection Analysis: Examining One Packet Killers.

Description of the lecture: Security Operations Center (SOC) teams monitor network traffic using SIEM and IPS solutions, along with other security tools. However, these tools can sometimes fall short in their capability, particularly when faced with complex attacks that exploit legitimate network protocols, such as a single, crafted packet. To combat these threats, SOC teams must adopt advanced techniques such as Deep Packet Inspection (DPI). The webinar explores DPI analysis techniques to detect and mitigate "One Packet Killers", using real-world examples from DHCP, H.225.0, Modbus over TCP, WTP, and BAT_GW protocols. Furthermore, it examines the intricacies of each protocol and highlights how specific message manipulations within these protocols can activate Denial-of-Service (DoS) attacks or disrupt communication flows. By mastering DPI techniques and addressing these protocol security weaknesses, SOC teams can enhance their ability to maintain a robust network security posture.


Content:

Opening words

Why IPS, WAF, and SIEM solutions are not enough.

Summary of the need for deep packet inspection analysis.

The four main categories of weaknesses/vulnerabilities.

DoS Attack Categories.

One Packet Killer via a vulnerability (CVE-2021-45105).

One Packet Killer via a weak protocol design in DHCP.

One Packet Killer via a weak protocol design in Modbus over TCP.

One Packet Killer via a weak protocol design in WTP.

One Packet Killer via a weak protocol design in BAT_GW.

One Packet Killer via a weak protocol design in H.225.0.

Findings (a breakdown of the possibilities and limitations behind functionalities within protocols which can be misused for DoS attacks under specific circumstances).

Protocol-based DoS Attacks.

DoS Attacks: Classification and Protocol Weakness Examples.

Some possible reasons why an attacker might send a single such packet ('One Packet Killer').

Conclusions of the webinar.

Recommendations on protocol weaknesses.

An example of a 'Silent Killer' using a ubiquitous protocol DNS.

Q&A.

Closing words.


URL: https://www.youtube.com/watch?v=8cX7Fn5AM04

Click to watch on YouTube:

[![Michał Sołtysik - Deep Packet Inspection Analysis - Examining One Packet Killers (ENG)](https://i1.ytimg.com/vi/SgrgnwtIT50/mqdefault.jpg)](https://www.youtube.com/watch?v=8cX7Fn5AM04)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - Remcos RAT threat analysis on Windows including IEC 60870-5-104 traffic (ENG):


Title of the lecture: Remcos RAT threat analysis on Windows including, surprisingly enough, IEC 60870-5-104 traffic.

Description of the lecture: Typically, malware uses popular protocols such as HTTP or TLS to exfiltrate data. However, Remcons uses IEC 60870 part 5, which provides a communication profile for sending basic telecontrol messages between two systems usually in electrical engineering and power system automation, for that very reason.


Content:

Remcos analysis

IEC 60870-5-104 traffic analysis


URL: https://www.youtube.com/watch?v=4fc_NcJxIyw

Click to watch on YouTube:

[![Michał Sołtysik - Remcos RAT threat analysis on Windows including IEC 60870-5-104 traffic (ENG)](https://i1.ytimg.com/vi/SgrgnwtIT50/mqdefault.jpg)](https://www.youtube.com/embed/4fc_NcJxIyw)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Author:

Michał Sołtysik

Cybersecurity Analyst & Consultant

Specializing in deep packet inspection (i.e. network edge profiling and 0-day attacks).

To date, he has identified 254 protocols in the IT, OT and IoT areas used for cyber attacks.

Additionally, a Digital and Network Forensics Examiner, CyberWarfare Organizer and SOC Trainer.


CM)CTA - Certified Master Cyber Threat Analyst

CySA+, C)CSA & C3SA - Certified Cyber Security Analyst

CCDA - Certified Cyber Defense Analyst

C|SA - Certified SOC Analyst

PSAA - Practical SOC Analyst Associate

CM)CFI - Certified Master Cyber Forensic Investigator

GNFA - GIAC Network Forensic Analyst

C)NFE - Certified Network Forensics Examiner

C)DFE - Certified Digital Forensics Examiner

eCDFP - eLearnSecurity Certified Digital Forensics Professional

ISO/IEC 27037:2012 - Lead Implementer

WCNA - Wireshark Certified Network Analyst

C|ND - Certified Network Defender

CCD - Certified CyberDefender

C)ISSO - Certified Information Systems Security Officer

C)PTC - Certified Penetration Testing Consultant

C)PTE - Certified Penetration Testing Engineer

C)PEH - Certified Professional Ethical Hacker

C)VA - Certified Vulnerability Assessor

RvBCWP - Red vs Blue Cyber Warfare Practitioner

CM)IPS - Certified Master Intrusion Prevention Specialist

eCTHP - eLearnSecurity Certified Threat Hunting Professional

C)TIA - Certified Threat Intelligence Analyst

CIoTSP - Certified Internet of Things Security Practitioner

OOSE - OPSWAT OT Security Expert

CNSP - Certified Network Security Practitioner

CNSE - Certified Network Security Engineer

CCC - Certified Cybersecurity Consultant

CCE - Certified Cybersecurity Expert

CCSS - Certified Cyber Security Specialist


Issued by GIAC (associated with SANS Institute), Mile2, EC-Council, CompTIA, INE Security, TCM Security, CyberWarFare Labs, CyberDefenders, The SecOps Group, CertNexus, OPSWAT Academy, Protocol Analysis Institute (WCNA Certification Program), United States Cybersecurity Institute, Pacific Certifications, Blockchain Council and Global Tech Council.


Accredited by ANAB under ISO/IEC 17024.

Accredited by the NSA CNSS 4011-4016.

Accredited by ABIS under ISO/IEC 17011.

Approved by DoD under Directive 8570 (previously) / 8140 (presently).

Mapped to NIST / Homeland Security NICCS's Cyber Security Workforce Framework.

Mapped to NCWF (NICE Cybersecurity Workforce Framework).

Approved on the FBI Cyber Security Certification Requirement list (Tier 1-3).

Recognized by NCSC - part of GCHQ (UK's intelligence, security, and cyber agency).


Contact:

Official website: https://michalsoltysik.com/

Mail: me@michalsoltysik.com

LinkedIn: https://www.linkedin.com/in/michal-soltysik-ssh-soc/

Cybersecurity content: https://www.youtube.com/playlist?list=PL0RdRWQWldOAAKBqOVEutxKMP-a6CNoLY

Accredible: https://www.credential.net/profile/michalsoltysik/wallet

Credly: https://www.credly.com/users/michal-soltysik

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
