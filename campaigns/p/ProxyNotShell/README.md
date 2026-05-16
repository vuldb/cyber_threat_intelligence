# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=user` | Medium
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/about.php` | Medium
4 | File | `/academic-calendar` | High
5 | File | `/add-normal-ticket.php` | High
6 | File | `/add-pig.php` | Medium
7 | File | `/add-product.php` | High
8 | File | `/addelidetails.php` | High
9 | File | `/adding-exec.php` | High
10 | File | `/addpayment.php` | High
11 | File | `/adm/index.php` | High
12 | File | `/admin#themes` | High
13 | File | `/admin.php/addon/index` | High
14 | File | `/admin.php?id=posts&action=display&value=1&postid=` | High
15 | File | `/admin.php?mod=brand&act=del` | High
16 | File | `/admin/add-ambulance.php` | High
17 | File | `/admin/add-art-product.php` | High
18 | File | `/admin/add-artist.php` | High
19 | File | `/admin/add-services.php` | High
20 | File | `/admin/addroom.php` | High
21 | File | `/admin/add_student.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/admin_football.php` | High
24 | File | `/admin/app/profile_crud.php` | High
25 | File | `/admin/assign_save.php` | High
26 | File | `/admin/attachment/download` | High
27 | File | `/admin/attendance_row.php` | High
28 | File | `/admin/auto-taxi-entry-detail.php` | High
29 | File | `/admin/ballot_down.php` | High
30 | File | `/admin/bookdate.php` | High
31 | File | `/admin/booktime.php` | High
32 | File | `/admin/candidates_add.php` | High
33 | File | `/admin/candidates_delete.php` | High
34 | File | `/admin/case-status` | High
35 | File | `/admin/category_save.php` | High
36 | File | `/admin/changeimage.php` | High
37 | File | `/Admin/changepassword.php` | High
38 | File | `/admin/check_admin.php` | High
39 | File | `/admin/complaint-search.php` | High
40 | File | `/admin/conferences/list/` | High
41 | File | `/admin/confirm.php` | High
42 | File | `/admin/contactus.php` | High
43 | File | `/admin/core/new_user` | High
44 | File | `/admin/course.php` | High
45 | File | `/admin/deletedoctorclinic.php` | High
46 | File | `/admin/deleteitem.php` | High
47 | File | `/admin/delete_file.php` | High
48 | File | `/admin/doctor-specilization.php` | High
49 | File | `/admin/edit-admin.php` | High
50 | File | `/admin/edit-artist-detail.php?editid=1` | High
51 | File | `/admin/edit-category.php` | High
52 | File | `/admin/edit-guard-detail.php` | High
53 | File | `/admin/edit-subjects-detail.php` | High
54 | File | `/admin/edit.php` | High
55 | File | `/admin/edit_activity.php` | High
56 | File | `/admin/edit_admin_details.php?id=admin` | High
57 | File | `/admin/edit_admin_query.php` | High
58 | File | `/admin/edit_expenses_query.php` | High
59 | File | `/admin/edit_members.php` | High
60 | File | `/admin/edit_student_query.php` | High
61 | File | `/admin/eligibility.php` | High
62 | File | `/admin/employee/index.php?view=edit` | High
63 | File | `/admin/expense-type` | High
64 | File | `/admin/forget-password.php` | High
65 | File | `/admin/getmanagerregion.php` | High
66 | File | `/admin/group/edit.do` | High
67 | File | `/admin/images/add` | High
68 | File | `/admin/ImgUpdaPost.php` | High
69 | File | `/admin/inbox.php&action=read` | High
70 | File | `/admin/index.php` | High
71 | File | `/admin/index.php?add_product` | High
72 | File | `/admin/index.php?language=en&nv=upload` | High
73 | File | `/admin/lab.php` | High
74 | File | `/admin/login-back.php` | High
75 | File | `/admin/login.php` | High
76 | File | `/admin/manage-notices.php` | High
77 | File | `/admin/manage-tickets.php` | High
78 | File | `/admin/manage_user.php` | High
79 | File | `/admin/member_save.php` | High
80 | File | `/admin/menus/view_menu.php` | High
81 | File | `/admin/new-autoortaxi-entry-form.php` | High
82 | File | `/Admin/News.php` | High
83 | File | `/admin/operation/user.php` | High
84 | File | `/admin/operations/expense.php` | High
85 | File | `/admin/Operations/Role.php` | High
86 | File | `/admin/pages_account.php` | High
87 | File | `/admin/payment_save.php` | High
88 | File | `/admin/print1.php` | High
89 | File | `/admin/redirect.php` | High
90 | File | `/Admin/registration.php` | High
91 | File | `/admin/rooms.php` | High
92 | File | `/admin/save_student.php` | High
93 | File | `/admin/search-directory.php` | High
94 | File | `/admin/search-invoices.php` | High
95 | File | `/admin/service` | High
96 | File | `/admin/sign/out` | High
97 | File | `/admin/storage/delete` | High
98 | File | `/admin/subject/controller.php` | High
99 | File | `/admin/suppliercontroller.php` | High
100 | File | `/admin/system.php` | High
101 | File | `/admin/team_update.php` | High
102 | File | `/admin/updateorder.php` | High
103 | File | `/admin/updatestudent.php` | High
104 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
105 | File | `/admin/user.php` | High
106 | File | `/admin/user/edit.do` | High
107 | File | `/admin/users.php` | High
108 | File | `/admin/v1/blog/edit` | High
109 | File | `/admin/vacancy/index.php` | High
110 | File | `/admin/view-user-queries.php` | High
111 | File | `/admin/view_payorder.php` | High
112 | File | `/admin/voters_add.php` | High
113 | File | `/admin/voters_row.php` | High
114 | File | `/administrator` | High
115 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
116 | File | `/Administrator/PHP/AdminAddCategory.php` | High
117 | File | `/Administrator/PHP/AdminEditCategory.php` | High
118 | File | `/Administrator/PHP/AdminReply.php` | High
119 | File | `/administrator/weweee.php` | High
120 | File | `/adminlogin.php` | High
121 | File | `/admin_pic.php` | High
122 | File | `/aim/storage/query.py` | High
123 | File | `/ajax.php?action=calculate_payroll` | High
124 | File | `/ajax.php?action=delete_trainer` | High
125 | File | `/ajax.php?action=end_membership` | High
126 | File | `/alphaware/summary.php` | High
127 | File | `/anony/mjpg.cgi` | High
128 | File | `/api/database/testConnect` | High
129 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
130 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
131 | File | `/api/users/updateEmail/` | High
132 | File | `/api/wizard/getBasicInfo` | High
133 | ... | ... | ...

There are 1178 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
