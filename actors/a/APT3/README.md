# APT3 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT3](https://vuldb.com/?actor.apt3). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt3](https://vuldb.com/?actor.apt3)

## Campaigns

The following _campaigns_ are known and can be associated with APT3:

* CVE-2015-5119
* Double Tap

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT3:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT3.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.99.20.198](https://vuldb.com/?ip.23.99.20.198) | - | - | High
2 | [54.169.89.240](https://vuldb.com/?ip.54.169.89.240) | ec2-54-169-89-240.ap-southeast-1.compute.amazonaws.com | - | Medium
3 | [104.151.248.173](https://vuldb.com/?ip.104.151.248.173) | 173.248-151-104.rdns.scalabledns.com | Double Tap | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT3_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT3. This data is unique as it uses our predictive model for actor profiling.

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
31 | File | `/admin/book_add.php` | High
32 | File | `/admin/categories/manage_category.php` | High
33 | File | `/admin/changeimage.php` | High
34 | File | `/admin/changeimage2.php` | High
35 | File | `/admin/changeimage3.php` | High
36 | File | `/admin/chatroom.php` | High
37 | File | `/admin/company/controller.php` | High
38 | File | `/admin/complaint-details.php` | High
39 | File | `/admin/complaint-search.php` | High
40 | File | `/admin/content/index` | High
41 | File | `/admin/controller/delete_group_student.php` | High
42 | File | `/admin/court-type` | High
43 | File | `/admin/delete-doctor.php` | High
44 | File | `/Admin/delete-fee.php` | High
45 | File | `/admin/del_category.php` | High
46 | File | `/admin/div_data/delete?divId=9` | High
47 | File | `/admin/edit-accepted-appointment.php` | High
48 | File | `/admin/edit-art-product-detail.php?editid=2` | High
49 | File | `/admin/edit-category.php` | High
50 | File | `/admin/edit-pass-detail.php` | High
51 | File | `/admin/edit_category.php` | High
52 | File | `/admin/file/upload.do` | High
53 | File | `/admin/forgot-password.php` | High
54 | File | `/admin/index.php` | High
55 | File | `/admin/index.php/web/ajax_all_lists` | High
56 | File | `/admin/index3.php` | High
57 | File | `/admin/inquiries/view_inquiry.php` | High
58 | File | `/Admin/InsertCategory.php` | High
59 | File | `/Admin/InsertState.php` | High
60 | File | `/admin/leancloud.php` | High
61 | File | `/admin/list_ipAddressPolicy.php` | High
62 | File | `/admin/loadUsers` | High
63 | File | `/Admin/login.php` | High
64 | File | `/admin/manage-users.php` | High
65 | File | `/admin/member_save.php` | High
66 | File | `/admin/menus/view_menu.php` | High
67 | File | `/admin/menu_save.php` | High
68 | File | `/admin/Operations/Role.php` | High
69 | File | `/admin/pages/edit_chicken.php` | High
70 | File | `/admin/positions_row.php` | High
71 | File | `/admin/print.php` | High
72 | File | `/admin/products/manage_product.php` | High
73 | File | `/admin/quote-details.php` | High
74 | File | `/admin/read.php?mudi=getSignal` | High
75 | File | `/admin/registration.php` | High
76 | File | `/admin/request-received-bydonar.php` | High
77 | File | `/admin/search-appointment.php` | High
78 | File | `/admin/search-vehicle.php` | High
79 | File | `/admin/search.php` | High
80 | File | `/admin/setup.cgi` | High
81 | File | `/admin/singlelogin.php?submit=1` | High
82 | File | `/admin/state.php` | High
83 | File | `/admin/students/view_details.php` | High
84 | File | `/admin/student_edit_photo.php` | High
85 | File | `/admin/suppliercontroller.php` | High
86 | File | `/admin/tasks` | Medium
87 | File | `/admin/template/edit` | High
88 | File | `/admin/update_s6.php` | High
89 | File | `/admin/update_users.php` | High
90 | File | `/admin/upload/authorImg/` | High
91 | File | `/admin/upload/img` | High
92 | File | `/admin/user-profile.php` | High
93 | File | `/admin/user/controller.php` | High
94 | File | `/admin/user/list` | High
95 | File | `/admin/usermanagement.php` | High
96 | File | `/admin/view-foreigner-ticket.php` | High
97 | File | `/admin/view-user-queries.php` | High
98 | File | `/admin/voters_row.php` | High
99 | File | `/adminac.php` | Medium
100 | File | `/Admin_dashboard/edit_profile` | High
101 | File | `/admin_topic.php?action=delall` | High
102 | File | `/adv_dhcps.php` | High
103 | File | `/ajax.php?action=delete_member` | High
104 | File | `/ajax.php?action=delete_position` | High
105 | File | `/ajax.php?action=save_employee_attendance` | High
106 | File | `/ajax.php?action=save_payment` | High
107 | File | `/ajax.php?action=save_user` | High
108 | File | `/allocated_rooms.php` | High
109 | File | `/Android/data/com.myairtelapp/files/` | High
110 | File | `/api.php` | Medium
111 | File | `/api/admin/store/product/save` | High
112 | File | `/api/authentication/login` | High
113 | File | `/api/blade-user/submit` | High
114 | File | `/api/ServiceAgent/start_service` | High
115 | File | `/api/v1/getbaseconfig` | High
116 | File | `/api/v3/search/categories` | High
117 | File | `/api/videos/public` | High
118 | File | `/api/wizard/getCapabilityWeb` | High
119 | ... | ... | ...

There are 1058 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fireeye/iocs/blob/master/APT3/62f65dae-9475-44b0-a9eb-c1baebbd9885.ioc
* https://github.com/fireeye/iocs/blob/master/APT3/db0b6ac6-874a-498e-892b-ac7c2020e061.ioc
* https://www.fireeye.com/blog/threat-research/2014/11/operation_doubletap.html
* https://www.fireeye.com/blog/threat-research/2015/07/demonstrating_hustle.html
* https://www.recordedfuture.com/chinese-mss-behind-apt3/
* https://www.threatminer.org/report.php?q=APTGroupUPSTargetsUSGovernmentwithHackingTeamFlashExploit-PaloAltoNetworksBlogPaloAltoNetworksBlog.pdf&y=2015
* https://www.threatminer.org/report.php?q=OperationDoubleTap.pdf&y=2014
* https://www.threatminer.org/report.php?q=SecondAdobeFlashZero-DayCVE-2015-5122fromHackingTeamExploitedinStrategicWebCompromiseTargetingJapaneseVictims%C2%ABThreatResearchBlog_FireEyeInc.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
