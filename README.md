-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Cybersecurity content (in English and Polish):

https://www.youtube.com/playlist?list=PL0RdRWQWldOAAKBqOVEutxKMP-a6CNoLY

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - How Web Protocol Weaknesses Enable Layer 7 DoS Attacks (ENG):

<br>

Title of the lecture: How Web Protocol Weaknesses Enable Layer 7 DoS Attacks.

Description of the lecture: This presentation delves into the inherent vulnerabilities within the design of web protocols which indirectly expose web pages to Layer 7 Denial-of-Service (DoS) attacks - regardless of the use of modern transport encryption mechanisms (e.g., WTLS, DTLS, TLS 1.2/1.3, or (G)QUIC). We'll meticulously dissect the specific weaknesses of the Internet Cache Protocol (ICP) and explore how it can be weaponized to circumvent security measures. Our analysis will further delve into the vulnerabilities residing within the handshake processes of DTLS, (G)QUIC, TLS 1.2/1.3, and WTLS. This session will provide valuable insights for security professionals and web developers, highlighting the importance of layered security strategies beyond encryption protocols to defend against DoS attacks.

<br>

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

<br>

URL: https://www.youtube.com/watch?v=_xP7_BnZCts

Click to watch on YouTube:

[![Michał Sołtysik - How Web Protocol Weaknesses Enable Layer 7 DoS Attacks (ENG)](https://github.com/MichalSoltysikSOC/Cybersecurity-content-videos/blob/main/screenshots/ENG_YouTube_avatar_ECC_CyberTalks_Again.png)](https://www.youtube.com/watch?v=_xP7_BnZCts)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - Deep packet inspection analyses - why the typical approach is not enough (ENG):

<br>

Title of the lecture: Deep packet inspection analyses: why the typical approach is not enough.

Description of the lecture: There is an unquestionable need to perform regular deep packet inspection analyses, i.e. network edge profiling. Providing standard SOC type services that use tools, such as SIEM, SOAR, IPS, WAF, EDR and others leads to a partial waste of human resources due to the constant dealing with the so-called "false positives". The cybersecurity industry is currently characterized by superficiality, insufficient competence and low cyber awareness. Cybercriminals are in possession of hundreds of mechanisms that they regularly take advantage of to break through firewalls. In this lecture, I will present an advanced view of the realities that teams such as SOC are unable to deal with, and explain why this is the case. I will use extensive knowledge of a variety of threats, based on analysis of 252 different network protocols from the areas of IT, OT and IoT.

<br>

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

<br>

URL: https://www.youtube.com/watch?v=_ulFvQ1z7j8

Click to watch on YouTube:

[![Michał Sołtysik - Deep packet inspection analyses - why the typical approach is not enough (ENG)](https://github.com/MichalSoltysikSOC/Cybersecurity-content-videos/blob/main/screenshots/ENG_YouTube_avatar_THS.png)](https://www.youtube.com/embed/_ulFvQ1z7j8)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - Deep Packet Inspection Analysis - Examining One Packet Killers (ENG):

<br>

Title of the lecture: Deep Packet Inspection Analysis: Examining One Packet Killers.

Description of the lecture: Security Operations Center (SOC) teams monitor network traffic using SIEM and IPS solutions, along with other security tools. However, these tools can sometimes fall short in their capability, particularly when faced with complex attacks that exploit legitimate network protocols, such as a single, crafted packet. To combat these threats, SOC teams must adopt advanced techniques such as Deep Packet Inspection (DPI). The webinar explores DPI analysis techniques to detect and mitigate "One Packet Killers", using real-world examples from DHCP, H.225.0, Modbus over TCP, WTP, and BAT_GW protocols. Furthermore, it examines the intricacies of each protocol and highlights how specific message manipulations within these protocols can activate Denial-of-Service (DoS) attacks or disrupt communication flows. By mastering DPI techniques and addressing these protocol security weaknesses, SOC teams can enhance their ability to maintain a robust network security posture.

<br>

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

<br>

URL: https://www.youtube.com/watch?v=8cX7Fn5AM04

Click to watch on YouTube:

[![Michał Sołtysik - Deep Packet Inspection Analysis - Examining One Packet Killers (ENG)](https://github.com/MichalSoltysikSOC/Cybersecurity-content-videos/blob/main/screenshots/ENG_YouTube_avatar_ECC_CyberTalks.png)](https://www.youtube.com/watch?v=8cX7Fn5AM04)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Michał Sołtysik - Remcos RAT threat analysis on Windows including IEC 60870-5-104 traffic (ENG):

<br>

Title of the lecture: Remcos RAT threat analysis on Windows including, surprisingly enough, IEC 60870-5-104 traffic.

Description of the lecture: Typically, malware uses popular protocols such as HTTP or TLS to exfiltrate data. However, Remcons uses IEC 60870 part 5, which provides a communication profile for sending basic telecontrol messages between two systems usually in electrical engineering and power system automation, for that very reason.

<br>

Content:

Remcos analysis

IEC 60870-5-104 traffic analysis

<br>

URL: https://www.youtube.com/watch?v=4fc_NcJxIyw

Click to watch on YouTube:

[![Michał Sołtysik - Remcos RAT threat analysis on Windows including IEC 60870-5-104 traffic (ENG)](https://github.com/MichalSoltysikSOC/Cybersecurity-content-videos/blob/main/screenshots/ENG_YouTube_avatar_IEC_60870-5-104.png)](https://www.youtube.com/embed/4fc_NcJxIyw)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Author: Michał Sołtysik

Cybersecurity Consultant and Blue Team, Purple Team, and Red Team Analyst, bringing a broad and in-depth range of expertise to his cybersecurity practice.

He is also a Digital and Network Forensics Examiner, Cyber Warfare Organizer, and SOC Trainer, specializing in SOC operational capability and maturity development, network edge traffic profiling, and adversary emulation in EDR testing.

<br>

CM)CTA - Certified Master Cyber Threat Analyst

CySA+, C)CSA & C3SA - Certified Cybersecurity Analyst

CCDA - Certified Cyber Defense Analyst

HTB CDSA - Hack The Box Certified Defensive Security Analyst

C|SA - Certified SOC Analyst

PSAA - Practical SOC Analyst Associate

CBTeamer - Certified Blue Teamer

CBTP - Certified Blue Team Practitioner

CM)CFI - Certified Master Cyber Forensic Investigator

GCFA - GIAC Certified Forensic Analyst

GNFA - GIAC Network Forensic Analyst

C)NFE - Certified Network Forensics Examiner

C)DFE - Certified Digital Forensics Examiner

eCDFP - eLearnSecurity Certified Digital Forensics Professional

CDFEH - CYBER 5W Digital Forensics Evidence Handler

ISO/IEC 27037:2012 - Lead Implementer

WCNA - Wireshark Certified Network Analyst

GCED - GIAC Certified Enterprise Defender

C|ND - Certified Network Defender

CCD - Certified CyberDefender

C)ISSO - Certified Information Systems Security Officer

CPTA - Certified Purple Team Analyst

HTB CPTS - Hack The Box Certified Penetration Testing Specialist

C)PTC - Certified Penetration Testing Consultant

C)PTE - Certified Penetration Testing Engineer

