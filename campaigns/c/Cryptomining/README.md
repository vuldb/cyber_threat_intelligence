# Cryptomining - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cryptomining_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cryptomining:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [HU](https://vuldb.com/?country.hu)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cryptomining or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [TeamTNT](https://vuldb.com/?actor.teamtnt) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cryptomining.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.122.15.138](https://vuldb.com/?ip.5.122.15.138) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [45.9.148.182](https://vuldb.com/?ip.45.9.148.182) | - | [TeamTNT](https://vuldb.com/?actor.teamtnt) | High
3 | [45.136.244.146](https://vuldb.com/?ip.45.136.244.146) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cryptomining. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cryptomining. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/ajax.php?action=read_msg` | High
2 | File | `/api /v3/auth` | High
3 | File | `/cgi-bin/editBookmark` | High
4 | File | `/debug/pprof` | Medium
5 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
6 | File | `/env` | Low
7 | File | `/goform/SetNetControlList` | High
8 | File | `/goform/SetStaticRouteCfg` | High
9 | File | `/modules/tasks/summary.inc.php` | High
10 | File | `/rest/api/2/user/picker` | High
11 | File | `/src/chatbotapp/chatWindow.java` | High
12 | File | `/uncpath/` | Medium
13 | File | `/wp-json` | Medium
14 | File | `admin/categories_industry.php` | High
15 | File | `admin/category.inc.php` | High
16 | File | `admin/class-woo-popup-admin.php` | High
17 | ... | ... | ...

There are 138 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.trendmicro.co.jp/archives/20418
* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-campaign-briefs/log4j-indicators-of-compromise-to-date/
* https://thedfirreport.com/2020/11/12/cryptominers-exploiting-weblogic-rce-cve-2020-14882/
* https://thedfirreport.com/2021/01/18/all-that-for-a-coinminer/
* https://www.trendmicro.com/en_us/research/21/k/compromised-docker-hub-accounts-abused-for-cryptomining-linked-t.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
