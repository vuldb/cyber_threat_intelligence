# Microsoft Exchange - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Microsoft Exchange_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Microsoft Exchange:

* [US](https://vuldb.com/?country.us)
* [JP](https://vuldb.com/?country.jp)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 31 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Microsoft Exchange or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Tortilla](https://vuldb.com/?actor.tortilla) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Microsoft Exchange.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [54.221.65.242](https://vuldb.com/?ip.54.221.65.242) | ec2-54-221-65-242.compute-1.amazonaws.com | [Tortilla](https://vuldb.com/?actor.tortilla) | Medium
4 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Microsoft Exchange. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-27, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Microsoft Exchange. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/academic/studenview_left.php` | High
2 | File | `/Admin/add-student.php` | High
3 | File | `/admin/add_user_modal.php` | High
4 | File | `/admin/admin-profile.php` | High
5 | File | `/admin/article/article-add.php` | High
6 | File | `/admin/article/article-edit-run.php` | High
7 | File | `/admin/category/cate-edit-run.php` | High
8 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
9 | File | `/admin/inquiries/view_inquiry.php` | High
10 | File | `/admin/modal_add_product.php` | High
11 | File | `/admin/new-content` | High
12 | File | `/admin/read.php?mudi=announContent` | High
13 | File | `/admin/services/manage_service.php` | High
14 | File | `/admin/suppliers/view_details.php` | High
15 | File | `/admin/transactions/track_shipment.php` | High
16 | File | `/admin/upload.php` | High
17 | File | `/admin/user/manage_user.php` | High
18 | File | `/alarm_pi/alarmService.php` | High
19 | File | `/api/crontab` | Medium
20 | File | `/api/es/admin/v3/security/user/1` | High
21 | File | `/api/ping` | Medium
22 | File | `/api/RecordingList/DownloadRecord?file=` | High
23 | File | `/api/runscript` | High
24 | File | `/api/sys/login` | High
25 | File | `/api/sys/set_passwd` | High
26 | File | `/application/common.php#action_log` | High
27 | File | `/asms/admin/products/manage_product.php` | High
28 | File | `/asms/products/view_product.php` | High
29 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
30 | File | `/category.php` | High
31 | File | `/changeimage.php` | High
32 | File | `/classes/Master.php?f=delete_service` | High
33 | File | `/config/getuser` | High
34 | File | `/config/list` | Medium
35 | File | `/dashboard/snapshot/*?orgId=0` | High
36 | File | `/dosen/data` | Medium
37 | File | `/E-mobile/App/System/File/downfile.php` | High
38 | File | `/export` | Low
39 | File | `/forum/away.php` | High
40 | File | `/gena.cgi` | Medium
41 | File | `/general/ipanel/menu_code.php?MENU_TYPE=FAV` | High
42 | File | `/home/cavesConsole` | High
43 | File | `/home/kickPlayer` | High
44 | File | `/home/masterConsole` | High
45 | File | `/home/sendBroadcast` | High
46 | File | `/inc/jquery/uploadify/uploadify.php` | High
47 | File | `/include/dialog/select_templets_post.php` | High
48 | File | `/index.php/sysmanage/Login/login_auth/` | High
49 | File | `/jurusanmatkul/data` | High
50 | File | `/kelasdosen/data` | High
51 | File | `/lan.asp` | Medium
52 | ... | ... | ...

There are 457 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2021/11/babuk-exploits-exchange.html
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/09/threat-advisory-exchange-server-vulns.txt
* https://isc.sans.edu/forums/diary/Scanning+for+Microsoft+Exchange+eDiscovery/27748/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
