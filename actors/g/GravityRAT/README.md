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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GravityRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.kss.pid` | Medium
2 | File | `/admin.php?m=Config&a=add` | High
3 | File | `/adminsys/index.php?load=admins&act=edit_info&act_type=add` | High
4 | File | `/advance_push/public/login` | High
5 | File | `/bin/goahead` | Medium
6 | File | `/box_code_base.c` | High
7 | File | `/category/list?limit=10&offset=0&order=desc` | High
8 | File | `/cgi-bin` | Medium
9 | File | `/cgi-bin/cstecgi.cgi` | High
10 | File | `/cgi-bin/nas_sharing.cgi` | High
11 | File | `/cgi-bin/wlogin.cgi` | High
12 | File | `/configs/application.ini` | High
13 | File | `/core/MY_Security.php` | High
14 | File | `/dede/freelist_edit.php` | High
15 | File | `/download` | Medium
16 | File | `/dus/shopliste/index.php` | High
17 | File | `/egroupware/index.php` | High
18 | File | `/etc/passwd` | Medium
19 | File | `/event-management/index.php` | High
20 | File | `/ext/phar/phar_object.c` | High
21 | File | `/forum/away.php` | High
22 | File | `/fpui/jsp/index.jsp` | High
23 | File | `/goform/GetParentControlInfo` | High
24 | File | `/goform/langSwitch` | High
25 | File | `/goform/setAutoPing` | High
26 | File | `/HNAP1` | Low
27 | File | `/home/kickPlayer` | High
28 | File | `/Hospital-Management-System-master/contact.php` | High
29 | File | `/Hospital-Management-System-master/func.php` | High
30 | File | `/htdocs/cgibin` | High
31 | File | `/iisadmin` | Medium
32 | File | `/index.php` | Medium
33 | File | `/jerry-core/ecma/base/ecma-helpers.c` | High
34 | File | `/knowledgebase/view.php` | High
35 | File | `/LEPTON_stable_2.2.2/upload/admins/pages/index.php` | High
36 | File | `/Manager/index.aspx` | High
37 | File | `/mc-admin/page-edit.php` | High
38 | File | `/navigate/navigate_download.php` | High
39 | File | `/opensis/modules/users/Staff.php` | High
40 | File | `/pay-with-paypal/{id}` | High
41 | File | `/secure/QueryComponent!Default.jspa` | High
42 | File | `/spacecom/login.php` | High
43 | File | `/text/pdf/PdfReader.java` | High
44 | File | `/var/run/jboss-eap/` | High
45 | File | `/var/www/core/controller/index.php` | High
46 | File | `/wp-json` | Medium
47 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
48 | File | `act.php` | Low
49 | File | `addfav.php` | Medium
50 | File | `addguest.cgi` | Medium
51 | File | `admin.php` | Medium
52 | File | `Admin.php` | Medium
53 | File | `admin.php?action=file&ctrl=download&path=../../1.txt` | High
54 | File | `admin/add-news.php` | High
55 | File | `admin/admin.php` | High
56 | File | `admin/file.do` | High
57 | File | `admin/index.php` | High
58 | File | `admin/index.php?id=themes&action=edit_chunk` | High
59 | File | `adsearch.php` | Medium
60 | File | `announcements.php` | High
61 | File | `ans.pl` | Low
62 | File | `apachectl` | Medium
63 | File | `app/admin/controller/themecontroller.php` | High
64 | File | `arch/arm64/kernel/sys.c` | High
65 | File | `archive_read_extract2.c` | High
66 | File | `article.php` | Medium
67 | File | `articles/index.php` | High
68 | File | `assets/download.aspx` | High
69 | File | `audio/SDL_wave.c` | High
70 | File | `auth.c` | Low
71 | File | `auth.php` | Medium
72 | File | `C.html` | Low
73 | File | `C:\dir` | Low
74 | File | `cairo-truetype-subset.c` | High
75 | File | `calc.php` | Medium
76 | File | `cart.php` | Medium
77 | File | `cgi-bin` | Low
78 | File | `cgi-bin/awstats.pl` | High
79 | File | `checkuser.php` | High
80 | File | `client.c` | Medium
81 | File | `clients/editclient.php` | High
82 | File | `clone-master-clean-up.sh` | High
83 | File | `cloud.php` | Medium
84 | ... | ... | ...

There are 738 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
