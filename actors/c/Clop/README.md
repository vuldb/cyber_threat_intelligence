# Clop - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Clop](https://vuldb.com/?actor.clop). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.clop](https://vuldb.com/?actor.clop)

## Campaigns

The following _campaigns_ are known and can be associated with Clop:

* CVE-2023-34362
* Fortra GoAnywhere

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Clop:

* [PL](https://vuldb.com/?country.pl)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Clop.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
2 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | Fortra GoAnywhere | Medium
3 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | Fortra GoAnywhere | High
4 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | Fortra GoAnywhere | High
5 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | Fortra GoAnywhere | High
6 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | Fortra GoAnywhere | High
7 | [5.34.180.205](https://vuldb.com/?ip.5.34.180.205) | bkp-vm-ams.layer6.net | CVE-2023-34362 | High
8 | [5.62.43.184](https://vuldb.com/?ip.5.62.43.184) | r-184-43-62-5.consumer-pool.prcdn.net | - | High
9 | [5.149.248.68](https://vuldb.com/?ip.5.149.248.68) | - | CVE-2023-34362 | High
10 | [5.149.250.74](https://vuldb.com/?ip.5.149.250.74) | verizon.com | CVE-2023-34362 | High
11 | [5.149.250.92](https://vuldb.com/?ip.5.149.250.92) | digiable.net | CVE-2023-34362 | High
12 | [5.188.86.114](https://vuldb.com/?ip.5.188.86.114) | - | CVE-2023-34362 | High
13 | [5.188.86.250](https://vuldb.com/?ip.5.188.86.250) | - | CVE-2023-34362 | High
14 | [5.188.87.27](https://vuldb.com/?ip.5.188.87.27) | - | CVE-2023-34362 | High
15 | [5.188.87.194](https://vuldb.com/?ip.5.188.87.194) | - | CVE-2023-34362 | High
16 | [5.188.87.226](https://vuldb.com/?ip.5.188.87.226) | - | CVE-2023-34362 | High
17 | [5.252.23.116](https://vuldb.com/?ip.5.252.23.116) | vm1120066.stark-industries.solutions | CVE-2023-34362 | High
18 | [5.252.25.88](https://vuldb.com/?ip.5.252.25.88) | free.ds | CVE-2023-34362 | High
19 | [5.252.189.0](https://vuldb.com/?ip.5.252.189.0) | - | - | High
20 | [5.252.190.0](https://vuldb.com/?ip.5.252.190.0) | - | - | High
21 | [5.252.191.0](https://vuldb.com/?ip.5.252.191.0) | - | - | High
22 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | Fortra GoAnywhere | High
23 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | Fortra GoAnywhere | High
24 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | Fortra GoAnywhere | High
25 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | Fortra GoAnywhere | High
26 | [44.206.3.111](https://vuldb.com/?ip.44.206.3.111) | ec2-44-206-3-111.compute-1.amazonaws.com | Fortra GoAnywhere | Medium
27 | [45.56.165.248](https://vuldb.com/?ip.45.56.165.248) | nordns.crowncloud.net | CVE-2023-34362 | High
28 | ... | ... | ... | ...

There are 110 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Clop_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Clop. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin-profile.php` | High
2 | File | `/Admin/changepassword.php` | High
3 | File | `/admin/edit_supplier.php` | High
4 | File | `/admin/general-setting` | High
5 | File | `/admin/service` | High
6 | File | `/catalog/all-products` | High
7 | File | `/changePassword` | High
8 | File | `/firewall/urlblist.php` | High
9 | File | `/forum/away.php` | High
10 | File | `/goform/addIpMacBind` | High
11 | File | `/goform/DelDhcpRule` | High
12 | File | `/goform/delIpMacBind` | High
13 | File | `/goform/DelPortMapping` | High
14 | File | `/goform/modifyDhcpRule` | High
15 | File | `/goform/modifyIpMacBind` | High
16 | File | `/goform/setBlackRule` | High
17 | File | `/goform/SetDDNSCfg` | High
18 | ... | ... | ...

There are 143 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/moveit-transfer-vulnerability-actively-exploited/
* https://unit42.paloaltonetworks.com/cl0p-group-distributes-ransomware-data-with-torrents/
* https://www.bleepingcomputer.com/news/security/clop-ransomware-tries-to-disable-windows-defender-malwarebytes/
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
