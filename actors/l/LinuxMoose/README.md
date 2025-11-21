# LinuxMoose - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LinuxMoose](https://vuldb.com/?actor.linuxmoose). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.linuxmoose](https://vuldb.com/?actor.linuxmoose)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LinuxMoose:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LinuxMoose.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.124.41.11](https://vuldb.com/?ip.27.124.41.11) | - | - | High
2 | [27.124.41.31](https://vuldb.com/?ip.27.124.41.31) | - | - | High
3 | [27.124.41.33](https://vuldb.com/?ip.27.124.41.33) | - | - | High
4 | [27.124.41.52](https://vuldb.com/?ip.27.124.41.52) | - | - | High
5 | [42.119.173.138](https://vuldb.com/?ip.42.119.173.138) | - | - | High
6 | [62.210.6.34](https://vuldb.com/?ip.62.210.6.34) | 62-210-6-34.rev.poneytelecom.eu | - | High
7 | [77.247.177.31](https://vuldb.com/?ip.77.247.177.31) | - | - | High
8 | [77.247.177.36](https://vuldb.com/?ip.77.247.177.36) | - | - | High
9 | [77.247.177.87](https://vuldb.com/?ip.77.247.177.87) | - | - | High
10 | [77.247.178.177](https://vuldb.com/?ip.77.247.178.177) | - | - | High
11 | [79.176.26.142](https://vuldb.com/?ip.79.176.26.142) | bzq-79-176-26-142.red.bezeqint.net | - | High
12 | [82.146.63.15](https://vuldb.com/?ip.82.146.63.15) | ebay2.com | - | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LinuxMoose_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LinuxMoose. This data is unique as it uses our predictive model for actor profiling.

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
16 | File | `/admin-dashboard` | High
17 | File | `/admin-manage-user.php` | High
18 | File | `/admin-profile.php` | High
19 | File | `/admin/` | Low
20 | File | `/admin/add-ambulance.php` | High
21 | File | `/admin/add-art-medium.php` | High
22 | File | `/admin/add-category.php` | High
23 | File | `/admin/admin-profile.php` | High
24 | File | `/admin/admin_action.php` | High
25 | File | `/admin/ajax.php?action=login` | High
26 | File | `/admin/ajax.php?action=save_vacancy` | High
27 | File | `/admin/app/product.php` | High
28 | File | `/admin/application-bwdates-reports-details.php` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
31 | File | `/admin/ballot_up.php` | High
32 | File | `/admin/bookdate.php` | High
33 | File | `/admin/bwdates-report-details.php` | High
34 | File | `/admin/bwdates-reports-details.php` | High
35 | File | `/admin/bwdates-request-report-details.php` | High
36 | File | `/admin/candidates_row.php` | High
37 | File | `/admin/categories/save` | High
38 | File | `/admin/category.php` | High
39 | File | `/admin/change-emailid.php` | High
40 | File | `/admin/chatroom.php` | High
41 | File | `/admin/clients/manage.php` | High
42 | File | `/admin/content/book` | High
43 | File | `/admin/content/editor` | High
44 | File | `/admin/content/index` | High
45 | File | `/admin/create_product.php` | High
46 | File | `/admin/delete_s2.php` | High
47 | File | `/admin/departments/manage_department.php` | High
48 | File | `/admin/doctor-specilization.php` | High
49 | File | `/admin/edit-category.php` | High
50 | File | `/admin/edit-doctor.php` | High
51 | File | `/admin/edit-nurse.php` | High
52 | File | `/Admin/edit-photo.php` | High
53 | File | `/admin/edit-services.php` | High
54 | File | `/admin/edit-subcategory.php` | High
55 | File | `/admin/editorder.php` | High
56 | File | `/admin/edit_product.php` | High
57 | File | `/admin/edit_room.php` | High
58 | File | `/admin/edit_user.php` | High
59 | File | `/admin/goods/update` | High
60 | File | `/admin/index.php` | High
61 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
62 | File | `/admin/manage-foreigners-ticket.php` | High
63 | File | `/admin/manage-site.php` | High
64 | File | `/admin/manage-teams.php` | High
65 | File | `/admin/manage_complaint.php` | High
66 | File | `/Admin/match.php` | High
67 | File | `/admin/network/ajax_getChannelList` | High
68 | File | `/admin/network/diag_ping6` | High
69 | File | `/admin/Operation/User.php` | High
70 | File | `/admin/operations/booking.php` | High
71 | File | `/admin/operations/expense_category.php` | High
72 | File | `/admin/operations/payment.php` | High
73 | File | `/admin/password-recovery.php` | High
74 | File | `/admin/positions_row.php` | High
75 | File | `/admin/profile.php` | High
76 | File | `/admin/regester.php` | High
77 | File | `/Admin/resultdetails.php` | High
78 | File | `/admin/room.php` | High
79 | File | `/admin/rules.php` | High
80 | File | `/admin/search-directory.php` | High
81 | File | `/admin/search-invoices.php` | High
82 | File | `/admin/sensitive_word/list` | High
83 | File | `/admin/sign/out` | High
84 | File | `/admin/sms_setting.php` | High
85 | File | `/admin/tag/save` | High
86 | File | `/admin/update-users.php` | High
87 | File | `/admin/update_s1.php` | High
88 | File | `/admin/update_s4.php` | High
89 | File | `/admin/update_s8.php` | High
90 | File | `/admin/update_users.php` | High
91 | File | `/admin/user.php` | High
92 | File | `/admin/users.php` | High
93 | File | `/admin/view-appointment.php` | High
94 | File | `/admin/voters_row.php` | High
95 | File | `/admin?do=admin:user:editPost` | High
96 | File | `/adminprofile.php` | High
97 | File | `/adphar.php` | Medium
98 | File | `/adposition/queryAll` | High
99 | File | `/ajax.php?action=delete_allowances` | High
100 | File | `/ajax.php?action=delete_position` | High
101 | File | `/ajax.php?action=save_borrower` | High
102 | File | `/ajax.php?action=save_plan` | High
103 | File | `/ajax.php?action=save_schedule` | High
104 | File | `/animalsupdate.php` | High
105 | File | `/api/front/search/books` | High
106 | File | `/api/job/add/` | High
107 | File | `/api/role` | Medium
108 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
109 | File | `/api/upload` | Medium
110 | File | `/app/api/controller/Site.php` | High
111 | File | `/Applications/Steal/main.cpp` | High
112 | File | `/auth/info` | Medium
113 | File | `/backend/admin/his_admin_add_vendor.php` | High
114 | File | `/backend/admin/his_admin_register_patient.php` | High
115 | File | `/backend/register.php` | High
116 | File | `/bank/statements.php` | High
117 | File | `/bank/transfer.php` | High
118 | File | `/bbdms/admin/update-contactinfo.php` | High
119 | File | `/billaction.php` | High
120 | File | `/boafrm/formFilter` | High
121 | File | `/boafrm/formMapDelDevice` | High
122 | File | `/boafrm/formOneKeyAccessButton` | High
123 | File | `/boafrm/formParentControl` | High
124 | File | `/boafrm/formRoute` | High
125 | File | `/boafrm/formTmultiAP` | High
126 | File | `/book-appointment.php` | High
127 | File | `/bookingconfirm.php` | High
128 | File | `/browsemdcn.php` | High
129 | File | `/BRS_top.html` | High
130 | File | `/bwdates-report-result.php` | High
131 | ... | ... | ...

There are 1159 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/moose
* https://ioc.hatenablog.com/entry/2015/05/28/000000
* https://www.threatminer.org/report.php?q=Dissecting-LinuxMoose.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
