# Report: Melissa Virus
## Andrew McGowan

## Table Of Contents:

- [Executive Summary](#executive-summary)
- [Victims of the Attack](#victims-of-the-attack)
- [Technologies and Tools Used](#technologies-and-tools-used)
- [Timeline of the Attack](#timeline-of-the-attack)
- [Systems Targeted](#systems-targeted)
- [Motivations and Objectives of the Attack](#motivations-and-objectives-of-the-attack)
- [Attack Outcomes](#attack-outcomes)
- [Mitigation Techniques](#mitigation-techniques)
- [Security Controls](#security-controls)
- [Conclusion](#conclusion)
- [References](#references)

## [Executive Summary](#executive-summary)
The Melissa virus is a macro virus that appeared in March 1999. It is considered one of the most notorious email viruses in cybersecurity history. It was created by David L. Smith. Using social engineering and the macro functions found in Microsoft Word, it was able to spread rapidly through email. The name “Melissa” comes after the name of an exotic dancer Smith knew in Florida. The virus began its distribution on a Usenet newsgroup called “alt.sex.” It was disguised in a file that contained login credentials to various adult websites. This would entice users to download and open the Word Document.

Melissa used vulnerabilities in Microsoft Word and Outlook to spread quickly and cause significant disruptions around the world. In this report, we are going to go into more detail on the attack, victims, tools, technologies, targeted systems, timeline, motivations, outcomes, and mitigation techniques.

## [Victims of the Attack](#victims-of-the-attack)
Melissa’s main victims were individuals and companies using Microsoft Outlook as an email client. Victims included:
- **Large companies:** Microsoft, Intel, and Lucent Technologies experienced large email disruptions, severe slowdowns, and, in some cases, temporary email server shutdowns.
- **Government:** The U.S. Military (all branches), The Pentagon, The U.S. Department of Justice, The U.S. Department of Defense, and several others were affected by the virus. Infected email servers and networks caused delays in operations, hindering effective communication and government processes.
- **Education:** Universities and schools, which relied heavily on email communication, experienced slowdowns and email outages, leading to administrative and academic issues.
- **Individuals:** Microsoft Outlook users' email accounts were also victims. Rapid spreading of the virus through personal contacts created a bad situation, causing widespread disruptions.

## [Technologies and Tools Used](#technologies-and-tools-used)
- **Macro Virus (MITRE ATT&CK: T1204.002 - User Execution: Malicious File):** Melissa was a macro virus that infected Microsoft Word documents. When the document was opened, the virus deployed its payload, the malicious macro, causing the virus to spread.
- **Microsoft Outlook (MITRE ATT&CK: T1071.001 - Application Layer Protocol: Web Protocols):** Melissa spread through the use of Microsoft Outlook, sending itself to the first 50 contacts in the victim's address book. This allowed it to spread quickly through email networks, exploiting the trust between email contacts.
- **Email Attachments (MITRE ATT&CK: T1566.001 - Phishing: Spearphishing Attachment & T1566 - Phishing):** Infected word documents were sent as email attachments. The subject lines were designed to trick recipients with messages such as "Important Message From [Sender]" and "Here's that document you asked for, ;)".

## [Timeline of the Attack](#timeline-of-the-attack)
- **March 26, 1999:** First detection of Melissa. It spread to tens of thousands of systems within hours, causing email servers and networks to become overwhelmed and leading to widespread disruptions.
- **March 26 - 29, 1999:** The virus spread more rapidly, overwhelming major email servers with traffic. Companies like Microsoft and Intel temporarily shut down email servers to mitigate the spread. The virus generated immense email traffic, causing slowdowns and outages.
- **April 1, 1999:** The FBI arrested and charged David L. Smith, the creator of the Melissa virus, with causing damage to computer networks. The arrest was a significant milestone in cybersecurity, highlighting the impact of malware creation and distribution.

## [Systems Targeted](#systems-targeted)
- **Microsoft Word and Outlook:** Melissa targeted the macro capabilities of Word and the email functionality of Outlook. The widespread use of both made them ideal targets, leading to the virus's successful spread.
- **Email Servers:** Email servers were particularly affected due to the virus's mass-mailing nature. Overwhelmed email servers caused significant slowdowns and outages, leading to widespread network congestion.

## [Motivations and Objectives of the Attack](#motivations-and-objectives-of-the-attack)
- **Demonstration of Technical Skill:** Melissa was likely Smith’s attempt to showcase his technical abilities and knowledge of macro programming, demonstrating how macros could be used maliciously.
- **Disruption:** Melissa caused global disruption, highlighting vulnerabilities in widely-used software and creating chaos. The impact and rapid spread emphasized the need for better security awareness and measures.

## [Attack Outcomes](#attack-outcomes)
- **Widespread Email Disruptions:** Melissa caused significant disruptions, forcing many companies to shut down email servers temporarily to contain the virus. Overwhelmed servers generated massive email traffic, leading to network congestion and slowdowns.
- **Financial Losses:** Melissa caused an estimated $80 million in financial impact due to productivity loss and mitigation efforts. Companies invested in additional resources to contain and remove the virus.
- **Legal Consequences:** Smith was arrested and convicted, receiving a 20-month federal prison sentence and a $5,000 fine. His arrest and conviction demonstrated the consequences of creating and distributing malware.

## [Mitigation Techniques](#mitigation-techniques)
- **Robust Email Security Measures:** Implement email filtering to prevent suspicious attachments and educate users on the risks of opening unknown email attachments to prevent receiving or opening malicious emails.
- **Antivirus Software:** Use antivirus software to detect and block malicious macros. Ensure regular updates to stay ahead of new vulnerabilities and prevent malware from causing significant damage.
- **Software Updates and Patches:** Keep software up to date with the latest patches to close vulnerabilities exploited by viruses. Regular updates reduce the risk of exploitation.
- **Education:** Regularly train users on safe email practices and the risks of opening unfamiliar attachments. User education helps prevent falling victim to social engineering attacks such as phishing.

## [Security Controls](#security-controls)
- **Filtering Emails:** Use filtering solutions to detect and block malicious attachments. Configure email servers to scan for threats in incoming and outgoing emails to prevent malicious emails from reaching users.
- **Macros Disabled by Default:** Disable macros by default in Microsoft Office. Educate users to enable macros only from trusted sources to prevent executing malicious macros unknowingly.
- **Incident Response Plan (IRP):** Develop and implement an IRP to quickly address and mitigate malware outbreaks. An IRP helps companies respond to incidents effectively and efficiently.
- **Regular Vulnerability Assessments (RVA):** Conduct RVA to identify and address security weaknesses in the network. Regular assessments help companies address vulnerabilities before they can be exploited.

## [Conclusion](#conclusion)
The Melissa virus served as a wake-up call for the cybersecurity world, highlighting the potential for global disruption from a macro virus. Understanding the impact of such attacks allows for the implementation of mitigation techniques and security controls to prevent future incidents.

## [References](#references)
- [FBI. (2019, March 25). The Melissa Virus. FBI. Retrieved June 20, 2024](https://www.fbi.gov/news/stories/melissa-virus-20th-anniversary-032519)
- [F-Secure. (n.d.). Virus:W32/Melissa. F-Secure. Retrieved June 20, 2024](https://www.f-secure.com/v-descs/melissa.shtml)
- [Gillis, A. S. (n.d.). Melissa Virus. TechTarget. Retrieved June 20, 2024](https://www.techtarget.com/searchsecurity/definition/Melissa-virus)
- [Lemos, R. (2005, March 29). Melissa's long gone, but lessons remain. CNET. Retrieved June 20, 2024](https://www.cnet.com/news/privacy/melissas-long-gone-but-lessons-remain/)
- [Malicious Life podcast. (2021, February 9). The Melissa Virus [Video]. YouTube. Retrieved June 20, 2024](https://www.youtube.com/watch?v=-KrjPxBygz4)
- [NationSquid. (2022, August 20). The Email That Took Down the Military | The Melissa Virus [YouTube video] [Video]. Retrieved June 20, 2022](https://www.youtube.com/watch?v=Nl8M8SF6Db0)
- [symantec. (1999, March 26). W97M.Melissa.A. symantec. Retrieved June 20, 2024](https://web.archive.org/web/20061110161357/http://www.symantec.com/security_response/writeup.jsp?docid=2000-122113-1425-99)
- [Wikipedia. (2024, April 27). alt.sex. Wikipedia. Retrieved June 20, 2024](https://en.wikipedia.org/wiki/Alt.sex)
- [Wikipedia. (2024, June 7). Melissa (computer virus). Wikipedia. Retrieved June 20, 2024](https://en.wikipedia.org/wiki/Melissa_(computer_virus))
