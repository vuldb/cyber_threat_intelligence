# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Camerashy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Naikon](https://vuldb.com/?actor.naikon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Camerashy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
2 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
3 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | [Naikon](https://vuldb.com/?actor.naikon) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/?p=products` | Medium
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/academy/tutor/filter` | High
5 | File | `/Account/login.php` | High
6 | File | `/ad-list` | Medium
7 | File | `/add_classes.php` | High
8 | File | `/admin` | Low
9 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
10 | File | `/admin.php?p=/Area/index#tab=t2` | High
11 | File | `/admin/` | Low
12 | File | `/admin/?page=bike` | High
13 | File | `/admin/?page=maintenance/brand` | High
14 | File | `/admin/?page=user/list` | High
15 | File | `/admin/about-us.php` | High
16 | File | `/admin/action/add_con.php` | High
17 | File | `/admin/action/delete-vaccine.php` | High
18 | File | `/admin/action/edit_chicken.php` | High
19 | File | `/admin/action/new-father.php` | High
20 | File | `/admin/add-services.php` | High
21 | File | `/admin/add_user_modal.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/admin_content_tag.php?action=save_content` | High
24 | File | `/admin/admin_login_process.php` | High
25 | File | `/admin/admin_user.php` | High
26 | File | `/admin/ajax.php?action=confirm_order` | High
27 | File | `/admin/assign/assign.php` | High
28 | File | `/admin/ballot_down.php` | High
29 | File | `/admin/bwdates-report-details.php` | High
30 | File | `/admin/categories/manage_category.php` | High
31 | File | `/admin/categories/view_category.php` | High
32 | File | `/admin/category/cate-edit-run.php` | High
33 | File | `/admin/cms_admin.php` | High
34 | File | `/admin/cms_content.php` | High
35 | File | `/admin/configurations/userInfo` | High
36 | File | `/admin/courses/manage_course.php` | High
37 | File | `/admin/curriculum/view_curriculum.php` | High
38 | File | `/admin/deduction_edit.php` | High
39 | File | `/admin/del_category.php` | High
40 | File | `/admin/departments/manage_department.php` | High
41 | File | `/admin/edit-admin.php` | High
42 | File | `/admin/edit_categories.php` | High
43 | File | `/admin/edit_teacher.php` | High
44 | File | `/admin/employee_row.php` | High
45 | File | `/admin/index.php` | High
46 | File | `/admin/inventory/manage_stock.php` | High
47 | File | `/admin/invoice.php` | High
48 | File | `/admin/list_addr_fwresource_ip.php` | High
49 | File | `/admin/login.php` | High
50 | File | `/Admin/login.php` | High
51 | File | `/admin/maintenance/brand.php` | High
52 | File | `/admin/makehtml_freelist_action.php` | High
53 | File | `/admin/manage-users.php` | High
54 | File | `/admin/manage_academic.php` | High
55 | File | `/Admin/News.php` | High
56 | File | `/admin/offenses/view_details.php` | High
57 | File | `/admin/operations/expense_category.php` | High
58 | File | `/admin/pages/subjects.php` | High
59 | File | `/admin/pages/update_go.php` | High
60 | File | `/admin/positions_row.php` | High
61 | File | `/admin/products/manage_product.php` | High
62 | File | `/admin/read.php?mudi=getSignal` | High
63 | File | `/admin/reminders/manage_reminder.php` | High
64 | File | `/admin/report/index.php` | High
65 | File | `/admin/sales/manage_sale.php` | High
66 | File | `/admin/search-appointment.php` | High
67 | File | `/admin/services/view_service.php` | High
68 | File | `/admin/students.php` | High
69 | File | `/admin/students/update_status.php` | High
70 | File | `/admin/students/view_details.php` | High
71 | File | `/admin/sys_sql_query.php` | High
72 | File | `/admin/test_status.php` | High
73 | File | `/admin/upload` | High
74 | File | `/admin/upload/img` | High
75 | File | `/admin/uploads/` | High
76 | File | `/admin/user/manage_user.php` | High
77 | File | `/admin/view_sendlist.php` | High
78 | File | `/admin/vote_edit.php` | High
79 | File | `/adminapi/system/crud` | High
80 | File | `/adminapi/system/file/openfile` | High
81 | File | `/admin_ping.htm` | High
82 | File | `/admin_system/api.php` | High
83 | File | `/ajax-api.php` | High
84 | File | `/ajax.php?action=save_company` | High
85 | File | `/analysisProject/pagingQueryData` | High
86 | File | `/api/admin/store/product/save` | High
87 | File | `/api/authentication/login` | High
88 | File | `/api/controllers/admin/app/AppController.php` | High
89 | File | `/api/controllers/common/UploadsController.php` | High
90 | File | `/api/controllers/merchant/design/MaterialController.php` | High
91 | File | `/api/controllers/merchant/shop/PosterController.php` | High
92 | File | `/api/es/admin/v3/security/user/1` | High
93 | File | `/api/stl/actions/search` | High
94 | File | `/api/sys/login` | High
95 | File | `/app/api/controller/collect.php` | High
96 | File | `/app/controller/Setup.php` | High
97 | File | `/app/index/controller/Common.php` | High
98 | File | `/app/middleware/TokenVerify.php` | High
99 | File | `/app/sys1.php` | High
100 | File | `/application/index/common.php` | High
101 | File | `/application/index/controller/Databasesource.php` | High
102 | File | `/application/index/controller/Datament.php` | High
103 | File | `/application/index/controller/Icon.php` | High
104 | File | `/application/index/controller/Pay.php` | High
105 | File | `/application/index/controller/Screen.php` | High
106 | File | `/application/index/controller/Service.php` | High
107 | File | `/application/index/controller/Unity.php` | High
108 | File | `/application/pay/controller/Api.php` | High
109 | File | `/application/plugins/controller/Upload.php` | High
110 | File | `/application/websocket/controller/Setting.php` | High
111 | File | `/App_Resource/UEditor/server/upload.aspx` | High
112 | File | `/article/DelectArticleById/` | High
113 | File | `/assets/php/upload.php` | High
114 | File | `/att_add.php` | Medium
115 | File | `/auth/auth.php?user=1` | High
116 | File | `/author/list?limit=10&offset=0&order=desc` | High
117 | File | `/b2b-supermarket/shopping-cart` | High
118 | File | `/blog-single.php` | High
119 | File | `/boafrm/formMapDelDevice` | High
120 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
121 | File | `/cancel.php` | Medium
122 | File | `/category/list?limit=10&offset=0&order=desc` | High
123 | File | `/cgi-bin/adm.cgi` | High
124 | File | `/cgi-bin/cstecgi.cgi` | High
125 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
126 | File | `/cgi-bin/DownloadCfg/RouterCfm.cfg` | High
127 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
128 | File | `/cgi-bin/koha/catalogue/search.pl` | High
129 | File | `/cgi-bin/ping.cgi` | High
130 | ... | ... | ...

There are 1159 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
