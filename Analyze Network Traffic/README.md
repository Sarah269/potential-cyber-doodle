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
