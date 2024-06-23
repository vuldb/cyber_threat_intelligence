# SparkRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SparkRAT](https://vuldb.com/?actor.sparkrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sparkrat](https://vuldb.com/?actor.sparkrat)

## Campaigns

The following _campaigns_ are known and can be associated with SparkRAT:

* CVE-2024-27198 / CVE-2024-27199

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SparkRAT:

* [SC](https://vuldb.com/?country.sc)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SparkRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [38.54.94.13](https://vuldb.com/?ip.38.54.94.13) | - | CVE-2024-27198 / CVE-2024-27199 | High
2 | [43.140.252.169](https://vuldb.com/?ip.43.140.252.169) | - | - | High
3 | [54.180.27.29](https://vuldb.com/?ip.54.180.27.29) | ec2-54-180-27-29.ap-northeast-2.compute.amazonaws.com | - | Medium
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SparkRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SparkRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/asms/classes/Master.php?f=delete_transaction` | High
3 | File | `/cgi-bin/editBookmark` | High
4 | File | `/goform/addressNat` | High
5 | File | `/goform/aspForm` | High
6 | File | `/include/menu_v.inc.php` | High
7 | File | `/librarian/lab.php` | High
8 | File | `/login/` | Low
9 | File | `/omos/admin/?page=user/list` | High
10 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
11 | ... | ... | ...

There are 88 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/52899/
* https://asec.ahnlab.com/en/53267/
* https://threatfox.abuse.ch
* https://twitter.com/suyog41/status/1655524692164214784
* https://twitter.com/suyog41/status/1699438327508734306
* https://www.trendmicro.com/en_us/research/24/c/teamcity-vulnerability-exploits-lead-to-jasmin-ransomware.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
