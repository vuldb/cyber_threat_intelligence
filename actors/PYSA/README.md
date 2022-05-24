# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PYSA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.129.64.190](https://vuldb.com/?ip.23.129.64.190) | - | - | High
2 | [45.147.231.210](https://vuldb.com/?ip.45.147.231.210) | - | - | High
3 | [185.220.100.240](https://vuldb.com/?ip.185.220.100.240) | tor-exit-13.zbau.f3netze.de | - | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PYSA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PYSA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/acms/admin/cargo_types/view_cargo_type.php` | High
2 | File | `/acms/classes/Master.php?f=delete_img` | High
3 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
4 | File | `/admin.php?id=siteoptions&social=edit&sid=2` | High
5 | File | `/admin/inbox.php&action=delete` | High
6 | File | `/admin/posts.php` | High
7 | File | `/administrator/alerts/alertLightbox.php` | High
8 | File | `/agenttrayicon` | High
9 | File | `/api/students/me/messages/` | High
10 | File | `/apps/acs-commons/content/page-compare.html` | High
11 | File | `/base/SysEveMenuAuthPointMapper.xml` | High
12 | File | `/cgi-bin/luci/api/switch` | High
13 | File | `/cms/admin/?page=client/view_client` | High
14 | File | `/cms/admin/?page=invoice/view_invoice` | High
15 | File | `/College_Management_System/admin/display-teacher.php` | High
16 | File | `/ctpms/admin/?page=individuals/view_individual` | High
17 | File | `/ctpms/admin/applications/update_status.php` | High
18 | File | `/ctpms/admin/individuals/update_status.php` | High
19 | File | `/ctpms/classes/Master.php?f=delete_img` | High
20 | File | `/dict/list.do` | High
21 | File | `/dms/admin/reports/daily_collection_report.php` | High
22 | File | `/farm/store.php` | High
23 | File | `/goform/setsambacfg` | High
24 | File | `/hocms/classes/Master.php?f=delete_collection` | High
25 | File | `/hocms/classes/Master.php?f=delete_member` | High
26 | File | `/index.php?page=reserve` | High
27 | File | `/mdiy/dict/listExcludeApp` | High
28 | File | `/mgmt/tm/util/bash` | High
29 | File | `/nova/bin/detnet` | High
30 | File | `/owa/auth/logon.aspx` | High
31 | File | `/preauth` | Medium
32 | File | `/purchase_order/admin/?page=user` | High
33 | File | `/reps/classes/Master.php?f=delete_amenity` | High
34 | File | `/RestAPI` | Medium
35 | ... | ... | ...

There are 297 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
