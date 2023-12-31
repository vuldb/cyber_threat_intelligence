# IRATA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [IRATA](https://vuldb.com/?actor.irata). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.irata](https://vuldb.com/?actor.irata)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with IRATA:

* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of IRATA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.144.130.58](https://vuldb.com/?ip.5.144.130.58) | 5-144-130-58.static.hostiran.name | - | High
2 | [5.161.202.99](https://vuldb.com/?ip.5.161.202.99) | static.99.202.161.5.clients.your-server.de | - | High
3 | [5.255.113.62](https://vuldb.com/?ip.5.255.113.62) | - | - | High
4 | [5.255.117.115](https://vuldb.com/?ip.5.255.117.115) | - | - | High
5 | [5.255.117.149](https://vuldb.com/?ip.5.255.117.149) | - | - | High
6 | [5.255.126.184](https://vuldb.com/?ip.5.255.126.184) | - | - | High
7 | [20.74.163.6](https://vuldb.com/?ip.20.74.163.6) | - | - | High
8 | [20.197.199.136](https://vuldb.com/?ip.20.197.199.136) | - | - | High
9 | ... | ... | ... | ...

There are 32 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _IRATA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by IRATA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/addemployee.php` | High
2 | File | `/admin/countrymanagement.php` | High
3 | File | `/admin/maintenance/view_designation.php` | High
4 | File | `/admin/photo.php` | High
5 | File | `/admin/reports.php` | High
6 | File | `/admin/success_story.php` | High
7 | File | `/admin/user/team` | High
8 | File | `/cgi-bin/login.cgi` | High
9 | File | `/cm/delete` | Medium
10 | File | `/dipam/athlete-profile.php` | High
11 | File | `/dipam/save-delegates.php` | High
12 | File | `/forum/away.php` | High
13 | File | `/getcfg.php` | Medium
14 | File | `/goform/RouteStatic` | High
15 | File | `/hrm/employeeadd.php` | High
16 | File | `/hrm/employeeview.php` | High
17 | File | `/login.php` | Medium
18 | File | `/mkshop/Men/profile.php` | High
19 | File | `/pms/admin/prisons/view_prison.php` | High
20 | File | `/product` | Medium
21 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
22 | File | `/services/Card/findUser` | High
23 | File | `/spip.php` | Medium
24 | File | `/TeleoptiWFM/Administration/GetOneTenant` | High
25 | File | `/uncpath/` | Medium
26 | File | `/wordpress/wp-admin/options-general.php` | High
27 | File | `?r=recruit/interview/export&interviews=x` | High
28 | File | `actions.hsp` | Medium
29 | File | `adclick.php` | Medium
30 | ... | ... | ...

There are 258 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/087fb94dc34cb66d30105933b33ab6517996e8dfd07fac4fa17e47900d3cd33c/
* https://bazaar.abuse.ch/sample/50abd8e28534d77ae9fa85c016a0fb180e372f0284fd84014dc7fc9d42692883/
* https://bazaar.abuse.ch/sample/ab46635a51c709b132e5245456e78a00c86c169c0aa24e56e557d574aa8c36d0/
* https://bazaar.abuse.ch/sample/d39434517a7a7d6bc62fe68d8bd4e43b4132734bcf7abcd6f3eec8de3eb23fcf/
* https://bazaar.abuse.ch/sample/efc9d49d3bea48fd72d09d1588d69af7c0eb61a0eb72568986116d4a205e4711/
* https://threatfox.abuse.ch
* https://threatfox.abuse.ch/ioc/845209/
* https://tria.ge/230709-y4d3bsfh67/behavioral2#report:~:text=Network-,Requests,-TCP
* https://tria.ge/230919-tagtxacb46/behavioral1
* https://twitter.com/onecert_ir/status/1558944995628941312
* https://twitter.com/onecert_ir/status/1564267795680055297
* https://urlhaus.abuse.ch/host/23.88.43.247/
* https://www.joesandbox.com/analysis/1277946
* https://www.joesandbox.com/analysis/1311115#iocs
* https://www.joesandbox.com/analysis/1313677
* https://www.joesandbox.com/analysis/1313726

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
