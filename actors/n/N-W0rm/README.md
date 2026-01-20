# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.254.54](https://vuldb.com/?ip.2.56.254.54) | - | - | High
2 | [5.188.159.44](https://vuldb.com/?ip.5.188.159.44) | - | - | High
3 | [14.241.58.222](https://vuldb.com/?ip.14.241.58.222) | static.vnpt.vn | - | High
4 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
5 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
6 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
7 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
8 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
9 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
10 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
11 | [37.113.171.12](https://vuldb.com/?ip.37.113.171.12) | dynamicip-37-113-171-12.pppoe.chel.ertelecom.ru | - | High
12 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
13 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
14 | [37.139.129.243](https://vuldb.com/?ip.37.139.129.243) | - | - | High
15 | [42.157.128.69](https://vuldb.com/?ip.42.157.128.69) | - | - | High
16 | [43.248.98.121](https://vuldb.com/?ip.43.248.98.121) | - | - | High
17 | [43.248.129.34](https://vuldb.com/?ip.43.248.129.34) | - | - | High
18 | [43.248.129.49](https://vuldb.com/?ip.43.248.129.49) | - | - | High
19 | [43.248.130.253](https://vuldb.com/?ip.43.248.130.253) | - | - | High
20 | [43.249.193.230](https://vuldb.com/?ip.43.249.193.230) | - | - | High
21 | [45.14.165.18](https://vuldb.com/?ip.45.14.165.18) | - | - | High
22 | ... | ... | ... | ...

There are 82 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/AcceptZip.ashx` | High
4 | File | `/action.php` | Medium
5 | File | `/actuator` | Medium
6 | File | `/adding-exec.php` | High
7 | File | `/addmem.php` | Medium
8 | File | `/addpayment.php` | High
9 | File | `/addrecord.php` | High
10 | File | `/addstock.php` | High
11 | File | `/admin#article/edit?id=2` | High
12 | File | `/admin#themes` | High
13 | File | `/admin-cp/file-manager/upload` | High
14 | File | `/admin-cp/theme/install` | High
15 | File | `/admin-inbox.php` | High
16 | File | `/admin/` | Low
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-directory.php` | High
20 | File | `/admin/add-team.php` | High
21 | File | `/admin/add_cars.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/AdminLogin.php` | High
24 | File | `/admin/admin_running.php` | High
25 | File | `/admin/ajax.php?action=login` | High
26 | File | `/admin/app/profile_crud.php` | High
27 | File | `/admin/app/role_crud.php` | High
28 | File | `/admin/approve_user.php` | High
29 | File | `/admin/attendance_row.php` | High
30 | File | `/admin/blogger.php?action=update_avatar` | High
31 | File | `/admin/bookdate.php` | High
32 | File | `/admin/bookings/manage_booking.php` | High
33 | File | `/admin/bwdates-reports-details.php` | High
34 | File | `/admin/bwdates-request-report-details.php` | High
35 | File | `/admin/cashadvance_row.php` | High
36 | File | `/admin/check_admin_login.php` | High
37 | File | `/admin/class.php` | High
38 | File | `/admin/class.php?dowhat=modifyclass` | High
39 | File | `/admin/clients/manage.php` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/create_product.php` | High
42 | File | `/admin/deleteuser.php` | High
43 | File | `/admin/delete_user.php` | High
44 | File | `/admin/edit-accepted-appointment.php` | High
45 | File | `/admin/edit-category-detail.php` | High
46 | File | `/admin/edit-category.php` | High
47 | File | `/admin/edit-customer-detailed.php` | High
48 | File | `/admin/edit-subcategory.php` | High
49 | File | `/admin/edit-teacher-detail.php` | High
50 | File | `/admin/edit-user-profile.php` | High
51 | File | `/admin/edit-user.php` | High
52 | File | `/admin/edit_categories.php` | High
53 | File | `/admin/edit_class.php` | High
54 | File | `/admin/edit_fuel.php` | High
55 | File | `/admin/edit_member.php` | High
56 | File | `/admin/edit_student_query.php` | High
57 | File | `/admin/edit_supplier.php` | High
58 | File | `/admin/eligibility.php` | High
59 | File | `/admin/employee/index.php` | High
60 | File | `/admin/extensions/download.php` | High
61 | File | `/admin/home/index.html` | High
62 | File | `/admin/inquiries/view_details.php` | High
63 | File | `/admin/login.php` | High
64 | File | `/admin/maintenance/view_designation.php` | High
65 | File | `/admin/manage-normal-ticket.php` | High
66 | File | `/admin/manage_theater.php` | High
67 | File | `/Admin/mode.php` | High
68 | File | `/admin/pages/student-print.php` | High
69 | File | `/admin/pass-bwdates-report.php` | High
70 | File | `/admin/php/crud.php` | High
71 | File | `/admin/print_barcode.php` | High
72 | File | `/Admin/Proses_Edit_Akun.php` | High
73 | File | `/admin/regester.php` | High
74 | File | `/admin/search-booking-request.php` | High
75 | File | `/admin/search-pass.php` | High
76 | File | `/admin/search.php` | High
77 | File | `/Admin/sporttype.php` | High
78 | File | `/admin/test_status.php` | High
79 | File | `/admin/update_s5.php` | High
80 | File | `/admin/update_user.php` | High
81 | File | `/admin/upload/authorImg/` | High
82 | File | `/admin/v1/blog/edit` | High
83 | File | `/admin/view-foreigner-ticket.php` | High
84 | File | `/admin/view_vacancy.php` | High
85 | File | `/admin/voters_row.php` | High
86 | File | `/adminac.php` | Medium
87 | File | `/admin_class.php` | High
88 | File | `/admin_link.php?action=delall` | High
89 | File | `/admin_topic.php?action=delall` | High
90 | File | `/agenda_preferencias.php` | High
91 | File | `/ajax.php?action=delete_loan` | High
92 | File | `/ajax.php?action=delete_product` | High
93 | File | `/ajax.php?action=delete_receiving` | High
94 | File | `/ample/app/action/edit_product.php` | High
95 | File | `/api/` | Low
96 | File | `/api/2.0/rest/aggregator/xml` | High
97 | File | `/api/admin/question/edit` | High
98 | File | `/api/controllers/common/UploadsController.php` | High
99 | File | `/api/system/sendWebSocketMsg` | High
100 | File | `/api/upload/image` | High
101 | File | `/api/v2.0/users` | High
102 | File | `/api/wizard/networkSetup` | High
103 | File | `/app/ajax/search_sales_report.php` | High
104 | File | `/app/sae/design/desktop/flat` | High
105 | File | `/App/Tpl/Admin/Default/Log/index.html` | High
106 | File | `/application/models/ApplicationDataObject.class.php` | High
107 | File | `/auth/user/all.api` | High
108 | File | `/b2b-supermarket/catalog/all-products` | High
109 | File | `/bank/statements.php` | High
110 | File | `/bin/httpd` | Medium
111 | File | `/biurl_grou` | Medium
112 | File | `/boafrm/formDebugDiagnosticRun` | High
113 | File | `/boafrm/formFilter` | High
114 | File | `/boafrm/formMapDel` | High
115 | ... | ... | ...

There are 1022 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3602383/
* https://urlhaus.abuse.ch/url/3607222/
* https://urlhaus.abuse.ch/url/3607417/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
