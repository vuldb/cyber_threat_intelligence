# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Proxy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [SystemBC](https://vuldb.com/?actor.systembc) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Proxy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
6 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
7 | [85.206.167.134](https://vuldb.com/?ip.85.206.167.134) | localhost | [SystemBC](https://vuldb.com/?actor.systembc) | High
8 | [85.206.167.139](https://vuldb.com/?ip.85.206.167.139) | localhost | [SystemBC](https://vuldb.com/?actor.systembc) | High
9 | [85.206.167.143](https://vuldb.com/?ip.85.206.167.143) | localhost | [SystemBC](https://vuldb.com/?actor.systembc) | High
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-41 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=tickets` | High
3 | File | `/?page=user` | Medium
4 | File | `/add-apartment.php` | High
5 | File | `/add-office.php` | High
6 | File | `/add-subadmin.php` | High
7 | File | `/addCandidate.php` | High
8 | File | `/addcategory.php` | High
9 | File | `/add_drive.php` | High
10 | File | `/add_reserve.php` | High
11 | File | `/admin` | Low
12 | File | `/admin-api/mp/material/upload-news-image` | High
13 | File | `/admin-cp/theme/editor/default` | High
14 | File | `/admin.php?mod=brand&act=del` | High
15 | File | `/admin/?page=reminders/view_reminder` | High
16 | File | `/admin/about-us.php` | High
17 | File | `/admin/aboutus.php` | High
18 | File | `/admin/add-normal-ticket.php` | High
19 | File | `/admin/add-scdetails.php` | High
20 | File | `/admin/addexec.php` | High
21 | File | `/admin/addroom.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/adminprofile.php` | High
24 | File | `/admin/admin_feature.php` | High
25 | File | `/admin/admin_running.php` | High
26 | File | `/admin/ajax.php?action=save_settings` | High
27 | File | `/admin/assign/assign.php` | High
28 | File | `/admin/blood/update/B+.php` | High
29 | File | `/admin/bookdate.php` | High
30 | File | `/admin/booking_report.php` | High
31 | File | `/admin/booktime.php` | High
32 | File | `/admin/candidates_add.php` | High
33 | File | `/admin/case-status` | High
34 | File | `/admin/categories/manage_category.php` | High
35 | File | `/admin/categories/view_category.php` | High
36 | File | `/admin/category.php` | High
37 | File | `/admin/change-image.php` | High
38 | File | `/admin/changeimage3.php` | High
39 | File | `/Admin/changepassword.php` | High
40 | File | `/admin/check_admin.php` | High
41 | File | `/admin/content/index` | High
42 | File | `/admin/controller/delete_group_student.php` | High
43 | File | `/admin/court-type` | High
44 | File | `/Admin/delete-fee.php` | High
45 | File | `/admin/deletegallery.php` | High
46 | File | `/admin/delete_members.php` | High
47 | File | `/admin/departments/manage_department.php` | High
48 | File | `/admin/div_data/delete?divId=9` | High
49 | File | `/admin/edit-category.php` | High
50 | File | `/admin/edit-class.php` | High
51 | File | `/Admin/edit-photo.php` | High
52 | File | `/admin/edit-user-profile.php` | High
53 | File | `/admin/edit_admin_query.php` | High
54 | File | `/admin/edit_room.php` | High
55 | File | `/admin/edit_teacher.php` | High
56 | File | `/admin/expense-type` | High
57 | File | `/admin/forgot-password.php` | High
58 | File | `/admin/index.php` | High
59 | File | `/admin/index.php/news/edit` | High
60 | File | `/admin/index.php/web/ajax_all_lists` | High
61 | File | `/admin/ind_backstage.php` | High
62 | File | `/admin/inquiries/view_inquiry.php` | High
63 | File | `/Admin/InsertCategory.php` | High
64 | File | `/Admin/InsertState.php` | High
65 | File | `/admin/list_addr_fwresource_ip.php` | High
66 | File | `/admin/manage-users.php` | High
67 | File | `/Admin/match.php` | High
68 | File | `/admin/member_save.php` | High
69 | File | `/Admin/News.php` | High
70 | File | `/admin/operation/user.php` | High
71 | File | `/admin/Operations/Role.php` | High
72 | File | `/admin/operations/travellers.php` | High
73 | File | `/admin/overtime_add.php` | High
74 | File | `/admin/plugin.php` | High
75 | File | `/admin/productadd_back.php` | High
76 | File | `/admin/profile.php` | High
77 | File | `/admin/read.php?mudi=getSignal` | High
78 | File | `/admin/request-received-bydonar.php` | High
79 | File | `/admin/return_add.php` | High
80 | File | `/admin/save_airlines.php` | High
81 | File | `/admin/save_student.php` | High
82 | File | `/admin/save_user.php` | High
83 | File | `/admin/search-appointment.php` | High
84 | File | `/admin/search-autoortaxi.php` | High
85 | File | `/admin/service` | High
86 | File | `/admin/settings/index.php?page=accounts` | High
87 | File | `/admin/setup.cgi` | High
88 | File | `/admin/students.php` | High
89 | File | `/admin/sys/role/list` | High
90 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
91 | File | `/admin/tag/list` | High
92 | File | `/admin/tags/save` | High
93 | File | `/admin/transaction/deposit` | High
94 | File | `/admin/update-rooms.php` | High
95 | File | `/admin/update-users.php` | High
96 | File | `/admin/update_room.php` | High
97 | File | `/admin/update_users.php` | High
98 | File | `/admin/upload/authorImg/` | High
99 | File | `/admin/user-profile.php` | High
100 | File | `/admin/view-appointment.php` | High
101 | File | `/admin/view-appointment.php?viewid=11` | High
102 | File | `/admin/view-enquiry.php` | High
103 | File | `/admin/view-foreigner-ticket.php` | High
104 | File | `/admin/view-normal-ticket.php` | High
105 | File | `/admin/view-user-queries.php` | High
106 | File | `/admin/voters_add.php` | High
107 | File | `/admin/voters_edit.php` | High
108 | File | `/administrator` | High
109 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
110 | File | `/admin_route/inc_service_credits.php` | High
111 | File | `/admin_topic.php?action=delall` | High
112 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
113 | File | `/adms/admin/?page=vehicles/view_transaction` | High
114 | File | `/adms/classes/Users.php` | High
115 | File | `/adv_dhcps.php` | High
116 | File | `/ajax.php?action=delete_borrower` | High
117 | File | `/ajax.php?action=delete_member` | High
118 | File | `/ajax.php?action=save_category` | High
119 | File | `/ajax.php?action=save_employee_attendance` | High
120 | File | `/ajax.php?action=save_payment` | High
121 | File | `/ajax.php?action=save_user` | High
122 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
123 | File | `/ajax_state.php` | High
124 | File | `/allocated_rooms.php` | High
125 | File | `/Android/data/com.myairtelapp/files/` | High
126 | File | `/animalsupdate.php` | High
127 | ... | ... | ...

There are 1128 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.lumen.com/systembc-bringing-the-noise/
* https://github.com/vishalyadav70/Proxy-Server/blob/main/proxy/blacklist.txt
* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
