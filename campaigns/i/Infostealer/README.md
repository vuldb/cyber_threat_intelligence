# Infostealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Infostealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Infostealer:

* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Infostealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Infostealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.34.178.21](https://vuldb.com/?ip.5.34.178.21) | node240816.us | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
2 | [5.188.87.58](https://vuldb.com/?ip.5.188.87.58) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
3 | [46.173.215.132](https://vuldb.com/?ip.46.173.215.132) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
4 | [66.42.63.27](https://vuldb.com/?ip.66.42.63.27) | 66.42.63.27.vultrusercontent.com | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Infostealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-35, CWE-41 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Infostealer. This data is unique as it uses our predictive model for actor profiling.

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
20 | File | `/admin/addexec.php` | High
21 | File | `/admin/addpackage.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/adminprofile.php` | High
24 | File | `/admin/admin_feature.php` | High
25 | File | `/admin/admin_running.php` | High
26 | File | `/admin/admin_user.php` | High
27 | File | `/admin/ajax.php?action=save_settings` | High
28 | File | `/admin/assign/assign.php` | High
29 | File | `/admin/blood/update/B+.php` | High
30 | File | `/admin/bookdate.php` | High
31 | File | `/admin/booking_report.php` | High
32 | File | `/admin/booktime.php` | High
33 | File | `/admin/bwdates-reports-details.php` | High
34 | File | `/admin/candidates_add.php` | High
35 | File | `/admin/categories/view_category.php` | High
36 | File | `/admin/category.php` | High
37 | File | `/admin/change-image.php` | High
38 | File | `/admin/changeimage.php` | High
39 | File | `/admin/content/book` | High
40 | File | `/admin/controller/delete_group_student.php` | High
41 | File | `/admin/court-type` | High
42 | File | `/admin/deletegallery.php` | High
43 | File | `/admin/delete_members.php` | High
44 | File | `/admin/delete_s7.php` | High
45 | File | `/admin/departments/manage_department.php` | High
46 | File | `/admin/disapprove_user.php` | High
47 | File | `/admin/edit-category.php` | High
48 | File | `/admin/edit-class.php` | High
49 | File | `/Admin/edit-photo.php` | High
50 | File | `/admin/edit-user-profile.php` | High
51 | File | `/admin/edit_class.php` | High
52 | File | `/admin/edit_room.php` | High
53 | File | `/admin/edit_teacher.php` | High
54 | File | `/admin/index.php` | High
55 | File | `/admin/index.php/news/edit` | High
56 | File | `/admin/index.php/web/ajax_all_lists` | High
57 | File | `/admin/ind_backstage.php` | High
58 | File | `/admin/inquiries/view_inquiry.php` | High
59 | File | `/admin/list_addr_fwresource_ip.php` | High
60 | File | `/Admin/match.php` | High
61 | File | `/admin/network/diag_iperf` | High
62 | File | `/admin/operations/travellers.php` | High
63 | File | `/admin/overtime_add.php` | High
64 | File | `/admin/pass-bwdates-report.php` | High
65 | File | `/admin/plugin.php` | High
66 | File | `/admin/productadd_back.php` | High
67 | File | `/admin/profile.php` | High
68 | File | `/admin/read.php?mudi=getSignal` | High
69 | File | `/admin/return_add.php` | High
70 | File | `/admin/role/list` | High
71 | File | `/admin/salary_slip.php` | High
72 | File | `/admin/save_airlines.php` | High
73 | File | `/admin/save_user.php` | High
74 | File | `/admin/search-autoortaxi.php` | High
75 | File | `/admin/sensitive_word/list` | High
76 | File | `/admin/settings/index.php?page=accounts` | High
77 | File | `/admin/students.php` | High
78 | File | `/admin/sys/role/list` | High
79 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
80 | File | `/admin/tag/list` | High
81 | File | `/admin/tags/save` | High
82 | File | `/admin/transaction/deposit` | High
83 | File | `/admin/update-rooms.php` | High
84 | File | `/admin/update-users.php` | High
85 | File | `/admin/update_room.php` | High
86 | File | `/admin/update_s3.php` | High
87 | File | `/admin/upload/authorImg/` | High
88 | File | `/admin/view-appointment.php` | High
89 | File | `/admin/view-appointment.php?viewid=11` | High
90 | File | `/admin/view-enquiry.php` | High
91 | File | `/admin/view-normal-ticket.php` | High
92 | File | `/admin/voters_edit.php` | High
93 | File | `/admin?do=admin:user:editPost` | High
94 | File | `/administrator` | High
95 | File | `/admin_area/index.php` | High
96 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
97 | File | `/admin_route/inc_service_credits.php` | High
98 | File | `/admin_topic.php?action=delall` | High
99 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
100 | File | `/adms/admin/?page=vehicles/view_transaction` | High
101 | File | `/adms/classes/Users.php` | High
102 | File | `/ajax.php?action=delete_borrower` | High
103 | File | `/ajax.php?action=save_category` | High
104 | File | `/ajax.php?action=save_deductions` | High
105 | File | `/ajax.php?action=save_supplier` | High
106 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
107 | File | `/ajax_state.php` | High
108 | File | `/animalsupdate.php` | High
109 | File | `/api/client/editemedia.php` | High
110 | File | `/api/dept/build` | High
111 | File | `/api/file/downloadfile` | High
112 | File | `/api/job/add/` | High
113 | File | `/api/open/forms/` | High
114 | File | `/api/wechat/app_auth` | High
115 | File | `/api/wizard/getBasicInfo` | High
116 | File | `/api/wizard/getDualbandSync` | High
117 | File | `/app/admin/controller/Images.php` | High
118 | File | `/app/control/byt_cv_manager` | High
119 | ... | ... | ...

There are 1054 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://labs.withsecure.com/publications/darkgate-malware-campaign

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
