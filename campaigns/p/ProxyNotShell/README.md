# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/add-students.php` | High
3 | File | `/addcategory.php` | High
4 | File | `/addclient1.php` | High
5 | File | `/addproduct.php` | High
6 | File | `/admin` | Low
7 | File | `/admin-cp/theme/editor/default` | High
8 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
9 | File | `/admin/?page=user/list` | High
10 | File | `/admin/admin-add-employee.php` | High
11 | File | `/admin/ajax.php?action=delete_user` | High
12 | File | `/admin/ajax.php?action=login` | High
13 | File | `/admin/ajax.php?action=save_settings` | High
14 | File | `/admin/category_save.php` | High
15 | File | `/admin/clients/` | High
16 | File | `/admin/config_ISCGroupNoCache.php` | High
17 | File | `/admin/config_MT.php?action=delete` | High
18 | File | `/admin/config_time_sync.php` | High
19 | File | `/admin/content` | High
20 | File | `/admin/dialog/select_images_post.php` | High
21 | File | `/admin/emp-profile-avatar.php` | High
22 | File | `/admin/foreigner-bwdates-reports-details.php` | High
23 | File | `/admin/forgot-password.php` | High
24 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
25 | File | `/admin/forms/option_lists/edit.php` | High
26 | File | `/admin/get_balance.php` | High
27 | File | `/admin/get_price.php` | High
28 | File | `/admin/index.php` | High
29 | File | `/admin/index.php?page=manage_product` | High
30 | File | `/admin/inquiries/view_inquiry.php` | High
31 | File | `/admin/login.php` | High
32 | File | `/admin/manage_model.php` | High
33 | File | `/admin/manage_user.php` | High
34 | File | `/admin/media_folders` | High
35 | File | `/admin/member_save.php` | High
36 | File | `/admin/menu.php` | High
37 | File | `/admin/mod_reports/index.php` | High
38 | File | `/admin/mod_reports/printreport.php` | High
39 | File | `/admin/mod_reservation/controller.php` | High
40 | File | `/admin/mod_reservation/index.php` | High
41 | File | `/admin/mod_room/controller.php?action=add` | High
42 | File | `/admin/mod_room/index.php` | High
43 | File | `/admin/mod_users/index.php` | High
44 | File | `/admin/normal-search.php` | High
45 | File | `/admin/orders/controller.php` | High
46 | File | `/admin/orders/index.php` | High
47 | File | `/admin/pages/` | High
48 | File | `/admin/products/index.php` | High
49 | File | `/admin/settings/index.php?page=accounts` | High
50 | File | `/admin/system.html` | High
51 | File | `/admin/system.php` | High
52 | File | `/admin/template` | High
53 | File | `/admin/view_reserved.php` | High
54 | File | `/admin/view_sendlist.php` | High
55 | File | `/ajax.php` | Medium
56 | File | `/ajax.php?action=load_answered` | High
57 | File | `/ajax.php?action=login` | High
58 | File | `/ajax.php?action=save_establishment` | High
59 | File | `/ajax.php?action=save_user` | High
60 | File | `/api/Common/uploadFile` | High
61 | File | `/api/deploy/upload` | High
62 | File | `/api/deploy/upload /api/database/upload` | High
63 | File | `/api/dept` | Medium
64 | File | `/api/dept/build` | High
65 | File | `/api/file/downloadfile` | High
66 | File | `/api/file/downloadUrl` | High
67 | File | `/api/file/multiDownload` | High
68 | File | `/api/role` | Medium
69 | File | `/api/v2/maps` | Medium
70 | File | `/App/Core/Extend/Function/ydLib.php` | High
71 | File | `/apply/index.php` | High
72 | File | `/assoc_table.php` | High
73 | File | `/AttendanceMonitoring/department/index.php` | High
74 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
75 | File | `/authMonitCallcenter` | High
76 | File | `/bolt/editcontent/showcases` | High
77 | File | `/book-services.php` | High
78 | File | `/branch_viewmore.php` | High
79 | File | `/candidate/controller.php` | High
80 | File | `/cap.js` | Low
81 | File | `/cgi-bin/cstecgi.cgi` | High
82 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
83 | File | `/cgi-bin/ExportSettings.sh` | High
84 | File | `/cgi-bin/p1_ftpserver.php` | High
85 | File | `/cgi-bin/photocenter_mgr.cgi` | High
86 | File | `/change_password.php` | High
87 | File | `/classes/Master.php` | High
88 | File | `/classes/Master.php?f=delete_category` | High
89 | File | `/classes/Master.php?f=log_employee` | High
90 | File | `/classes/Master.php?f=log_visitor` | High
91 | ... | ... | ...

There are 800 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
