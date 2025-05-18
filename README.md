# Document-Enterprise-Issue
CISCO Network Defense First-Lab

<h2>🎫Scenario</h2>

Athena Learning Incorporated is an educational service provider. Athena has two major lines of business: course content creation and online learning services. Athena creates learning content and hosts learning content. Athena also provides internet sales services that enable its partners to charge their students to attend their courses.

Athena employs about 100 people in its headquarters office, and about 5 people each in its London and Singapore offices. Because it provides content and delivery services globally, Athena must comply with diverse privacy and security standards.

Athena serves as custodian for its own content and content that belongs to its partners. That content includes text, graphic, video, and interactive assets. This content is the essential intellectual property of the company. It also manages student account information including student registration, authentication, records, and payment information. Athena manages its own SQL databases, some of which are connected to web portals.

The Athena network consists of mostly MS Windows and Apple IOS clients with a mix of Microsoft and Linux servers to store business and employee records, learning content assets, and financial information, including customer data. The hosts include various PC brands and models of varying age. Different versions of operating systems are in use. Athena uses cloud services to deliver courses to the public, but must house assembled courses on the internal network for creation and editing. When the courses become available, they are mirrored to the cloud. Employees are permitted to use their personal phones and tablets for work. In addition, some employees work from home, but require full network access to do so. Athena also hosts its own DNS, email, and intranet services.

Athena employees use common office application software, custom applications, and tools that have been created internally.

Athena provides access to parts of its internal network to its partners through a secure web portal. Clients are able to preview their course content and deliver course assets to Athena for assembly in the Athena learning management system. Students interact with the cloud-managed learning platform through their web account logins.

In this lab, you will apply your knowledge of cybersecurity threats and mitigation techniques to a corporate setting. You will read about a business, classify its assets, and then list the potential vulnerabilities and threats that the business faces. Finally, you will recommend threat mitigation measures for the threats that you identify

<h2>Part 1: Record your assessment of Athena's cybersecurity issues.</h2>

`Note: All table content is my answers.`

| Information/Data Assets  | Threats | Mitigation |
| :-------------: | :-------------: | :-------------: |
| Employee Information  | Malicious Employee, BlackHat  | Encrypt data,MFA,Minimal Privilege,Use History ,Hardening Layers   |
| Costumer Information  | Malicious Employee, BlackHat  | Encrypt data,MFA,Minimal Privilege,Use History ,Hardening Layers   |
| Confidential Information  | Malicious Employee, BlackHat  | Encrypt data,MFA,Minimal Privilege,Use History ,Hardening Layers   |
| Financial Information  | Malicious Employee, BlackHat  | Encrypt data,MFA,Minimal Privilege,Use History ,Hardening Layers |
| Learning Content  | Malicious Employee, BlackHat  | Encrypt data,Hardening Layers  |

| Software Assets  | Threats | Mitigation |
| :-------------: | :-------------: | :-------------: |
| MS Windows  | Outdated Software, Malware, Phishing  | Update System  |
| Apple IOS  | Outdated Software, Malware, Phishing   | Update System  |
| SQL  | SQL Injection  | Better life cycle of software, implementing a better code  |
| Applications  | Outdated Software  | Update System and policy  |
| Web Portal  | XSS  | Better life cycle of software, implementing a better code  |

| Physical Assets  | Threats | Mitigation |
| :-------------: | :-------------: | :-------------: |
| PC  | Outdated Versions  | Update System  |
| Database  | DDoS, No energy  | Firewall, Additional Energy  |
| Internet  | No energy, Physical Issue | Additional Energy, backup devices  |


| Network Access | Threats | Mitigation |
| :-------------: | :-------------: | :-------------: |
| DNS service  | DNS Spoofing, Tunneling or Hijack  | DNS firewall or NGFW, MFA settings |
| Email Service  | Phishing, Whaling  | MFA, Email Filter  |
| Intranet Service  | Weak Password, Unauthorised access  | Minimal privilege, password rules  |
| Remote Access  | Man in the middle  | VPN , MFA  |

<h2>Part 2:</h2>

`What is the difference between a threat and a vulnerability?`

A threat is something that can potentially make damage to something like a thief or a employee untrained.
Vulnerability is something like a door open, everyone can enter right? But is not a risk if no one wants to enter. Sometimes vulnerability is a outdated software or OS, sometimes its a port open.
Additionally, risk is how likely it is that a threat will exploit a vulnerability.

<h2>💭Reflection: </h2>

`1. Why is it useful to categorize assets when identifying threats and mitigation techniques?`

By thinking about possible threats to your company or project, you can better understand what to protect and how.

`2. Do some threats have the same or similar mitigation measures? Why is it important to note this?`

Yes, some measures fit into several types of attack, this is important because it shows how significant it is to implement new security measures, as it greatly reduces the attack window.

`3. What have you learned about the application of knowledge of cybersecurity threats and mitigation techniques to the context of a simulated organization?`

In practice, I was able to better see the various types of threats. Of course, I was unable to identify them all, but with continued study I hope to be able to better see the different possibilities.



