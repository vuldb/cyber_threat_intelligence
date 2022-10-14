# StealthyTrident - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _StealthyTrident_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with StealthyTrident:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with StealthyTrident or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [StealthyTrident](https://vuldb.com/?actor.stealthytrident) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of StealthyTrident.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.77.55.145](https://vuldb.com/?ip.45.77.55.145) | 45.77.55.145.vultr.com | [StealthyTrident](https://vuldb.com/?actor.stealthytrident) | Medium
2 | [45.77.173.124](https://vuldb.com/?ip.45.77.173.124) | 45.77.173.124.vultr.com | [StealthyTrident](https://vuldb.com/?actor.stealthytrident) | Medium
3 | [139.180.208.225](https://vuldb.com/?ip.139.180.208.225) | 139.180.208.225.vultr.com | [StealthyTrident](https://vuldb.com/?actor.stealthytrident) | Medium

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within StealthyTrident. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1059 | CWE-94 | Cross Site Scripting | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during StealthyTrident. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.user` | Low
2 | File | `/.perf` | Low
3 | File | `/admin/` | Low
4 | File | `/etc/password` | High
5 | File | `/php/` | Low
6 | File | `/Pwrchute` | Medium
7 | File | `/status` | Low
8 | File | `/var/yp` | Low
9 | File | `/_vti_pvt/access.cnf` | High
10 | File | `1.TEXT` | Low
11 | File | `14all.cgi` | Medium
12 | File | `500error.jsp` | Medium
13 | File | `ab.c` | Low
14 | File | `account_update.php` | High
15 | File | `add.php` | Low
16 | File | `addentry.cgi` | Medium
17 | File | `addressbook.php/options.php/search.php/help.php` | High
18 | File | `admin.html` | Medium
19 | File | `admin.php` | Medium
20 | File | `admin/auth/checksession.php` | High
21 | File | `administrator/phpinfo.php` | High
22 | File | `AdminViewError/AdminAddadmin` | High
23 | File | `admin_ug_auth.php` | High
24 | File | `admin_user.db` | High
25 | File | `advserver.exe` | High
26 | File | `ad_member.php` | High
27 | File | `agentadmin.php` | High
28 | File | `aolsecurityprivate.class` | High
29 | File | `article.php` | Medium
30 | File | `artlist.php` | Medium
31 | File | `astrocam.cgi` | Medium
32 | File | `as_web.exe/as_web4.exe` | High
33 | File | `athcgi.exe` | Medium
34 | File | `auction.cgi` | Medium
35 | File | `auth.inc.php` | Medium
36 | File | `axspawn.c` | Medium
37 | File | `backend.php/screen.php/comment.php` | High
38 | File | `badmin.c` | Medium
39 | File | `books.php` | Medium
40 | File | `bttv-driver.c` | High
41 | File | `bugzilla_email_append.pl` | High
42 | File | `bug_update_advanced_page.php/bug_update_page.php/view_bug_advanced_page.php/view_bug_page.php` | High
43 | File | `calendar.php` | Medium
44 | File | `category.cfm` | Medium
45 | File | `cgi-bin` | Low
46 | File | `cgi-bin/` | Medium
47 | File | `cgicso.c` | Medium
48 | File | `cgitest.exe` | Medium
49 | File | `charities.cron` | High
50 | File | `check_me.mod.php` | High
51 | File | `chetcpasswd.cgi` | High
52 | File | `cio_main.c` | Medium
53 | File | `clear_cookies.php` | High
54 | File | `CodeBrws.asp` | Medium
55 | File | `colegal.htm` | Medium
56 | File | `com.ms.vm.loader.cabcracker` | High
57 | File | `compose.php` | Medium
58 | ... | ... | ...

There are 505 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/stealthytrident

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
