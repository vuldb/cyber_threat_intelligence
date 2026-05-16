# MoonPeak - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MoonPeak](https://vuldb.com/?actor.moonpeak). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.moonpeak](https://vuldb.com/?actor.moonpeak)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MoonPeak:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MoonPeak.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.255.80.162](https://vuldb.com/?ip.27.255.80.162) | - | - | High
2 | [27.255.81.118](https://vuldb.com/?ip.27.255.81.118) | - | - | High
3 | [45.87.153.79](https://vuldb.com/?ip.45.87.153.79) | vm1856550.stark-industries.solutions | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MoonPeak_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MoonPeak. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/action/upload_file` | High
3 | File | `/actuator` | Medium
4 | File | `/add-notes.php` | High
5 | File | `/addcategory.php` | High
6 | File | `/addelivery.php` | High
7 | File | `/add_judge.php` | High
8 | File | `/admin-profile.php` | High
9 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
10 | File | `/admin/` | Low
11 | File | `/admin/?page=establishment` | High
12 | File | `/admin/about-us.php` | High
13 | File | `/admin/aboutus.php` | High
14 | File | `/admin/about_edit.php?action=modify` | High
15 | File | `/Admin/add-student.php` | High
16 | File | `/admin/addexec.php` | High
17 | File | `/admin/add_account.php` | High
18 | File | `/admin/add_admin.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/admin.php` | High
21 | File | `/admin/adminprofile.php` | High
22 | File | `/admin/admin_feature.php` | High
23 | File | `/admin/admin_running.php` | High
24 | File | `/admin/admin_user.php` | High
25 | File | `/admin/ajax.php?action=save_settings` | High
26 | File | `/admin/app/login_crud.php` | High
27 | File | `/admin/apply.php` | High
28 | File | `/admin/assign/assign.php` | High
29 | File | `/admin/blood/update/o-.php` | High
30 | File | `/admin/booking_report.php` | High
31 | File | `/admin/candidates_add.php` | High
32 | File | `/admin/categories/view_category.php` | High
33 | File | `/admin/change-image.php` | High
34 | File | `/admin/chatroom.php` | High
35 | File | `/admin/class.php?dowhat=modifyclass` | High
36 | File | `/admin/content/book` | High
37 | File | `/admin/content/filemanager/uploads` | High
38 | File | `/admin/controller/delete_group_student.php` | High
39 | File | `/admin/court-type` | High
40 | File | `/admin/deletegallery.php` | High
41 | File | `/admin/delete_s7.php` | High
42 | File | `/admin/departments/manage_department.php` | High
43 | File | `/admin/disapprove_user.php` | High
44 | File | `/admin/edit-boat.php` | High
45 | File | `/admin/edit-category.php` | High
46 | File | `/admin/edit-class.php` | High
47 | File | `/admin/edit-customer-detailed.php` | High
48 | File | `/Admin/edit-photo.php` | High
49 | File | `/admin/edit-user-profile.php` | High
50 | File | `/admin/edit_class.php` | High
51 | File | `/admin/edit_room.php` | High
52 | File | `/admin/edit_teacher.php` | High
53 | File | `/admin/expense_report.php` | High
54 | File | `/admin/fields/manage_field.php` | High
55 | File | `/admin/index.php` | High
56 | File | `/admin/index.php/news/edit` | High
57 | File | `/admin/inquiries/view_inquiry.php` | High
58 | File | `/admin/list_addr_fwresource_ip.php` | High
59 | File | `/admin/manage-scdetails.php` | High
60 | File | `/Admin/match.php` | High
61 | File | `/admin/operations/travellers.php` | High
62 | File | `/admin/overtime_add.php` | High
63 | File | `/admin/pages/list` | High
64 | File | `/admin/pass-bwdates-report.php` | High
65 | File | `/admin/photo.php` | High
66 | File | `/admin/plugin.php` | High
67 | File | `/admin/productadd_back.php` | High
68 | File | `/admin/profile.php` | High
69 | File | `/admin/salary_slip.php` | High
70 | File | `/admin/save_user.php` | High
71 | File | `/admin/search-autoortaxi.php` | High
72 | File | `/admin/session.php` | High
73 | File | `/admin/settings/index.php?page=accounts` | High
74 | File | `/admin/students.php` | High
75 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
76 | File | `/admin/tags/save` | High
77 | File | `/admin/templets_one_edit.php` | High
78 | File | `/admin/transaction/deposit` | High
79 | File | `/admin/update-rooms.php` | High
80 | File | `/admin/update-users.php` | High
81 | File | `/admin/update_room.php` | High
82 | File | `/admin/update_user.php` | High
83 | File | `/admin/upload/authorImg/` | High
84 | File | `/admin/users-applications.php` | High
85 | File | `/admin/view-appointment.php` | High
86 | File | `/admin/view-appointment.php?viewid=11` | High
87 | File | `/admin/view-enquiry.php` | High
88 | File | `/admin/view-member-report.php` | High
89 | File | `/admin/view-normal-ticket.php` | High
90 | File | `/admin/voters_edit.php` | High
91 | File | `/admin?do=admin:user:editPost` | High
92 | File | `/administrator` | High
93 | File | `/admin_class.php` | High
94 | File | `/admin_route/inc_service_credits.php` | High
95 | File | `/admin_topic.php?action=delall` | High
96 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
97 | File | `/adms/admin/?page=vehicles/view_transaction` | High
98 | File | `/adms/classes/Users.php` | High
99 | File | `/ajax.php` | Medium
100 | File | `/ajax.php?action=delete_borrower` | High
101 | File | `/ajax.php?action=save_category` | High
102 | File | `/ajax.php?action=save_supplier` | High
103 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
104 | File | `/ajax_state.php` | High
105 | File | `/animalsupdate.php` | High
106 | File | `/api/backend/core/web-file-upload/upload` | High
107 | File | `/api/backend/v1/user/create` | High
108 | File | `/api/config/list` | High
109 | File | `/api/dept/build` | High
110 | File | `/api/es/admin/v3/security/user/1` | High
111 | File | `/api/esps` | Medium
112 | File | `/api/file/downloadfile` | High
113 | File | `/api/job/add/` | High
114 | File | `/api/open/forms/` | High
115 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
116 | File | `/api/wechat/app_auth` | High
117 | ... | ... | ...

There are 1033 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/moonpeak-malware-infrastructure-north-korea/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
