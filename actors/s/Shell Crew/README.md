# Shell Crew - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shell Crew](https://vuldb.com/?actor.shell_crew). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shell_crew](https://vuldb.com/?actor.shell_crew)

## Campaigns

The following _campaigns_ are known and can be associated with Shell Crew:

* StreamEx

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shell Crew:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shell Crew.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [12.0.742.112](https://vuldb.com/?ip.12.0.742.112) | - | - | High
2 | [31.210.102.210](https://vuldb.com/?ip.31.210.102.210) | . | StreamEx | High
3 | [43.249.81.209](https://vuldb.com/?ip.43.249.81.209) | - | StreamEx | High
4 | [43.249.81.210](https://vuldb.com/?ip.43.249.81.210) | - | - | High
5 | [50.115.138.215](https://vuldb.com/?ip.50.115.138.215) | 50-115-138-215.genericreverse.com | - | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shell Crew_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shell Crew. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action.php` | Medium
2 | File | `/action/upload_file` | High
3 | File | `/actuator` | Medium
4 | File | `/add-notes.php` | High
5 | File | `/addelivery.php` | High
6 | File | `/adding-exec.php` | High
7 | File | `/addmem.php` | Medium
8 | File | `/addstock.php` | High
9 | File | `/add_achievement_details.php` | High
10 | File | `/admin#article/edit?id=2` | High
11 | File | `/admin#themes` | High
12 | File | `/admin-inbox.php` | High
13 | File | `/admin/` | Low
14 | File | `/admin/?page=state` | High
15 | File | `/admin/about-us.php` | High
16 | File | `/admin/aboutus.php` | High
17 | File | `/admin/admin-profile.php` | High
18 | File | `/admin/adminprofile.php` | High
19 | File | `/admin/admin_action.php` | High
20 | File | `/admin/admin_members.php?ac=search` | High
21 | File | `/admin/ajax.php?action=login` | High
22 | File | `/admin/ajax.php?action=save_settings` | High
23 | File | `/admin/app/product.php` | High
24 | File | `/admin/app/profile_crud.php` | High
25 | File | `/admin/approve_user.php` | High
26 | File | `/admin/archives_add.php` | High
27 | File | `/admin/attendance_row.php` | High
28 | File | `/admin/blogger.php?action=update_avatar` | High
29 | File | `/admin/book_row.php` | High
30 | File | `/admin/bwdates-reports-details.php` | High
31 | File | `/admin/bwdates-request-report-details.php` | High
32 | File | `/admin/categories/save` | High
33 | File | `/admin/check_admin_login.php` | High
34 | File | `/admin/class.php` | High
35 | File | `/admin/class.php?dowhat=modifyclass` | High
36 | File | `/admin/contact-us.php` | High
37 | File | `/admin/contactus.php` | High
38 | File | `/admin/create_product.php` | High
39 | File | `/admin/deleteuser.php` | High
40 | File | `/admin/edit-category-detail.php` | High
41 | File | `/admin/edit-customer-detailed.php` | High
42 | File | `/admin/edit-subadmin.php` | High
43 | File | `/admin/edit-teacher-detail.php` | High
44 | File | `/admin/edit-user.php` | High
45 | File | `/admin/edit_class.php` | High
46 | File | `/admin/edit_fuel.php` | High
47 | File | `/admin/edit_product.php` | High
48 | File | `/admin/edit_user.php` | High
49 | File | `/admin/inquiries/view_details.php` | High
50 | File | `/admin/login.php` | High
51 | File | `/admin/maintenance/view_designation.php` | High
52 | File | `/admin/manage-normal-ticket.php` | High
53 | File | `/Admin/mode.php` | High
54 | File | `/admin/network/diag_nslookup` | High
55 | File | `/admin/network/diag_pinginterface` | High
56 | File | `/admin/newsletterdel.php` | High
57 | File | `/admin/normal-search.php` | High
58 | File | `/admin/options-theme.php` | High
59 | File | `/admin/pages/student-print.php` | High
60 | File | `/admin/password-recovery.php` | High
61 | File | `/admin/php/crud.php` | High
62 | File | `/admin/positions_row.php` | High
63 | File | `/admin/print_barcode.php` | High
64 | File | `/Admin/Proses_Edit_Akun.php` | High
65 | File | `/admin/receipt.php` | High
66 | File | `/admin/regester.php` | High
67 | File | `/admin/search-booking-request.php` | High
68 | File | `/admin/search-pass.php` | High
69 | File | `/Admin/sporttype.php` | High
70 | File | `/admin/update-users.php` | High
71 | File | `/admin/update_s8.php` | High
72 | File | `/admin/update_user.php` | High
73 | File | `/admin/upload/authorImg/` | High
74 | File | `/admin/v1/blog/edit` | High
75 | File | `/admin/view-appointment.php` | High
76 | File | `/admin/view-foreigner-ticket.php` | High
77 | File | `/admin/voters_row.php` | High
78 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
79 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
80 | File | `/admin_class.php?action=login` | High
81 | File | `/admin_topic.php?action=delall` | High
82 | File | `/ajax.php?action=delete_loan` | High
83 | File | `/ajax.php?action=login` | High
84 | File | `/ajax.php?action=save_plan` | High
85 | File | `/api/admin/question/edit` | High
86 | File | `/api/backend/v1/user/create` | High
87 | File | `/api/controllers/common/UploadsController.php` | High
88 | File | `/api/files/recipepictures/` | High
89 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
90 | File | `/api/system/sendWebSocketMsg` | High
91 | File | `/api/v1/settings` | High
92 | File | `/api/wizard/networkSetup` | High
93 | File | `/app-api/v1/members/openid/` | High
94 | File | `/app/ajax/search_sales_report.php` | High
95 | File | `/app/ConfirmSmsCode` | High
96 | File | `/application/models/ApplicationDataObject.class.php` | High
97 | File | `/Applications/Steal/main.cpp` | High
98 | File | `/auth/user/all.api` | High
99 | File | `/authentication.cgi` | High
100 | File | `/bank/statements.php` | High
101 | File | `/bank/transfer.php` | High
102 | File | `/bin/httpd` | Medium
103 | File | `/biurl_grou` | Medium
104 | File | `/boafrm/formDdns` | High
105 | File | `/boafrm/formFilter` | High
106 | File | `/boafrm/formParentControl` | High
107 | File | `/boafrm/formTracerouteDiagnosticRun` | High
108 | File | `/boafrm/formVpnConfigSetup` | High
109 | File | `/boafrm/formWsc` | High
110 | File | `/bolt/editcontent/showcases` | High
111 | File | `/bookingconfirm.php` | High
112 | ... | ... | ...

There are 990 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2017/02/shell-crew-variants-continue-to-fly-under-big-avs-radar
* https://www.threatminer.org/report.php?q=RSAIncidentResponseEmergingThreatProfile_ShellCrew.pdf&y=2014
* https://www.threatminer.org/report.php?q=ShellCrewVariantsContinuetoFlyUnderBigAV%E2%80%99sRadar-Cylance.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
