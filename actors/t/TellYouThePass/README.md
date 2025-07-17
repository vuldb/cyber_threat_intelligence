# TellYouThePass - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TellYouThePass](https://vuldb.com/?actor.tellyouthepass). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tellyouthepass](https://vuldb.com/?actor.tellyouthepass)

## Campaigns

The following _campaigns_ are known and can be associated with TellYouThePass:

* CVE-2024-4577

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TellYouThePass:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TellYouThePass.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.116.254.172](https://vuldb.com/?ip.14.116.254.172) | - | CVE-2024-4577 | High
2 | [14.225.53.162](https://vuldb.com/?ip.14.225.53.162) | static.vnpt.vn | CVE-2024-4577 | High
3 | [39.97.209.211](https://vuldb.com/?ip.39.97.209.211) | - | CVE-2024-4577 | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TellYouThePass_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TellYouThePass. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/AcceptZip.ashx` | High
2 | File | `/account/forgotpassword` | High
3 | File | `/ad-list` | Medium
4 | File | `/add-customer.php` | High
5 | File | `/addpayment.php` | High
6 | File | `/add_members.php` | High
7 | File | `/admin` | Low
8 | File | `/admin#themes` | High
9 | File | `/admin-api/infra/file/upload` | High
10 | File | `/admin-profile.php` | High
11 | File | `/admin.php?p=/Area/index#tab=t2` | High
12 | File | `/admin/` | Low
13 | File | `/admin/aboutus.php` | High
14 | File | `/admin/action/add_con.php` | High
15 | File | `/admin/action/update-deworm.php` | High
16 | File | `/admin/add-admin.php` | High
17 | File | `/admin/add-art-medium.php` | High
18 | File | `/admin/add-doctor.php` | High
19 | File | `/admin/add-subadmin.php` | High
20 | File | `/admin/add_student.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/admin/allemployees.php` | High
23 | File | `/admin/all_users.php` | High
24 | File | `/admin/api/admin/v2_products` | High
25 | File | `/admin/app/product.php` | High
26 | File | `/admin/app/profile_crud.php` | High
27 | File | `/admin/archives/edit` | High
28 | File | `/admin/article/list_approve` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
30 | File | `/admin/assign_save.php` | High
31 | File | `/admin/auto-taxi-entry-detail.php` | High
32 | File | `/admin/booking-bwdates-reports-details.php` | High
33 | File | `/admin/book_add.php` | High
34 | File | `/Admin/Category.php` | High
35 | File | `/admin/category/index.php` | High
36 | File | `/admin/category_update.php` | High
37 | File | `/admin/combo.php` | High
38 | File | `/admin/company/controller.php` | High
39 | File | `/admin/complaint-search.php` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/content/editor` | High
42 | File | `/admin/course.php` | High
43 | File | `/admin/edit-admin.php` | High
44 | File | `/admin/edit-category.php` | High
45 | File | `/admin/edit-guard-detail.php` | High
46 | File | `/admin/edit-services.php` | High
47 | File | `/admin/edit-teacher-info.php` | High
48 | File | `/admin/editempprofile.php` | High
49 | File | `/admin/edit_supplier.php` | High
50 | File | `/admin/edit_teacher.php` | High
51 | File | `/admin/File/fileUpload` | High
52 | File | `/admin/finished.php` | High
53 | File | `/admin/forgot-password.php` | High
54 | File | `/admin/get_price.php` | High
55 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
56 | File | `/admin/index.php/news/edit` | High
57 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
58 | File | `/Admin/InsertCity.php` | High
59 | File | `/admin/invoice.php` | High
60 | File | `/admin/leancloud.php` | High
61 | File | `/admin/list_localuser.php` | High
62 | File | `/admin/login.php` | High
63 | File | `/admin/login_process.php` | High
64 | File | `/admin/manage-pages.php` | High
65 | File | `/admin/manage_complaint.php` | High
66 | File | `/admin/massage.php` | High
67 | File | `/admin/member_save.php` | High
68 | File | `/admin/menu_save.php` | High
69 | File | `/admin/modal_add_product.php` | High
70 | File | `/admin/network/diag_nslookup` | High
71 | File | `/admin/network/wifi_schedule` | High
72 | File | `/admin/newsletter.php` | High
73 | File | `/Admin/NewsReport.php` | High
74 | File | `/admin/pages/` | High
75 | File | `/admin/password-recovery.php` | High
76 | File | `/admin/positions_add.php` | High
77 | File | `/admin/profile.php` | High
78 | File | `/admin/redirect.php` | High
79 | File | `/admin/registration.php` | High
80 | File | `/admin/reminders/manage_reminder.php` | High
81 | File | `/admin/reset-password.php` | High
82 | File | `/admin/sales/index.php` | High
83 | File | `/admin/save_settings.php` | High
84 | File | `/admin/search-appointment.php` | High
85 | File | `/admin/search-directory.php` | High
86 | File | `/admin/search-report-details.php` | High
87 | File | `/admin/search.php` | High
88 | File | `/admin/services/manage_service.php` | High
89 | File | `/admin/students.php` | High
90 | File | `/admin/students/manage_academic.php` | High
91 | File | `/admin/sys/role/list` | High
92 | File | `/admin/sys/user/list` | High
93 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
94 | File | `/admin/updatecomplaint.php` | High
95 | File | `/admin/user/index.php` | High
96 | File | `/admin/user_save.php` | High
97 | File | `/admin/vote_edit.php` | High
98 | File | `/adminSQL` | Medium
99 | File | `/adpweb/wechat/verifyToken/` | High
100 | File | `/ajax.php?action=delete_member` | High
101 | File | `/ajax.php?action=delete_trainer` | High
102 | File | `/ajax.php?action=login` | High
103 | File | `/ajax.php?action=save_member` | High
104 | File | `/ajx.php` | Medium
105 | File | `/all_student.php` | High
106 | File | `/Android/data/com.myairtelapp/files/` | High
107 | File | `/animalsadd.php` | High
108 | File | `/api/` | Low
109 | File | `/api/controllers/merchant/shop/PosterController.php` | High
110 | File | `/api/data.php` | High
111 | File | `/api/file/downloadfile` | High
112 | File | `/api/v1/bait/set` | High
113 | File | `/api/v1/getbaseconfig` | High
114 | File | `/api/v1/user/login` | High
115 | File | `/api/v2/cli/commands` | High
116 | File | `/api/v2/open/rowsInfo` | High
117 | File | `/api/wizard/getNetworkStatus` | High
118 | File | `/app/api/controller/default/Sqlite.php` | High
119 | File | `/application/controller/Transaki.php` | High
120 | File | `/application/index/controller/Screen.php` | High
121 | File | `/application/pay/controller/Api.php` | High
122 | File | `/att_add.php` | Medium
123 | File | `/b2b-supermarket/shopping-cart` | High
124 | File | `/backend/register.php` | High
125 | File | `/birthing_record.php` | High
126 | File | `/Bloodgroop_process.php` | High
127 | File | `/boafrm/formDMZ` | High
128 | File | `/boafrm/formDosCfg` | High
129 | File | `/boafrm/formFilter` | High
130 | File | `/boafrm/formIPv6Addr` | High
131 | File | `/boafrm/formIpv6Setup` | High
132 | ... | ... | ...

There are 1168 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/cve-2024-4577-ongoing-exploitation-of-a-critical-php-vulnerability/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
