# GravityRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GravityRAT](https://vuldb.com/?actor.gravityrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gravityrat](https://vuldb.com/?actor.gravityrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GravityRAT:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GravityRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.189.159.23](https://vuldb.com/?ip.5.189.159.23) | mail.camzx.com | - | High
2 | [75.2.37.224](https://vuldb.com/?ip.75.2.37.224) | a68b99834d539a7e9.awsglobalaccelerator.com | - | High
3 | [104.21.12.211](https://vuldb.com/?ip.104.21.12.211) | - | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GravityRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GravityRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.kss.pid` | Medium
2 | File | `/admin.php?m=Config&a=add` | High
3 | File | `/admin/login.php` | High
4 | File | `/adminsys/index.php?load=admins&act=edit_info&act_type=add` | High
5 | File | `/advance_push/public/login` | High
6 | File | `/bin/goahead` | Medium
7 | File | `/box_code_base.c` | High
8 | File | `/cgi-bin` | Medium
9 | File | `/cgi-bin/cstecgi.cgi` | High
10 | File | `/cgi-bin/wlogin.cgi` | High
11 | File | `/configs/application.ini` | High
12 | File | `/core/MY_Security.php` | High
13 | File | `/download` | Medium
14 | File | `/dus/shopliste/index.php` | High
15 | File | `/egroupware/index.php` | High
16 | File | `/etc/passwd` | Medium
17 | File | `/event-management/index.php` | High
18 | File | `/ext/phar/phar_object.c` | High
19 | File | `/forum/away.php` | High
20 | File | `/fpui/jsp/index.jsp` | High
21 | File | `/goform/langSwitch` | High
22 | File | `/goform/setAutoPing` | High
23 | File | `/HNAP1` | Low
24 | File | `/Hospital-Management-System-master/contact.php` | High
25 | File | `/Hospital-Management-System-master/func.php` | High
26 | File | `/htdocs/cgibin` | High
27 | File | `/iisadmin` | Medium
28 | File | `/index.php` | Medium
29 | File | `/jerry-core/ecma/base/ecma-helpers.c` | High
30 | File | `/knowledgebase/view.php` | High
31 | File | `/LEPTON_stable_2.2.2/upload/admins/pages/index.php` | High
32 | File | `/Manager/index.aspx` | High
33 | File | `/mc-admin/page-edit.php` | High
34 | File | `/navigate/navigate_download.php` | High
35 | File | `/opensis/modules/users/Staff.php` | High
36 | File | `/pay-with-paypal/{id}` | High
37 | File | `/preferences/tags` | High
38 | File | `/secure/QueryComponent!Default.jspa` | High
39 | File | `/spacecom/login.php` | High
40 | File | `/var/run/jboss-eap/` | High
41 | File | `/var/www/core/controller/index.php` | High
42 | File | `/wp-json` | Medium
43 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
44 | File | `act.php` | Low
45 | File | `addfav.php` | Medium
46 | File | `addguest.cgi` | Medium
47 | File | `admin.php` | Medium
48 | File | `Admin.php` | Medium
49 | File | `admin.php?action=file&ctrl=download&path=../../1.txt` | High
50 | File | `admin/add-news.php` | High
51 | File | `admin/admin.php` | High
52 | File | `admin/file.do` | High
53 | File | `admin/index.php` | High
54 | File | `admin/index.php?id=themes&action=edit_chunk` | High
55 | File | `adsearch.php` | Medium
56 | File | `announcements.php` | High
57 | File | `ans.pl` | Low
58 | File | `apachectl` | Medium
59 | File | `app/admin/controller/themecontroller.php` | High
60 | File | `arch/arm64/kernel/sys.c` | High
61 | File | `archive_read_extract2.c` | High
62 | File | `article.php` | Medium
63 | File | `articles/index.php` | High
64 | File | `assets/download.aspx` | High
65 | File | `audio/SDL_wave.c` | High
66 | File | `auth.c` | Low
67 | File | `auth.php` | Medium
68 | File | `C.html` | Low
69 | File | `C:\dir` | Low
70 | File | `cairo-truetype-subset.c` | High
71 | File | `calc.php` | Medium
72 | File | `cart.php` | Medium
73 | File | `category.php` | Medium
74 | File | `cgi-bin` | Low
75 | File | `cgi-bin/awstats.pl` | High
76 | File | `checkuser.php` | High
77 | File | `client.c` | Medium
78 | File | `clients/editclient.php` | High
79 | File | `clone-master-clean-up.sh` | High
80 | File | `cloud.php` | Medium
81 | File | `cobc/parser.y` | High
82 | File | `CodeBrws.asp` | Medium
83 | File | `collect` | Low
84 | File | `comments.php` | Medium
85 | ... | ... | ...

There are 752 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com
* https://www.welivesecurity.com/2023/06/15/android-gravityrat-goes-after-whatsapp-backups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
