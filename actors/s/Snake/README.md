# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | - | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | - | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | Snake | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snake_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/add-students.php` | High
3 | File | `/addproduct.php` | High
4 | File | `/admin` | Low
5 | File | `/admin-cp/theme/editor/default` | High
6 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
7 | File | `/admin/?page=user/list` | High
8 | File | `/admin/ajax.php?action=delete_user` | High
9 | File | `/admin/ajax.php?action=login` | High
10 | File | `/admin/ajax.php?action=save_settings` | High
11 | File | `/admin/category_save.php` | High
12 | File | `/Admin/changepassword.php` | High
13 | File | `/admin/clients` | High
14 | File | `/admin/clients/` | High
15 | File | `/admin/config_ISCGroupNoCache.php` | High
16 | File | `/admin/config_MT.php?action=delete` | High
17 | File | `/admin/config_time_sync.php` | High
18 | File | `/admin/content` | High
19 | File | `/admin/court` | Medium
20 | File | `/admin/expense-type` | High
21 | File | `/admin/foreigner-bwdates-reports-details.php` | High
22 | File | `/admin/forgot-password.php` | High
23 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
24 | File | `/admin/forms/option_lists/edit.php` | High
25 | File | `/admin/get_balance.php` | High
26 | File | `/admin/get_price.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/index.php?page=manage_product` | High
29 | File | `/admin/login.php` | High
30 | File | `/admin/maintenance/manage_brand.php` | High
31 | File | `/admin/manage_model.php` | High
32 | File | `/admin/manage_user.php` | High
33 | File | `/admin/media_folders` | High
34 | File | `/admin/member_save.php` | High
35 | File | `/admin/menu.php` | High
36 | File | `/admin/mod_reports/index.php` | High
37 | File | `/admin/mod_reports/printreport.php` | High
38 | File | `/admin/mod_reservation/controller.php` | High
39 | File | `/admin/mod_reservation/index.php` | High
40 | File | `/admin/mod_room/controller.php?action=add` | High
41 | File | `/admin/mod_room/index.php` | High
42 | File | `/admin/mod_users/index.php` | High
43 | File | `/admin/normal-search.php` | High
44 | File | `/admin/orders/controller.php` | High
45 | File | `/admin/orders/index.php` | High
46 | File | `/admin/pages/` | High
47 | File | `/admin/products/index.php` | High
48 | File | `/admin/role` | Medium
49 | File | `/admin/search-directory.php.` | High
50 | File | `/admin/settings/index.php?page=accounts` | High
51 | File | `/admin/system.html` | High
52 | File | `/admin/tasks` | Medium
53 | File | `/admin/tax` | Medium
54 | File | `/admin/template` | High
55 | File | `/admin/view_reserved.php` | High
56 | File | `/admin/view_sendlist.php` | High
57 | File | `/admin_class.php` | High
58 | File | `/ajax.php` | Medium
59 | File | `/ajax.php?action=load_answered` | High
60 | File | `/ajax.php?action=login` | High
61 | File | `/ajax.php?action=save_establishment` | High
62 | File | `/ajax.php?action=save_user` | High
63 | File | `/api/Common/uploadFile` | High
64 | File | `/api/deploy/upload` | High
65 | File | `/api/deploy/upload /api/database/upload` | High
66 | File | `/api/dept` | Medium
67 | File | `/api/dept/build` | High
68 | File | `/api/file/downloadfile` | High
69 | File | `/api/file/downloadUrl` | High
70 | File | `/api/file/multiDownload` | High
71 | File | `/api/role` | Medium
72 | File | `/api/v2/maps` | Medium
73 | File | `/App/Core/Extend/Function/ydLib.php` | High
74 | File | `/apply/index.php` | High
75 | File | `/assoc_table.php` | High
76 | File | `/AttendanceMonitoring/department/index.php` | High
77 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
78 | File | `/authMonitCallcenter` | High
79 | File | `/bolt/editcontent/showcases` | High
80 | File | `/book-services.php` | High
81 | File | `/branch_viewmore.php` | High
82 | File | `/candidate/controller.php` | High
83 | File | `/cap.js` | Low
84 | File | `/catalog/all-products` | High
85 | File | `/cgi-bin/cstecgi.cgi` | High
86 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
87 | File | `/cgi-bin/ExportSettings.sh` | High
88 | File | `/cgi-bin/nas_sharing.cgi` | High
89 | File | `/cgi-bin/photocenter_mgr.cgi` | High
90 | File | `/change_password.php` | High
91 | File | `/classes/Master.php` | High
92 | File | `/classes/Master.php?f=delete_category` | High
93 | File | `/classes/Master.php?f=load_registration` | High
94 | File | `/classes/Master.php?f=log_employee` | High
95 | File | `/classes/Master.php?f=log_visitor` | High
96 | File | `/classes/Master.php?f=save_package` | High
97 | File | `/classes/SystemSettings.php?f=update_settings` | High
98 | File | `/classes/Users.php?f=delete` | High
99 | File | `/classes/Users.php?f=register_user` | High
100 | ... | ... | ...

There are 889 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