C)PEH - Certified Professional Ethical Hacker

C)VA - Certified Vulnerability Assessor

RvBCWP - Red vs Blue Cyber Warfare Practitioner

CM)IPS - Certified Master Intrusion Prevention Specialist

eCTHP - eLearnSecurity Certified Threat Hunting Professional

CRTA - Certified Red Team Analyst

C)TIA - Certified Threat Intelligence Analyst

CIoTSP - Certified Internet of Things Security Practitioner

OOSE - OPSWAT OT Security Expert

CNSP - Certified Network Security Practitioner

CNSE - Certified Network Security Engineer

CCC - Certified Cybersecurity Consultant

CCE - Certified Cybersecurity Expert

CCSS - Certified Cyber Security Specialist

<br>

Issued by GIAC (associated with SANS Institute), Mile2 Cybersecurity Institute, EC-Council, CompTIA, HTB Academy, INE Security, TCM Security, CyberWarFare Labs, CyberDefenders, Cyber5W, The SecOps Group, CertNexus, OPSWAT Academy, Protocol Analysis Institute (WCNA Certification Program), United States Cybersecurity Institute, Pacific Certifications, Blockchain Council and Global Tech Council.

<br>

Accredited by ANAB (ANSI National Accreditation Board - the largest multi-disciplinary accreditation body in North America and a wholly owned subsidiary of ANSI, the American National Standards Institute), in accordance with ISO/IEC 17024.

Accredited by the National Security Agency (NSA) and the Committee on National Security Systems (CNSS) under the CNSS 4011-4016 training standards.

Accredited by ABIS (Accreditation Board for International Standards) in compliance with ISO/IEC 17011.

Approved by the U.S. Department of Defense (DoD) under Directive 8570 (superseded) and currently under Directive 8140.

Mapped to the National Institute of Standards and Technology (NIST) and the U.S. Department of Homeland Security's (DHS) National Initiative for Cybersecurity Careers and Studies (NICCS) Cybersecurity Workforce Framework.

Mapped to the NICE Cybersecurity Workforce Framework (NCWF).

Integrated into the U.S. Department of Defense (DoD) Cyber Mission Force Persistent Cyber Training Environment (PCTE).

Recognized within the Federal Risk and Authorization Management Program (FedRAMP) 3PAO personnel qualification requirements (RFC-0002, Sections 6.1.1 F.2 and 6.1.1 F.3), aligned with the U.S. Department of Defense (DoD) 8140 Cyber Workforce Qualification Program.

Approved on the Federal Bureau of Investigation (FBI) Cybersecurity Certification Requirements list (Tiers 1–3).

Recognized by the National Cyber Security Centre (NCSC), part of GCHQ (Government Communications Headquarters - the UK's intelligence, security, and cyber agency).

<br>

Contact:

Official website: https://michalsoltysik.com/

Mail: me@michalsoltysik.com

LinkedIn: https://www.linkedin.com/in/michal-soltysik-ssh-soc/

Cybersecurity content: https://www.youtube.com/playlist?list=PL0RdRWQWldOAAKBqOVEutxKMP-a6CNoLY

Accredible: https://www.credential.net/profile/michalsoltysik/wallet

Credly: https://www.credly.com/users/michal-soltysik

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
