# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Snake_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 1 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Snake or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Snake](https://vuldb.com/?actor.snake) | High
2 | [Snake Keylogger](https://vuldb.com/?actor.snake_keylogger) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | [Snake](https://vuldb.com/?actor.snake) | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | [Snake](https://vuldb.com/?actor.snake) | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | [Snake](https://vuldb.com/?actor.snake) | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | [Snake](https://vuldb.com/?actor.snake) | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=tracks` | High
3 | File | `/abcd/opac/php/otros_sitios.php` | High
4 | File | `/Actions.php?a=login` | High
5 | File | `/add-students.php` | High
6 | File | `/addcategory.php` | High
7 | File | `/addclient1.php` | High
8 | File | `/admin-cp/theme/editor/default` | High
9 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
10 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
11 | File | `/admin/about_edit.php?action=modify` | High
12 | File | `/admin/admin-add-employee.php` | High
13 | File | `/admin/ajax.php?action=login` | High
14 | File | `/admin/ajax.php?action=save_settings` | High
15 | File | `/admin/assets/` | High
16 | File | `/admin/categories/manage_category.php` | High
17 | File | `/admin/category_save.php` | High
18 | File | `/admin/class.php?dowhat=modifyclass` | High
19 | File | `/admin/clients/` | High
20 | File | `/admin/config_ISCGroupNoCache.php` | High
21 | File | `/admin/config_time_sync.php` | High
22 | File | `/admin/dialog/select_images_post.php` | High
23 | File | `/admin/edit_area.php` | High
24 | File | `/admin/educloud/videobind.html` | High
25 | File | `/admin/emp-profile-avatar.php` | High
26 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
27 | File | `/admin/forms/option_lists/edit.php` | High
28 | File | `/admin/get_balance.php` | High
29 | File | `/admin/get_price.php` | High
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
41 | File | `/admin/mod_room/index.php` | High
42 | File | `/admin/mod_users/index.php` | High
43 | File | `/admin/orders/controller.php` | High
44 | File | `/admin/orders/index.php` | High
45 | File | `/admin/pages/` | High
46 | File | `/admin/products/index.php` | High
47 | File | `/Admin/registration.php` | High
48 | File | `/admin/settings/index.php?page=accounts` | High
49 | File | `/admin/system.html` | High
50 | File | `/admin/system.php` | High
51 | File | `/admin/template/edit` | High
52 | File | `/admin/template/update` | High
53 | File | `/admin/user/user-move-run.php` | High
54 | File | `/admin/view_reserved.php` | High
55 | File | `/ajax.php` | Medium
56 | File | `/ajax.php?action=delete_deductions` | High
57 | File | `/ajax.php?action=load_answered` | High
58 | File | `/ajax.php?action=login` | High
59 | File | `/ajax.php?action=save_establishment` | High
60 | File | `/ajax.php?action=save_user` | High
61 | File | `/ajax/checkin.php` | High
62 | File | `/ajax/chpwd.php` | High
63 | File | `/ajax/getBasicInfo.php` | High
64 | File | `/api/Common/uploadFile` | High
65 | File | `/api/deploy/upload` | High
66 | File | `/api/deploy/upload /api/database/upload` | High
67 | File | `/api/dept` | Medium
68 | File | `/api/dept/build` | High
69 | File | `/api/file/downloadfile` | High
70 | File | `/api/file/downloadUrl` | High
71 | File | `/api/file/multiDownload` | High
72 | File | `/api/files/recipepictures/` | High
73 | File | `/api/role` | Medium
74 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
75 | File | `/api/system/user?deptId=1&page=1&size=10` | High
76 | File | `/App/Core/Extend/Function/ydLib.php` | High
77 | File | `/apply/index.php` | High
78 | File | `/AttendanceMonitoring/department/index.php` | High
79 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
80 | File | `/authMonitCallcenter` | High
81 | File | `/bolt/editcontent/showcases` | High
82 | File | `/branch_viewmore.php` | High
83 | File | `/buscar_integrada.php` | High
84 | File | `/candidate/controller.php` | High
85 | File | `/cap.js` | Low
86 | ... | ... | ...

There are 759 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.fortinet.com/blog/threat-research/deep-analysis-of-snake-keylogger-new-variant
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
