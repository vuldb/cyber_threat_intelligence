# StealthyTrident - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [StealthyTrident](https://vuldb.com/?actor.stealthytrident). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.stealthytrident](https://vuldb.com/?actor.stealthytrident)

## Campaigns

The following _campaigns_ are known and can be associated with StealthyTrident:

* StealthyTrident

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with StealthyTrident:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of StealthyTrident.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.77.55.145](https://vuldb.com/?ip.45.77.55.145) | 45.77.55.145.vultr.com | StealthyTrident | Medium
2 | [45.77.173.124](https://vuldb.com/?ip.45.77.173.124) | 45.77.173.124.vultr.com | StealthyTrident | Medium
3 | [139.180.208.225](https://vuldb.com/?ip.139.180.208.225) | 139.180.208.225.vultr.com | StealthyTrident | Medium

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _StealthyTrident_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059 | CWE-94 | Cross Site Scripting | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by StealthyTrident. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.user` | Low
2 | File | `/.perf` | Low
3 | File | `/admin/` | Low
4 | File | `/caucho-status` | High
5 | File | `/cgi-bin/readfile.tcl` | High
6 | File | `/etc/password` | High
7 | File | `/php/` | Low
8 | File | `/Pwrchute` | Medium
9 | File | `/status` | Low
10 | File | `/var/yp` | Low
11 | File | `/_vti_pvt/access.cnf` | High
12 | File | `1.TEXT` | Low
13 | File | `14all.cgi` | Medium
14 | File | `500error.jsp` | Medium
15 | File | `ab.c` | Low
16 | File | `account_update.php` | High
17 | File | `add.php` | Low
18 | File | `addentry.cgi` | Medium
19 | File | `addressbook.php/options.php/search.php/help.php` | High
20 | File | `admin.html` | Medium
21 | File | `admin.php` | Medium
22 | File | `admin/auth/checksession.php` | High
23 | File | `administrator/phpinfo.php` | High
24 | File | `AdminViewError/AdminAddadmin` | High
25 | File | `admin_ug_auth.php` | High
26 | File | `admin_user.db` | High
27 | File | `advserver.exe` | High
28 | File | `ad_member.php` | High
29 | File | `agentadmin.php` | High
30 | File | `aolsecurityprivate.class` | High
31 | File | `article.php` | Medium
32 | File | `artlist.php` | Medium
33 | File | `astrocam.cgi` | Medium
34 | File | `as_web.exe/as_web4.exe` | High
35 | File | `athcgi.exe` | Medium
36 | File | `auction.cgi` | Medium
37 | File | `auth.inc.php` | Medium
38 | File | `axspawn.c` | Medium
39 | File | `backend.php/screen.php/comment.php` | High
40 | File | `badmin.c` | Medium
41 | File | `books.php` | Medium
42 | File | `bttv-driver.c` | High
43 | File | `bugzilla_email_append.pl` | High
44 | File | `bug_update_advanced_page.php/bug_update_page.php/view_bug_advanced_page.php/view_bug_page.php` | High
45 | File | `calendar.php` | Medium
46 | File | `category.cfm` | Medium
47 | File | `cgi-bin` | Low
48 | File | `cgi-bin/` | Medium
49 | File | `cgicso.c` | Medium
50 | File | `cgitest.exe` | Medium
51 | File | `charities.cron` | High
52 | File | `check_me.mod.php` | High
53 | File | `chetcpasswd.cgi` | High
54 | File | `cio_main.c` | Medium
55 | File | `clear_cookies.php` | High
56 | File | `CodeBrws.asp` | Medium
57 | File | `colegal.htm` | Medium
58 | ... | ... | ...

There are 507 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/stealthytrident

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
