# Valyria - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Valyria](https://vuldb.com/?actor.valyria). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.valyria](https://vuldb.com/?actor.valyria)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Valyria:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 7 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Valyria. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/aa` | Low
4 | File | `/add-normal-ticket.php` | High
5 | File | `/addelidetails.php` | High
6 | File | `/add_drive.php` | High
7 | File | `/add_employee.php` | High
8 | File | `/add_reserve.php` | High
9 | File | `/admin.php/addon/index` | High
10 | File | `/admin.php?mod=brand&act=del` | High
11 | File | `/admin/?page=back_order/view_bo` | High
12 | File | `/admin/?page=maintenance/brand` | High
13 | File | `/admin/add-art-type.php` | High
14 | File | `/admin/add-artist.php` | High
15 | File | `/admin/add-category.php` | High
16 | File | `/admin/addroom.php` | High
17 | File | `/admin/admin-profile.php` | High
18 | File | `/admin/admin/save` | High
19 | File | `/admin/all-applications.php` | High
20 | File | `/admin/app/profile_crud.php` | High
21 | File | `/admin/app/slider_crud.php` | High
22 | File | `/Admin/assets/backend/seller/add_seller.php` | High
23 | File | `/admin/assign_save.php` | High
24 | File | `/admin/attachment/download` | High
25 | File | `/admin/attendance_row.php` | High
26 | File | `/admin/auto-taxi-entry-detail.php` | High
27 | File | `/admin/blogger.php?action=update_avatar` | High
28 | File | `/admin/candidates_delete.php` | High
29 | File | `/admin/category/add.do` | High
30 | File | `/admin/category_save.php` | High
31 | File | `/admin/checkout_query.php` | High
32 | File | `/admin/check_studid.php` | High
33 | File | `/admin/complaint-search.php` | High
34 | File | `/admin/contactus.php` | High
35 | File | `/admin/core/import_users.php` | High
36 | File | `/admin/core/new_user` | High
37 | File | `/Admin/CustomerReport.php` | High
38 | File | `/admin/department/add` | High
39 | File | `/admin/display-teacher.php` | High
40 | File | `/admin/doctor-specilization.php` | High
41 | File | `/admin/edit-admin.php` | High
42 | File | `/admin/edit-category.php` | High
43 | File | `/admin/edit-guard-detail.php` | High
44 | File | `/admin/edit-nurse.php` | High
45 | File | `/admin/edit-services.php` | High
46 | File | `/admin/edit-subjects-detail.php` | High
47 | File | `/admin/edit_activity.php` | High
48 | File | `/admin/edit_admin_details.php?id=admin` | High
49 | File | `/admin/edit_expenses_query.php` | High
50 | File | `/admin/edit_product.php` | High
51 | File | `/admin/edit_student_query.php` | High
52 | File | `/Admin/facilitator.php` | High
53 | File | `/admin/file.php` | High
54 | File | `/admin/file/rename.do` | High
55 | File | `/admin/forget-password.php` | High
56 | File | `/admin/forgot-password.php` | High
57 | File | `/admin/gallery.php` | High
58 | File | `/admin/getmanagerregion.php` | High
59 | File | `/admin/home/index.html` | High
60 | File | `/admin/ImgUpdaPost.php` | High
61 | File | `/admin/index.php` | High
62 | File | `/admin/index.php/news/edit` | High
63 | File | `/admin/lab.php` | High
64 | File | `/admin/login` | Medium
65 | File | `/admin/login-back.php` | High
66 | File | `/admin/login.php` | High
67 | File | `/admin/manage-art-medium.php` | High
68 | File | `/admin/manage-notices.php` | High
69 | File | `/admin/manage-users.php` | High
70 | File | `/admin/manage_booking.php` | High
71 | File | `/admin/manage_seat.php` | High
72 | File | `/admin/manage_user.php` | High
73 | File | `/admin/member_save.php` | High
74 | File | `/admin/message/search.php` | High
75 | File | `/admin/new-autoortaxi-entry-form.php` | High
76 | File | `/admin/offenses/view_details.php` | High
77 | File | `/admin/operation/user.php` | High
78 | File | `/admin/Operations/Role.php` | High
79 | File | `/admin/pass-bwdates-reports-details.php` | High
80 | File | `/admin/payment_save.php` | High
81 | File | `/admin/product/edit/` | High
82 | File | `/admin/redirect.php` | High
83 | File | `/admin/registration.php` | High
84 | File | `/admin/request-received-bydonar.php` | High
85 | File | `/admin/search-directory.php` | High
86 | File | `/admin/search.php` | High
87 | File | `/admin/semester.php` | High
88 | File | `/admin/storage/delete` | High
89 | File | `/admin/subject/controller.php` | High
90 | File | `/admin/subscriber-csv.php` | High
91 | File | `/admin/SysModule/edit.html` | High
92 | File | `/admin/teacher-salary.php` | High
93 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
94 | File | `/admin/update_s2.php` | High
95 | File | `/admin/update_s8.php` | High
96 | File | `/admin/users-applications.php` | High
97 | File | `/admin/user_update.php` | High
98 | File | `/admin/v1/blog/edit` | High
99 | File | `/admin/view-normal-ticket.php` | High
100 | File | `/admin/view-patient.php` | High
101 | File | `/admin/view_vacancy.php` | High
102 | File | `/admin/voters_row.php` | High
103 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
104 | File | `/Administrator/PHP/AdminAddCategory.php` | High
105 | File | `/Administrator/PHP/AdminEditCategory.php` | High
106 | File | `/Administrator/PHP/AdminReply.php` | High
107 | File | `/admin_pic.php` | High
108 | File | `/admin_single_student.php` | High
109 | File | `/aim/storage/query.py` | High
110 | File | `/ajax.php?action=calculate_payroll` | High
111 | File | `/ajax.php?action=delete_member` | High
112 | File | `/ajax.php?action=delete_package` | High
113 | File | `/ajax.php?action=delete_payroll` | High
114 | File | `/ajax.php?action=delete_trainer` | High
115 | File | `/ajax_city.php` | High
116 | File | `/ajx.php` | Medium
117 | File | `/all_student.php` | High
118 | File | `/api/admin/sys-user/reset/password/` | High
119 | File | `/api/article/del` | High
120 | File | `/api/backend/ext/import-data/import-channel` | High
121 | File | `/api/database/testConnect` | High
122 | File | `/api/File/downloadFile` | High
123 | File | `/api/GylOperator/LoadData` | High
124 | File | `/api/Security/` | High
125 | File | `/api/semantic/database/testConnect` | High
126 | File | `/api/users/updateAvatar` | High
127 | File | `/api/v1/serve/awel/flow/import` | High
128 | File | `/api/wizard/getCapability` | High
129 | ... | ... | ...

There are 1150 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
