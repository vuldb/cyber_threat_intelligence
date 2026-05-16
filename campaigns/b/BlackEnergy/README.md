# BlackEnergy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BlackEnergy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackEnergy:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BlackEnergy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
2 | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackEnergy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.9.32.230](https://vuldb.com/?ip.5.9.32.230) | static.230.32.9.5.clients.your-server.de | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
2 | [5.61.38.31](https://vuldb.com/?ip.5.61.38.31) | - | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
3 | [5.79.80.166](https://vuldb.com/?ip.5.79.80.166) | - | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
4 | [5.149.254.114](https://vuldb.com/?ip.5.149.254.114) | mail1.auditoriavanzada.info | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
5 | [5.255.87.39](https://vuldb.com/?ip.5.255.87.39) | - | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
6 | [31.210.111.154](https://vuldb.com/?ip.31.210.111.154) | . | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/action/upload_file` | High
3 | File | `/actuator` | Medium
4 | File | `/add-phlebotomist.php` | High
5 | File | `/addcategory.php` | High
6 | File | `/addelivery.php` | High
7 | File | `/adding-exec.php` | High
8 | File | `/addmem.php` | Medium
9 | File | `/addstock.php` | High
10 | File | `/admin#article/edit?id=2` | High
11 | File | `/admin#themes` | High
12 | File | `/admin-inbox.php` | High
13 | File | `/admin/` | Low
14 | File | `/admin/?page=state` | High
15 | File | `/admin/about-us.php` | High
16 | File | `/admin/aboutPost.php` | High
17 | File | `/admin/aboutus.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/adminprofile.php` | High
20 | File | `/admin/admin_members.php?ac=search` | High
21 | File | `/admin/ajax.php?action=save_settings` | High
22 | File | `/admin/api/theme-edit/` | High
23 | File | `/admin/app/login_crud.php` | High
24 | File | `/admin/app/profile_crud.php` | High
25 | File | `/admin/approve_user.php` | High
26 | File | `/admin/article/article-edit-run.php` | High
27 | File | `/admin/assign/assign.php` | High
28 | File | `/admin/attachment/download` | High
29 | File | `/admin/attendance_row.php` | High
30 | File | `/admin/blogger.php?action=update_avatar` | High
31 | File | `/admin/book_row.php` | High
32 | File | `/admin/bwdates-reports-details.php` | High
33 | File | `/admin/bwdates-request-report-details.php` | High
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
75 | File | `/admin/update-rooms.php` | High
76 | File | `/admin/update-users.php` | High
77 | File | `/admin/update_user.php` | High
78 | File | `/admin/upload/authorImg/` | High
79 | File | `/Admin/user-record.php` | High
80 | File | `/admin/user.php` | High
81 | File | `/admin/v1/blog/edit` | High
82 | File | `/admin/view-appointment.php` | High
83 | File | `/admin/view-enquiry.php` | High
84 | File | `/admin/view-foreigner-ticket.php` | High
85 | File | `/admin/voters_row.php` | High
86 | File | `/admin?do=admin:user:editPost` | High
87 | File | `/Administrator/PHP/AdminAddUser.php` | High
88 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
89 | File | `/admin_class.php?action=login` | High
90 | File | `/admin_topic.php?action=delall` | High
91 | File | `/ajax.php` | Medium
92 | File | `/ajax.php?action=delete_loan` | High
93 | File | `/ajax.php?action=save_plan` | High
94 | File | `/ajax.php?action=save_supplier` | High
95 | File | `/api/admin/question/edit` | High
96 | File | `/api/backend/v1/user/create` | High
97 | File | `/api/controllers/common/UploadsController.php` | High
98 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
99 | File | `/api/system/sendWebSocketMsg` | High
100 | File | `/api/v1/login` | High
101 | File | `/api/v1/settings` | High
102 | File | `/api/wizard/networkSetup` | High
103 | File | `/app-api/v1/members/openid/` | High
104 | File | `/app/ajax/search_sales_report.php` | High
105 | File | `/app/ConfirmSmsCode` | High
106 | File | `/application/models/ApplicationDataObject.class.php` | High
107 | File | `/auth/user/all.api` | High
108 | File | `/backend/admin/his_admin_register_patient.php` | High
109 | File | `/bank/statements.php` | High
110 | File | `/bank/transfer.php` | High
111 | File | `/bin/httpd` | Medium
112 | File | `/bin/main` | Medium
113 | File | `/biurl_grou` | Medium
114 | File | `/boafrm/formFilter` | High
115 | File | `/boafrm/formOneKeyAccessButton` | High
116 | File | `/boafrm/formParentControl` | High
117 | File | `/boafrm/formRoute` | High
118 | File | `/boafrm/formWlSiteSurvey` | High
119 | File | `/boafrm/formWlwds` | High
120 | File | `/boafrm/formWsc` | High
121 | File | `/bolt/editcontent/showcases` | High
122 | ... | ... | ...

There are 1078 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://blogs.mcafee.jp/blackenergy-cb6d
* https://www.threatminer.org/report.php?q=BlackEnergy2_Plugins_Router.pdf&y=2014
* https://www.welivesecurity.com/2016/01/03/blackenergy-sshbeardoor-details-2015-attacks-ukrainian-news-media-electric-industry/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
