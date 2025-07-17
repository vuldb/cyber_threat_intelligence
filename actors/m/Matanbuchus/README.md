# Matanbuchus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Matanbuchus](https://vuldb.com/?actor.matanbuchus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.matanbuchus](https://vuldb.com/?actor.matanbuchus)

## Campaigns

The following _campaigns_ are known and can be associated with Matanbuchus:

* Cobalt Strike

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Matanbuchus:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Matanbuchus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.252.155.81](https://vuldb.com/?ip.5.252.155.81) | - | - | High
2 | [8.211.34.5](https://vuldb.com/?ip.8.211.34.5) | - | - | High
3 | [34.130.217.52](https://vuldb.com/?ip.34.130.217.52) | 52.217.130.34.bc.googleusercontent.com | - | Medium
4 | [44.208.127.245](https://vuldb.com/?ip.44.208.127.245) | ec2-44-208-127-245.compute-1.amazonaws.com | Cobalt Strike | Medium
5 | [45.141.86.26](https://vuldb.com/?ip.45.141.86.26) | - | - | High
6 | [45.141.86.98](https://vuldb.com/?ip.45.141.86.98) | - | - | High
7 | [45.141.86.132](https://vuldb.com/?ip.45.141.86.132) | - | - | High
8 | [45.141.86.133](https://vuldb.com/?ip.45.141.86.133) | - | - | High
9 | [46.8.210.98](https://vuldb.com/?ip.46.8.210.98) | 622857.cloud4box.ru | - | High
10 | [47.89.157.126](https://vuldb.com/?ip.47.89.157.126) | - | - | High
11 | [47.254.129.255](https://vuldb.com/?ip.47.254.129.255) | - | - | High
12 | [62.113.117.216](https://vuldb.com/?ip.62.113.117.216) | v2751855.hosted-by-vdsina.ru | - | High
13 | [80.64.30.95](https://vuldb.com/?ip.80.64.30.95) | - | - | High
14 | [88.204.123.123](https://vuldb.com/?ip.88.204.123.123) | - | - | High
15 | [89.23.113.220](https://vuldb.com/?ip.89.23.113.220) | 44059-1.ip-ptr.tech | - | High
16 | [91.202.233.168](https://vuldb.com/?ip.91.202.233.168) | - | - | High
17 | [91.202.233.239](https://vuldb.com/?ip.91.202.233.239) | - | - | High
18 | [91.202.233.240](https://vuldb.com/?ip.91.202.233.240) | - | - | High
19 | [91.202.233.245](https://vuldb.com/?ip.91.202.233.245) | - | - | High
20 | [92.255.85.128](https://vuldb.com/?ip.92.255.85.128) | - | - | High
21 | [94.158.244.124](https://vuldb.com/?ip.94.158.244.124) | no-rdns.mivocloud.com | - | High
22 | ... | ... | ... | ...

There are 82 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Matanbuchus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Matanbuchus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/RecordingList/DownloadRecord?file=` | High
2 | File | `/apply.cgi` | Medium
3 | File | `/cgi-bin/cstecgi.cgi` | High
4 | File | `/php/ping.php` | High
5 | File | `/scripts/unlock_tasks.php` | High
6 | File | `/SysInfo1.htm` | High
7 | File | `/sysinfo_json.cgi` | High
8 | ... | ... | ...

There are 54 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://circleid.com/posts/20220721-matanbuchus-with-cobalt-strike-not-your-favorite-combo
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-06-16%20Matanbuchus%20IOCs
* https://search.censys.io/hosts/45.141.86.98
* https://search.censys.io/hosts/45.141.86.132
* https://search.censys.io/hosts/45.141.86.133
* https://search.censys.io/hosts/91.202.233.168
* https://search.censys.io/hosts/92.255.85.128
* https://search.censys.io/hosts/94.159.113.43
* https://search.censys.io/hosts/94.159.113.222
* https://search.censys.io/hosts/193.24.197.34
* https://search.censys.io/hosts/193.109.85.27
* https://search.censys.io/hosts/193.109.85.31
* https://search.censys.io/hosts/193.242.149.17
* https://search.censys.io/hosts/194.67.193.66
* https://search.censys.io/hosts/194.67.193.68
* https://search.censys.io/hosts/194.67.193.70
* https://search.censys.io/hosts/194.67.193.71
* https://search.censys.io/hosts/194.67.193.234
* https://search.censys.io/hosts/194.67.193.235
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=193.109.85.54
* https://tracker.viriback.com/index.php?q=193.109.85.61
* https://tracker.viriback.com/index.php?q=193.109.85.78
* https://tracker.viriback.com/index.php?q=193.109.85.79
* https://tracker.viriback.com/index.php?q=194.67.193.205
* https://www.malware-traffic-analysis.net/2024/06/17/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
