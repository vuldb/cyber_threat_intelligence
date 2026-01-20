# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
3 | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/action/upload_file` | High
3 | File | `/actuator` | Medium
4 | File | `/add-notes.php` | High
5 | File | `/add-office.php` | High
6 | File | `/add-subadmin.php` | High
7 | File | `/addCandidate.php` | High
8 | File | `/addcategory.php` | High
9 | File | `/addelivery.php` | High
10 | File | `/add_reserve.php` | High
11 | File | `/admin` | Low
12 | File | `/admin-cp/theme/editor/default` | High
13 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
14 | File | `/admin.php?mod=brand&act=del` | High
15 | File | `/admin/` | Low
16 | File | `/admin/?page=establishment` | High
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/about_edit.php?action=modify` | High
20 | File | `/Admin/add-student.php` | High
21 | File | `/admin/addexec.php` | High
22 | File | `/admin/add_account.php` | High
23 | File | `/admin/add_admin.php` | High
24 | File | `/admin/admin-profile.php` | High
25 | File | `/admin/admin.php` | High
26 | File | `/admin/adminprofile.php` | High
27 | File | `/admin/admin_feature.php` | High
28 | File | `/admin/admin_running.php` | High
29 | File | `/admin/admin_user.php` | High
30 | File | `/admin/ajax.php?action=save_settings` | High
31 | File | `/admin/apply.php` | High
32 | File | `/admin/assign/assign.php` | High
33 | File | `/admin/blood/update/o-.php` | High
34 | File | `/admin/bookdate.php` | High
35 | File | `/admin/booking_report.php` | High
36 | File | `/admin/booktime.php` | High
37 | File | `/admin/candidates_add.php` | High
38 | File | `/admin/categories/view_category.php` | High
39 | File | `/admin/category.php` | High
40 | File | `/admin/change-image.php` | High
41 | File | `/admin/chatroom.php` | High
42 | File | `/admin/content/book` | High
43 | File | `/admin/controller/delete_group_student.php` | High
44 | File | `/admin/court-type` | High
45 | File | `/admin/deletegallery.php` | High
46 | File | `/admin/delete_s7.php` | High
47 | File | `/admin/departments/manage_department.php` | High
48 | File | `/admin/disapprove_user.php` | High
49 | File | `/admin/edit-boat.php` | High
50 | File | `/admin/edit-category.php` | High
51 | File | `/admin/edit-class.php` | High
52 | File | `/Admin/edit-photo.php` | High
53 | File | `/admin/edit-user-profile.php` | High
54 | File | `/admin/edit_class.php` | High
55 | File | `/admin/edit_room.php` | High
56 | File | `/admin/edit_teacher.php` | High
57 | File | `/admin/expense_report.php` | High
58 | File | `/admin/index.php` | High
59 | File | `/admin/index.php/news/edit` | High
60 | File | `/admin/index.php/web/ajax_all_lists` | High
61 | File | `/admin/ind_backstage.php` | High
62 | File | `/admin/inquiries/view_inquiry.php` | High
63 | File | `/admin/list_addr_fwresource_ip.php` | High
64 | File | `/Admin/match.php` | High
65 | File | `/admin/operations/travellers.php` | High
66 | File | `/admin/overtime_add.php` | High
67 | File | `/admin/pages/list` | High
68 | File | `/admin/pass-bwdates-report.php` | High
69 | File | `/admin/photo.php` | High
70 | File | `/admin/plugin.php` | High
71 | File | `/admin/productadd_back.php` | High
72 | File | `/admin/profile.php` | High
73 | File | `/admin/read.php?mudi=getSignal` | High
74 | File | `/admin/salary_slip.php` | High
75 | File | `/admin/save_user.php` | High
76 | File | `/admin/search-autoortaxi.php` | High
77 | File | `/admin/session.php` | High
78 | File | `/admin/settings/index.php?page=accounts` | High
79 | File | `/admin/students.php` | High
80 | File | `/admin/sys/role/list` | High
81 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
82 | File | `/admin/tags/save` | High
83 | File | `/admin/transaction/deposit` | High
84 | File | `/admin/update-rooms.php` | High
85 | File | `/admin/update-users.php` | High
86 | File | `/admin/update_room.php` | High
87 | File | `/admin/update_user.php` | High
88 | File | `/admin/upload/authorImg/` | High
89 | File | `/admin/users-applications.php` | High
90 | File | `/admin/view-appointment.php` | High
91 | File | `/admin/view-appointment.php?viewid=11` | High
92 | File | `/admin/view-enquiry.php` | High
93 | File | `/admin/view-normal-ticket.php` | High
94 | File | `/admin/voters_edit.php` | High
95 | File | `/admin?do=admin:user:editPost` | High
96 | File | `/administrator` | High
97 | File | `/admin_class.php` | High
98 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
99 | File | `/admin_route/inc_service_credits.php` | High
100 | File | `/admin_topic.php?action=delall` | High
101 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
102 | File | `/adms/admin/?page=vehicles/view_transaction` | High
103 | File | `/adms/classes/Users.php` | High
104 | File | `/ajax.php` | Medium
105 | File | `/ajax.php?action=delete_borrower` | High
106 | File | `/ajax.php?action=save_category` | High
107 | File | `/ajax.php?action=save_supplier` | High
108 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
109 | File | `/ajax_state.php` | High
110 | File | `/animalsupdate.php` | High
111 | File | `/api/backend/core/web-file-upload/upload` | High
112 | File | `/api/dept/build` | High
113 | File | `/api/es/admin/v3/security/user/1` | High
114 | File | `/api/esps` | Medium
115 | File | `/api/file/downloadfile` | High
116 | File | `/api/job/add/` | High
117 | File | `/api/open/forms/` | High
118 | File | `/api/wechat/app_auth` | High
119 | File | `/api/wizard/getDualbandSync` | High
120 | File | `/app/admin/controller/Images.php` | High
121 | File | `/app/admin/controller/Upload.php` | High
122 | ... | ... | ...

There are 1081 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
