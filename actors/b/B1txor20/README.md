# B1txor20 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [B1txor20](https://vuldb.com/?actor.b1txor20). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.b1txor20](https://vuldb.com/?actor.b1txor20)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with B1txor20:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of B1txor20.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.69.50](https://vuldb.com/?ip.5.2.69.50) | - | - | High
2 | [23.129.64.216](https://vuldb.com/?ip.23.129.64.216) | - | - | High
3 | [23.154.177.4](https://vuldb.com/?ip.23.154.177.4) | - | - | High
4 | [45.13.104.179](https://vuldb.com/?ip.45.13.104.179) | nosoignons.cust.milkywan.net | - | High
5 | [45.61.185.90](https://vuldb.com/?ip.45.61.185.90) | MiamiTor4.us | - | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | - | High
7 | [46.166.139.111](https://vuldb.com/?ip.46.166.139.111) | - | - | High
8 | [51.15.43.205](https://vuldb.com/?ip.51.15.43.205) | 205-43-15-51.instances.scw.cloud | - | High
9 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | - | High
10 | [62.102.148.69](https://vuldb.com/?ip.62.102.148.69) | - | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _B1txor20_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by B1txor20. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/aa` | Low
4 | File | `/addelidetails.php` | High
5 | File | `/add_employee.php` | High
6 | File | `/add_reserve.php` | High
7 | File | `/add_student/` | High
8 | File | `/admin-api/mp/material/upload-permanent` | High
9 | File | `/admin.php` | Medium
10 | File | `/admin.php/addon/index` | High
11 | File | `/admin.php?mod=brand&act=del` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=back_order/view_bo` | High
14 | File | `/admin/?page=maintenance/brand` | High
15 | File | `/admin/aboutPost.php` | High
16 | File | `/admin/aboutus.php` | High
17 | File | `/admin/accepted-appointment.php` | High
18 | File | `/admin/add-art-type.php` | High
19 | File | `/admin/add-category.php` | High
20 | File | `/admin/addroom.php` | High
21 | File | `/admin/add_student.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/admin/save` | High
24 | File | `/admin/adminprofile.php` | High
25 | File | `/admin/all-applications.php` | High
26 | File | `/admin/announcement/index.php?view=add` | High
27 | File | `/admin/app/profile_crud.php` | High
28 | File | `/admin/app/slider_crud.php` | High
29 | File | `/Admin/assets/backend/seller/add_seller.php` | High
30 | File | `/admin/assign_save.php` | High
31 | File | `/admin/attachment/download` | High
32 | File | `/admin/attendance_row.php` | High
33 | File | `/admin/auto-taxi-entry-detail.php` | High
34 | File | `/admin/between-date-complaintreport.php` | High
35 | File | `/admin/booking-search.php` | High
36 | File | `/admin/candidates_delete.php` | High
37 | File | `/admin/category.php` | High
38 | File | `/admin/category/add.do` | High
39 | File | `/admin/check_studid.php` | High
40 | File | `/admin/complaint-search.php` | High
41 | File | `/admin/confirm.php` | High
42 | File | `/admin/contact-list.php` | High
43 | File | `/admin/contactus.php` | High
44 | File | `/admin/core/new_user` | High
45 | File | `/Admin/CustomerReport.php` | High
46 | File | `/admin/delete-session.php` | High
47 | File | `/admin/delete_member.php` | High
48 | File | `/admin/department/add` | High
49 | File | `/admin/display-teacher.php` | High
50 | File | `/admin/doctor-specilization.php` | High
51 | File | `/admin/edit-admin.php` | High
52 | File | `/admin/edit-category.php` | High
53 | File | `/admin/edit-course.php` | High
54 | File | `/admin/edit-nurse.php` | High
55 | File | `/admin/edit-subjects-detail.php` | High
56 | File | `/admin/edit_activity.php` | High
57 | File | `/admin/edit_admin.php` | High
58 | File | `/admin/edit_expenses.php` | High
59 | File | `/admin/edit_expenses_query.php` | High
60 | File | `/admin/edit_product.php` | High
61 | File | `/admin/edit_student_query.php` | High
62 | File | `/Admin/facilitator.php` | High
63 | File | `/admin/file.php` | High
64 | File | `/admin/file/rename.do` | High
65 | File | `/admin/forgot-password.php` | High
66 | File | `/admin/getmanagerregion.php` | High
67 | File | `/admin/home/index.html` | High
68 | File | `/admin/ImgUpdaPost.php` | High
69 | File | `/admin/index.php` | High
70 | File | `/admin/index.php/news/edit` | High
71 | File | `/admin/login` | Medium
72 | File | `/admin/login.php` | High
73 | File | `/admin/manage-users.php` | High
74 | File | `/admin/manage_movie.php` | High
75 | File | `/admin/manage_seat.php` | High
76 | File | `/admin/manage_user.php` | High
77 | File | `/admin/member_save.php` | High
78 | File | `/admin/message/search.php` | High
79 | File | `/admin/new-autoortaxi-entry-form.php` | High
80 | File | `/admin/offenses/view_details.php` | High
81 | File | `/admin/operation/user.php` | High
82 | File | `/admin/Operations/Role.php` | High
83 | File | `/admin/pass-bwdates-reports-details.php` | High
84 | File | `/admin/payment_save.php` | High
85 | File | `/admin/redirect.php` | High
86 | File | `/admin/registration.php` | High
87 | File | `/admin/request-received-bydonar.php` | High
88 | File | `/admin/search-report-details.php` | High
89 | File | `/admin/search.php` | High
90 | File | `/admin/semester.php` | High
91 | File | `/admin/storage/delete` | High
92 | File | `/admin/subject/controller.php` | High
93 | File | `/admin/SysModule/edit.html` | High
94 | File | `/admin/teacher-salary.php` | High
95 | File | `/admin/update-rooms.php` | High
96 | File | `/admin/update_fst.php` | High
97 | File | `/admin/user.php` | High
98 | File | `/admin/users-applications.php` | High
99 | File | `/admin/users.php` | High
100 | File | `/admin/user_update.php` | High
101 | File | `/admin/v1/link/edit` | High
102 | File | `/admin/view_vacancy.php` | High
103 | File | `/admin/voters_row.php` | High
104 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
105 | File | `/Administrator/PHP/AdminAddCategory.php` | High
106 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
107 | File | `/Administrator/PHP/AdminEditCategory.php` | High
108 | File | `/Administrator/PHP/AdminReply.php` | High
109 | File | `/admin_pic.php` | High
110 | File | `/admin_single_student.php` | High
111 | File | `/admin_single_student_update.php` | High
112 | File | `/aim/storage/query.py` | High
113 | File | `/ajax.php?action=calculate_payroll` | High
114 | File | `/ajax.php?action=delete_member` | High
115 | File | `/ajax.php?action=delete_package` | High
116 | File | `/ajax_city.php` | High
117 | File | `/ajx.php` | Medium
118 | File | `/all_student.php` | High
119 | File | `/api/admin/common/download/templates` | High
120 | File | `/api/admin/sys-user/reset/password/` | High
121 | ... | ... | ...

There are 1071 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/b1txor20-use-of-dns-tunneling_cn/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
