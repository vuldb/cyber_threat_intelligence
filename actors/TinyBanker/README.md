# TinyBanker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TinyBanker](https://vuldb.com/?actor.tinybanker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tinybanker](https://vuldb.com/?actor.tinybanker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TinyBanker:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [AR](https://vuldb.com/?country.ar)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TinyBanker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.32.207.78](https://vuldb.com/?ip.13.32.207.78) | server-13-32-207-78.iad66.r.cloudfront.net | - | High
2 | [78.108.118.108](https://vuldb.com/?ip.78.108.118.108) | g2wmcs22-3-isp1.fra.expertcity.com | - | High
3 | [78.108.118.118](https://vuldb.com/?ip.78.108.118.118) | g2wmcs26-1-isp1.fra.expertcity.com | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TinyBanker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TinyBanker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/ajax.php?action=delete_transaction` | High
2 | File | `/admin/ajax.php?action=delete_uploads` | High
3 | File | `/admin/ajax.php?action=delete_window` | High
4 | File | `/admin/ajax.php?action=save_queue` | High
5 | File | `/admin/api/theme-edit/` | High
6 | File | `/admin/article/list_approve` | High
7 | File | `/admin/client_edit.php` | High
8 | File | `/admin/curltest.cgi` | High
9 | File | `/admin/doctors/manage_doctor.php` | High
10 | File | `/admin/login.php` | High
11 | File | `/admin/manage_user.php` | High
12 | File | `/admin/news/sort_ok.php` | High
13 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
14 | File | `/admin/users/index.php` | High
15 | File | `/api/browserextension/UpdatePassword/` | High
16 | File | `/app/dao/CustomerDAO.php` | High
17 | File | `/apply.cgi` | Medium
18 | File | `/blog/blog.php` | High
19 | File | `/calendar/viewcalendar.php` | High
20 | File | `/cgi-bin/wlogin.cgi` | High
21 | File | `/classes/Master.php?f=delete_helmet` | High
22 | File | `/classes/Master.php?f=delete_stockout` | High
23 | File | `/common/download_agent_installer.php` | High
24 | File | `/config/api/v1/reboot` | High
25 | File | `/config/service/host.go` | High
26 | File | `/cwms/classes/Master.php?f=save_contact` | High
27 | File | `/dashboard/menu-list.php` | High
28 | File | `/dashboard/table-list.php` | High
29 | File | `/diag_ping_admin.asp` | High
30 | File | `/etc/passwd` | Medium
31 | File | `/etc/shadow.sample` | High
32 | File | `/fos/admin/ajax.php?action=login` | High
33 | File | `/goform/saveParentControlInfo` | High
34 | File | `/goform/setAdInfoDetail` | High
35 | File | `/goform/SetIpMacBind` | High
36 | File | `/goform/SetPptpServerCfg` | High
37 | File | `/goform/WifiBasicSet` | High
38 | File | `/hocms/classes/Master.php?f=delete_collection` | High
39 | File | `/hrm/controller/employee.php` | High
40 | File | `/hrm/state.php` | High
41 | File | `/hss/admin/?page=client/manage_client` | High
42 | ... | ... | ...

There are 367 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0409-0416.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-for-july-9-to-july-16.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
