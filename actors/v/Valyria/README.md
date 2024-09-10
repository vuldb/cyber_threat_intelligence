# Valyria - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Valyria](https://vuldb.com/?actor.valyria). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.valyria](https://vuldb.com/?actor.valyria)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Valyria:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RO](https://vuldb.com/?country.ro)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Valyria.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.248.159.254](https://vuldb.com/?ip.8.248.159.254) | - | - | High
2 | [8.249.221.254](https://vuldb.com/?ip.8.249.221.254) | - | - | High
3 | [8.253.45.248](https://vuldb.com/?ip.8.253.45.248) | - | - | High
4 | [8.253.131.111](https://vuldb.com/?ip.8.253.131.111) | - | - | High
5 | [12.139.45.113](https://vuldb.com/?ip.12.139.45.113) | - | - | High
6 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
7 | [45.60.22.20](https://vuldb.com/?ip.45.60.22.20) | - | - | High
8 | [50.62.26.129](https://vuldb.com/?ip.50.62.26.129) | ip-50-62-26-129.ip.secureserver.net | - | High
9 | [54.164.54.19](https://vuldb.com/?ip.54.164.54.19) | ec2-54-164-54-19.compute-1.amazonaws.com | - | Medium
10 | [64.185.227.155](https://vuldb.com/?ip.64.185.227.155) | 64-185-227-155.static.webnx.com | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Valyria_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Valyria. This data is unique as it uses our predictive model for actor profiling.

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
10 | File | `/admin/about_edit.php?action=modify` | High
11 | File | `/admin/admin-add-employee.php` | High
12 | File | `/admin/ajax.php?action=delete_user` | High
13 | File | `/admin/ajax.php?action=login` | High
14 | File | `/admin/ajax.php?action=save_settings` | High
15 | File | `/admin/assets/` | High
16 | File | `/admin/category_save.php` | High
17 | File | `/admin/class.php?dowhat=modifyclass` | High
18 | File | `/admin/clients/` | High
19 | File | `/admin/config_ISCGroupNoCache.php` | High
20 | File | `/admin/config_MT.php?action=delete` | High
21 | File | `/admin/config_time_sync.php` | High
22 | File | `/admin/content` | High
23 | File | `/admin/dialog/select_images_post.php` | High
24 | File | `/admin/emp-profile-avatar.php` | High
25 | File | `/admin/foreigner-bwdates-reports-details.php` | High
26 | File | `/admin/forgot-password.php` | High
27 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
28 | File | `/admin/forms/option_lists/edit.php` | High
29 | File | `/admin/get_balance.php` | High
30 | File | `/admin/get_price.php` | High
31 | File | `/admin/index.php` | High
32 | File | `/admin/index.php?page=manage_product` | High
33 | File | `/admin/inquiries/view_inquiry.php` | High
34 | File | `/admin/login.php` | High
35 | File | `/admin/maintenance/manage_brand.php` | High
36 | File | `/admin/manage_model.php` | High
37 | File | `/admin/manage_user.php` | High
38 | File | `/admin/media_folders` | High
39 | File | `/admin/member_save.php` | High
40 | File | `/admin/menu.php` | High
41 | File | `/admin/mod_reports/index.php` | High
42 | File | `/admin/mod_reports/printreport.php` | High
43 | File | `/admin/mod_reservation/controller.php` | High
44 | File | `/admin/mod_reservation/index.php` | High
45 | File | `/admin/mod_room/controller.php?action=add` | High
46 | File | `/admin/mod_room/index.php` | High
47 | File | `/admin/mod_users/index.php` | High
48 | File | `/admin/normal-search.php` | High
49 | File | `/admin/orders/controller.php` | High
50 | File | `/admin/orders/index.php` | High
51 | File | `/admin/pages/` | High
52 | File | `/admin/products/index.php` | High
53 | File | `/admin/search-directory.php.` | High
54 | File | `/admin/settings/index.php?page=accounts` | High
55 | File | `/admin/system.html` | High
56 | File | `/admin/system.php` | High
57 | File | `/admin/tasks` | Medium
58 | File | `/admin/tax` | Medium
59 | File | `/admin/template` | High
60 | File | `/admin/view_reserved.php` | High
61 | File | `/admin/view_sendlist.php` | High
62 | File | `/admin_class.php` | High
63 | File | `/ajax.php` | Medium
64 | File | `/ajax.php?action=load_answered` | High
65 | File | `/ajax.php?action=login` | High
66 | File | `/ajax.php?action=save_establishment` | High
67 | File | `/ajax.php?action=save_user` | High
68 | File | `/api/Common/uploadFile` | High
69 | File | `/api/deploy/upload` | High
70 | File | `/api/deploy/upload /api/database/upload` | High
71 | File | `/api/dept` | Medium
72 | File | `/api/dept/build` | High
73 | File | `/api/file/downloadfile` | High
74 | File | `/api/file/downloadUrl` | High
75 | File | `/api/file/multiDownload` | High
76 | File | `/api/role` | Medium
77 | File | `/api/v2/maps` | Medium
78 | File | `/App/Core/Extend/Function/ydLib.php` | High
79 | File | `/apply/index.php` | High
80 | File | `/assoc_table.php` | High
81 | File | `/AttendanceMonitoring/department/index.php` | High
82 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
83 | File | `/authMonitCallcenter` | High
84 | File | `/bolt/editcontent/showcases` | High
85 | File | `/book-services.php` | High
86 | File | `/branch_viewmore.php` | High
87 | File | `/candidate/controller.php` | High
88 | File | `/cap.js` | Low
89 | File | `/cgi-bin/cstecgi.cgi` | High
90 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
91 | File | `/cgi-bin/ExportSettings.sh` | High
92 | File | `/cgi-bin/p1_ftpserver.php` | High
93 | File | `/cgi-bin/photocenter_mgr.cgi` | High
94 | File | `/change_password.php` | High
95 | File | `/classes/Master.php` | High
96 | File | `/classes/Master.php?f=delete_category` | High
97 | File | `/classes/Master.php?f=load_registration` | High
98 | ... | ... | ...

There are 871 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-0928-1005.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-1005-1012.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1214-1221.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0118-0125.html
* https://blog.talosintelligence.com/2019/02/threat-roundup-0208-0215.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0221-0228.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-0925-1002.html
* https://blog.talosintelligence.com/threat-roundup-0505-0512-3/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
