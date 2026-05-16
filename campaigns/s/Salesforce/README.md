# Salesforce - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Salesforce_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Salesforce:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Salesforce or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [UNC6040](https://vuldb.com/?actor.unc6040) | High
2 | [UNC6395](https://vuldb.com/?actor.unc6395) | High
3 | [GRUB1](https://vuldb.com/?actor.grub1) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Salesforce.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [44.215.108.109](https://vuldb.com/?ip.44.215.108.109) | ec2-44-215-108-109.compute-1.amazonaws.com | [UNC6395](https://vuldb.com/?actor.unc6395) | Medium
2 | [109.70.100.68](https://vuldb.com/?ip.109.70.100.68) | tor-exit-anonymizer.appliedprivacy.net | [UNC6040](https://vuldb.com/?actor.unc6040) | High
3 | [109.70.100.71](https://vuldb.com/?ip.109.70.100.71) | tor-exit-anonymizer.appliedprivacy.net | [UNC6040](https://vuldb.com/?actor.unc6040) | High
4 | [154.41.95.2](https://vuldb.com/?ip.154.41.95.2) | - | [UNC6395](https://vuldb.com/?actor.unc6395) | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Salesforce. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-83 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Salesforce. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/a/sys/area/save` | High
4 | File | `/add-lockertype.php` | High
5 | File | `/add-normal-ticket.php` | High
6 | File | `/add-product.php` | High
7 | File | `/adm/index.php` | High
8 | File | `/admin#themes` | High
9 | File | `/admin-cp/menus` | High
10 | File | `/admin-cp/permalinks` | High
11 | File | `/admin.php/addon/index` | High
12 | File | `/admin.php?mod=brand&act=del` | High
13 | File | `/admin/accepted-appointment.php` | High
14 | File | `/admin/add-ambulance.php` | High
15 | File | `/admin/add-art-product.php` | High
16 | File | `/admin/add-artist.php` | High
17 | File | `/admin/addroom.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/admin/save` | High
20 | File | `/admin/admin_football.php` | High
21 | File | `/admin/app/profile_crud.php` | High
22 | File | `/admin/app/role_crud.php` | High
23 | File | `/admin/app/slider_crud.php` | High
24 | File | `/admin/assign_save.php` | High
25 | File | `/admin/attachment/download` | High
26 | File | `/admin/attendance_row.php` | High
27 | File | `/admin/bookdate.php` | High
28 | File | `/admin/booking-bwdates-reports-details.php` | High
29 | File | `/admin/booktime.php` | High
30 | File | `/admin/bwdates-reports-details.php` | High
31 | File | `/admin/candidates_add.php` | High
32 | File | `/admin/candidates_delete.php` | High
33 | File | `/admin/checkout_query.php` | High
34 | File | `/admin/check_availability.php` | High
35 | File | `/admin/complaint-search.php` | High
36 | File | `/admin/completed-requests.php` | High
37 | File | `/admin/course.php` | High
38 | File | `/admin/doctor-specilization.php` | High
39 | File | `/admin/edit-admin.php` | High
40 | File | `/admin/edit-art-product-detail.php?editid=2` | High
41 | File | `/admin/edit-guard-detail.php` | High
42 | File | `/admin/edit-team.php` | High
43 | File | `/admin/edit-user.php` | High
44 | File | `/admin/edit_activity.php` | High
45 | File | `/admin/edit_admin_details.php?id=admin` | High
46 | File | `/admin/edit_admin_query.php` | High
47 | File | `/admin/edit_expenses.php` | High
48 | File | `/admin/edit_expenses_query.php` | High
49 | File | `/admin/edit_query_account.php` | High
50 | File | `/admin/edit_student_query.php` | High
51 | File | `/admin/eligibility.php` | High
52 | File | `/admin/forget-password.php` | High
53 | File | `/admin/getmanagerregion.php` | High
54 | File | `/admin/group/edit.do` | High
55 | File | `/admin/ImgUpdaPost.php` | High
56 | File | `/admin/includes/edit_post.php` | High
57 | File | `/admin/index.php` | High
58 | File | `/admin/lab.php` | High
59 | File | `/admin/login-back.php` | High
60 | File | `/admin/login.php` | High
61 | File | `/admin/manage-art-medium.php` | High
62 | File | `/admin/manage-foreigners-ticket.php` | High
63 | File | `/admin/manage-notices.php` | High
64 | File | `/admin/manage-tickets.php` | High
65 | File | `/admin/manage-users.php` | High
66 | File | `/admin/manage_user.php` | High
67 | File | `/admin/member_save.php` | High
68 | File | `/admin/message/search.php` | High
69 | File | `/admin/modules/lesson/index.php` | High
70 | File | `/admin/new-autoortaxi-entry-form.php` | High
71 | File | `/admin/operation/user.php` | High
72 | File | `/admin/positions_edit.php` | High
73 | File | `/admin/redirect.php` | High
74 | File | `/admin/search-directory.php` | High
75 | File | `/admin/search-invoices.php` | High
76 | File | `/admin/storage/delete` | High
77 | File | `/Admin/student.php` | High
78 | File | `/admin/students.php` | High
79 | File | `/admin/subject/controller.php` | High
80 | File | `/admin/suppliercontroller.php` | High
81 | File | `/admin/system/variableList.do` | High
82 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
83 | File | `/admin/user.php` | High
84 | File | `/admin/user/edit.do` | High
85 | File | `/admin/v1/blog/edit` | High
86 | File | `/admin/view-user-queries.php` | High
87 | File | `/admin/View_user.php` | High
88 | File | `/admin/voters_row.php` | High
89 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
90 | File | `/Administrator/PHP/AdminAddCategory.php` | High
91 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
92 | File | `/Administrator/PHP/AdminEditCategory.php` | High
93 | File | `/Administrator/PHP/AdminReply.php` | High
94 | File | `/Administrator/PHP/AdminUpdateCategory.php` | High
95 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
96 | File | `/admin_link.php?action=delall` | High
97 | File | `/admin_pic.php` | High
98 | File | `/adv_mac_filter.php` | High
99 | File | `/AGE0000700/GetImageMedico?fooId=1` | High
100 | File | `/aim/storage/query.py` | High
101 | File | `/airag/knowledge/doc/edit` | High
102 | File | `/ajax.php?action=calculate_payroll` | High
103 | File | `/ajax.php?action=delete_allowances` | High
104 | File | `/ajax.php?action=delete_package` | High
105 | File | `/ajax.php?action=delete_trainer` | High
106 | File | `/ajax.php?action=delete_user` | High
107 | File | `/ajax.php?action=end_membership` | High
108 | File | `/ajax.php?action=save_membership` | High
109 | File | `/ajax.php?action=save_payroll` | High
110 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
111 | File | `/api/database/testConnect` | High
112 | File | `/api/file/upload` | High
113 | File | `/api/info/long_task` | High
114 | File | `/api/undo/` | Medium
115 | File | `/api/wizard/getssidname` | High
116 | File | `/api/wizard/setLanguage` | High
117 | File | `/app/api/controller/collect.php` | High
118 | File | `/app/register.php?action=reg` | High
119 | File | `/app/sms.php` | Medium
120 | File | `/appDetail.jsp` | High
121 | ... | ... | ...

There are 1077 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.cloudflare.com/response-to-salesloft-drift-incident/
* https://cloud.google.com/blog/topics/threat-intelligence/data-theft-salesforce-instances-via-salesloft-drift/
* https://www.recordedfuture.com/blog/salesforce-gainsight-security-incident

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
