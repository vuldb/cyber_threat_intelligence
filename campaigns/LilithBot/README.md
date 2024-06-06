# LilithBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LilithBot_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LilithBot:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LilithBot or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Eternity](https://vuldb.com/?actor.eternity) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LilithBot.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.9.148.203](https://vuldb.com/?ip.45.9.148.203) | - | [Eternity](https://vuldb.com/?actor.eternity) | High
2 | [77.73.133.12](https://vuldb.com/?ip.77.73.133.12) | - | [Eternity](https://vuldb.com/?actor.eternity) | High
3 | [91.243.59.210](https://vuldb.com/?ip.91.243.59.210) | - | [Eternity](https://vuldb.com/?actor.eternity) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LilithBot. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LilithBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/admin/art/data.html` | High
2 | File | `/ajax.php?action=read_msg` | High
3 | File | `/debug/pprof` | Medium
4 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
5 | File | `/env` | Low
6 | File | `/forum/away.php` | High
7 | File | `/goform/SetNetControlList` | High
8 | File | `/goform/SetStaticRouteCfg` | High
9 | File | `/librarian/bookdetails.php` | High
10 | File | `/ptipupgrade.cgi` | High
11 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
12 | File | `/src/chatbotapp/chatWindow.java` | High
13 | File | `/staff/bookdetails.php` | High
14 | File | `about.php` | Medium
15 | File | `admin.color.php` | High
16 | File | `admin/addons/archive/archive.php` | High
17 | File | `admin/categories_industry.php` | High
18 | File | `admin/class-woo-popup-admin.php` | High
19 | File | `admin/content/postcategory` | High
20 | ... | ... | ...

There are 169 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.zscaler.com/blogs/security-research/analysis-lilithbot-malware-and-eternity-threat-group

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
