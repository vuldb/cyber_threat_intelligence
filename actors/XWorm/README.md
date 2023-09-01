# XWorm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XWorm](https://vuldb.com/?actor.xworm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xworm](https://vuldb.com/?actor.xworm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XWorm:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XWorm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.69.115.178](https://vuldb.com/?ip.3.69.115.178) | ec2-3-69-115-178.eu-central-1.compute.amazonaws.com | - | Medium
2 | [20.125.118.35](https://vuldb.com/?ip.20.125.118.35) | - | - | High
3 | [31.220.76.124](https://vuldb.com/?ip.31.220.76.124) | ip-124-76-220-31.static.contabo.net | - | High
4 | [45.139.105.105](https://vuldb.com/?ip.45.139.105.105) | - | - | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XWorm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XWorm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.kss.pid` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin.php?m=Config&a=add` | High
4 | File | `/admin/ajax.php` | High
5 | File | `/admin/ajax.php?action=save_window` | High
6 | File | `/admin/index3.php` | High
7 | File | `/adminsys/index.php?load=admins&act=edit_info&act_type=add` | High
8 | File | `/advance_push/public/login` | High
9 | File | `/bin/goahead` | Medium
10 | File | `/cgi-bin` | Medium
11 | File | `/cgi-bin/wlogin.cgi` | High
12 | File | `/config/list` | Medium
13 | File | `/configs/application.ini` | High
14 | File | `/core/MY_Security.php` | High
15 | File | `/download` | Medium
16 | File | `/dus/shopliste/index.php` | High
17 | File | `/egroupware/index.php` | High
18 | File | `/etc/passwd` | Medium
19 | File | `/event-management/index.php` | High
20 | File | `/ext/phar/phar_object.c` | High
21 | File | `/fpui/jsp/index.jsp` | High
22 | File | `/goform/langSwitch` | High
23 | File | `/goform/WifiBasicSet` | High
24 | File | `/HNAP1` | Low
25 | File | `/Hospital-Management-System-master/contact.php` | High
26 | File | `/Hospital-Management-System-master/func.php` | High
27 | File | `/htdocs/cgibin` | High
28 | File | `/iisadmin` | Medium
29 | File | `/index.php` | Medium
30 | File | `/jerry-core/ecma/base/ecma-helpers.c` | High
31 | File | `/knowledgebase/view.php` | High
32 | File | `/LEPTON_stable_2.2.2/upload/admins/pages/index.php` | High
33 | File | `/login.php` | Medium
34 | File | `/Manager/index.aspx` | High
35 | File | `/mc-admin/page-edit.php` | High
36 | File | `/news-portal-script/information.php` | High
37 | File | `/pay-with-paypal/{id}` | High
38 | File | `/reviewer/system/system/admins/manage/users/user-update.php` | High
39 | File | `/search.php` | Medium
40 | File | `/secure/QueryComponent!Default.jspa` | High
41 | File | `/showfile.php` | High
42 | File | `/spacecom/login.php` | High
43 | File | `/template/edit` | High
44 | File | `/var/run/jboss-eap/` | High
45 | File | `/var/www/core/controller/index.php` | High
46 | File | `/wp-json` | Medium
47 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
48 | File | `act.php` | Low
49 | File | `addfav.php` | Medium
50 | File | `addguest.cgi` | Medium
51 | File | `admin.color.php` | High
52 | File | `admin.php` | Medium
53 | File | `Admin.php` | Medium
54 | File | `admin/add-news.php` | High
55 | File | `admin/admin.php` | High
56 | File | `admin/courses/view_course.php` | High
57 | File | `admin/file.do` | High
58 | File | `admin/index.php` | High
59 | File | `admin/index.php?id=themes&action=edit_chunk` | High
60 | File | `adminHome.php` | High
61 | File | `adsearch.php` | Medium
62 | File | `ans.pl` | Low
63 | File | `Ap4Sample.h` | Medium
64 | File | `apachectl` | Medium
65 | File | `app/admin/controller/themecontroller.php` | High
66 | File | `arch/arm64/kernel/sys.c` | High
67 | File | `archive_read_extract2.c` | High
68 | File | `article.php` | Medium
69 | File | `articles/index.php` | High
70 | File | `assets/download.aspx` | High
71 | File | `audio/SDL_wave.c` | High
72 | File | `auth.c` | Low
73 | File | `auth.php` | Medium
74 | File | `BBStore.php` | Medium
75 | File | `C.html` | Low
76 | File | `C:\dir` | Low
77 | File | `cairo-truetype-subset.c` | High
78 | File | `calc.php` | Medium
79 | File | `cart.php` | Medium
80 | File | `category.cfm` | Medium
81 | File | `cgi-bin` | Low
82 | File | `checkuser.php` | High
83 | File | `client.c` | Medium
84 | File | `clients/editclient.php` | High
85 | ... | ... | ...

There are 752 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/07d48cef-8f74-4755-96c9-c793a8ede462
* https://bazaar.abuse.ch/sample/a19a8e6782f0008c3b10276c764962f6f27b27754d826f8d3679ef15bea122d5/
* https://threatfox.abuse.ch
* https://twitter.com/ScumBots/status/1633119068986257413

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
