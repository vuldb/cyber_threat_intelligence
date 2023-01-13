# APT33 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT33](https://vuldb.com/?actor.apt33). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt33](https://vuldb.com/?actor.apt33)

## Campaigns

The following _campaigns_ are known and can be associated with APT33:

* Elfin
* PoshC2
* Powerton

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT33:

* [PL](https://vuldb.com/?country.pl)
* [ES](https://vuldb.com/?country.es)
* [SV](https://vuldb.com/?country.sv)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT33.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.79.66.241](https://vuldb.com/?ip.5.79.66.241) | - | Powerton | High
2 | [5.79.127.177](https://vuldb.com/?ip.5.79.127.177) | - | Elfin | High
3 | [5.135.120.57](https://vuldb.com/?ip.5.135.120.57) | - | - | High
4 | [5.135.199.25](https://vuldb.com/?ip.5.135.199.25) | - | - | High
5 | [5.187.21.70](https://vuldb.com/?ip.5.187.21.70) | - | Elfin | High
6 | [5.187.21.71](https://vuldb.com/?ip.5.187.21.71) | - | Elfin | High
7 | [8.26.21.117](https://vuldb.com/?ip.8.26.21.117) | 117.21.26.8.serverpronto.com | Elfin | High
8 | [8.26.21.119](https://vuldb.com/?ip.8.26.21.119) | ns1.glasscitysoftware.net | Elfin | High
9 | [8.26.21.120](https://vuldb.com/?ip.8.26.21.120) | ns2.glasscitysoftware.net | Elfin | High
10 | [8.26.21.220](https://vuldb.com/?ip.8.26.21.220) | mail2.boldinbox.com | Elfin | High
11 | [8.26.21.221](https://vuldb.com/?ip.8.26.21.221) | mail3.boldinbox.com | Elfin | High
12 | [8.26.21.222](https://vuldb.com/?ip.8.26.21.222) | mail9.servidorz.com | Elfin | High
13 | [8.26.21.223](https://vuldb.com/?ip.8.26.21.223) | mail5.boldinbox.com | Elfin | High
14 | [31.7.62.48](https://vuldb.com/?ip.31.7.62.48) | - | - | High
15 | [37.48.105.178](https://vuldb.com/?ip.37.48.105.178) | - | Elfin | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT33_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT33. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/api/theme-edit/` | High
2 | File | `/api/audits` | Medium
3 | File | `/bin/sh` | Low
4 | File | `/bsms_ci/index.php/user/edit_user/` | High
5 | File | `/calendar/viewcalendar.php` | High
6 | File | `/classes/Master.php?f=delete_appointment` | High
7 | File | `/classes/Users.php?f=delete_client` | High
8 | File | `/clients/profile` | High
9 | File | `/cms/notify` | Medium
10 | File | `/depotHead/list` | High
11 | File | `/device/signin` | High
12 | File | `/env` | Low
13 | File | `/ext/phar/phar_object.c` | High
14 | File | `/goform/setSysPwd` | High
15 | File | `/goform/SysToolReboot` | High
16 | File | `/goform/SysToolRestoreSet` | High
17 | File | `/goform/WifiBasicSet` | High
18 | File | `/goform/wifiSSIDset` | High
19 | File | `/gpac/src/bifs/unquantize.c` | High
20 | File | `/hrm/employeeadd.php` | High
21 | File | `/hss/?page=product_per_brand` | High
22 | File | `/hss/admin/?page=client/manage_client` | High
23 | File | `/hss/admin/?page=user/manage_user` | High
24 | File | `/index.php?module=configuration/application` | High
25 | File | `/index.php?module=entities/forms&entities_id=24` | High
26 | File | `/index.php?module=help_pages/pages&entities_id=24` | High
27 | File | `/login` | Low
28 | File | `/network_test.php` | High
29 | File | `/odlms//classes/Master.php?f=delete_activity` | High
30 | File | `/php-sms/admin/quotes/manage_remark.php` | High
31 | File | `/plugin/getList` | High
32 | File | `/projects/listprojects.php` | High
33 | File | `/queuing/admin/ajax.php?action=save_settings` | High
34 | File | `/rukovoditel/index.php?module=users/login` | High
35 | File | `/tmp` | Low
36 | File | `/v1/sql-runner` | High
37 | File | `/var/polycom/cma/upgrade/scripts` | High
38 | File | `/var/tmp/abrt/*/maps` | High
39 | File | `/web/IndexController.java` | High
40 | File | `/youthappam/editcategory.php` | High
41 | File | `3_row-order.php` | High
42 | File | `4840/tcp` | Medium
43 | File | `AbstractScheduleJob.java` | High
44 | File | `AccountTypePreferenceLoader.java` | High
45 | File | `addrtoname.c` | Medium
46 | ... | ... | ...

There are 396 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/jeFF0Falltrades/IoCs/blob/master/APT/poshc2_apt_33.md
* https://securelist.com/twas-the-night-before/91599/
* https://securityaffairs.co/wordpress/93845/apt/apt33-vpn-networks.html
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/elfin-apt33-espionage
* https://www.fireeye.com/blog/threat-research/2018/12/overruled-containing-a-potentially-destructive-adversary.html
* https://www.symantec.com/blogs/threat-intelligence/elfin-apt33-espionage

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
