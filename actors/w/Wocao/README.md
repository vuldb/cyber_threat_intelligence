# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Wocao](https://vuldb.com/?actor.wocao). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wocao](https://vuldb.com/?actor.wocao)

## Campaigns

The following _campaigns_ are known and can be associated with Wocao:

* Wocao

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | - | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | - | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | - | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | - | Medium
5 | [4.96.46.65](https://vuldb.com/?ip.4.96.46.65) | - | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Wocao_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Wocao. This data is unique as it uses our predictive model for actor profiling.

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
14 | File | `/admin/assets/` | High
15 | File | `/admin/blood/update/B+.php` | High
16 | File | `/admin/blood/update/o-.php` | High
17 | File | `/admin/categories/manage_category.php` | High
18 | File | `/admin/class.php?dowhat=modifyclass` | High
19 | File | `/admin/dialog/select_images_post.php` | High
20 | File | `/admin/edit_area.php` | High
21 | File | `/admin/edit_manufacturer.php` | High
22 | File | `/admin/educloud/videobind.html` | High
23 | File | `/admin/emp-profile-avatar.php` | High
24 | File | `/admin/inquiries/view_details.php` | High
25 | File | `/admin/inquiries/view_inquiry.php` | High
26 | File | `/admin/login.php` | High
27 | File | `/admin/maintenance/manage_department.php` | High
28 | File | `/admin/mod_reports/index.php` | High
29 | File | `/admin/mod_reports/printreport.php` | High
30 | File | `/admin/mod_reservation/controller.php` | High
31 | File | `/admin/mod_reservation/index.php` | High
32 | File | `/admin/mod_room/index.php` | High
33 | File | `/admin/mod_users/index.php` | High
34 | File | `/admin/orders/controller.php` | High
35 | File | `/admin/orders/index.php` | High
36 | File | `/admin/products/index.php` | High
37 | File | `/Admin/registration.php` | High
38 | File | `/admin/robot.php` | High
39 | File | `/admin/system.html` | High
40 | File | `/admin/system.php` | High
41 | File | `/admin/template/edit` | High
42 | File | `/admin/template/update` | High
43 | File | `/admin/user/user-move-run.php` | High
44 | File | `/ajax.php` | Medium
45 | File | `/ajax.php?action=delete_deductions` | High
46 | File | `/ajax.php?action=load_answered` | High
47 | File | `/ajax.php?action=login` | High
48 | File | `/ajax.php?action=save_category` | High
49 | File | `/ajax.php?action=save_establishment` | High
50 | File | `/ajax.php?action=save_user` | High
51 | File | `/ajax.php?action=signup` | High
52 | File | `/ajax.php?action=update_account` | High
53 | File | `/ajax/checkin.php` | High
54 | File | `/ajax/chpwd.php` | High
55 | File | `/ajax/getBasicInfo.php` | High
56 | File | `/api/deploy/upload` | High
57 | File | `/api/deploy/upload /api/database/upload` | High
58 | File | `/api/file/downloadfile` | High
59 | File | `/api/file/downloadUrl` | High
60 | File | `/api/file/multiDownload` | High
61 | File | `/api/files/recipepictures/` | High
62 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
63 | File | `/api/system/user?deptId=1&page=1&size=10` | High
64 | File | `/app/action/add_staff.php` | High
65 | File | `/app/admin/controller/file/File.php` | High
66 | File | `/apply/index.php` | High
67 | File | `/AttendanceMonitoring/department/index.php` | High
68 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
69 | File | `/authMonitCallcenter` | High
70 | File | `/buscar_integrada.php` | High
71 | File | `/candidate/controller.php` | High
72 | File | `/cap.js` | Low
73 | File | `/cgi-bin/apkg_mgr.cgi` | High
74 | File | `/cgi-bin/cstecgi.cgi` | High
75 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
76 | File | `/cgi-bin/hd_config.cgi` | High
77 | File | `/cgi-bin/p1_ftpserver.php` | High
78 | ... | ... | ...

There are 684 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fox-it/operation-wocao
* https://github.com/fox-it/operation-wocao/blob/master/hashes.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
