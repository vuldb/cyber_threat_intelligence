# RondoDox - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RondoDox](https://vuldb.com/?actor.rondodox). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rondodox](https://vuldb.com/?actor.rondodox)

## Campaigns

The following _campaigns_ are known and can be associated with RondoDox:

* CVE-2024-3721 / CVE-2024-12856
* CVE-2025-55182

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RondoDox:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RondoDox.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.231.70.66](https://vuldb.com/?ip.5.231.70.66) | - | CVE-2025-55182 | High
2 | [5.255.121.141](https://vuldb.com/?ip.5.255.121.141) | - | CVE-2025-55182 | High
3 | [14.103.145.202](https://vuldb.com/?ip.14.103.145.202) | - | CVE-2024-3721 / CVE-2024-12856 | High
4 | [14.103.145.211](https://vuldb.com/?ip.14.103.145.211) | - | CVE-2024-3721 / CVE-2024-12856 | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RondoDox_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RondoDox. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/action/upload_file` | High
3 | File | `/actuator` | Medium
4 | File | `/add-notes.php` | High
5 | File | `/add-phlebotomist.php` | High
6 | File | `/addcategory.php` | High
7 | File | `/addelivery.php` | High
8 | File | `/adding-exec.php` | High
9 | File | `/addmem.php` | Medium
10 | File | `/addstock.php` | High
11 | File | `/add_achievement_details.php` | High
12 | File | `/admin#article/edit?id=2` | High
13 | File | `/admin#themes` | High
14 | File | `/admin-inbox.php` | High
15 | File | `/admin/` | Low
16 | File | `/admin/?page=state` | High
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/adminprofile.php` | High
21 | File | `/admin/admin_members.php?ac=search` | High
22 | File | `/admin/ajax.php?action=save_settings` | High
23 | File | `/admin/app/login_crud.php` | High
24 | File | `/admin/app/profile_crud.php` | High
25 | File | `/admin/approve_user.php` | High
26 | File | `/admin/article/article-edit-run.php` | High
27 | File | `/admin/assign/assign.php` | High
28 | File | `/admin/attendance_row.php` | High
29 | File | `/admin/blogger.php?action=update_avatar` | High
30 | File | `/admin/book_row.php` | High
31 | File | `/admin/bwdates-reports-details.php` | High
32 | File | `/admin/bwdates-request-report-details.php` | High
33 | File | `/Admin/changepassword.php` | High
34 | File | `/admin/check_admin_login.php` | High
35 | File | `/admin/class.php` | High
36 | File | `/admin/class.php?dowhat=modifyclass` | High
37 | File | `/admin/contactus.php` | High
38 | File | `/admin/deleteuser.php` | High
39 | File | `/admin/delete_student.php` | High
40 | File | `/admin/edit-category-detail.php` | High
41 | File | `/admin/edit-customer-detailed.php` | High
42 | File | `/admin/edit-subadmin.php` | High
43 | File | `/admin/edit-teacher-detail.php` | High
44 | File | `/admin/edit-user.php` | High
45 | File | `/admin/edit_class.php` | High
46 | File | `/admin/edit_fuel.php` | High
47 | File | `/admin/edit_product.php` | High
48 | File | `/admin/general/change-lang` | High
49 | File | `/admin/index.php` | High
50 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
51 | File | `/admin/inquiries/view_details.php` | High
52 | File | `/admin/lab.php` | High
53 | File | `/admin/login.php` | High
54 | File | `/admin/maintenance/view_designation.php` | High
55 | File | `/admin/manage-normal-ticket.php` | High
56 | File | `/Admin/match.php` | High
57 | File | `/Admin/mode.php` | High
58 | File | `/admin/network/diag_nslookup` | High
59 | File | `/admin/network/diag_pinginterface` | High
60 | File | `/admin/normal-search.php` | High
61 | File | `/admin/options-theme.php` | High
62 | File | `/admin/pages/student-print.php` | High
63 | File | `/admin/pass-bwdates-report.php` | High
64 | File | `/admin/password-recovery.php` | High
65 | File | `/admin/php/crud.php` | High
66 | File | `/admin/print_barcode.php` | High
67 | File | `/Admin/Proses_Edit_Akun.php` | High
68 | File | `/admin/regester.php` | High
69 | File | `/admin/request-received-bydonar.php` | High
70 | File | `/admin/robot.php` | High
71 | File | `/admin/search-booking-request.php` | High
72 | File | `/admin/search-pass.php` | High
73 | File | `/admin/sou.php` | High
74 | File | `/Admin/sporttype.php` | High
75 | File | `/admin/update-users.php` | High
76 | File | `/admin/update_s8.php` | High
77 | File | `/admin/update_user.php` | High
78 | File | `/admin/upload/authorImg/` | High
79 | File | `/Admin/user-record.php` | High
80 | File | `/admin/user.php` | High
81 | File | `/admin/v1/blog/edit` | High
82 | File | `/admin/view-appointment.php` | High
83 | File | `/admin/view-enquiry.php` | High
84 | File | `/admin/view-foreigner-ticket.php` | High
85 | File | `/admin/voters_row.php` | High
86 | File | `/admin79f2ec220c7e.php?c=api&m=demo&name=mobile` | High
87 | File | `/admin?do=admin:user:editPost` | High
88 | File | `/Administrator/PHP/AdminAddUser.php` | High
89 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
90 | File | `/admin_class.php?action=login` | High
91 | File | `/admin_topic.php?action=delall` | High
92 | File | `/ajax.php` | Medium
93 | File | `/ajax.php?action=delete_loan` | High
94 | File | `/ajax.php?action=save_plan` | High
95 | File | `/ajax.php?action=save_supplier` | High
96 | File | `/api/admin/question/edit` | High
97 | File | `/api/backend/v1/user/create` | High
98 | File | `/api/controllers/common/UploadsController.php` | High
99 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
100 | File | `/api/system/sendWebSocketMsg` | High
101 | File | `/api/v1/login` | High
102 | File | `/api/v1/settings` | High
103 | File | `/api/wizard/networkSetup` | High
104 | File | `/app-api/v1/members/openid/` | High
105 | File | `/app/ajax/search_sales_report.php` | High
106 | File | `/app/ConfirmSmsCode` | High
107 | File | `/application/models/ApplicationDataObject.class.php` | High
108 | File | `/auth/user/all.api` | High
109 | File | `/backend/admin/his_admin_register_patient.php` | High
110 | File | `/bank/statements.php` | High
111 | File | `/bank/transfer.php` | High
112 | File | `/bin/httpd` | Medium
113 | File | `/bin/main` | Medium
114 | File | `/biurl_grou` | Medium
115 | File | `/boafrm/formFilter` | High
116 | File | `/boafrm/formOneKeyAccessButton` | High
117 | File | `/boafrm/formParentControl` | High
118 | File | `/boafrm/formRoute` | High
119 | File | `/boafrm/formWlSiteSurvey` | High
120 | File | `/boafrm/formWlwds` | High
121 | ... | ... | ...

There are 1071 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://beelzebub.ai/blog/rondo-dox-v2/
* https://hunt.io/blog/china-hosting-malware-c2-infrastructure
* https://urlhaus.abuse.ch/url/3610576/
* https://urlhaus.abuse.ch/url/3736092/
* https://www.cloudsek.com/blog/rondodox-botnet-weaponizes-react2shell
* https://www.fortinet.com/blog/threat-research/rondobox-unveiled-breaking-down-a-botnet-threat

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
