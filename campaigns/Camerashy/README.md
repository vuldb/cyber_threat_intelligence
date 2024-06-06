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
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/?g=log_import_save` | High
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/academy/tutor/filter` | High
5 | File | `/actuator/heapdump` | High
6 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
7 | File | `/admin.php?p=/Area/index#tab=t2` | High
8 | File | `/admin/` | Low
9 | File | `/admin/?page=system_info` | High
10 | File | `/admin/action/add_con.php` | High
11 | File | `/admin/action/delete-vaccine.php` | High
12 | File | `/admin/action/edit_chicken.php` | High
13 | File | `/admin/action/new-father.php` | High
14 | File | `/admin/action/new-feed.php` | High
15 | File | `/admin/action/update-deworm.php` | High
16 | File | `/Admin/add-admin.php` | High
17 | File | `/admin/add-ambulance.php` | High
18 | File | `/admin/add-category.php` | High
19 | File | `/admin/addTithes.php` | High
20 | File | `/admin/add_ikev2.php` | High
21 | File | `/admin/add_user_modal.php` | High
22 | File | `/admin/add_visitor.php` | High
23 | File | `/admin/admin-profile.php` | High
24 | File | `/admin/admin.php` | High
25 | File | `/admin/admin_content_tag.php?action=save_content` | High
26 | File | `/admin/admin_login_process.php` | High
27 | File | `/admin/admin_user.php` | High
28 | File | `/admin/ajax.php?action=confirm_order` | High
29 | File | `/admin/api/admin/v2_products` | High
30 | File | `/admin/api/theme-edit/` | High
31 | File | `/admin/app/login_crud.php` | High
32 | File | `/admin/app/profile_crud.php` | High
33 | File | `/admin/applicants/controller.php` | High
34 | File | `/admin/applicants/index.php` | High
35 | File | `/admin/article/article-edit-run.php` | High
36 | File | `/admin/booking-bwdates-reports-details.php` | High
37 | File | `/admin/booking-search.php` | High
38 | File | `/admin/bookings/view_details.php` | High
39 | File | `/admin/candidates_row.php` | High
40 | File | `/admin/case-status` | High
41 | File | `/admin/cms_content.php` | High
42 | File | `/admin/configurations/userInfo` | High
43 | File | `/admin/config_Anticrack.php` | High
44 | File | `/admin/config_save.php` | High
45 | File | `/admin/content` | High
46 | File | `/admin/course.php` | High
47 | File | `/admin/deduction_row.php` | High
48 | File | `/admin/del_service.php` | High
49 | File | `/admin/edit-services.php` | High
50 | File | `/admin/edit_categories.php` | High
51 | File | `/admin/edit_category.php` | High
52 | File | `/admin/edit_product.php` | High
53 | File | `/admin/edit_supplier.php` | High
54 | File | `/admin/edit_teacher.php` | High
55 | File | `/admin/employee/controller.php` | High
56 | File | `/admin/employee/index.php` | High
57 | File | `/admin/employee_edit.php` | High
58 | File | `/admin/foreigner-bwdates-reports-details.php` | High
59 | File | `/admin/forgot-password.php` | High
60 | File | `/admin/general-setting` | High
61 | File | `/admin/index.php` | High
62 | File | `/admin/index.php?act=reset_admin_psw` | High
63 | File | `/admin/index.php?page=categories` | High
64 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
65 | File | `/admin/invoice.php` | High
66 | File | `/admin/list_crl_conf` | High
67 | File | `/Admin/login.php` | High
68 | File | `/admin/login.php` | High
69 | File | `/admin/maintenance/brand.php` | High
70 | File | `/admin/maintenance/manage_brand.php` | High
71 | File | `/admin/maintenance/view_designation.php` | High
72 | File | `/admin/makehtml_freelist_action.php` | High
73 | File | `/admin/manage-ambulance.php` | High
74 | File | `/admin/manage-users.php` | High
75 | File | `/admin/modal_add_product.php` | High
76 | File | `/admin/offenses/view_details.php` | High
77 | File | `/admin/order.php` | High
78 | File | `/admin/pages/student-print.php` | High
79 | File | `/admin/pages/update_go.php` | High
80 | File | `/admin/positions_add.php` | High
81 | File | `/admin/product/manage.php` | High
82 | File | `/admin/product/manage_product.php` | High
83 | File | `/admin/products/manage_product.php` | High
84 | File | `/admin/read.php?mudi=announContent` | High
85 | File | `/admin/read.php?mudi=getSignal` | High
86 | File | `/admin/receipt.php` | High
87 | File | `/admin/reportupload.aspx` | High
88 | File | `/admin/request-received-bydonar.php` | High
89 | File | `/admin/search-appointment.php` | High
90 | File | `/admin/search.php` | High
91 | File | `/admin/service` | High
92 | File | `/admin/singlelogin.php` | High
93 | File | `/admin/students.php` | High
94 | File | `/admin/students/update_status.php` | High
95 | File | `/admin/tag.php` | High
96 | File | `/admin/tax` | Medium
97 | File | `/admin/template` | High
98 | File | `/admin/twitter.php` | High
99 | File | `/admin/upload/img` | High
100 | File | `/admin/uploads/` | High
101 | File | `/admin/vacancy/index.php` | High
102 | File | `/admin/view_sendlist.php` | High
103 | File | `/admin/voters_row.php` | High
104 | File | `/admin/vote_edit.php` | High
105 | File | `/adminapi/system/crud` | High
106 | File | `/adminapi/system/file/openfile` | High
107 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
108 | File | `/admin_class.php` | High
109 | File | `/admin_route/dec_service_credits.php` | High
110 | File | `/admin_route/inc_service_credits.php` | High
111 | File | `/ajax.php?action=save_company` | High
112 | File | `/api/admin/system/store/order/list` | High
113 | File | `/api/client/editemedia.php` | High
114 | File | `/api/controllers/admin/app/AppController.php` | High
115 | File | `/api/controllers/admin/app/ComboController.php` | High
116 | File | `/api/controllers/merchant/app/ComboController.php` | High
117 | File | `/api/controllers/merchant/design/MaterialController.php` | High
118 | File | `/api/controllers/merchant/shop/PosterController.php` | High
119 | File | `/api/ping` | Medium
120 | File | `/api/sys/set_passwd` | High
121 | File | `/api/upload` | Medium
122 | File | `/app/api/controller/caiji.php` | High
123 | File | `/app/api/controller/collect.php` | High
124 | File | `/app/api/controller/default/File.php` | High
125 | File | `/app/api/controller/default/Sqlite.php` | High
126 | File | `/app/Http/Controllers/ImageController.php` | High
127 | File | `/app/index/controller/Common.php` | High
128 | File | `/app/middleware/TokenVerify.php` | High
129 | File | `/app/sys1.php` | High
130 | File | `/application/index/common.php` | High
131 | File | `/application/index/controller/Icon.php` | High
132 | File | `/application/index/controller/Pay.php` | High
133 | File | `/application/index/controller/Screen.php` | High
134 | File | `/application/index/controller/Service.php` | High
135 | File | `/application/index/controller/Unity.php` | High
136 | File | `/application/pay/controller/Api.php` | High
137 | File | `/apps/login_auth.php` | High
138 | File | `/apps/reg_go.php` | High
139 | File | `/auth/auth.php?user=1` | High
140 | File | `/author/list?limit=10&offset=0&order=desc` | High
141 | File | `/backend/register.php` | High
142 | File | `/bishe/register` | High
143 | File | `/blog-single.php` | High
144 | File | `/boafrm/formMapDelDevice` | High
145 | File | `/book-services.php` | High
146 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
147 | File | `/cart.php` | Medium
148 | File | `/cas/logout` | Medium
149 | File | `/category/list?limit=10&offset=0&order=desc` | High
150 | File | `/cgi-bin/cstecgi.cgi` | High
151 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
152 | ... | ... | ...

There are 1349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
