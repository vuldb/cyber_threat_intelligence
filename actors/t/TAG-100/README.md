# TAG-100 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TAG-100](https://vuldb.com/?actor.tag-100). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tag-100](https://vuldb.com/?actor.tag-100)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TAG-100:

* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TAG-100.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [38.54.15.164](https://vuldb.com/?ip.38.54.15.164) | - | - | High
2 | [38.54.115.34](https://vuldb.com/?ip.38.54.115.34) | - | - | High
3 | [104.244.79.119](https://vuldb.com/?ip.104.244.79.119) | - | - | High
4 | [144.202.125.201](https://vuldb.com/?ip.144.202.125.201) | 144.202.125.201.vultrusercontent.com | - | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TAG-100_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TAG-100. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutedit.php` | High
2 | File | `/addcompany.php` | High
3 | File | `/admin/?page=inventory/view_inventory&id=2` | High
4 | File | `/Admin/add-admin.php` | High
5 | File | `/admin/assets/` | High
6 | File | `/admin/assign/assign.php` | High
7 | File | `/admin/config_time_sync.php` | High
8 | File | `/admin/edit.php` | High
9 | File | `/admin/edit_subject.php` | High
10 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
11 | File | `/admin/index.php` | High
12 | File | `/admin/inquiries/view_details.php` | High
13 | File | `/admin/process_category_add.php` | High
14 | File | `/admin/subnets/ripe-query.php` | High
15 | File | `/admin/system.html` | High
16 | File | `/adplanet/PlanetUser` | High
17 | File | `/ajax/myshop` | Medium
18 | File | `/api/runscript` | High
19 | File | `/api/v2/maps` | Medium
20 | File | `/assets/php/upload.php` | High
21 | File | `/baseOpLog.do` | High
22 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/downloadFile.cgi` | High
25 | File | `/cgi-bin/hd_config.cgi` | High
26 | File | `/cgi-bin/system_mgr.cgi` | High
27 | File | `/Cinema-Reservation/booking.php` | High
28 | File | `/classes/Master.php?f=delete_message` | High
29 | File | `/classes/Master.php?f=log_employee` | High
30 | File | `/classes/Master.php?f=log_visitor` | High
31 | File | `/classes/Users.php` | High
32 | File | `/classes/Users.php?f=delete` | High
33 | File | `/classes/Users.php?f=save` | High
34 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
35 | File | `/cm/update_rows/page?id=2` | High
36 | File | `/cms/classes/Users.php?f=delete_client` | High
37 | File | `/com/esafenet/servlet/ajax/UsbKeyAjax.java` | High
38 | File | `/ctpms/classes/Master.php?f=delete_img` | High
39 | File | `/debug/pprof` | Medium
40 | File | `/Doctor/user_appointment.php` | High
41 | File | `/E-Insurance/` | High
42 | File | `/edit_book.php` | High
43 | File | `/employee_gatepass/classes/Master.php?f=delete_department` | High
44 | File | `/employee_gatepass/classes/Users.php?f=ssave` | High
45 | File | `/etc/tomcat8/Catalina/attack` | High
46 | File | `/ext/collect/find_text.do` | High
47 | File | `/feedback/post/` | High
48 | File | `/files/list-file` | High
49 | File | `/forum/away.php` | High
50 | File | `/front/admin/tenancyDetail.php` | High
51 | File | `/goform/aspForm` | High
52 | File | `/goform/DhcpSetSe` | High
53 | ... | ... | ...

There are 460 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/UNC****/TAG-*/TAG-100%20Uses%20Open-Source%20Tools%20in%20Suspected%20Global%20Espionage%20Campaign.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
