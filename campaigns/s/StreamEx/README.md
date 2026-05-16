# StreamEx - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _StreamEx_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with StreamEx:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with StreamEx or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of StreamEx.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.210.102.210](https://vuldb.com/?ip.31.210.102.210) | . | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
2 | [43.249.81.209](https://vuldb.com/?ip.43.249.81.209) | - | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
3 | [88.208.228.56](https://vuldb.com/?ip.88.208.228.56) | bextec.co.uk | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within StreamEx. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during StreamEx. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/actuator` | Medium
3 | File | `/add-phlebotomist.php` | High
4 | File | `/addcategory.php` | High
5 | File | `/adding-exec.php` | High
6 | File | `/addmem.php` | Medium
7 | File | `/addProduct.php` | High
8 | File | `/addstock.php` | High
9 | File | `/admin#article/edit?id=2` | High
10 | File | `/admin#themes` | High
11 | File | `/admin-inbox.php` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=state` | High
14 | File | `/admin/about-us.php` | High
15 | File | `/admin/aboutPost.php` | High
16 | File | `/admin/add-module.php` | High
17 | File | `/admin/add_expenses.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/api/theme-edit/` | High
20 | File | `/admin/app/login_crud.php` | High
21 | File | `/admin/app/profile_crud.php` | High
22 | File | `/admin/approve_user.php` | High
23 | File | `/admin/article/article-edit-run.php` | High
24 | File | `/admin/assign/assign.php` | High
25 | File | `/admin/attachment/download` | High
26 | File | `/admin/attendance_row.php` | High
27 | File | `/admin/blogger.php?action=update_avatar` | High
28 | File | `/admin/bwdates-reports-details.php` | High
29 | File | `/admin/bwdates-request-report-details.php` | High
30 | File | `/admin/check_admin_login.php` | High
31 | File | `/admin/class.php` | High
32 | File | `/admin/class.php?dowhat=modifyclass` | High
33 | File | `/admin/contactus.php` | High
34 | File | `/admin/deleteuser.php` | High
35 | File | `/admin/delete_student.php` | High
36 | File | `/admin/edit-category-detail.php` | High
37 | File | `/admin/edit-customer-detailed.php` | High
38 | File | `/admin/edit-teacher-detail.php` | High
39 | File | `/admin/edit-user.php` | High
40 | File | `/admin/edit_class.php` | High
41 | File | `/admin/edit_fuel.php` | High
42 | File | `/admin/general/change-lang` | High
43 | File | `/admin/index.php` | High
44 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
45 | File | `/admin/inquiries/view_details.php` | High
46 | File | `/admin/lab.php` | High
47 | File | `/admin/maintenance/view_designation.php` | High
48 | File | `/admin/manage-normal-ticket.php` | High
49 | File | `/Admin/match.php` | High
50 | File | `/Admin/mode.php` | High
51 | File | `/admin/pages/student-print.php` | High
52 | File | `/admin/pass-bwdates-report.php` | High
53 | File | `/admin/php/crud.php` | High
54 | File | `/admin/print_barcode.php` | High
55 | File | `/Admin/Proses_Edit_Akun.php` | High
56 | File | `/admin/receipt.php` | High
57 | File | `/admin/regester.php` | High
58 | File | `/admin/request-received-bydonar.php` | High
59 | File | `/admin/robot.php` | High
60 | File | `/admin/search-booking-request.php` | High
61 | File | `/admin/search-pass.php` | High
62 | File | `/admin/sou.php` | High
63 | File | `/Admin/sporttype.php` | High
64 | File | `/admin/update-rooms.php` | High
65 | File | `/admin/update_user.php` | High
66 | File | `/admin/upload/authorImg/` | High
67 | File | `/Admin/user-record.php` | High
68 | File | `/admin/user.php` | High
69 | File | `/admin/v1/blog/edit` | High
70 | File | `/admin/view-enquiry.php` | High
71 | File | `/admin/view-foreigner-ticket.php` | High
72 | File | `/admin/voters_row.php` | High
73 | File | `/admin?do=admin:user:editPost` | High
74 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
75 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
76 | File | `/Administrator/PHP/AdminAddUser.php` | High
77 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
78 | File | `/Administrator/PHP/AdminEditUser.php` | High
79 | File | `/Administrator/PHP/AdminReply.php` | High
80 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
81 | File | `/admin_topic.php?action=delall` | High
82 | File | `/adv_mac_filter.php` | High
83 | File | `/ajax.php` | Medium
84 | File | `/ajax.php?action=delete_loan` | High
85 | File | `/ajax.php?action=login` | High
86 | File | `/ajax.php?action=save_supplier` | High
87 | File | `/api/admin/question/edit` | High
88 | File | `/api/controllers/common/UploadsController.php` | High
89 | File | `/api/files/recipepictures/` | High
90 | File | `/api/system/sendWebSocketMsg` | High
91 | File | `/api/v1/login` | High
92 | File | `/api/v1/settings` | High
93 | File | `/api/wizard/networkSetup` | High
94 | File | `/app-api/v1/members/openid/` | High
95 | File | `/app/ajax/search_sales_report.php` | High
96 | File | `/app/register.php?action=reg` | High
97 | File | `/application/models/ApplicationDataObject.class.php` | High
98 | File | `/auth/user/all.api` | High
99 | File | `/backend/admin/his_admin_register_patient.php` | High
100 | File | `/bank/statements.php` | High
101 | File | `/bank/transfer.php` | High
102 | File | `/bin/httpd` | Medium
103 | File | `/bin/main` | Medium
104 | File | `/biurl_grou` | Medium
105 | File | `/boaform/formSamba` | High
106 | File | `/boafrm/formDdns` | High
107 | File | `/boafrm/formFilter` | High
108 | File | `/boafrm/formOneKeyAccessButton` | High
109 | File | `/boafrm/formParentControl` | High
110 | File | `/boafrm/formRoute` | High
111 | File | `/boafrm/formTracerouteDiagnosticRun` | High
112 | File | `/boafrm/formVpnConfigSetup` | High
113 | File | `/boafrm/formWlSiteSurvey` | High
114 | File | `/boafrm/formWlwds` | High
115 | File | `/boafrm/formWsc` | High
116 | File | `/bolt/editcontent/showcases` | High
117 | File | `/bookingconfirm.php` | High
118 | File | `/C6/JHSoft.Web.AcceptAip/AcceptShow.aspx/` | High
119 | File | `/cart.php` | Medium
120 | ... | ... | ...

There are 1064 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.blackberry.com/en/2017/02/shell-crew-variants-continue-to-fly-under-big-avs-radar

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
