# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
3 | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/activation.php` | High
3 | File | `/actuator` | Medium
4 | File | `/ad-list` | Medium
5 | File | `/add-phlebotomist.php` | High
6 | File | `/add-teacher.php` | High
7 | File | `/add.php` | Medium
8 | File | `/addcompany.php` | High
9 | File | `/addcustcom.php` | High
10 | File | `/adding-exec.php` | High
11 | File | `/add_reserve.php` | High
12 | File | `/admin-cp/file-manager/upload` | High
13 | File | `/admin-dashboard` | High
14 | File | `/admin-page.php` | High
15 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
16 | File | `/admin/add-admin.php` | High
17 | File | `/admin/add-art-medium.php` | High
18 | File | `/admin/add-customer-services.php` | High
19 | File | `/admin/add-customer.php` | High
20 | File | `/admin/add-foreigner-ticket.php` | High
21 | File | `/admin/add_room.php` | High
22 | File | `/admin/adminScoreUrl` | High
23 | File | `/admin/ajax.php?action=login` | High
24 | File | `/admin/allemployees.php` | High
25 | File | `/admin/app/product.php` | High
26 | File | `/admin/app/service_crud.php` | High
27 | File | `/admin/app/web_crud.php` | High
28 | File | `/admin/attendance_action.php` | High
29 | File | `/admin/ballot_up.php` | High
30 | File | `/admin/borrow_add.php` | High
31 | File | `/admin/bwdates-report-details.php` | High
32 | File | `/admin/bwdates-reports-details.php` | High
33 | File | `/admin/categories/view_category.php` | High
34 | File | `/admin/check_admin.php` | High
35 | File | `/admin/contact-us.php` | High
36 | File | `/admin/content/book` | High
37 | File | `/admin/controller/delete_group_student.php` | High
38 | File | `/admin/delete-user.php` | High
39 | File | `/admin/deletegallery.php` | High
40 | File | `/admin/delete_student.php` | High
41 | File | `/admin/departments/manage_department.php` | High
42 | File | `/admin/edit-boat.php` | High
43 | File | `/admin/edit-category.php` | High
44 | File | `/admin/edit-customer-detailed.php` | High
45 | File | `/admin/edit-services.php` | High
46 | File | `/admin/edit_categories.php` | High
47 | File | `/admin/edit_room.php` | High
48 | File | `/admin/edit_user.php` | High
49 | File | `/admin/execedituser.php` | High
50 | File | `/admin/forgot-password.php` | High
51 | File | `/admin/general/change-lang` | High
52 | File | `/admin/ImgUpdaPost.php` | High
53 | File | `/admin/index.php` | High
54 | File | `/admin/index.php/web/ajax_all_lists` | High
55 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
56 | File | `/admin/inquiries/view_details.php` | High
57 | File | `/admin/login` | Medium
58 | File | `/admin/login.php` | High
59 | File | `/admin/login_process.php` | High
60 | File | `/admin/manage-students.php` | High
61 | File | `/admin/manage-teams.php` | High
62 | File | `/Admin/mode.php` | High
63 | File | `/admin/model/addOrUpdate` | High
64 | File | `/admin/modules/student/index.php` | High
65 | File | `/admin/network/diag_iperf` | High
66 | File | `/admin/network/diag_pinginterface` | High
67 | File | `/admin/operations/tax.php` | High
68 | File | `/admin/php/crud.php` | High
69 | File | `/admin/profile.php` | High
70 | File | `/admin/quote-details.php` | High
71 | File | `/admin/regester.php` | High
72 | File | `/admin/registration.php` | High
73 | File | `/admin/search-directory.php` | High
74 | File | `/admin/search-invoices.php` | High
75 | File | `/admin/state.php` | High
76 | File | `/admin/tag.php` | High
77 | File | `/admin/tags/save` | High
78 | File | `/admin/twitter.php` | High
79 | File | `/admin/update-image.php` | High
80 | File | `/admin/user.php` | High
81 | File | `/admin/user/manage_user.php` | High
82 | File | `/admin/view-incomingvehicle-detail.php` | High
83 | File | `/admin/voters_row.php` | High
84 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
85 | File | `/adms/admin/?page=vehicles/view_transaction` | High
86 | File | `/ajax.php` | Medium
87 | File | `/ajax.php?action=delete_plan` | High
88 | File | `/ajax.php?action=login` | High
89 | File | `/ajax.php?action=save_category` | High
90 | File | `/ajax.php?action=save_deductions` | High
91 | File | `/api/comment/add` | High
92 | File | `/api/dept/build` | High
93 | File | `/api/file/multiDownload` | High
94 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
95 | File | `/api/settings` | High
96 | File | `/api/test/download` | High
97 | File | `/api/v1/getbaseconfig` | High
98 | File | `/api/wizard/getCapabilityWeb` | High
99 | File | `/api/wizard/getNetworkStatus` | High
100 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
101 | File | `/application/models/ApplicationDataObject.class.php` | High
102 | File | `/apps/api/views/deploy_api.py` | High
103 | File | `/apps/system/services/role_menu.go` | High
104 | File | `/authenticate.php` | High
105 | File | `/backend/doc/his_doc_register_patient.php` | High
106 | File | `/backend/register.php` | High
107 | File | `/backups/` | Medium
108 | File | `/bank/show.php` | High
109 | File | `/bank/transfer.php` | High
110 | File | `/boafrm/formIpv6Setup` | High
111 | File | `/boafrm/formStats` | High
112 | File | `/boafrm/formWlanMultipleAP` | High
113 | File | `/boafrm/formWlSiteSurvey` | High
114 | File | `/boafrm/formWsc` | High
115 | File | `/browse.php` | Medium
116 | File | `/browsemdcn.php` | High
117 | File | `/bwdates-report-result.php` | High
118 | File | `/cancelbookingpatient.php` | High
119 | File | `/cart_add.php` | High
120 | File | `/CDGServer3/logManagement/backupLogDetail.jsp` | High
121 | File | `/cgi-bin/cstecgi.cgi` | High
122 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
123 | File | `/cgi-bin/discovery.cgi` | High
124 | File | `/cgi-bin/firewall.cgi` | High
125 | File | `/cgi-bin/hd_config.cgi` | High
126 | File | `/cgi-bin/internet.cgi?Command=lanCfg` | High
127 | File | `/cgi-bin/luci/api/cmd` | High
128 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
129 | File | `/cgi-bin/wireless.cgi` | High
130 | File | `/change_pass/forgot_password_sql.php` | High
131 | ... | ... | ...

There are 1168 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
