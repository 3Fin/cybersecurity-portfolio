Welcome to My Cybersecurity Portfolio
## 1. About Me
I am a cybersecurity student with a strong interest in network security, cybersecurity operations, and the practical application of security technologies. I enjoy exploring how computer networks operate, understanding potential security risks, and learning how different security mechanisms protect systems and data. Through coursework and hands-on laboratory exercises, I have been developing my knowledge of networking, system administration, and cybersecurity fundamentals. My learning experiences include network configuration, access control, firewall concepts, network traffic analysis, and security monitoring. I am particularly interested in network defence, threat detection, and security analysis. This portfolio documents my technical development, practical projects, laboratory experiences, and continuous learning journey as I work towards a career in the cybersecurity industry.

## 2. Technical Skills
My current skills are listed with self-assessment levels. Beginner means I can complete introductory exercises with guidance. Working knowledge means I can apply the fundamentals in familiar coursework and laboratory tasks.

| Skill | Current level | Evidence or learning context |
| --- | --- | --- |
| Linux and Windows fundamentals | Working knowledge | Coursework and Kali laboratory use |
| TCP/IP, IP addressing and subnetting | Working knowledge | [TCP and DNS investigation]({{ '/projects/network-traffic-analysis/' | relative_url }}) |
| VLANs, routing and switching | Working knowledge | Cisco Packet Tracer coursework |
| Access Control Lists and port security | Working knowledge | Networking security coursework |
| Firewall concepts | Working knowledge | Course laboratory exercises |
| VPN fundamentals | Beginner | Introductory coursework |
| Wireshark and TShark | Beginner | [Packet capture and protocol analysis]({{ '/projects/network-traffic-analysis/' | relative_url }}) |
| Snort 3 | Beginner | [Custom rules and alert analysis]({{ '/projects/snort-intrusion-detection/' | relative_url }}) |
| Nmap | Beginner | Introductory tool learning |
| Python | Beginner | Fundamental programming study |
| Cisco Packet Tracer | Working knowledge | Network configuration coursework |
| Git and GitHub | Working knowledge | Portfolio commits, branches and merged pull requests |
| Network traffic analysis and security monitoring | Beginner | Both documented portfolio projects |
| Troubleshooting | Working knowledge | Documented Wireshark display and Snort capture-file troubleshooting |

## 3. Certifications and Training
This section highlights my cybersecurity certifications, training, and continuous professional development.
- **Certification:** NISP Level 2 Certificate (National Information Security Professional)
- **Coursework:** Cybersecurity and computer networking subjects.
- **Practical Training:** Network configuration, security laboratory exercises, and troubleshooting.
- **Independent Learning:** Exploring cybersecurity tools, network defence techniques, and security analysis.

I continue to expand my technical knowledge through hands-on practice, academic learning, and independent cybersecurity study.

## 4. Projects
This portfolio contains practical projects developed in controlled laboratory environments.

### Project 1: Network Traffic Analysis and Protocol Investigation Using TShark
Completed on 19 November 2026. I used TShark, Wireshark's command-line analyzer, to investigate TCP connections, HTTP communication, and DNS resolution. The report includes original captures, screenshots, protocol analysis, and checksum-verified evidence.

[View Project]({{ '/projects/network-traffic-analysis/' | relative_url }})

### Project 2: Network Intrusion Detection and Alert Analysis Using Snort 3
Completed laboratory experiments on 19 November 2026 using Snort 3.12.2.0. I validated two custom rules, compared ordinary and marked HTTP requests, and recorded three custom alerts during live loopback monitoring. The report includes rules, configuration snapshots, captures, and verified logs.

[View Project]({{ '/projects/snort-intrusion-detection/' | relative_url }})

Both projects have completed laboratory experiments and documented results. HTTP traffic was generated on the Kali loopback interface, and DNS resolution used the VM's configured resolver.

## 5. Learning Journey
My cybersecurity learning journey has gradually developed from understanding networking fundamentals to exploring network security mechanisms and practical security analysis. Through coursework and laboratory exercises, I have learned how devices communicate, how networks are structured, and how security controls can be implemented to protect network resources.

One of the important areas I have studied is network configuration and communication. I have practised IP addressing, subnetting, VLAN configuration, routing, and switching using Cisco Packet Tracer. These exercises helped me understand how devices communicate across different network segments and how network infrastructure can be organised. I also learned that incorrect configurations can affect connectivity and that systematic verification is important when troubleshooting network problems.

I have also explored several network security mechanisms, including Access Control Lists (ACLs), port security, firewall configuration, and VPN fundamentals. Through laboratory exercises, I developed a better understanding of how access restrictions can control traffic, how port security can limit unauthorised devices, and how firewalls can enforce network security policies. Configuring and verifying these technologies helped me connect theoretical networking concepts with practical security implementations.

Troubleshooting has been an important part of my learning experience. During network configuration exercises, I encountered connectivity problems and configuration errors that required me to inspect device settings, verify interfaces, check addressing information, and test network communication. These experiences taught me not to rely on assumptions. Instead, I should examine the configuration, identify possible causes, test changes systematically, and verify whether the problem has been resolved.

Although I have gained experience with network configuration and security fundamentals, I still need to improve my understanding of packet-level analysis, intrusion detection, and the interpretation of security events. I want to become more confident in identifying suspicious network behaviour and understanding how detection systems distinguish normal traffic from potentially malicious activity.

In my traffic analysis project, Wireshark failed to start because it could not connect to the graphical display. I identified the display connection error and switched to TShark. I verified the solution by saving and reading TCP, HTTP, and DNS captures. I documented a rejected connection, a successful handshake, an HTTP response, and a matching DNS query-response pair. In my Snort 3 project, I compared ordinary and marked requests. The marker rule triggered only for the marked sample, while the baseline rule matched both. This taught me to evaluate a rule against controls and interpret alerts in context.

By 3 December 2026, I will complete three additional Snort rule test cases covering header capitalization, whitespace changes, and segmented TCP delivery. For each case, I will save the capture, rule version, expected result, observed alert count, and a short explanation. I will measure completion by publishing all three documented comparisons and explaining each result, including any missed matches. This goal will help me understand how signature design and protocol processing affect detection.

## 6. Career Objective
My career objective is to become an entry-level Security Operations Center (SOC) Analyst, with a focus on network security monitoring and threat detection. I aim to build a strong technical foundation and develop the practical skills required to investigate security events, analyse network traffic, identify potential threats, and support defensive security operations.

I will take three steps toward this role. First, I will strengthen my networking and Linux knowledge through regular laboratory practice. Second, I will extend my TShark and Snort projects with additional control tests and clearer analysis of detection limitations. Third, I will practise security alert triage through relevant training and controlled exercises, documenting how I examine evidence and decide what needs further investigation. In the future, I hope to contribute to a cybersecurity team by applying technical knowledge, analytical thinking, and continuous learning to real-world security challenges.

## 7. Contact Information
- **GitHub:** [3Fin](https://github.com/3Fin)
- **Portfolio:** [Cybersecurity Portfolio](https://3Fin.github.io/cybersecurity-portfolio/)
- **LinkedIn:** [LinkedIn profile](https://www.linkedin.com/in/%E6%80%9D%E5%90%8D-%E9%99%88-9365a3450/)
