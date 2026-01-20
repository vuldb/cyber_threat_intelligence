# SmartLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SmartLoader](https://vuldb.com/?actor.smartloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.smartloader](https://vuldb.com/?actor.smartloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmartLoader:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SmartLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [64.188.98.71](https://vuldb.com/?ip.64.188.98.71) | - | - | High
2 | [77.105.164.40](https://vuldb.com/?ip.77.105.164.40) | 2366squidsbased.example.com | - | High
3 | [77.105.164.59](https://vuldb.com/?ip.77.105.164.59) | - | - | High
4 | [77.105.164.65](https://vuldb.com/?ip.77.105.164.65) | - | - | High
5 | [77.105.164.178](https://vuldb.com/?ip.77.105.164.178) | 3292squidsbased.example.com | - | High
6 | [80.66.81.11](https://vuldb.com/?ip.80.66.81.11) | zaroshiico.com | - | High
7 | [80.66.81.134](https://vuldb.com/?ip.80.66.81.134) | argentajagneaux2.serv.host | - | High
8 | [80.66.85.195](https://vuldb.com/?ip.80.66.85.195) | plokas.serv.host | - | High
9 | [80.66.89.146](https://vuldb.com/?ip.80.66.89.146) | argentajagneaux.serv.host | - | High
10 | [80.66.89.161](https://vuldb.com/?ip.80.66.89.161) | mudriedmouse604.serv.host | - | High
11 | [80.66.89.165](https://vuldb.com/?ip.80.66.89.165) | mudriedmouse6041.serv.host | - | High
12 | [87.120.36.50](https://vuldb.com/?ip.87.120.36.50) | - | - | High
13 | [89.169.12.42](https://vuldb.com/?ip.89.169.12.42) | apicuke5917.serv.host | - | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SmartLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SmartLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/action.php` | Medium
3 | File | `/action/upload_file` | High
4 | File | `/actuator` | Medium
5 | File | `/add-notes.php` | High
6 | File | `/add-phlebotomist.php` | High
7 | File | `/addcategory.php` | High
8 | File | `/addelivery.php` | High
9 | File | `/adding-exec.php` | High
10 | File | `/addmem.php` | Medium
11 | File | `/addstock.php` | High
12 | File | `/add_achievement_details.php` | High
13 | File | `/admin#article/edit?id=2` | High
14 | File | `/admin#themes` | High
15 | File | `/admin-inbox.php` | High
16 | File | `/admin/` | Low
17 | File | `/admin/?page=state` | High
18 | File | `/admin/about-us.php` | High
19 | File | `/admin/aboutus.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/adminprofile.php` | High
22 | File | `/admin/admin_action.php` | High
23 | File | `/admin/admin_members.php?ac=search` | High
24 | File | `/admin/ajax.php?action=save_settings` | High
25 | File | `/admin/app/product.php` | High
26 | File | `/admin/app/profile_crud.php` | High
27 | File | `/admin/approve_user.php` | High
28 | File | `/admin/article/article-edit-run.php` | High
29 | File | `/admin/assign/assign.php` | High
30 | File | `/admin/attendance_row.php` | High
31 | File | `/admin/blogger.php?action=update_avatar` | High
32 | File | `/admin/book_row.php` | High
33 | File | `/admin/bwdates-reports-details.php` | High
34 | File | `/admin/bwdates-request-report-details.php` | High
35 | File | `/admin/check_admin_login.php` | High
36 | File | `/admin/class.php` | High
37 | File | `/admin/class.php?dowhat=modifyclass` | High
38 | File | `/admin/contactus.php` | High
39 | File | `/admin/create_product.php` | High
40 | File | `/admin/deleteuser.php` | High
41 | File | `/admin/delete_student.php` | High
42 | File | `/admin/edit-category-detail.php` | High
43 | File | `/admin/edit-customer-detailed.php` | High
44 | File | `/admin/edit-student-profile.php` | High
45 | File | `/admin/edit-subadmin.php` | High
46 | File | `/admin/edit-teacher-detail.php` | High
47 | File | `/admin/edit-user.php` | High
48 | File | `/admin/edit_class.php` | High
49 | File | `/admin/edit_fuel.php` | High
50 | File | `/admin/edit_product.php` | High
51 | File | `/admin/edit_user.php` | High
52 | File | `/admin/general/change-lang` | High
53 | File | `/admin/index.php` | High
54 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
55 | File | `/admin/inquiries/view_details.php` | High
56 | File | `/admin/lab.php` | High
57 | File | `/admin/login.php` | High
58 | File | `/admin/maintenance/view_designation.php` | High
59 | File | `/admin/manage-normal-ticket.php` | High
60 | File | `/Admin/mode.php` | High
61 | File | `/admin/network/diag_nslookup` | High
62 | File | `/admin/network/diag_pinginterface` | High
63 | File | `/admin/normal-search.php` | High
64 | File | `/admin/options-theme.php` | High
65 | File | `/admin/pages/student-print.php` | High
66 | File | `/admin/pass-bwdates-report.php` | High
67 | File | `/admin/password-recovery.php` | High
68 | File | `/admin/php/crud.php` | High
69 | File | `/admin/positions_row.php` | High
70 | File | `/admin/print_barcode.php` | High
71 | File | `/Admin/Proses_Edit_Akun.php` | High
72 | File | `/admin/regester.php` | High
73 | File | `/admin/request-received-bydonar.php` | High
74 | File | `/admin/robot.php` | High
75 | File | `/admin/search-booking-request.php` | High
76 | File | `/admin/search-pass.php` | High
77 | File | `/admin/sou.php` | High
78 | File | `/Admin/sporttype.php` | High
79 | File | `/admin/update-users.php` | High
80 | File | `/admin/update_s8.php` | High
81 | File | `/admin/update_user.php` | High
82 | File | `/admin/upload/authorImg/` | High
83 | File | `/Admin/user-record.php` | High
84 | File | `/admin/user.php` | High
85 | File | `/admin/v1/blog/edit` | High
86 | File | `/admin/view-appointment.php` | High
87 | File | `/admin/view-enquiry.php` | High
88 | File | `/admin/view-foreigner-ticket.php` | High
89 | File | `/admin/voters_row.php` | High
90 | File | `/admin?do=admin:user:editPost` | High
91 | File | `/Administrator/PHP/AdminAddUser.php` | High
92 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
93 | File | `/admin_class.php?action=login` | High
94 | File | `/admin_topic.php?action=delall` | High
95 | File | `/ajax.php?action=delete_loan` | High
96 | File | `/ajax.php?action=save_plan` | High
97 | File | `/ajax.php?action=save_supplier` | High
98 | File | `/api/admin/question/edit` | High
99 | File | `/api/backend/v1/user/create` | High
100 | File | `/api/controllers/common/UploadsController.php` | High
101 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
102 | File | `/api/system/sendWebSocketMsg` | High
103 | File | `/api/v1/login` | High
104 | File | `/api/v1/settings` | High
105 | File | `/api/wizard/networkSetup` | High
106 | File | `/app-api/v1/members/openid/` | High
107 | File | `/app/ajax/search_sales_report.php` | High
108 | File | `/app/ConfirmSmsCode` | High
109 | File | `/application/models/ApplicationDataObject.class.php` | High
110 | File | `/auth/user/all.api` | High
111 | File | `/backend/admin/his_admin_register_patient.php` | High
112 | File | `/bank/statements.php` | High
113 | File | `/bank/transfer.php` | High
114 | File | `/bin/httpd` | Medium
115 | File | `/bin/main` | Medium
116 | File | `/biurl_grou` | Medium
117 | File | `/boafrm/formFilter` | High
118 | File | `/boafrm/formOneKeyAccessButton` | High
119 | File | `/boafrm/formParentControl` | High
120 | File | `/boafrm/formRoute` | High
121 | File | `/boafrm/formWlSiteSurvey` | High
122 | File | `/boafrm/formWlwds` | High
123 | File | `/boafrm/formWsc` | High
124 | ... | ... | ...

There are 1102 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/7ce0eb95-f936-4d8a-bae2-50a51c741b98
* https://app.any.run/tasks/b17cd494-24d2-412d-8dda-f6456d43657a
* https://app.any.run/tasks/f08ed7f8-f60c-4ad9-8f7d-7dc0125f5a86
* https://asec.ahnlab.com/en/89551/
* https://bazaar.abuse.ch/sample/4833e3f6c520312f6cc2716fb89a31c86e143e410305ffdff072786bce948e0c/
* https://bazaar.abuse.ch/sample/27817cb00db5746496c10138655beddb88f5733866452be4bbd51481dbb4a08d/
* https://bazaar.abuse.ch/sample/ac8e9c3db9933684515f091b2637bce105febd069ab8fe6fb0e0ac3caba1ee8b/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
