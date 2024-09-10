# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Wocao](https://vuldb.com/?actor.wocao). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wocao](https://vuldb.com/?actor.wocao)

## Campaigns

The following _campaigns_ are known and can be associated with Wocao:

* Wocao

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RO](https://vuldb.com/?country.ro)
* ...

There are 2 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=tracks` | High
3 | File | `/Actions.php?a=login` | High
4 | File | `/add-students.php` | High
5 | File | `/addcategory.php` | High
6 | File | `/addclient1.php` | High
7 | File | `/addproduct.php` | High
8 | File | `/admin-cp/theme/editor/default` | High
9 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
10 | File | `/admin/about_edit.php?action=modify` | High
11 | File | `/admin/admin-add-employee.php` | High
12 | File | `/admin/ajax.php?action=delete_user` | High
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
24 | File | `/admin/emp-profile-avatar.php` | High
25 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
26 | File | `/admin/forms/option_lists/edit.php` | High
27 | File | `/admin/get_balance.php` | High
28 | File | `/admin/get_price.php` | High
29 | File | `/admin/inquiries/view_inquiry.php` | High
30 | File | `/admin/login.php` | High
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
43 | File | `/admin/orders/controller.php` | High
44 | File | `/admin/orders/index.php` | High
45 | File | `/admin/pages/` | High
46 | File | `/admin/products/index.php` | High
47 | File | `/Admin/registration.php` | High
48 | File | `/admin/settings/index.php?page=accounts` | High
49 | File | `/admin/system.html` | High
50 | File | `/admin/system.php` | High
51 | File | `/admin/template/edit` | High
52 | File | `/admin/user/user-move-run.php` | High
53 | File | `/admin/view_reserved.php` | High
54 | File | `/admin/view_sendlist.php` | High
55 | File | `/ajax.php` | Medium
56 | File | `/ajax.php?action=load_answered` | High
57 | File | `/ajax.php?action=login` | High
58 | File | `/ajax.php?action=save_establishment` | High
59 | File | `/ajax.php?action=save_user` | High
60 | File | `/ajax/checkin.php` | High
61 | File | `/ajax/chpwd.php` | High
62 | File | `/ajax/getBasicInfo.php` | High
63 | File | `/api/Common/uploadFile` | High
64 | File | `/api/deploy/upload` | High
65 | File | `/api/deploy/upload /api/database/upload` | High
66 | File | `/api/dept` | Medium
67 | File | `/api/dept/build` | High
68 | File | `/api/file/downloadfile` | High
69 | File | `/api/file/downloadUrl` | High
70 | File | `/api/file/multiDownload` | High
71 | File | `/api/files/recipepictures/` | High
72 | File | `/api/role` | Medium
73 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
74 | File | `/api/system/user?deptId=1&page=1&size=10` | High
75 | File | `/api/v2/maps` | Medium
76 | File | `/App/Core/Extend/Function/ydLib.php` | High
77 | File | `/apply/index.php` | High
78 | File | `/AttendanceMonitoring/department/index.php` | High
79 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
80 | File | `/authMonitCallcenter` | High
81 | File | `/bolt/editcontent/showcases` | High
82 | File | `/branch_viewmore.php` | High
83 | File | `/candidate/controller.php` | High
84 | File | `/cap.js` | Low
85 | File | `/cgi-bin/apkg_mgr.cgi` | High
86 | File | `/cgi-bin/cstecgi.cgi` | High
87 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
88 | File | `/cgi-bin/ExportSettings.sh` | High
89 | File | `/cgi-bin/hd_config.cgi` | High
90 | File | `/cgi-bin/p1_ftpserver.php` | High
91 | File | `/cgi-bin/photocenter_mgr.cgi` | High
92 | ... | ... | ...

There are 808 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
