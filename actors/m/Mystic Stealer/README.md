# Mystic Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mystic Stealer](https://vuldb.com/?actor.mystic_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mystic_stealer](https://vuldb.com/?actor.mystic_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mystic Stealer:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mystic Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.111.145.27](https://vuldb.com/?ip.3.111.145.27) | ec2-3-111-145-27.ap-south-1.compute.amazonaws.com | - | Medium
2 | [5.42.64.18](https://vuldb.com/?ip.5.42.64.18) | - | - | High
3 | [5.42.64.20](https://vuldb.com/?ip.5.42.64.20) | - | - | High
4 | [5.42.65.126](https://vuldb.com/?ip.5.42.65.126) | - | - | High
5 | [5.42.92.43](https://vuldb.com/?ip.5.42.92.43) | hosted-by.yeezyhost.net | - | High
6 | [5.42.92.88](https://vuldb.com/?ip.5.42.92.88) | hosted-by.yeezyhost.net | - | High
7 | [5.42.92.211](https://vuldb.com/?ip.5.42.92.211) | . | - | High
8 | [5.42.94.125](https://vuldb.com/?ip.5.42.94.125) | juicy-milk.aeza.network | - | High
9 | [5.75.183.169](https://vuldb.com/?ip.5.75.183.169) | static.169.183.75.5.clients.your-server.de | - | High
10 | [5.188.87.45](https://vuldb.com/?ip.5.188.87.45) | - | - | High
11 | [5.196.93.222](https://vuldb.com/?ip.5.196.93.222) | 934.gra.abcvg.ovh | - | High
12 | [13.200.127.74](https://vuldb.com/?ip.13.200.127.74) | ec2-13-200-127-74.ap-south-1.compute.amazonaws.com | - | Medium
13 | [13.208.166.206](https://vuldb.com/?ip.13.208.166.206) | ec2-13-208-166-206.ap-northeast-3.compute.amazonaws.com | - | Medium
14 | [13.232.156.210](https://vuldb.com/?ip.13.232.156.210) | ec2-13-232-156-210.ap-south-1.compute.amazonaws.com | - | Medium
15 | [23.163.0.179](https://vuldb.com/?ip.23.163.0.179) | mail.pnet-asp.tech | - | High
16 | [34.88.245.41](https://vuldb.com/?ip.34.88.245.41) | 41.245.88.34.bc.googleusercontent.com | - | Medium
17 | [37.139.129.70](https://vuldb.com/?ip.37.139.129.70) | - | - | High
18 | [41.208.73.44](https://vuldb.com/?ip.41.208.73.44) | 41.208.73.44.static.ltt.ly | - | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mystic Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mystic Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/account.php` | Medium
3 | File | `/action.php` | Medium
4 | File | `/Actions.php` | Medium
5 | File | `/adaddmed.php` | High
6 | File | `/add-notes.php` | High
7 | File | `/add-phlebotomist.php` | High
8 | File | `/addCatController.php` | High
9 | File | `/addcategory.php` | High
10 | File | `/addcompany.php` | High
11 | File | `/addcustcom.php` | High
12 | File | `/addelivery.php` | High
13 | File | `/add_achievement_details.php` | High
14 | File | `/admin` | Low
15 | File | `/admin#themes` | High
16 | File | `/admin-manage-user.php` | High
17 | File | `/admin-profile.php` | High
18 | File | `/admin/` | Low
19 | File | `/admin/aboutus.php` | High
20 | File | `/admin/add-ambulance.php` | High
21 | File | `/admin/add-art-medium.php` | High
22 | File | `/admin/add-category.php` | High
23 | File | `/admin/admin-profile.php` | High
24 | File | `/admin/admin_action.php` | High
25 | File | `/admin/ajax.php?action=login` | High
26 | File | `/admin/ajax.php?action=save_vacancy` | High
27 | File | `/admin/app/product.php` | High
28 | File | `/admin/app/profile_crud.php` | High
29 | File | `/admin/application-bwdates-reports-details.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
32 | File | `/admin/ballot_up.php` | High
33 | File | `/admin/bookdate.php` | High
34 | File | `/admin/book_row.php` | High
35 | File | `/admin/bwdates-report-details.php` | High
36 | File | `/admin/bwdates-reports-details.php` | High
37 | File | `/admin/bwdates-request-report-details.php` | High
38 | File | `/admin/candidates_row.php` | High
39 | File | `/admin/category.php` | High
40 | File | `/admin/change-emailid.php` | High
41 | File | `/admin/chatroom.php` | High
42 | File | `/admin/clients/manage.php` | High
43 | File | `/admin/content/book` | High
44 | File | `/admin/content/editor` | High
45 | File | `/admin/content/index` | High
46 | File | `/admin/create_product.php` | High
47 | File | `/admin/delete_s2.php` | High
48 | File | `/admin/departments/manage_department.php` | High
49 | File | `/admin/doctor-specilization.php` | High
50 | File | `/admin/edit-category.php` | High
51 | File | `/admin/edit-doctor.php` | High
52 | File | `/admin/edit-nurse.php` | High
53 | File | `/Admin/edit-photo.php` | High
54 | File | `/admin/edit-services.php` | High
55 | File | `/admin/edit-subcategory.php` | High
56 | File | `/admin/editorder.php` | High
57 | File | `/admin/edit_product.php` | High
58 | File | `/admin/edit_room.php` | High
59 | File | `/admin/edit_user.php` | High
60 | File | `/admin/goods/update` | High
61 | File | `/admin/index.php` | High
62 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
63 | File | `/admin/login.php` | High
64 | File | `/admin/manage-foreigners-ticket.php` | High
65 | File | `/admin/manage-site.php` | High
66 | File | `/admin/manage-teams.php` | High
67 | File | `/admin/manage_complaint.php` | High
68 | File | `/Admin/match.php` | High
69 | File | `/admin/network/ajax_getChannelList` | High
70 | File | `/admin/network/diag_ping6` | High
71 | File | `/admin/Operation/User.php` | High
72 | File | `/admin/operations/booking.php` | High
73 | File | `/admin/operations/expense_category.php` | High
74 | File | `/admin/operations/payment.php` | High
75 | File | `/admin/password-recovery.php` | High
76 | File | `/admin/positions_row.php` | High
77 | File | `/admin/profile.php` | High
78 | File | `/admin/regester.php` | High
79 | File | `/Admin/resultdetails.php` | High
80 | File | `/admin/room.php` | High
81 | File | `/admin/rules.php` | High
82 | File | `/admin/search-directory.php` | High
83 | File | `/admin/search-invoices.php` | High
84 | File | `/admin/sensitive_word/list` | High
85 | File | `/admin/sign/out` | High
86 | File | `/admin/sms_setting.php` | High
87 | File | `/admin/tag/save` | High
88 | File | `/admin/update-users.php` | High
89 | File | `/admin/update_s1.php` | High
90 | File | `/admin/update_s4.php` | High
91 | File | `/admin/update_s8.php` | High
92 | File | `/admin/update_users.php` | High
93 | File | `/admin/user.php` | High
94 | File | `/admin/users.php` | High
95 | File | `/admin/view-appointment.php` | High
96 | File | `/admin/voters_row.php` | High
97 | File | `/admin?do=admin:user:editPost` | High
98 | File | `/adminprofile.php` | High
99 | File | `/adphar.php` | Medium
100 | File | `/adposition/queryAll` | High
101 | File | `/ajax.php?action=delete_allowances` | High
102 | File | `/ajax.php?action=delete_position` | High
103 | File | `/ajax.php?action=save_borrower` | High
104 | File | `/ajax.php?action=save_plan` | High
105 | File | `/ajax.php?action=save_schedule` | High
106 | File | `/animalsupdate.php` | High
107 | File | `/api/front/search/books` | High
108 | File | `/api/job/add/` | High
109 | File | `/api/role` | Medium
110 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
111 | File | `/api/upload` | Medium
112 | File | `/app/api/controller/Site.php` | High
113 | File | `/Applications/Steal/main.cpp` | High
114 | File | `/auth/info` | Medium
115 | File | `/backend/admin/his_admin_add_vendor.php` | High
116 | File | `/backend/admin/his_admin_register_patient.php` | High
117 | File | `/backend/register.php` | High
118 | File | `/bank/statements.php` | High
119 | File | `/bank/transfer.php` | High
120 | File | `/bbdms/admin/update-contactinfo.php` | High
121 | File | `/billaction.php` | High
122 | File | `/boafrm/formFilter` | High
123 | File | `/boafrm/formMapDelDevice` | High
124 | File | `/boafrm/formOneKeyAccessButton` | High
125 | File | `/boafrm/formParentControl` | High
126 | File | `/boafrm/formRoute` | High
127 | File | `/boafrm/formTmultiAP` | High
128 | File | `/book-appointment.php` | High
129 | ... | ... | ...

There are 1149 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/3bfdcee7-1163-4cb5-a421-c89ebe581fb3
* https://app.any.run/tasks/6a907458-4ae2-4bbf-a4cd-120e7c7c5b60
* https://app.any.run/tasks/83e1bcf1-7e3f-46d1-b87f-9dc761b34cd0
* https://app.any.run/tasks/342f5538-7e82-4f54-908e-18efa2cc2669
* https://app.any.run/tasks/b15ddaaf-9197-4310-af15-d2f45ef44c91
* https://app.any.run/tasks/d1a96aea-a514-4f86-acd7-e9391a8ec959
* https://blog.pulsedive.com/identifying-mystic-stealer-control-panels/
* https://github.com/threatlabz/iocs/blob/main/mystic_stealer/c2s.txt
* https://pulsedive.com/threat/Mystic%20Stealer
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/security-research/mystic-stealer
* https://x.com/Xanderuxsf5/status/1940324451046031670

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
