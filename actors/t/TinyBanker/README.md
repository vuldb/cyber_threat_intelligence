# TinyBanker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TinyBanker](https://vuldb.com/?actor.tinybanker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tinybanker](https://vuldb.com/?actor.tinybanker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TinyBanker:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [BR](https://vuldb.com/?country.br)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TinyBanker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.32.207.78](https://vuldb.com/?ip.13.32.207.78) | server-13-32-207-78.iad66.r.cloudfront.net | - | High
2 | [78.108.118.108](https://vuldb.com/?ip.78.108.118.108) | g2wmcs22-3-isp1.fra.expertcity.com | - | High
3 | [78.108.118.118](https://vuldb.com/?ip.78.108.118.118) | g2wmcs26-1-isp1.fra.expertcity.com | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TinyBanker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TinyBanker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=reserve` | High
3 | File | `/?page=tickets` | High
4 | File | `/Actions.php?a=login` | High
5 | File | `/add-students.php` | High
6 | File | `/addcompany.php` | High
7 | File | `/admin` | Low
8 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=categories/view_category` | High
11 | File | `/admin/?page=musics/manage_music` | High
12 | File | `/Admin/add-admin.php` | High
13 | File | `/admin/admin-add-employee.php` | High
14 | File | `/admin/admin-update-employee.php` | High
15 | File | `/admin/admin_invt2.php` | High
16 | File | `/admin/ajax.php?action=delete_user` | High
17 | File | `/admin/ajax.php?action=save_settings` | High
18 | File | `/admin/assets/` | High
19 | File | `/admin/blood/update/B+.php` | High
20 | File | `/admin/blood/update/o-.php` | High
21 | File | `/admin/categories/manage_category.php` | High
22 | File | `/admin/clients/` | High
23 | File | `/admin/config_MT.php?action=delete` | High
24 | File | `/admin/config_time_sync.php` | High
25 | File | `/admin/dialog/select_images_post.php` | High
26 | File | `/admin/edit_area.php` | High
27 | File | `/admin/edit_manufacturer.php` | High
28 | File | `/admin/emp-profile-avatar.php` | High
29 | File | `/admin/foreigner-bwdates-reports-details.php` | High
30 | File | `/admin/foreigner-search.php` | High
31 | File | `/admin/forgot-password.php` | High
32 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
33 | File | `/admin/get_price.php` | High
34 | File | `/admin/index.php` | High
35 | File | `/admin/index.php?page=categories` | High
36 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
37 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
38 | File | `/admin/index.php?r=user%2Fcreate` | High
39 | File | `/admin/login.php` | High
40 | File | `/admin/maintenance/manage_department.php` | High
41 | File | `/admin/manage_complaint.php` | High
42 | File | `/admin/manage_user.php` | High
43 | File | `/admin/normal-bwdates-reports-details.php` | High
44 | File | `/admin/pages/` | High
45 | File | `/admin/pages/list` | High
46 | File | `/admin/print_barcode.php` | High
47 | File | `/Admin/registration.php` | High
48 | File | `/admin/robot.php` | High
49 | File | `/admin/system.html` | High
50 | File | `/admin/system.php` | High
51 | File | `/admin/template/edit` | High
52 | File | `/admin/user/user-move-run.php` | High
53 | File | `/admin/view_reserved.php` | High
54 | File | `/admin_class.php` | High
55 | File | `/ajax.php` | Medium
56 | File | `/ajax.php?action=delete_deductions` | High
57 | File | `/ajax.php?action=login` | High
58 | File | `/ajax.php?action=save_category` | High
59 | File | `/ajax.php?action=save_establishment` | High
60 | File | `/ajax.php?action=save_quiz` | High
61 | File | `/ajax.php?action=save_user` | High
62 | File | `/ajax.php?action=signup` | High
63 | File | `/ajax.php?action=update_account` | High
64 | File | `/api/blade-system/menu/list?updatexml` | High
65 | File | `/api/Common/uploadFile` | High
66 | File | `/api/dept` | Medium
67 | File | `/api/dept/build` | High
68 | File | `/api/files/recipepictures/` | High
69 | File | `/api/role` | Medium
70 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
71 | File | `/api/system/user?deptId=1&page=1&size=10` | High
72 | File | `/api/test/download` | High
73 | File | `/api/user` | Medium
74 | File | `/api/v2/maps` | Medium
75 | File | `/app/action/add_staff.php` | High
76 | File | `/app/admin/controller/file/File.php` | High
77 | File | `/App/Core/Extend/Function/ydLib.php` | High
78 | File | `/app/uploading/upload-mp3.php` | High
79 | File | `/authMonitCallcenter` | High
80 | File | `/bolt/editcontent/showcases` | High
81 | File | `/branch_viewmore.php` | High
82 | File | `/cgi-bin/cstecgi.cgi` | High
83 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
84 | File | `/cgi-bin/hd_config.cgi` | High
85 | File | `/cgi-bin/myMusic.cgi` | High
86 | File | `/cgi-bin/p1_ftpserver.php` | High
87 | File | `/cgi-bin/photocenter_mgr.cgi` | High
88 | File | `/cgi-bin/s3.cgi` | High
89 | File | `/cgi-bin/webdav_mgr.cgi` | High
90 | File | `/cgi-bin/webfile_mgr.cgi` | High
91 | File | `/cgi-bin/widget_api.cgi` | High
92 | File | `/change_password.php` | High
93 | File | `/checkout` | Medium
94 | File | `/classes/Master.php` | High
95 | File | `/classes/Master.php?f=delete_category` | High
96 | File | `/classes/Master.php?f=delete_record` | High
97 | File | `/classes/Master.php?f=log_employee` | High
98 | File | `/classes/Master.php?f=log_visitor` | High
99 | File | `/classes/Master.php?f=save_medicine` | High
100 | File | `/classes/Master.php?f=save_package` | High
101 | File | `/classes/SystemSettings.php?f=update_settings` | High
102 | ... | ... | ...

There are 898 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0409-0416.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-for-july-9-to-july-16.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
