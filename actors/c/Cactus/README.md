# Cactus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cactus](https://vuldb.com/?actor.cactus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cactus](https://vuldb.com/?actor.cactus)

## Campaigns

The following _campaigns_ are known and can be associated with Cactus:

* CVE-2023-38035
* CVE-2023-41266 / CVE-2023-41265 / CVE-2023-48365

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cactus:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [BE](https://vuldb.com/?country.be)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cactus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.227.203.210](https://vuldb.com/?ip.23.227.203.210) | 23-227-203-210.static.hvvc.us | - | High
2 | [45.61.136.79](https://vuldb.com/?ip.45.61.136.79) | - | CVE-2023-38035 | High
3 | [45.61.136.127](https://vuldb.com/?ip.45.61.136.127) | - | CVE-2023-38035 | High
4 | [45.61.137.65](https://vuldb.com/?ip.45.61.137.65) | - | - | High
5 | [45.61.138.99](https://vuldb.com/?ip.45.61.138.99) | - | CVE-2023-38035 | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cactus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cactus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/add-students.php` | High
3 | File | `/addcategory.php` | High
4 | File | `/addclient1.php` | High
5 | File | `/addproduct.php` | High
6 | File | `/admin-cp/theme/editor/default` | High
7 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
8 | File | `/admin/admin-add-employee.php` | High
9 | File | `/admin/admin-update-employee.php` | High
10 | File | `/admin/ajax.php?action=delete_user` | High
11 | File | `/admin/ajax.php?action=login` | High
12 | File | `/admin/ajax.php?action=save_settings` | High
13 | File | `/admin/assets/` | High
14 | File | `/admin/category_save.php` | High
15 | File | `/admin/check_admin.php` | High
16 | File | `/admin/clients/` | High
17 | File | `/admin/config_ISCGroupNoCache.php` | High
18 | File | `/admin/config_time_sync.php` | High
19 | File | `/admin/dialog/select_images_post.php` | High
20 | File | `/admin/emp-profile-avatar.php` | High
21 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
22 | File | `/admin/forms/option_lists/edit.php` | High
23 | File | `/admin/get_balance.php` | High
24 | File | `/admin/get_price.php` | High
25 | File | `/admin/index.php` | High
26 | File | `/admin/inquiries/view_inquiry.php` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/manage_complaint.php` | High
29 | File | `/admin/manage_model.php` | High
30 | File | `/admin/manage_user.php` | High
31 | File | `/admin/media_folders` | High
32 | File | `/admin/member_save.php` | High
33 | File | `/admin/menu.php` | High
34 | File | `/admin/mod_reports/index.php` | High
35 | File | `/admin/mod_reports/printreport.php` | High
36 | File | `/admin/mod_reservation/controller.php` | High
37 | File | `/admin/mod_reservation/index.php` | High
38 | File | `/admin/mod_room/controller.php?action=add` | High
39 | File | `/admin/mod_room/index.php` | High
40 | File | `/admin/mod_users/index.php` | High
41 | File | `/admin/orders/controller.php` | High
42 | File | `/admin/orders/index.php` | High
43 | File | `/admin/pages/` | High
44 | File | `/admin/pages/list` | High
45 | File | `/admin/products/index.php` | High
46 | File | `/admin/settings/index.php?page=accounts` | High
47 | File | `/admin/system.html` | High
48 | File | `/admin/system.php` | High
49 | File | `/admin/view_reserved.php` | High
50 | File | `/admin/view_sendlist.php` | High
51 | File | `/ajax.php` | Medium
52 | File | `/ajax.php?action=delete_block` | High
53 | File | `/ajax.php?action=load_answered` | High
54 | File | `/ajax.php?action=login` | High
55 | File | `/ajax.php?action=save_establishment` | High
56 | File | `/ajax.php?action=save_user` | High
57 | File | `/ajax/get_patient_history.php` | High
58 | File | `/api/Common/uploadFile` | High
59 | File | `/api/deploy/upload` | High
60 | File | `/api/deploy/upload /api/database/upload` | High
61 | File | `/api/dept` | Medium
62 | File | `/api/dept/build` | High
63 | File | `/api/file/downloadfile` | High
64 | File | `/api/file/downloadUrl` | High
65 | File | `/api/file/multiDownload` | High
66 | File | `/api/role` | Medium
67 | File | `/api/user` | Medium
68 | File | `/App/Core/Extend/Function/ydLib.php` | High
69 | File | `/apply/index.php` | High
70 | File | `/attendancelist.php` | High
71 | File | `/AttendanceMonitoring/department/index.php` | High
72 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
73 | File | `/authMonitCallcenter` | High
74 | File | `/bolt/editcontent/showcases` | High
75 | File | `/branch_viewmore.php` | High
76 | File | `/candidate/controller.php` | High
77 | File | `/cap.js` | Low
78 | File | `/cgi-bin/cstecgi.cgi` | High
79 | ... | ... | ...

There are 696 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://northwave-cybersecurity.com/whitepapers-articles/pricksense-how-cactus-exploits-qlik-sense
* https://www.arcticwolf.com/resources/blog/qlik-sense-exploited-in-cactus-ransomware-campaign/
* https://www.bitdefender.com/blog/businessinsights/cactus-analyzing-a-coordinated-ransomware-attack-on-corporate-networks/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
