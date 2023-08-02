# potential-cyber-doodle

This repository is dedicated to cybersecurity

<p><b>Project:  Enabling and configuring Microsoft Firewall</b><p>
<p>Purpose:  To prevent access from hackers and malware</p>
Actions:  

* Block incoming/outgoing protocols except TCP & UDP
* Block selected TCP/UCP outgoing ports.  
* Block incoming/outgoing traffic for malicious IPs.
* Block incoming/outgoing traffic for selected windows programs

Tools: Windows Firewall, Malwarebytes Windows Firewall Control  
Insight: Ongoing monitoring of firewall logs required: allowed incoming, blocked incoming, allowed outgoing, blocked outgoing


<p><b>Project:  Analyzing Network Traffic using Wireshark</b></p>
<p>Purpose:  To identify susipicous activity</p>
Actions:   

* Filtered capture dumps to look at HTTPS,UDP, or DNS traffic
* Filtered on number of DNS answer counts
* Researched IPs with a lot of retransmissions using Virustotal and www.abuseipdb.com
* Researched URLs associated with DNS requests using Virustotal

Tools:  Wireshark, Virustotal, www.abuseipdb.com

Observations:  
* Observed a lot of retransmissions
* Found several URLs returning a high number of DNS answers.  Expected 5 or less however, found 12 or more answers.
* Identified four IPs that were classified as malicious or malware by one or more Virustotal anti-virus engines

  
