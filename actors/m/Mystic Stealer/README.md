# Mystic Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mystic Stealer](https://vuldb.com/?actor.mystic_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mystic_stealer](https://vuldb.com/?actor.mystic_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mystic Stealer:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 3 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mystic Stealer. This data is unique as it uses our predictive model for actor profiling.

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
47 | File | `/admin/general/change-lang` | High
48 | File | `/admin/index.php` | High
49 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
50 | File | `/admin/inquiries/view_details.php` | High
51 | File | `/admin/lab.php` | High
52 | File | `/admin/login.php` | High
53 | File | `/admin/maintenance/view_designation.php` | High
54 | File | `/admin/manage-normal-ticket.php` | High
55 | File | `/Admin/match.php` | High
56 | File | `/Admin/mode.php` | High
57 | File | `/admin/network/diag_nslookup` | High
58 | File | `/admin/network/diag_pinginterface` | High
59 | File | `/admin/normal-search.php` | High
60 | File | `/admin/options-theme.php` | High
61 | File | `/admin/pages/student-print.php` | High
62 | File | `/admin/pass-bwdates-report.php` | High
63 | File | `/admin/password-recovery.php` | High
64 | File | `/admin/php/crud.php` | High
65 | File | `/admin/print_barcode.php` | High
66 | File | `/Admin/Proses_Edit_Akun.php` | High
67 | File | `/admin/regester.php` | High
68 | File | `/admin/request-received-bydonar.php` | High
69 | File | `/admin/robot.php` | High
70 | File | `/admin/search-booking-request.php` | High
71 | File | `/admin/search-pass.php` | High
72 | File | `/admin/sou.php` | High
73 | File | `/Admin/sporttype.php` | High
74 | File | `/admin/update-rooms.php` | High
75 | File | `/admin/update_user.php` | High
76 | File | `/admin/upload/authorImg/` | High
77 | File | `/Admin/user-record.php` | High
78 | File | `/admin/user.php` | High
79 | File | `/admin/v1/blog/edit` | High
80 | File | `/admin/view-appointment.php` | High
81 | File | `/admin/view-enquiry.php` | High
82 | File | `/admin/view-foreigner-ticket.php` | High
83 | File | `/admin/voters_row.php` | High
84 | File | `/admin?do=admin:user:editPost` | High
85 | File | `/Administrator/PHP/AdminAddUser.php` | High
86 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
87 | File | `/admin_class.php?action=login` | High
88 | File | `/admin_topic.php?action=delall` | High
89 | File | `/ajax.php` | Medium
90 | File | `/ajax.php?action=delete_loan` | High
91 | File | `/ajax.php?action=save_supplier` | High
92 | File | `/api/admin/question/edit` | High
93 | File | `/api/backend/v1/user/create` | High
94 | File | `/api/controllers/common/UploadsController.php` | High
95 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
96 | File | `/api/system/sendWebSocketMsg` | High
97 | File | `/api/v1/login` | High
98 | File | `/api/v1/settings` | High
99 | File | `/api/wizard/networkSetup` | High
100 | File | `/app-api/v1/members/openid/` | High
101 | File | `/app/ajax/search_sales_report.php` | High
102 | File | `/app/ConfirmSmsCode` | High
103 | File | `/application/models/ApplicationDataObject.class.php` | High
104 | File | `/auth/user/all.api` | High
105 | File | `/backend/admin/his_admin_register_patient.php` | High
106 | File | `/bank/statements.php` | High
107 | File | `/bank/transfer.php` | High
108 | File | `/bin/httpd` | Medium
109 | File | `/bin/main` | Medium
110 | File | `/biurl_grou` | Medium
111 | File | `/boafrm/formFilter` | High
112 | File | `/boafrm/formOneKeyAccessButton` | High
113 | File | `/boafrm/formParentControl` | High
114 | File | `/boafrm/formRoute` | High
115 | File | `/boafrm/formWlSiteSurvey` | High
116 | File | `/boafrm/formWlwds` | High
117 | File | `/boafrm/formWsc` | High
118 | File | `/bolt/editcontent/showcases` | High
119 | File | `/bookingconfirm.php` | High
120 | ... | ... | ...

There are 1065 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
