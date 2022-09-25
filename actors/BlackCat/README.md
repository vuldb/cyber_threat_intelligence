# BlackCat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackCat](https://vuldb.com/?actor.blackcat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blackcat](https://vuldb.com/?actor.blackcat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackCat:

* [US](https://vuldb.com/?country.us)
* [PT](https://vuldb.com/?country.pt)
* [DE](https://vuldb.com/?country.de)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackCat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.46.245.56](https://vuldb.com/?ip.20.46.245.56) | - | - | High
2 | [23.106.223.97](https://vuldb.com/?ip.23.106.223.97) | - | - | High
3 | [37.120.238.58](https://vuldb.com/?ip.37.120.238.58) | - | - | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackCat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackCat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/Label/js_del` | High
2 | File | `/admin.php/Label/page_del` | High
3 | File | `/admin.php/user/zu_del` | High
4 | File | `/admin/delstu.php` | High
5 | File | `/admin/edit_admin_details.php?id=admin` | High
6 | File | `/admin/foldernotice/list` | High
7 | File | `/admin/image/list` | High
8 | File | `/ajax/set_sys_time/` | High
9 | File | `/api/programs/orgUnits?programs` | High
10 | File | `/api/v1/user` | Medium
11 | File | `/application/controllers/Users.php` | High
12 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
13 | File | `/bcms/admin/?page=service_transactions/manage_service_transaction` | High
14 | File | `/bcms/classes/Master.php?f=delete_court_rental` | High
15 | File | `/cgi/get_param.cgi` | High
16 | File | `/checklogin.jsp` | High
17 | File | `/ci_hms/search` | High
18 | File | `/ci_spms/admin/search/searching/` | High
19 | File | `/classes/Master.php?f=delete_category` | High
20 | File | `/classes/Master.php?f=delete_payment` | High
21 | File | `/classes/Master.php?f=delete_schedule` | High
22 | File | `/company/account/safety/trade` | High
23 | File | `/ctpms/admin/?page=individuals/view_individual` | High
24 | File | `/ctpms/classes/Master.php?f=delete_img` | High
25 | File | `/dashboard/reports/logs/view` | High
26 | File | `/dashboard/snapshot/*?orgId=0` | High
27 | File | `/dotrace.asp` | Medium
28 | File | `/etc/init0.d/S80telnetd.sh` | High
29 | File | `/fuel/sitevariables/delete/4` | High
30 | File | `/goform/AdvSetLanIp` | High
31 | File | `/goform/aspForm` | High
32 | ... | ... | ...

There are 275 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/03/from-blackmatter-to-blackcat-analyzing.html
* https://www.ic3.gov/Media/News/2022/220420.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
