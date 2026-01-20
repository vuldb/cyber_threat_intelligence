# Ponystealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ponystealer](https://vuldb.com/?actor.ponystealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ponystealer](https://vuldb.com/?actor.ponystealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ponystealer:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [JP](https://vuldb.com/?country.jp)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ponystealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.42.73.29](https://vuldb.com/?ip.20.42.73.29) | - | - | High
2 | [23.40.30.30](https://vuldb.com/?ip.23.40.30.30) | a23-40-30-30.deploy.static.akamaitechnologies.com | - | High
3 | [23.56.9.181](https://vuldb.com/?ip.23.56.9.181) | a23-56-9-181.deploy.static.akamaitechnologies.com | - | High
4 | [23.227.38.65](https://vuldb.com/?ip.23.227.38.65) | myshopify.com | - | High
5 | [23.238.221.30](https://vuldb.com/?ip.23.238.221.30) | - | - | High
6 | [34.240.216.169](https://vuldb.com/?ip.34.240.216.169) | ec2-34-240-216-169.eu-west-1.compute.amazonaws.com | - | Medium
7 | [35.194.164.137](https://vuldb.com/?ip.35.194.164.137) | 137.164.194.35.bc.googleusercontent.com | - | Medium
8 | [45.76.142.81](https://vuldb.com/?ip.45.76.142.81) | 45.76.142.81.vultrusercontent.com | - | Medium
9 | [47.91.170.222](https://vuldb.com/?ip.47.91.170.222) | - | - | High
10 | [47.254.67.48](https://vuldb.com/?ip.47.254.67.48) | - | - | High
11 | [50.63.202.69](https://vuldb.com/?ip.50.63.202.69) | ip-50-63-202-69.ip.secureserver.net | - | High
12 | [50.63.202.89](https://vuldb.com/?ip.50.63.202.89) | ip-50-63-202-89.ip.secureserver.net | - | High
13 | [52.5.251.20](https://vuldb.com/?ip.52.5.251.20) | ec2-52-5-251-20.compute-1.amazonaws.com | - | Medium
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ponystealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ponystealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//etc/RT2870STA.dat` | High
2 | File | `/99/ImportSQLTable` | High
3 | File | `/?page=tickets` | High
4 | File | `/add-apartment.php` | High
5 | File | `/add-students.php` | High
6 | File | `/adding-exec.php` | High
7 | File | `/adds.php` | Medium
8 | File | `/add_drive.php` | High
9 | File | `/add_members.php` | High
10 | File | `/add_overtime.php` | High
11 | File | `/admin#article/edit?id=2` | High
12 | File | `/admin-api/mp/material/upload-news-image` | High
13 | File | `/admin-api/mp/material/upload-permanent` | High
14 | File | `/admin-cp/theme/editor/default` | High
15 | File | `/admin/?page=inmates/view_inmate` | High
16 | File | `/admin/?page=reminders/view_reminder` | High
17 | File | `/admin/?page=user/list` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-customer.php` | High
20 | File | `/admin/add-normal-ticket.php` | High
21 | File | `/admin/add-scdetails.php` | High
22 | File | `/admin/addroom.php` | High
23 | File | `/admin/add_student.php` | High
24 | File | `/admin/admin-profile.php` | High
25 | File | `/admin/admin-update-employee.php` | High
26 | File | `/admin/all-request.php` | High
27 | File | `/admin/applicants/controller.php` | High
28 | File | `/admin/article/add/do` | High
29 | File | `/admin/blood/update/B+.php` | High
30 | File | `/admin/booking-bwdates-reports-details.php` | High
31 | File | `/admin/booktime.php` | High
32 | File | `/admin/book_add.php` | High
33 | File | `/admin/categories/manage_category.php` | High
34 | File | `/admin/change-image.php` | High
35 | File | `/admin/changeimage.php` | High
36 | File | `/admin/changeimage2.php` | High
37 | File | `/admin/changeimage3.php` | High
38 | File | `/admin/chatroom.php` | High
39 | File | `/admin/company/controller.php` | High
40 | File | `/admin/complaint-details.php` | High
41 | File | `/admin/complaint-search.php` | High
42 | File | `/admin/content/index` | High
43 | File | `/admin/controller/delete_group_student.php` | High
44 | File | `/admin/court-type` | High
45 | File | `/admin/delete-doctor.php` | High
46 | File | `/Admin/delete-fee.php` | High
47 | File | `/admin/del_category.php` | High
48 | File | `/admin/div_data/delete?divId=9` | High
49 | File | `/admin/edit-accepted-appointment.php` | High
50 | File | `/admin/edit-art-product-detail.php?editid=2` | High
51 | File | `/admin/edit-category.php` | High
52 | File | `/admin/edit-pass-detail.php` | High
53 | File | `/admin/edit_category.php` | High
54 | File | `/admin/file/upload.do` | High
55 | File | `/admin/forgot-password.php` | High
56 | File | `/admin/index.php` | High
57 | File | `/admin/index.php/web/ajax_all_lists` | High
58 | File | `/admin/index3.php` | High
59 | File | `/admin/inquiries/view_inquiry.php` | High
60 | File | `/Admin/InsertCategory.php` | High
61 | File | `/Admin/InsertState.php` | High
62 | File | `/admin/leancloud.php` | High
63 | File | `/admin/list_ipAddressPolicy.php` | High
64 | File | `/admin/loadUsers` | High
65 | File | `/Admin/login.php` | High
66 | File | `/admin/manage-users.php` | High
67 | File | `/admin/member_save.php` | High
68 | File | `/admin/menus/view_menu.php` | High
69 | File | `/admin/menu_save.php` | High
70 | File | `/admin/Operations/Role.php` | High
71 | File | `/admin/pages/edit_chicken.php` | High
72 | File | `/admin/positions_row.php` | High
73 | File | `/admin/print.php` | High
74 | File | `/admin/products/manage_product.php` | High
75 | File | `/admin/quote-details.php` | High
76 | File | `/admin/read.php?mudi=getSignal` | High
77 | File | `/admin/registration.php` | High
78 | File | `/admin/request-received-bydonar.php` | High
79 | File | `/admin/search-appointment.php` | High
80 | File | `/admin/search-vehicle.php` | High
81 | File | `/admin/search.php` | High
82 | File | `/admin/setup.cgi` | High
83 | File | `/admin/singlelogin.php?submit=1` | High
84 | File | `/admin/state.php` | High
85 | File | `/admin/students/view_details.php` | High
86 | File | `/admin/student_edit_photo.php` | High
87 | File | `/admin/suppliercontroller.php` | High
88 | File | `/admin/tasks` | Medium
89 | File | `/admin/template/edit` | High
90 | File | `/admin/update_s6.php` | High
91 | File | `/admin/update_users.php` | High
92 | File | `/admin/upload/authorImg/` | High
93 | File | `/admin/upload/img` | High
94 | File | `/admin/user-profile.php` | High
95 | File | `/admin/user/controller.php` | High
96 | File | `/admin/user/list` | High
97 | File | `/admin/usermanagement.php` | High
98 | File | `/admin/view-foreigner-ticket.php` | High
99 | File | `/admin/view-user-queries.php` | High
100 | File | `/admin/voters_row.php` | High
101 | File | `/adminac.php` | Medium
102 | File | `/Admin_dashboard/edit_profile` | High
103 | File | `/admin_topic.php?action=delall` | High
104 | File | `/adv_dhcps.php` | High
105 | File | `/ajax.php?action=delete_member` | High
106 | File | `/ajax.php?action=delete_position` | High
107 | File | `/ajax.php?action=save_employee_attendance` | High
108 | File | `/ajax.php?action=save_payment` | High
109 | File | `/ajax.php?action=save_user` | High
110 | File | `/allocated_rooms.php` | High
111 | File | `/Android/data/com.myairtelapp/files/` | High
112 | File | `/api.php` | Medium
113 | File | `/api/admin/store/product/save` | High
114 | File | `/api/authentication/login` | High
115 | File | `/api/blade-user/submit` | High
116 | File | `/api/ServiceAgent/start_service` | High
117 | File | `/api/v1/getbaseconfig` | High
118 | File | `/api/v3/search/categories` | High
119 | File | `/api/videos/public` | High
120 | ... | ... | ...

There are 1069 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/threat-roundup-0817-0824.html
* https://blog.talosintelligence.com/2018/08/threat-roundup-0824-0831.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0412-0419.html
* https://blog.talosintelligence.com/2019/06/threat-roundup-0621-0628.html
* https://blog.talosintelligence.com/2020/09/threat-roundup-0828-0904.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-1016-1023.html
* https://blog.talosintelligence.com/2020/11/threat-roundup-1113-1120.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1126-1203.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
