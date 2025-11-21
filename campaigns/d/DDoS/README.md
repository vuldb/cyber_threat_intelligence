# DDoS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _DDoS_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DDoS:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with DDoS or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Ddostf DDoS](https://vuldb.com/?actor.ddostf_ddos) | High
2 | [Gafgyt](https://vuldb.com/?actor.gafgyt) | High
3 | [Mirai](https://vuldb.com/?actor.mirai) | High
4 | ... | ...

There are 5 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DDoS.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.97.62.136](https://vuldb.com/?ip.23.97.62.136) | - | [ShadowV2](https://vuldb.com/?actor.shadowv2) | High
2 | [23.97.62.139](https://vuldb.com/?ip.23.97.62.139) | - | [ShadowV2](https://vuldb.com/?actor.shadowv2) | High
3 | [45.61.136.130](https://vuldb.com/?ip.45.61.136.130) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
4 | [45.61.186.13](https://vuldb.com/?ip.45.61.186.13) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
5 | [46.29.166.105](https://vuldb.com/?ip.46.29.166.105) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
6 | [46.249.32.109](https://vuldb.com/?ip.46.249.32.109) | reverse.hostingbb.com | [Gafgyt](https://vuldb.com/?actor.gafgyt) | High
7 | [84.201.154.133](https://vuldb.com/?ip.84.201.154.133) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
8 | [86.105.144.83](https://vuldb.com/?ip.86.105.144.83) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
9 | [86.105.144.104](https://vuldb.com/?ip.86.105.144.104) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
10 | [86.105.144.132](https://vuldb.com/?ip.86.105.144.132) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within DDoS. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during DDoS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adds.php` | Medium
2 | File | `/admin.php` | Medium
3 | File | `/admin/blood/update/B+.php` | High
4 | File | `/admin/bwdates-report-details.php` | High
5 | File | `/admin/doctors/view_doctor.php` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/modules/bibliography/index.php` | High
8 | File | `/admin/read.php?mudi=announContent` | High
9 | File | `/admin/students/manage.php` | High
10 | File | `/admin/sys/role/list` | High
11 | File | `/adminlogin.asp` | High
12 | File | `/api/v1/chat.getThreadsList` | High
13 | File | `/app/controller/Books.php` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
16 | File | `/controller/Index.php` | High
17 | File | `/dev/audio` | Medium
18 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
19 | File | `/etc/crash` | Medium
20 | File | `/etc/master.passwd` | High
21 | File | `/etc/passwd` | Medium
22 | File | `/forum/away.php` | High
23 | File | `/goform/AddSysLogRule` | High
24 | File | `/goform/aspForm` | High
25 | File | `/goform/Diagnosis` | High
26 | File | `/goform/formSetDomainFilter` | High
27 | File | `/goform/WifiBasicSet` | High
28 | File | `/Hospital-Management-System-master/func.php` | High
29 | File | `/include/friends.inc.php` | High
30 | File | `/index.php?module=configuration/application` | High
31 | File | `/kruxton/receipt.php` | High
32 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
33 | File | `/members/view_member.php` | High
34 | File | `/mgmt/tm/util/bash` | High
35 | File | `/minio/upload` | High
36 | File | `/nova/bin/cerm` | High
37 | File | `/plesk-site-preview/` | High
38 | File | `/profile.php` | Medium
39 | File | `/scas/admin/` | Medium
40 | File | `/services/view_service.php` | High
41 | File | `/servlet/webacc` | High
42 | File | `/squashfs-root/etc/shadow` | High
43 | File | `/src/njs/src/njs_module.c` | High
44 | File | `/userRpm/popupSiteSurveyRpm.htm` | High
45 | File | `/userui/ticket_list.php` | High
46 | File | `/user_dashboard/view_donor.php` | High
47 | File | `/user_proposal_update_order.php` | High
48 | File | `/usr/5bin/su` | Medium
49 | File | `/vloggers_merch/classes/Master.php?f=delete_category` | High
50 | File | `/wp-admin/options-general.php` | High
51 | File | `/zm/index.php` | High
52 | File | `1.x/src/rogatkin/web/WarRoller.java` | High
53 | File | `abook_database.php` | High
54 | File | `accounts/inc/include.php` | High
55 | File | `ActivityOptions.java` | High
56 | File | `adaptive-images-script.php` | High
57 | File | `adclick.php` | Medium
58 | File | `additem.asp` | Medium
59 | File | `adherents/subscription/info.php` | High
60 | File | `admin.asp` | Medium
61 | File | `admin.php` | Medium
62 | File | `admin/admin.php` | High
63 | File | `admin/admin_users.php` | High
64 | File | `admin/article_save.php` | High
65 | File | `admin/header.php` | High
66 | File | `admin/index.php` | High
67 | File | `admin/login.asp` | High
68 | File | `admin/manage-comments.php` | High
69 | File | `admin/manage-news.php` | High
70 | File | `admin/plugin-settings.php` | High
71 | File | `administrator/components/com_media/helpers/media.php` | High
72 | File | `administrator/index.php` | High
73 | File | `admin_login.asp` | High
74 | File | `al_initialize.php` | High
75 | File | `annonces-p-f.php` | High
76 | File | `announce.php` | Medium
77 | ... | ... | ...

There are 681 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/58878/
* https://blog.netlab.360.com/new-ddos-botnet-wszeor/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://isc.sans.edu/diary/32308
* https://www.darktrace.com/blog/shadowv2-an-emerging-ddos-for-hire-botnet

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
