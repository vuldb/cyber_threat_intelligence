# DDoS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _DDoS_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DDoS:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with DDoS or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Ddostf DDoS](https://vuldb.com/?actor.ddostf_ddos) | High
2 | [Gafgyt](https://vuldb.com/?actor.gafgyt) | High
3 | [Mirai](https://vuldb.com/?actor.mirai) | High
4 | ... | ...

There are 3 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DDoS.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.61.136.130](https://vuldb.com/?ip.45.61.136.130) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
2 | [45.61.186.13](https://vuldb.com/?ip.45.61.186.13) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
3 | [46.29.166.105](https://vuldb.com/?ip.46.29.166.105) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
4 | [46.249.32.109](https://vuldb.com/?ip.46.249.32.109) | reverse.hostingbb.com | [Gafgyt](https://vuldb.com/?actor.gafgyt) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within DDoS. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during DDoS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin.php` | Medium
3 | File | `/admin/doctors/view_doctor.php` | High
4 | File | `/admin/modules/bibliography/index.php` | High
5 | File | `/admin/students/manage.php` | High
6 | File | `/adminlogin.asp` | High
7 | File | `/api/v1/chat.getThreadsList` | High
8 | File | `/app/controller/Books.php` | High
9 | File | `/controller/Index.php` | High
10 | File | `/coreframe/app/content/admin/content.php` | High
11 | File | `/dev/audio` | Medium
12 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
13 | File | `/etc/crash` | Medium
14 | File | `/etc/master.passwd` | High
15 | File | `/etc/passwd` | Medium
16 | File | `/forum/away.php` | High
17 | File | `/goform/AddSysLogRule` | High
18 | File | `/goform/Diagnosis` | High
19 | File | `/goform/WifiBasicSet` | High
20 | File | `/Hospital-Management-System-master/contact.php` | High
21 | File | `/include/friends.inc.php` | High
22 | File | `/index.php?module=configuration/application` | High
23 | File | `/kruxton/receipt.php` | High
24 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
25 | File | `/members/view_member.php` | High
26 | File | `/mgmt/tm/util/bash` | High
27 | File | `/nova/bin/cerm` | High
28 | File | `/plesk-site-preview/` | High
29 | File | `/scas/admin/` | Medium
30 | File | `/services/view_service.php` | High
31 | File | `/servlet/webacc` | High
32 | File | `/sitemagic/upgrade.php` | High
33 | File | `/src/njs/src/njs_module.c` | High
34 | File | `/userui/ticket_list.php` | High
35 | File | `/user_proposal_update_order.php` | High
36 | File | `/usr/5bin/su` | Medium
37 | File | `/vloggers_merch/classes/Master.php?f=delete_category` | High
38 | File | `/wp-admin/options-general.php` | High
39 | File | `/zm/index.php` | High
40 | File | `1.x/src/rogatkin/web/WarRoller.java` | High
41 | File | `abook_database.php` | High
42 | File | `accounts/inc/include.php` | High
43 | File | `ActivityOptions.java` | High
44 | File | `adaptive-images-script.php` | High
45 | File | `adclick.php` | Medium
46 | File | `additem.asp` | Medium
47 | File | `adherents/subscription/info.php` | High
48 | File | `admin.asp` | Medium
49 | File | `admin.php` | Medium
50 | File | `admin/admin.php` | High
51 | File | `admin/admin_users.php` | High
52 | File | `admin/article_save.php` | High
53 | File | `admin/header.php` | High
54 | File | `admin/index.php` | High
55 | File | `admin/login.asp` | High
56 | File | `admin/manage-comments.php` | High
57 | File | `admin/manage-news.php` | High
58 | File | `admin/plugin-settings.php` | High
59 | File | `administrator/components/com_media/helpers/media.php` | High
60 | File | `administrator/index.php` | High
61 | File | `admin_login.asp` | High
62 | File | `al_initialize.php` | High
63 | File | `annonces-p-f.php` | High
64 | File | `announce.php` | Medium
65 | File | `announcement.php` | High
66 | File | `announcements.php` | High
67 | File | `app/admin/routing/edit-bgp-mapping-search.php` | High
68 | File | `app/models/user.rb` | High
69 | File | `application/config/config.php` | High
70 | File | `application/controllers/basedata/inventory.php` | High
71 | File | `apply.cgi` | Medium
72 | File | `apps/app_article/controller/rating.php` | High
73 | File | `article.php` | Medium
74 | File | `articles.php` | Medium
75 | File | `artikel_anzeige.php` | High
76 | File | `AudioFlinger.cpp` | High
77 | File | `auktion.cgi` | Medium
78 | File | `authfiles/login.asp` | High
79 | ... | ... | ...

There are 692 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/58878/
* https://blog.netlab.360.com/new-ddos-botnet-wszeor/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
