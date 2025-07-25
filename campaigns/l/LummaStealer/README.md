# LummaStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LummaStealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LummaStealer:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LummaStealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Beast](https://vuldb.com/?actor.beast) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LummaStealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.155.249.117](https://vuldb.com/?ip.45.155.249.117) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [84.17.38.250](https://vuldb.com/?ip.84.17.38.250) | 84-17-38-250.bunnyinfra.net | [Beast](https://vuldb.com/?actor.beast) | High
3 | [89.187.169.3](https://vuldb.com/?ip.89.187.169.3) | 89-187-169-3.bunnyinfra.net | [Beast](https://vuldb.com/?actor.beast) | High
4 | [104.18.42.227](https://vuldb.com/?ip.104.18.42.227) | - | [Beast](https://vuldb.com/?actor.beast) | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LummaStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LummaStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\SSCService` | High
2 | File | `.git/` | Low
3 | File | `/add-students.php` | High
4 | File | `/admin/?page=user/manage_user` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/admin-profile.php` | High
7 | File | `/admin/adminHome.php` | High
8 | File | `/admin/api/theme-edit/` | High
9 | File | `/admin/booking-search.php` | High
10 | File | `/admin/delete-doctor.php` | High
11 | File | `/admin/modules/bibliography/index.php` | High
12 | File | `/admin/msg.php` | High
13 | File | `/admin/report.php` | High
14 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
15 | File | `/apply/index.php` | High
16 | File | `/classes/Master.php?f=delete_category` | High
17 | File | `/conf/app.conf` | High
18 | File | `/cwc/login` | Medium
19 | File | `/goform/AddDnsForward` | High
20 | File | `/goform/fromRouteStatic` | High
21 | File | `/goform/ModifyPppAuthWhiteMac` | High
22 | File | `/goform/saveParentControlInfo` | High
23 | File | `/goform/setcfm` | High
24 | File | `/goform/setsambacfg` | High
25 | File | `/goform/SetSysTimeCfg` | High
26 | File | `/goform/WifiWpsStart` | High
27 | File | `/goform/WriteFacMac` | High
28 | File | `/hedwig.cgi` | Medium
29 | File | `/index/jobfairol/show/` | High
30 | ... | ... | ...

There are 250 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cybereason.com/blog/threat-analysis-rise-of-lummastealer
* https://www.trendmicro.com/en_us/research/25/a/how-cracks-and-installers-bring-malware-to-your-device.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
