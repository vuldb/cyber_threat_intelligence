# FatalRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FatalRAT](https://vuldb.com/?actor.fatalrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fatalrat](https://vuldb.com/?actor.fatalrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FatalRAT:

* [HK](https://vuldb.com/?country.hk)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FatalRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.124.44.137](https://vuldb.com/?ip.27.124.44.137) | - | - | High
2 | [43.154.91.3](https://vuldb.com/?ip.43.154.91.3) | - | - | High
3 | [45.119.55.16](https://vuldb.com/?ip.45.119.55.16) | - | - | High
4 | [45.204.192.216](https://vuldb.com/?ip.45.204.192.216) | - | - | High
5 | [45.204.215.237](https://vuldb.com/?ip.45.204.215.237) | - | - | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FatalRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FatalRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/api/log/killJob` | High
4 | File | `/api/upload.php` | High
5 | File | `/baseOpLog.do` | High
6 | File | `/bitrix/admin/ldap_server_edit.php` | High
7 | File | `/cgi-bin/api-get_line_status` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/controller/OnlinePreviewController.java` | High
10 | File | `/export` | Low
11 | File | `/includes/rrdtool.inc.php` | High
12 | File | `/lab.html` | Medium
13 | File | `/manage/IPSetup.php` | High
14 | ... | ... | ...

There are 107 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/66/fatalrat-backdoor-ioc/
* https://bazaar.abuse.ch/sample/1924b09ff1e25fe9d39bad70f094766863f366543658627fe94f435b07da6109/
* https://community.blueliv.com/#!/s/6107d20982df4141693319a7
* https://threatfox.abuse.ch
* https://tria.ge/241112-fvt33swbrg/behavioral1
* https://www.welivesecurity.com/2023/02/16/these-arent-apps-youre-looking-for-fake-installers/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
