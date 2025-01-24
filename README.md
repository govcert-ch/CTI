![](images/swiss-cybercow.png)

# GovCERT.ch Cyber Threat Intelligence
In this directory we post technical cyber threat Intelligence and provide it as is under TLP:CLEAR.

##  📗 Table of Contents

* [OffensiveCIDRs/Bruteforce.csv](OffensiveCIDRs/Bruteforce.csv): Contains top CIDRs (/24) involved in bruteforce attacks against O365 and edge devices (such as SSL-VPNs). You may not expect any legitimate traffic from these sources towards any internal ressources. 
* * [OffensiveCIDRs/Bruteforce_CIDR-only](OffensiveCIDRs/Bruteforce_CIDR-only.csv): This list contains the same data as [OffensiveCIDRs/Bruteforce.csv](OffensiveCIDRs/Bruteforce.csv) but just the CIDRs (no additional information such as ASN on geo location). You may want to use this list in an automated manner for mitigating bruteforce attacks against O365 and edge devices (such as SSL-VPns).
* [20250120_NoName057-DDoS-CH_CIDR-with-info.csv](20250120_NoName057-DDoS-CH_CIDR-with-info.csv): Contains top CIDRs (/24) that participated in DDoS attacks in the week of 2025-01-20 (week #4) against Swiss targets. These attacks were allegedly conducted by hacktivist group NoName057(16), using L7 attacks (HTTP/s GET flood). GovCERT.ch has contacted the abuse desks of the relevant network owners (AS) and asked them to take the appropriate actions to prevent further abuse of their service.
* [20250120_NoName057-DDoS-CH_CIDR-only.csv](20250120_NoName057-DDoS-CH_CIDR-only.csv): This list contains the same data as [20250120_NoName057-DDoS-CH_CIDR-with-info.csv](20250120_NoName057-DDoS-CH_CIDR-with-info.csv) but just the CIDRs (no additional information such as ASN on geo location). You may want to use this list in an automated manner for temporarily blocking and mitigating NoName057(16) L7 DDoS attacks. Please consider that blocking CIDRs will probably cause false positives. We therefore recommend you to only block those if you are under attack and as a temporary measure.
* [20241010_GorillaBot](20241010_GorillaBot): Contains a report and IoCs from the analysis of the GorillaBot DDoS-as-a-Service Malware and Infrastructure.
* [20240627_macOS_PoseidonStealer](20240627_macOS_PoseidonStealer): Contains information about a Poseidon Stealer malspam campaign targeting Swiss macOS users and the related MISP Event. 
* [20240615_NoName057-attacking-ips.csv](20240615_NoName057-attacking-ips.csv): Contains IPv4 addresses that allegedly participated in DDoS attacks on 2024-06-14 and 2024-06-15 against Swiss targets. These attacks were conducted by hacktivist group NoName057(16), using L7 attacks (HTTP/s GET flood). The majority of the IP addresses belong to VPN service providers that got misused by NoName057(16) for launching DDoS attacks.
* [20240615_NoName057-controller-ips.csv](20240615_NoName057-controller-ips.csv): Contains IPv4 addresses that allegedly were used in June 2024 by NoName057(16) to command and control their DDoS tool called "DDoSia".
* [20240117_NoName057-DDoS-CH.csv](20240117_NoName057-DDoS-CH.csv): Contains IPv4 addresses that participated in DDoS attacks on 2024-01-17 against Swiss targets. These attacks were allegedly conducted by hacktivist group NoName057(16), using L7 attacks (HTTP/s GET flood). GovCERT.ch has contacted the abuse desks of the relevant network owners (AS) and asked them to take the appropriate actions to prevent further abuse of their service.


Disclaimer:

* Data published here is provided "as it is" without any warranty or liability
* AS number, AS name and country code for published IP addresses has been provided by Team Cymru's  [IP to ASN Mapping Service](https://www.team-cymru.com/ip-asn-mapping)
