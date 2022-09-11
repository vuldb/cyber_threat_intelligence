# UAC-0056 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0056](https://vuldb.com/?actor.uac-0056). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0056](https://vuldb.com/?actor.uac-0056)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-0056:

* Cobalt Strike
* GraphSteel/GrimPlant
* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0056:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0056.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.42.185.63](https://vuldb.com/?ip.31.42.185.63) | dedicated.vsys.host | Ukraine | High
2 | [45.84.0.116](https://vuldb.com/?ip.45.84.0.116) | n5336.md | - | High
3 | [45.146.164.37](https://vuldb.com/?ip.45.146.164.37) | - | Ukraine | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0056_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0056. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin.php` | Medium
3 | File | `/admin/?page=system_info/contact_info` | High
4 | File | `/admin/doctors/view_doctor.php` | High
5 | File | `/admin/login.php` | High
6 | File | `/admin/modules/bibliography/index.php` | High
7 | File | `/adminlogin.asp` | High
8 | File | `/app/controller/Books.php` | High
9 | File | `/aqpg/users/login.php` | High
10 | File | `/cgi/get_param.cgi` | High
11 | File | `/controller/Index.php` | High
12 | File | `/coreframe/app/content/admin/content.php` | High
13 | File | `/debug/pprof` | Medium
14 | File | `/dl/dl_print.php` | High
15 | File | `/etc/master.passwd` | High
16 | File | `/etc/passwd` | Medium
17 | File | `/goform/aspForm` | High
18 | File | `/hocms/classes/Master.php?f=delete_collection` | High
19 | File | `/Hospital-Management-System-master/contact.php` | High
20 | File | `/include/friends.inc.php` | High
21 | File | `/index.php` | Medium
22 | File | `/members/view_member.php` | High
23 | File | `/plesk-site-preview/` | High
24 | File | `/school/model/get_admin_profile.php` | High
25 | File | `/servlet/webacc` | High
26 | File | `/sitemagic/upgrade.php` | High
27 | File | `/student-grading-system/rms.php?page=grade` | High
28 | File | `/timeline2.php` | High
29 | File | `/uncpath/` | Medium
30 | File | `/userui/ticket_list.php` | High
31 | File | `/usr/bin/pkexec` | High
32 | File | `/wp-admin/options-general.php` | High
33 | File | `/zm/index.php` | High
34 | File | `/_next` | Low
35 | File | `abook_database.php` | High
36 | File | `accounts/inc/include.php` | High
37 | File | `adaptive-images-script.php` | High
38 | File | `additem.asp` | Medium
39 | File | `adherents/subscription/info.php` | High
40 | File | `admin.asp` | Medium
41 | File | `admin.php` | Medium
42 | File | `admin/admin.php` | High
43 | File | `admin/admin_users.php` | High
44 | File | `admin/general.php` | High
45 | File | `admin/header.php` | High
46 | File | `admin/inc/change_action.php` | High
47 | File | `admin/index.php` | High
48 | File | `admin/info.php` | High
49 | File | `admin/login.asp` | High
50 | File | `admin/manage-comments.php` | High
51 | File | `admin/manage-news.php` | High
52 | File | `admin/plugin-settings.php` | High
53 | File | `admin/specials.php` | High
54 | File | `admin/upload.php` | High
55 | File | `admin:de` | Medium
56 | File | `admincp/attachment.php&do=rebuild&type` | High
57 | File | `admincp/auth/checklogin.php` | High
58 | File | `admincp/auth/secure.php` | High
59 | File | `administrator/components/com_media/helpers/media.php` | High
60 | File | `administrator/index.php` | High
61 | File | `admin_login.asp` | High
62 | File | `ajax_url.php` | Medium
63 | File | `album_portal.php` | High
64 | File | `al_initialize.php` | High
65 | File | `anjel.index.php` | High
66 | File | `annonces-p-f.php` | High
67 | File | `announce.php` | Medium
68 | File | `announcement.php` | High
69 | File | `announcements.php` | High
70 | File | `app/admin/routing/edit-bgp-mapping-search.php` | High
71 | File | `application/config/config.php` | High
72 | File | `apply.cgi` | Medium
73 | File | `apps/app_article/controller/rating.php` | High
74 | File | `article.php` | Medium
75 | File | `articles.php` | Medium
76 | File | `artikel_anzeige.php` | High
77 | File | `Atom.CMS_admin_ajax_pages.php` | High
78 | File | `auktion.cgi` | Medium
79 | File | `auth.php` | Medium
80 | File | `authfiles/login.asp` | High
81 | File | `basket.php` | Medium
82 | File | `books.php` | Medium
83 | File | `browse-category.php` | High
84 | File | `browse.php` | Medium
85 | File | `browse_videos.php` | High
86 | File | `BrudaNews/BrudaGB` | High
87 | File | `bwlist_inc.html` | High
88 | File | `calendar.php` | Medium
89 | File | `callme_page.php` | High
90 | File | `cart.php` | Medium
91 | File | `cart_add.php` | Medium
92 | File | `case.filemanager.php` | High
93 | File | `catalog.php` | Medium
94 | File | `catalogshop.php` | High
95 | File | `catalogue.asp` | High
96 | File | `category.cfm` | Medium
97 | ... | ... | ...

There are 861 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/533/unc2589-iocs/
* https://blog.malwarebytes.com/threat-intelligence/2022/07/cobalt-strikes-again-uac-0056-continues-to-target-ukraine-in-its-latest-campaign/
* https://cert.gov.ua/article/18419
* https://cert.gov.ua/article/37704
* https://cert.gov.ua/article/38374
* https://cert.gov.ua/article/39882
* https://community.blueliv.com/#!/s/624be71d82df413eb235593a
* https://unit42.paloaltonetworks.com/ukraine-targeted-outsteel-saintbot/
* https://www.sentinelone.com/blog/threat-actor-uac-0056-targeting-ukraine-with-fake-translation-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
