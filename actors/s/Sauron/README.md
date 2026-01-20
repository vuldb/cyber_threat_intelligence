# Sauron - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sauron](https://vuldb.com/?actor.sauron). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sauron](https://vuldb.com/?actor.sauron)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sauron:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sauron.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.252.125.88](https://vuldb.com/?ip.37.252.125.88) | - | - | High
2 | [66.228.52.133](https://vuldb.com/?ip.66.228.52.133) | li294-133.members.linode.com | - | High
3 | [74.125.148.11](https://vuldb.com/?ip.74.125.148.11) | rate-limited-proxy-74-125-148-11.google.com | - | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sauron_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sauron. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/action.php` | Medium
3 | File | `/action/upload_file` | High
4 | File | `/actuator` | Medium
5 | File | `/add-notes.php` | High
6 | File | `/add-phlebotomist.php` | High
7 | File | `/addCatController.php` | High
8 | File | `/addcategory.php` | High
9 | File | `/addelivery.php` | High
10 | File | `/adding-exec.php` | High
11 | File | `/addmem.php` | Medium
12 | File | `/addstock.php` | High
13 | File | `/add_achievement_details.php` | High
14 | File | `/admin#article/edit?id=2` | High
15 | File | `/admin#themes` | High
16 | File | `/admin-inbox.php` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?page=state` | High
19 | File | `/admin/about-us.php` | High
20 | File | `/admin/aboutus.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/admin/adminprofile.php` | High
23 | File | `/admin/admin_action.php` | High
24 | File | `/admin/admin_members.php?ac=search` | High
25 | File | `/admin/ajax.php?action=login` | High
26 | File | `/admin/ajax.php?action=save_settings` | High
27 | File | `/admin/app/product.php` | High
28 | File | `/admin/app/profile_crud.php` | High
29 | File | `/admin/approve_user.php` | High
30 | File | `/admin/article/article-edit-run.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
32 | File | `/admin/attendance_row.php` | High
33 | File | `/admin/blogger.php?action=update_avatar` | High
34 | File | `/admin/book_row.php` | High
35 | File | `/admin/bwdates-reports-details.php` | High
36 | File | `/admin/bwdates-request-report-details.php` | High
37 | File | `/admin/check_admin_login.php` | High
38 | File | `/admin/class.php` | High
39 | File | `/admin/class.php?dowhat=modifyclass` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/create_product.php` | High
42 | File | `/admin/deleteuser.php` | High
43 | File | `/admin/delete_s2.php` | High
44 | File | `/admin/delete_student.php` | High
45 | File | `/admin/edit-category-detail.php` | High
46 | File | `/admin/edit-customer-detailed.php` | High
47 | File | `/admin/edit-subadmin.php` | High
48 | File | `/admin/edit-teacher-detail.php` | High
49 | File | `/admin/edit-user.php` | High
50 | File | `/admin/edit_class.php` | High
51 | File | `/admin/edit_fuel.php` | High
52 | File | `/admin/edit_product.php` | High
53 | File | `/admin/edit_user.php` | High
54 | File | `/admin/index.php` | High
55 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
56 | File | `/admin/inquiries/view_details.php` | High
57 | File | `/admin/lab.php` | High
58 | File | `/admin/login.php` | High
59 | File | `/admin/maintenance/view_designation.php` | High
60 | File | `/admin/manage-normal-ticket.php` | High
61 | File | `/admin/manage-teams.php` | High
62 | File | `/Admin/mode.php` | High
63 | File | `/admin/network/diag_nslookup` | High
64 | File | `/admin/network/diag_pinginterface` | High
65 | File | `/admin/normal-search.php` | High
66 | File | `/admin/options-theme.php` | High
67 | File | `/admin/pages/student-print.php` | High
68 | File | `/admin/pass-bwdates-report.php` | High
69 | File | `/admin/password-recovery.php` | High
70 | File | `/admin/php/crud.php` | High
71 | File | `/admin/positions_row.php` | High
72 | File | `/admin/print_barcode.php` | High
73 | File | `/Admin/Proses_Edit_Akun.php` | High
74 | File | `/admin/regester.php` | High
75 | File | `/admin/request-received-bydonar.php` | High
76 | File | `/admin/robot.php` | High
77 | File | `/admin/search-booking-request.php` | High
78 | File | `/admin/search-pass.php` | High
79 | File | `/admin/sensitive_word/list` | High
80 | File | `/Admin/sporttype.php` | High
81 | File | `/admin/update-users.php` | High
82 | File | `/admin/update_s8.php` | High
83 | File | `/admin/update_user.php` | High
84 | File | `/admin/upload/authorImg/` | High
85 | File | `/Admin/user-record.php` | High
86 | File | `/admin/user.php` | High
87 | File | `/admin/v1/blog/edit` | High
88 | File | `/admin/view-appointment.php` | High
89 | File | `/admin/view-foreigner-ticket.php` | High
90 | File | `/admin/voters_row.php` | High
91 | File | `/admin?do=admin:user:editPost` | High
92 | File | `/admin_class.php?action=login` | High
93 | File | `/admin_topic.php?action=delall` | High
94 | File | `/ajax.php?action=delete_loan` | High
95 | File | `/ajax.php?action=save_plan` | High
96 | File | `/ajax.php?action=save_supplier` | High
97 | File | `/api/admin/question/edit` | High
98 | File | `/api/backend/v1/user/create` | High
99 | File | `/api/controllers/common/UploadsController.php` | High
100 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
101 | File | `/api/system/sendWebSocketMsg` | High
102 | File | `/api/v1/login` | High
103 | File | `/api/v1/settings` | High
104 | File | `/api/wizard/networkSetup` | High
105 | File | `/app-api/v1/members/openid/` | High
106 | File | `/app/ajax/search_sales_report.php` | High
107 | File | `/app/ConfirmSmsCode` | High
108 | File | `/application/models/ApplicationDataObject.class.php` | High
109 | File | `/Applications/Steal/main.cpp` | High
110 | File | `/auth/user/all.api` | High
111 | File | `/backend/admin/his_admin_register_patient.php` | High
112 | File | `/bank/statements.php` | High
113 | File | `/bank/transfer.php` | High
114 | File | `/bbdms/admin/update-contactinfo.php` | High
115 | File | `/bin/httpd` | Medium
116 | File | `/biurl_grou` | Medium
117 | File | `/boafrm/formFilter` | High
118 | File | `/boafrm/formMapDelDevice` | High
119 | File | `/boafrm/formOneKeyAccessButton` | High
120 | File | `/boafrm/formParentControl` | High
121 | File | `/boafrm/formRoute` | High
122 | File | `/boafrm/formWsc` | High
123 | File | `/bolt/editcontent/showcases` | High
124 | File | `/bookingconfirm.php` | High
125 | File | `/C6/JHSoft.Web.AcceptAip/AcceptShow.aspx/` | High
126 | ... | ... | ...

There are 1116 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=The-ProjectSauron-APT_research_KL.pdf&y=2016
* https://www.threatminer.org/_reports/2016/The-ProjectSauron-APT_IOCs_KL.pdf#viewer.action=download

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
