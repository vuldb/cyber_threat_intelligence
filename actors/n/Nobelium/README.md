# Nobelium - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nobelium](https://vuldb.com/?actor.nobelium). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nobelium](https://vuldb.com/?actor.nobelium)

## Campaigns

The following _campaigns_ are known and can be associated with Nobelium:

* Tomiris

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nobelium:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nobelium.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.67.239.91](https://vuldb.com/?ip.13.67.239.91) | - | - | High
2 | [31.42.177.78](https://vuldb.com/?ip.31.42.177.78) | contact8.mxweb4.website | - | High
3 | [37.120.247.135](https://vuldb.com/?ip.37.120.247.135) | - | - | High
4 | [45.14.70.186](https://vuldb.com/?ip.45.14.70.186) | - | - | High
5 | [45.32.59.31](https://vuldb.com/?ip.45.32.59.31) | 45.32.59.31.vultrusercontent.com | - | Medium
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nobelium_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nobelium. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/edit.php` | High
2 | File | `/admin/functions.php` | High
3 | File | `/admin/user/manage_user.php` | High
4 | File | `/cgi-bin/webadminget.cgi` | High
5 | File | `/dashboard/updatelogo.php` | High
6 | File | `/etc/networkd-dispatcher` | High
7 | File | `/etc/openshift/server_priv.pem` | High
8 | File | `/etc/shadow.sample` | High
9 | File | `/guest_auth/cfg/upLoadCfg.php` | High
10 | File | `/index.php` | Medium
11 | File | `/Interface/DevManage/EC.php?cmd=upload` | High
12 | File | `/MicroStrategyWS/happyaxis.jsp` | High
13 | File | `/mkshop/Men/profile.php` | High
14 | File | `/notice-edit.php` | High
15 | File | `/Noxen-master/users.php` | High
16 | File | `/opt/teradata/gsctools/bin/t2a.pl` | High
17 | File | `/public/login.htm` | High
18 | File | `/start_apply.htm` | High
19 | File | `/uncpath/` | Medium
20 | File | `/upload` | Low
21 | ... | ... | ...

There are 175 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/174/nobelium-apt-iocs/
* https://blogs.infoblox.com/cyber-threat-intelligence/nobelium-campaigns-and-malware/
* https://community.blueliv.com/#!/s/6078a53c82df413eb5355f1a
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/2022_01_06_C2%20Nobelium.csv
* https://securelist.com/darkhalo-after-solarwinds-the-tomiris-connection/104311/
* https://www.microsoft.com/security/blog/2021/05/27/new-sophisticated-email-based-attack-from-nobelium/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
