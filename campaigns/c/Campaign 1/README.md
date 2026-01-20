# Campaign 1 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 1_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 1:

* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Campaign 1 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign 1.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [10.16.91.131](https://vuldb.com/?ip.10.16.91.131) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [11.24.8.54](https://vuldb.com/?ip.11.24.8.54) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [11.25.41.114](https://vuldb.com/?ip.11.25.41.114) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [13.33.26.95](https://vuldb.com/?ip.13.33.26.95) | server-13-33-26-95.phx50.r.cloudfront.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [13.56.107.66](https://vuldb.com/?ip.13.56.107.66) | ec2-13-56-107-66.us-west-1.compute.amazonaws.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | Medium
6 | [14.40.57.104](https://vuldb.com/?ip.14.40.57.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [15.85.30.84](https://vuldb.com/?ip.15.85.30.84) | atp467w084.sgp.hp.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [19.140.139.6](https://vuldb.com/?ip.19.140.139.6) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [20.143.69.60](https://vuldb.com/?ip.20.143.69.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [23.26.60.60](https://vuldb.com/?ip.23.26.60.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | [23.92.211.10](https://vuldb.com/?ip.23.92.211.10) | gramwide.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
12 | [25.108.63.68](https://vuldb.com/?ip.25.108.63.68) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
13 | [26.50.108.98](https://vuldb.com/?ip.26.50.108.98) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
14 | [27.22.41.133](https://vuldb.com/?ip.27.22.41.133) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
15 | [29.136.101.40](https://vuldb.com/?ip.29.136.101.40) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
16 | [30.101.13.14](https://vuldb.com/?ip.30.101.13.14) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
17 | [33.9.140.76](https://vuldb.com/?ip.33.9.140.76) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
18 | [36.75.63.47](https://vuldb.com/?ip.36.75.63.47) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/action.php` | Medium
3 | File | `/action/upload_file` | High
4 | File | `/add-notes.php` | High
5 | File | `/add.home.php` | High
6 | File | `/add.php` | Medium
7 | File | `/addcategory.php` | High
8 | File | `/addcompany.php` | High
9 | File | `/addcustind.php` | High
10 | File | `/addmem.php` | Medium
11 | File | `/add_personal_details.php` | High
12 | File | `/admin` | Low
13 | File | `/admin#themes` | High
14 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
15 | File | `/admin/?page=borrow/view_borrow` | High
16 | File | `/admin/?page=user/list` | High
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/add-customer-services.php` | High
19 | File | `/admin/add-customer.php` | High
20 | File | `/admin/add-foreigner-ticket.php` | High
21 | File | `/admin/add-propertytype.php` | High
22 | File | `/admin/add_title.php` | High
23 | File | `/admin/admin-area.php` | High
24 | File | `/admin/allemployees.php` | High
25 | File | `/admin/app/product.php` | High
26 | File | `/admin/app/profile_crud.php` | High
27 | File | `/admin/application-bwdates-reports-details.php` | High
28 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
29 | File | `/admin/assign/assign.php` | High
30 | File | `/admin/attendance_row.php` | High
31 | File | `/admin/book-details.php` | High
32 | File | `/admin/booktime.php` | High
33 | File | `/admin/budget/manage_budget.php` | High
34 | File | `/admin/candidates_add.php` | High
35 | File | `/admin/category-list.php` | High
36 | File | `/admin/change-emailid.php` | High
37 | File | `/admin/change-image.php` | High
38 | File | `/admin/changeimage.php` | High
39 | File | `/admin/conferences/get-all-status/` | High
40 | File | `/admin/contact-us.php` | High
41 | File | `/admin/content` | High
42 | File | `/admin/courses/view_course.php` | High
43 | File | `/admin/delete-row.php` | High
44 | File | `/admin/deleteitem.php` | High
45 | File | `/admin/deleteroom.php` | High
46 | File | `/admin/delete_s4.php` | High
47 | File | `/admin/de_activate.php` | High
48 | File | `/admin/doctor-specilization.php` | High
49 | File | `/admin/edit-equipmentform.php` | High
50 | File | `/admin/edit-services.php` | High
51 | File | `/admin/edit-state.php` | High
52 | File | `/admin/edit-user.php` | High
53 | File | `/admin/edit_product.php` | High
54 | File | `/Admin/edit_profile.php` | High
55 | File | `/admin/edit_room.php` | High
56 | File | `/admin/edit_user.php` | High
57 | File | `/admin/file/rename.do` | High
58 | File | `/admin/getallarticleinfo` | High
59 | File | `/admin/images/add` | High
60 | File | `/admin/index.php/web/ajax_all_lists` | High
61 | File | `/admin/indexConfigs/save` | High
62 | File | `/admin/ipAddPost.php` | High
63 | File | `/admin/link.php` | High
64 | File | `/admin/manage-students.php` | High
65 | File | `/admin/manage_complaint.php` | High
66 | File | `/Admin/match.php` | High
67 | File | `/admin/member_save.php` | High
68 | File | `/admin/menu_update.php` | High
69 | File | `/admin/modules/course/index.php` | High
70 | File | `/admin/modules/instructor/index.php` | High
71 | File | `/admin/network/ajax_getChannelList` | High
72 | File | `/admin/operations/booking.php` | High
73 | File | `/admin/operations/expense.php` | High
74 | File | `/admin/operations/packages.php` | High
75 | File | `/admin/operations/travellers.php` | High
76 | File | `/admin/order.php` | High
77 | File | `/admin/project/update/2` | High
78 | File | `/admin/regester.php` | High
79 | File | `/admin/request-received-bydonar.php` | High
80 | File | `/admin/rooms.php` | High
81 | File | `/admin/search-appointment.php` | High
82 | File | `/admin/sms_setting.php` | High
83 | File | `/admin/students/manage.php` | High
84 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
85 | File | `/admin/upload/authorImg/` | High
86 | File | `/admin/user/updatePwd` | High
87 | File | `/admin/visitor-details.php` | High
88 | File | `/admin/voters_add.php` | High
89 | File | `/adminFile/upload` | High
90 | File | `/administrator/bidlist.php` | High
91 | File | `/administrator/remove.php` | High
92 | File | `/adms/admin/?page=vehicles/view_transaction` | High
93 | File | `/adposition/queryAll` | High
94 | File | `/aim/storage/query.py` | High
95 | File | `/ajax.php` | Medium
96 | File | `/ajax.php?action=delete_category` | High
97 | File | `/ajax.php?action=delete_course` | High
98 | File | `/ajax.php?action=delete_customer` | High
99 | File | `/ajax.php?action=save_borrower` | High
100 | File | `/ajax.php?action=save_customer` | High
101 | File | `/ajax_state.php` | High
102 | File | `/all-orders.php` | High
103 | File | `/api.php` | Medium
104 | File | `/api/code/upload` | High
105 | File | `/api/dept/build` | High
106 | File | `/Api/FileUploadApi.ashx` | High
107 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
108 | File | `/api/process.php` | High
109 | File | `/api/system/dept/update` | High
110 | File | `/api/upload` | Medium
111 | File | `/api/v1.index.article/getList.html` | High
112 | File | `/api/wizard/networkSetup` | High
113 | File | `/app/api/v1/openvpn.py` | High
114 | File | `/app/platform/controllers/ResetpwdController.php` | High
115 | File | `/application/index/controller/Unity.php` | High
116 | File | `/App_Resource/UEditor/server/upload.aspx` | High
117 | File | `/auth_files/photo/` | High
118 | File | `/backend/doc/his_doc_register_patient.php` | High
119 | File | `/backend/register.php` | High
120 | File | `/backups/` | Medium
121 | File | `/bank/transfer.php` | High
122 | File | `/billaction.php` | High
123 | File | `/bin/httpd` | Medium
124 | File | `/boafrm/formFilter` | High
125 | File | `/boafrm/formIpQoS` | High
126 | File | `/boafrm/formIpv6Setup` | High
127 | File | `/boafrm/formMultiAPVLAN` | High
128 | File | `/boafrm/formOneKeyAccessButton` | High
129 | File | `/boafrm/formParentControl` | High
130 | File | `/boafrm/formReflashClientTbl` | High
131 | File | `/boafrm/formRoute` | High
132 | File | `/boafrm/formSysTel` | High
133 | File | `/boafrm/formWsc` | High
134 | File | `/book_list.php` | High
135 | File | `/browsemdcn.php` | High
136 | File | `/bwdates-report-result.php` | High
137 | ... | ... | ...

There are 1215 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_1_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
