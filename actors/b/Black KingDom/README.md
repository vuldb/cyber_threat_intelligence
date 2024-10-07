# Black KingDom - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Black KingDom](https://vuldb.com/?actor.black_kingdom). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.black_kingdom](https://vuldb.com/?actor.black_kingdom)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Black KingDom:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Black KingDom.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [104.21.89.10](https://vuldb.com/?ip.104.21.89.10) | - | - | High
2 | [172.64.80.0](https://vuldb.com/?ip.172.64.80.0) | - | - | High
3 | [185.220.101.204](https://vuldb.com/?ip.185.220.101.204) | tor-exit-204.relayon.org | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Black KingDom_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Black KingDom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/?page=tracks` | High
4 | File | `/abcd/opac/php/otros_sitios.php` | High
5 | File | `/Actions.php?a=login` | High
6 | File | `/addcategory.php` | High
7 | File | `/addclient1.php` | High
8 | File | `/admin-cp/theme/editor/default` | High
9 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
10 | File | `/admin/` | Low
11 | File | `/admin/about_edit.php?action=modify` | High
12 | File | `/Admin/add-admin.php` | High
13 | File | `/admin/admin-add-employee.php` | High
14 | File | `/admin/ajax.php?action=login` | High
15 | File | `/admin/ajax.php?action=save_settings` | High
16 | File | `/admin/assets/` | High
17 | File | `/admin/blood/update/B+.php` | High
18 | File | `/admin/blood/update/o-.php` | High
19 | File | `/admin/categories/manage_category.php` | High
20 | File | `/admin/category_save.php` | High
21 | File | `/admin/class.php?dowhat=modifyclass` | High
22 | File | `/admin/dialog/select_images_post.php` | High
23 | File | `/admin/edit_area.php` | High
24 | File | `/admin/edit_manufacturer.php` | High
25 | File | `/admin/educloud/videobind.html` | High
26 | File | `/admin/emp-profile-avatar.php` | High
27 | File | `/admin/inquiries/view_details.php` | High
28 | File | `/admin/inquiries/view_inquiry.php` | High
29 | File | `/admin/login.php` | High
30 | File | `/admin/maintenance/manage_department.php` | High
31 | File | `/admin/manage_model.php` | High
32 | File | `/admin/member_save.php` | High
33 | File | `/admin/menu.php` | High
34 | File | `/admin/mod_reports/index.php` | High
35 | File | `/admin/mod_reports/printreport.php` | High
36 | File | `/admin/mod_reservation/controller.php` | High
37 | File | `/admin/mod_reservation/index.php` | High
38 | File | `/admin/mod_room/index.php` | High
39 | File | `/admin/mod_users/index.php` | High
40 | File | `/admin/orders/controller.php` | High
41 | File | `/admin/orders/index.php` | High
42 | File | `/admin/products/index.php` | High
43 | File | `/Admin/registration.php` | High
44 | File | `/admin/robot.php` | High
45 | File | `/admin/system.html` | High
46 | File | `/admin/system.php` | High
47 | File | `/admin/template/edit` | High
48 | File | `/admin/template/update` | High
49 | File | `/admin/user/user-move-run.php` | High
50 | File | `/admin/view_reserved.php` | High
51 | File | `/ajax.php` | Medium
52 | File | `/ajax.php?action=delete_deductions` | High
53 | File | `/ajax.php?action=load_answered` | High
54 | File | `/ajax.php?action=login` | High
55 | File | `/ajax.php?action=save_category` | High
56 | File | `/ajax.php?action=save_establishment` | High
57 | File | `/ajax.php?action=save_user` | High
58 | File | `/ajax.php?action=signup` | High
59 | File | `/ajax.php?action=update_account` | High
60 | File | `/ajax/checkin.php` | High
61 | File | `/ajax/chpwd.php` | High
62 | File | `/ajax/getBasicInfo.php` | High
63 | File | `/api/deploy/upload` | High
64 | File | `/api/deploy/upload /api/database/upload` | High
65 | File | `/api/file/downloadfile` | High
66 | File | `/api/file/downloadUrl` | High
67 | File | `/api/file/multiDownload` | High
68 | File | `/api/files/recipepictures/` | High
69 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
70 | File | `/api/system/user?deptId=1&page=1&size=10` | High
71 | File | `/app/action/add_staff.php` | High
72 | File | `/app/admin/controller/file/File.php` | High
73 | File | `/App/Core/Extend/Function/ydLib.php` | High
74 | File | `/apply/index.php` | High
75 | File | `/AttendanceMonitoring/department/index.php` | High
76 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
77 | File | `/authMonitCallcenter` | High
78 | File | `/bolt/editcontent/showcases` | High
79 | File | `/buscar_integrada.php` | High
80 | File | `/candidate/controller.php` | High
81 | ... | ... | ...

There are 718 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware_BlackKingDom.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
