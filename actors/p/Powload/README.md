# Powload - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Powload](https://vuldb.com/?actor.powload). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powload](https://vuldb.com/?actor.powload)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Powload:

* [PL](https://vuldb.com/?country.pl)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Powload.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.29.155](https://vuldb.com/?ip.5.61.29.155) | 5-61-29-155.nrp.co | - | High
2 | [31.14.103.164](https://vuldb.com/?ip.31.14.103.164) | dns103164.phdns19.es | - | High
3 | [37.211.38.50](https://vuldb.com/?ip.37.211.38.50) | - | - | High
4 | [42.114.73.81](https://vuldb.com/?ip.42.114.73.81) | - | - | High
5 | [45.40.251.243](https://vuldb.com/?ip.45.40.251.243) | - | - | High
6 | [47.99.85.122](https://vuldb.com/?ip.47.99.85.122) | - | - | High
7 | [50.99.132.7](https://vuldb.com/?ip.50.99.132.7) | s50-99-132-7.ab.hsia.telus.net | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Powload_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Powload. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?g=net_pro_keyword_import_save` | High
3 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
4 | File | `/Account/login.php` | High
5 | File | `/actuator/heapdump` | High
6 | File | `/addproduct.php` | High
7 | File | `/admin` | Low
8 | File | `/admin-api/upload_image` | High
9 | File | `/admin/?page=borrow/view_borrow` | High
10 | File | `/admin/?page=user/list` | High
11 | File | `/Admin/add-admin.php` | High
12 | File | `/admin/add-ambulance.php` | High
13 | File | `/admin/addgiving.php` | High
14 | File | `/admin/addTithes.php` | High
15 | File | `/admin/add_ikev2.php` | High
16 | File | `/admin/add_postlogin.php` | High
17 | File | `/admin/add_sundaysch.php` | High
18 | File | `/admin/add_visitor.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/adminHome.php` | High
21 | File | `/admin/admin_cl.php?mudi=revPwd` | High
22 | File | `/admin/admin_user.php` | High
23 | File | `/admin/ajax.php?action=save_settings` | High
24 | File | `/admin/case-status` | High
25 | File | `/admin/case-type` | High
26 | File | `/admin/category/view_category.php` | High
27 | File | `/Admin/changepassword.php` | High
28 | File | `/admin/clients` | High
29 | File | `/admin/client_user` | High
30 | File | `/admin/config_Anticrack.php` | High
31 | File | `/admin/config_ISCGroupNoCache.php` | High
32 | File | `/admin/config_MT.php?action=delete` | High
33 | File | `/admin/content` | High
34 | File | `/admin/court` | Medium
35 | File | `/admin/court-type` | High
36 | File | `/admin/delete_log.php` | High
37 | File | `/Admin/edit-photo.php` | High
38 | File | `/admin/edit-post.php` | High
39 | File | `/Admin/edit_profile.php` | High
40 | File | `/admin/expense-type` | High
41 | File | `/admin/general-setting` | High
42 | File | `/admin/index.php` | High
43 | File | `/admin/index.php?page=categories` | High
44 | File | `/admin/index.php?page=manage_product` | High
45 | File | `/admin/judge` | Medium
46 | File | `/admin/list_crl_conf` | High
47 | File | `/admin/login.php` | High
48 | File | `/Admin/login.php` | High
49 | File | `/admin/maintenance/manage_brand.php` | High
50 | File | `/admin/manage-ambulance.php` | High
51 | File | `/admin/modules/product/controller.php?action=add` | High
52 | File | `/admin/mod_room/controller.php?action=add` | High
53 | File | `/admin/role` | Medium
54 | File | `/admin/search-directory.php.` | High
55 | File | `/admin/search.php` | High
56 | File | `/admin/service` | High
57 | File | `/admin/tag.php` | High
58 | File | `/admin/tasks` | Medium
59 | File | `/admin/tax` | Medium
60 | File | `/admin/twitter.php` | High
61 | File | `/Admin/user-record.php` | High
62 | File | `/admin/vendor` | High
63 | File | `/adminPage/conf/reload` | High
64 | File | `/adminPage/conf/saveCmd` | High
65 | File | `/adminPage/main/upload` | High
66 | File | `/adminPage/www/addOver` | High
67 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
68 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
69 | File | `/adminpanel/admin/query/addCourseExe.php` | High
70 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
71 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
72 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
73 | File | `/adminpanel/admin/query/loginExe.php` | High
74 | File | `/admin_class.php` | High
75 | File | `/ajax.php` | Medium
76 | File | `/api/blade-user/export-user` | High
77 | File | `/api/process.php` | High
78 | File | `/api/v2/maps` | Medium
79 | File | `/app/uploading/upload-mp3.php` | High
80 | File | `/application/controller/Pelanggan.php` | High
81 | File | `/application/controller/Pengeluaran.php` | High
82 | File | `/application/controller/Transaki.php` | High
83 | File | `/assoc_table.php` | High
84 | File | `/attendancelist.php` | High
85 | File | `/backend/register.php` | High
86 | File | `/cart.php` | Medium
87 | File | `/catalog/all-products` | High
88 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
89 | File | `/checkout` | Medium
90 | File | `/classes/Master.php?f=load_registration` | High
91 | File | `/classes/Master.php?f=log_employee` | High
92 | File | `/classes/Master.php?f=log_visitor` | High
93 | File | `/classes/Master.php?f=save_category` | High
94 | File | `/classes/SystemSettings.php?f=update_settings` | High
95 | File | `/classes/Users.php` | High
96 | File | `/classes/Users.php?f=delete` | High
97 | File | `/classes/Users.php?f=save` | High
98 | File | `/cms/classes/Users.php?f=delete_client` | High
99 | File | `/command_port.ini` | High
100 | File | `/control/activate_case.php` | High
101 | File | `/control/addcase_stage.php` | High
102 | File | `/control/adds.php` | High
103 | File | `/control/deactivate_case.php` | High
104 | File | `/control/register_case.php` | High
105 | File | `/deletefile.php` | High
106 | File | `/description.php` | High
107 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
108 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
109 | File | `/diag_s.php` | Medium
110 | File | `/doctor/view-appointment-detail.php` | High
111 | File | `/edit-subject.php` | High
112 | File | `/edit_book.php` | High
113 | File | `/emgui/rest/ums/messages` | High
114 | File | `/Employee/apply_leave.php` | High
115 | File | `/Employee/changepassword.php` | High
116 | File | `/Employee/delete_leave.php` | High
117 | File | `/Employee/edit-profile.php` | High
118 | File | `/employee_gatepass/classes/Users.php?f=ssave` | High
119 | File | `/endpoint/add-image.php` | High
120 | ... | ... | ...

There are 1063 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0921-0928.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1207-1214.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0419-to-0426.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0503-0510.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
