# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/aa` | Low
4 | File | `/add-normal-ticket.php` | High
5 | File | `/addelidetails.php` | High
6 | File | `/add_employee.php` | High
7 | File | `/add_reserve.php` | High
8 | File | `/admin-api/mp/material/upload-permanent` | High
9 | File | `/admin.php/addon/index` | High
10 | File | `/admin.php?mod=brand&act=del` | High
11 | File | `/admin/?page=back_order/view_bo` | High
12 | File | `/admin/?page=maintenance/brand` | High
13 | File | `/admin/accepted-appointment.php` | High
14 | File | `/admin/add-art-type.php` | High
15 | File | `/admin/add-category.php` | High
16 | File | `/admin/add-directory.php` | High
17 | File | `/admin/addroom.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/admin/save` | High
20 | File | `/admin/all-applications.php` | High
21 | File | `/admin/app/profile_crud.php` | High
22 | File | `/admin/app/slider_crud.php` | High
23 | File | `/Admin/assets/backend/seller/add_seller.php` | High
24 | File | `/admin/assign_save.php` | High
25 | File | `/admin/attachment/download` | High
26 | File | `/admin/attendance_row.php` | High
27 | File | `/admin/auto-taxi-entry-detail.php` | High
28 | File | `/admin/booking-search.php` | High
29 | File | `/admin/candidates_delete.php` | High
30 | File | `/admin/category.php` | High
31 | File | `/admin/category/add.do` | High
32 | File | `/admin/checkout_query.php` | High
33 | File | `/admin/check_studid.php` | High
34 | File | `/admin/complaint-search.php` | High
35 | File | `/admin/confirm.php` | High
36 | File | `/admin/contact-list.php` | High
37 | File | `/admin/contactus.php` | High
38 | File | `/admin/core/import_users.php` | High
39 | File | `/admin/core/new_user` | High
40 | File | `/Admin/CustomerReport.php` | High
41 | File | `/admin/delete-session.php` | High
42 | File | `/admin/delete_member.php` | High
43 | File | `/admin/department/add` | High
44 | File | `/admin/display-teacher.php` | High
45 | File | `/admin/doctor-specilization.php` | High
46 | File | `/admin/edit-admin.php` | High
47 | File | `/admin/edit-category.php` | High
48 | File | `/admin/edit-guard-detail.php` | High
49 | File | `/admin/edit-nurse.php` | High
50 | File | `/admin/edit-subjects-detail.php` | High
51 | File | `/admin/edit_activity.php` | High
52 | File | `/admin/edit_admin.php` | High
53 | File | `/admin/edit_admin_details.php?id=admin` | High
54 | File | `/admin/edit_expenses_query.php` | High
55 | File | `/admin/edit_product.php` | High
56 | File | `/admin/edit_student_query.php` | High
57 | File | `/Admin/facilitator.php` | High
58 | File | `/admin/file.php` | High
59 | File | `/admin/file/rename.do` | High
60 | File | `/admin/forgot-password.php` | High
61 | File | `/admin/gallery.php` | High
62 | File | `/admin/getmanagerregion.php` | High
63 | File | `/admin/home/index.html` | High
64 | File | `/admin/ImgUpdaPost.php` | High
65 | File | `/admin/index.php` | High
66 | File | `/admin/index.php/news/edit` | High
67 | File | `/admin/lab.php` | High
68 | File | `/admin/link/edit.do` | High
69 | File | `/admin/login` | Medium
70 | File | `/admin/login-back.php` | High
71 | File | `/admin/login.php` | High
72 | File | `/admin/manage-art-medium.php` | High
73 | File | `/admin/manage-notices.php` | High
74 | File | `/admin/manage-tickets.php` | High
75 | File | `/admin/manage-users.php` | High
76 | File | `/admin/manage_seat.php` | High
77 | File | `/admin/manage_user.php` | High
78 | File | `/admin/member_save.php` | High
79 | File | `/admin/message/search.php` | High
80 | File | `/admin/new-autoortaxi-entry-form.php` | High
81 | File | `/admin/offenses/view_details.php` | High
82 | File | `/admin/operation/user.php` | High
83 | File | `/admin/Operations/Role.php` | High
84 | File | `/admin/pass-bwdates-reports-details.php` | High
85 | File | `/admin/payment_save.php` | High
86 | File | `/admin/redirect.php` | High
87 | File | `/admin/registration.php` | High
88 | File | `/admin/request-received-bydonar.php` | High
89 | File | `/admin/search-directory.php` | High
90 | File | `/admin/search.php` | High
91 | File | `/admin/semester.php` | High
92 | File | `/admin/storage/delete` | High
93 | File | `/admin/subject/controller.php` | High
94 | File | `/admin/SysModule/edit.html` | High
95 | File | `/admin/teacher-salary.php` | High
96 | File | `/admin/update_fst.php` | High
97 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
98 | File | `/admin/update_s2.php` | High
99 | File | `/admin/user.php` | High
100 | File | `/admin/users-applications.php` | High
101 | File | `/admin/users.php` | High
102 | File | `/admin/user_update.php` | High
103 | File | `/admin/v1/blog/edit` | High
104 | File | `/admin/view-normal-ticket.php` | High
105 | File | `/admin/view_vacancy.php` | High
106 | File | `/admin/voters_row.php` | High
107 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
108 | File | `/Administrator/PHP/AdminAddCategory.php` | High
109 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
110 | File | `/Administrator/PHP/AdminEditCategory.php` | High
111 | File | `/Administrator/PHP/AdminReply.php` | High
112 | File | `/admin_pic.php` | High
113 | File | `/admin_single_student.php` | High
114 | File | `/aim/storage/query.py` | High
115 | File | `/ajax.php?action=calculate_payroll` | High
116 | File | `/ajax.php?action=delete_member` | High
117 | File | `/ajax.php?action=delete_package` | High
118 | File | `/ajax.php?action=delete_payroll` | High
119 | File | `/ajax.php?action=delete_trainer` | High
120 | File | `/ajax_city.php` | High
121 | File | `/ajx.php` | Medium
122 | File | `/all_student.php` | High
123 | File | `/api/admin/sys-user/reset/password/` | High
124 | File | `/api/article/del` | High
125 | File | `/api/backend/ext/import-data/import-channel` | High
126 | File | `/api/database/testConnect` | High
127 | File | `/api/File/downloadFile` | High
128 | File | `/api/Security/` | High
129 | File | `/api/semantic/database/testConnect` | High
130 | File | `/api/system/dept/update` | High
131 | ... | ... | ...

There are 1161 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
