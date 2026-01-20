# Cyber Jihad - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cyber Jihad_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cyber Jihad:

* [LA](https://vuldb.com/?country.la)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cyber Jihad or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [GIMF](https://vuldb.com/?actor.gimf) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cyber Jihad.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [111.90.148.5](https://vuldb.com/?ip.111.90.148.5) | server1.kamon.la | [GIMF](https://vuldb.com/?actor.gimf) | High
2 | [151.80.200.124](https://vuldb.com/?ip.151.80.200.124) | ip124.ip-151-80-200.eu | [GIMF](https://vuldb.com/?actor.gimf) | High
3 | [159.100.176.171](https://vuldb.com/?ip.159.100.176.171) | - | [GIMF](https://vuldb.com/?actor.gimf) | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cyber Jihad. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cyber Jihad. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/dl_sendmail.php` | High
2 | File | `/admin/file_manager/export` | High
3 | File | `/admin/index2.html` | High
4 | File | `/adminPage/conf/reload` | High
5 | File | `/admin_topic.php?action=delall` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/cron/settings/setJob/` | High
8 | File | `/api/v2/cli/commands` | High
9 | File | `/api2/html/` | Medium
10 | File | `/bitrix/admin/ldap_server_edit.php` | High
11 | File | `/cgi-bin/cstecgi.cgi` | High
12 | File | `/cgi-bin/koha/catalogue/search.pl` | High
13 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
14 | File | `/DXR.axd` | Medium
15 | File | `/forum/away.php` | High
16 | File | `/h/rest` | Low
17 | File | `/index/ajax/lang` | High
18 | File | `/log/decodmail.php` | High
19 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
20 | File | `/log_proxy` | Medium
21 | File | `/mailcleaner.php/getStats` | High
22 | ... | ... | ...

There are 186 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://ddanchev.blogspot.com/2021/06/exposing-currently-active-portfolio-of.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
