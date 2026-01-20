# Dust Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Dust Storm_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dust Storm:

* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Dust Storm or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dust Storm.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [6.9.2.1](https://vuldb.com/?ip.6.9.2.1) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
2 | [23.238.229.128](https://vuldb.com/?ip.23.238.229.128) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
3 | [27.255.72.68](https://vuldb.com/?ip.27.255.72.68) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
4 | [27.255.72.69](https://vuldb.com/?ip.27.255.72.69) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
5 | [27.255.72.78](https://vuldb.com/?ip.27.255.72.78) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
6 | [59.120.59.2](https://vuldb.com/?ip.59.120.59.2) | 59-120-59-2.hinet-ip.hinet.net | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
7 | [59.188.13.133](https://vuldb.com/?ip.59.188.13.133) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Dust Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Dust Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/action.php` | Medium
3 | File | `/action/upload_file` | High
4 | File | `/actuator` | Medium
5 | File | `/add-notes.php` | High
6 | File | `/add.home.php` | High
7 | File | `/add.php` | Medium
8 | File | `/addcategory.php` | High
9 | File | `/addcompany.php` | High
10 | File | `/addcustind.php` | High
11 | File | `/addmem.php` | Medium
12 | File | `/add_personal_details.php` | High
13 | File | `/admin` | Low
14 | File | `/admin#themes` | High
15 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
16 | File | `/admin/?page=borrow/view_borrow` | High
17 | File | `/admin/?page=user/list` | High
18 | File | `/admin/about-us.php` | High
19 | File | `/admin/add-customer-services.php` | High
20 | File | `/admin/add-customer.php` | High
21 | File | `/admin/add-foreigner-ticket.php` | High
22 | File | `/admin/add-propertytype.php` | High
23 | File | `/admin/addmanagerclinic.php` | High
24 | File | `/admin/add_title.php` | High
25 | File | `/admin/admin-area.php` | High
26 | File | `/admin/allemployees.php` | High
27 | File | `/admin/app/product.php` | High
28 | File | `/admin/app/profile_crud.php` | High
29 | File | `/admin/application-bwdates-reports-details.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
31 | File | `/admin/assign/assign.php` | High
32 | File | `/admin/attendance_row.php` | High
33 | File | `/admin/book-details.php` | High
34 | File | `/admin/booktime.php` | High
35 | File | `/admin/budget/manage_budget.php` | High
36 | File | `/admin/candidates_add.php` | High
37 | File | `/admin/category-list.php` | High
38 | File | `/admin/change-emailid.php` | High
39 | File | `/admin/change-image.php` | High
40 | File | `/admin/changeimage.php` | High
41 | File | `/admin/conferences/get-all-status/` | High
42 | File | `/admin/contact-us.php` | High
43 | File | `/admin/content` | High
44 | File | `/admin/courses/view_course.php` | High
45 | File | `/admin/delete-row.php` | High
46 | File | `/admin/deleteitem.php` | High
47 | File | `/admin/deleteroom.php` | High
48 | File | `/admin/delete_s4.php` | High
49 | File | `/admin/de_activate.php` | High
50 | File | `/admin/doctor-specilization.php` | High
51 | File | `/admin/edit-equipmentform.php` | High
52 | File | `/admin/edit-services.php` | High
53 | File | `/admin/edit-state.php` | High
54 | File | `/admin/edit-user.php` | High
55 | File | `/admin/edit_product.php` | High
56 | File | `/Admin/edit_profile.php` | High
57 | File | `/admin/edit_room.php` | High
58 | File | `/admin/edit_user.php` | High
59 | File | `/admin/execeditroom.php` | High
60 | File | `/admin/file/rename.do` | High
61 | File | `/admin/getallarticleinfo` | High
62 | File | `/admin/images/add` | High
63 | File | `/admin/index.php/web/ajax_all_lists` | High
64 | File | `/admin/indexConfigs/save` | High
65 | File | `/admin/ipAddPost.php` | High
66 | File | `/admin/link.php` | High
67 | File | `/admin/manage-students.php` | High
68 | File | `/admin/manage_complaint.php` | High
69 | File | `/Admin/match.php` | High
70 | File | `/admin/member_save.php` | High
71 | File | `/admin/menu_update.php` | High
72 | File | `/admin/modules/course/index.php` | High
73 | File | `/admin/modules/instructor/index.php` | High
74 | File | `/admin/network/ajax_getChannelList` | High
75 | File | `/admin/operations/booking.php` | High
76 | File | `/admin/operations/expense.php` | High
77 | File | `/admin/operations/packages.php` | High
78 | File | `/admin/operations/travellers.php` | High
79 | File | `/admin/project/update/2` | High
80 | File | `/admin/regester.php` | High
81 | File | `/Admin/registration.php` | High
82 | File | `/admin/request-received-bydonar.php` | High
83 | File | `/admin/rooms.php` | High
84 | File | `/admin/search-appointment.php` | High
85 | File | `/admin/sms_setting.php` | High
86 | File | `/admin/students/manage.php` | High
87 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
88 | File | `/admin/upload/authorImg/` | High
89 | File | `/admin/user/updatePwd` | High
90 | File | `/admin/visitor-details.php` | High
91 | File | `/admin/voters_add.php` | High
92 | File | `/adminFile/upload` | High
93 | File | `/administrator/bidlist.php` | High
94 | File | `/administrator/remove.php` | High
95 | File | `/adms/admin/?page=vehicles/view_transaction` | High
96 | File | `/adposition/queryAll` | High
97 | File | `/aim/storage/query.py` | High
98 | File | `/ajax.php` | Medium
99 | File | `/ajax.php?action=delete_category` | High
100 | File | `/ajax.php?action=delete_course` | High
101 | File | `/ajax.php?action=delete_customer` | High
102 | File | `/ajax.php?action=save_borrower` | High
103 | File | `/ajax.php?action=save_customer` | High
104 | File | `/ajax_state.php` | High
105 | File | `/all-orders.php` | High
106 | File | `/api/code/upload` | High
107 | File | `/api/dept/build` | High
108 | File | `/Api/FileUploadApi.ashx` | High
109 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
110 | File | `/api/process.php` | High
111 | File | `/api/system/dept/update` | High
112 | File | `/api/upload` | Medium
113 | File | `/api/v1.index.article/getList.html` | High
114 | File | `/api/wizard/networkSetup` | High
115 | File | `/app/api/v1/openvpn.py` | High
116 | File | `/app/platform/controllers/ResetpwdController.php` | High
117 | File | `/application/index/controller/Unity.php` | High
118 | File | `/App_Resource/UEditor/server/upload.aspx` | High
119 | File | `/auth_files/photo/` | High
120 | File | `/backend/doc/his_doc_register_patient.php` | High
121 | File | `/backend/register.php` | High
122 | File | `/backups/` | Medium
123 | File | `/bank/transfer.php` | High
124 | File | `/billaction.php` | High
125 | File | `/bin/httpd` | Medium
126 | File | `/blog/comment` | High
127 | File | `/boafrm/formFilter` | High
128 | File | `/boafrm/formIpQoS` | High
129 | File | `/boafrm/formIpv6Setup` | High
130 | File | `/boafrm/formMultiAPVLAN` | High
131 | File | `/boafrm/formOneKeyAccessButton` | High
132 | File | `/boafrm/formParentControl` | High
133 | File | `/boafrm/formReflashClientTbl` | High
134 | File | `/boafrm/formRoute` | High
135 | File | `/boafrm/formSysTel` | High
136 | File | `/boafrm/formWsc` | High
137 | File | `/book_list.php` | High
138 | ... | ... | ...

There are 1230 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.threatminer.org/report.php?q=Op_Dust_Storm_Report.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
