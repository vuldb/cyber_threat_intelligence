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
* [RU](https://vuldb.com/?country.ru)
* [AR](https://vuldb.com/?country.ar)
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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT33. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/?page=user/manage_user` | High
2 | File | `/admin/del.php` | High
3 | File | `/admin/delstu.php` | High
4 | File | `/admin/image.php` | High
5 | File | `/admin/lab.php` | High
6 | File | `/asan/asan_interceptors_memintrinsics.cpp` | High
7 | File | `/asan/asan_new_delete.cpp` | High
8 | File | `/blog/blogpublish.php` | High
9 | File | `/categories/view_category.php` | High
10 | File | `/classes/Master.php?f=delete_category` | High
11 | File | `/classes/Master.php?f=delete_schedule` | High
12 | File | `/classes/Users.php?f=save_client` | High
13 | File | `/dashboard/contact` | High
14 | File | `/dede/co_do.php` | High
15 | File | `/etc/init0.d/S80telnetd.sh` | High
16 | File | `/etc/shadow.sample` | High
17 | File | `/frm/` | Low
18 | File | `/goform/setAutoPing` | High
19 | File | `/goform/wifiSSIDset` | High
20 | File | `/inc/design.inc.php` | High
21 | File | `/includes/db_utils.php` | High
22 | File | `/includes/utils.php` | High
23 | File | `/index.php` | Medium
24 | File | `/ip/admin/` | Medium
25 | File | `/master/index.php` | High
26 | File | `/menu.htm` | Medium
27 | File | `/mkshope/login.php` | High
28 | File | `/mygym/admin/login.php` | High
29 | File | `/Noxen-master/users.php` | High
30 | File | `/patient/settings.php` | High
31 | File | `/php_action/createUser.php` | High
32 | File | `/pms/update_patient.php` | High
33 | File | `/ptippage.cgi` | High
34 | File | `/qr/I/` | Low
35 | File | `/registration.php` | High
36 | File | `/release-x64/otfccdump` | High
37 | File | `/sanitizer_common/sanitizer_common_interceptors.inc` | High
38 | File | `/schedules/view_schedule.php` | High
39 | File | `/server-status` | High
40 | File | `/src/jfif.c` | Medium
41 | File | `/stdio-common/vfprintf.c` | High
42 | File | `/stocks/manage_stockin.php` | High
43 | File | `/templates/stylesheets.php` | High
44 | File | `/users` | Low
45 | File | `/usr/bin/tddp` | High
46 | File | `/var/backup/tower` | High
47 | File | `/var/log/qualys/qualys-cloud-agent-scan.log` | High
48 | File | `/viewReport.php` | High
49 | File | `/webmail/server/webmail.php` | High
50 | File | `/whbs/?page=contact_us` | High
51 | File | `/wp/?cpmvc_id=1&cpmvc_do_action=mvparse&f=datafeed&calid=1&month_index=1&method=adddetails&id=2` | High
52 | File | `/xpdf/Lexer.cc` | High
53 | File | `/xpdf/Stream.cc` | High
54 | File | `addphotosform.php` | High
55 | File | `addreviewsform.php` | High
56 | File | `adm.cgi` | Low
57 | ... | ... | ...

There are 499 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
