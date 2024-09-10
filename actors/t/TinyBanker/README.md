# TinyBanker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TinyBanker](https://vuldb.com/?actor.tinybanker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tinybanker](https://vuldb.com/?actor.tinybanker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TinyBanker:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [ES](https://vuldb.com/?country.es)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TinyBanker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.32.207.78](https://vuldb.com/?ip.13.32.207.78) | server-13-32-207-78.iad66.r.cloudfront.net | - | High
2 | [78.108.118.108](https://vuldb.com/?ip.78.108.118.108) | g2wmcs22-3-isp1.fra.expertcity.com | - | High
3 | [78.108.118.118](https://vuldb.com/?ip.78.108.118.118) | g2wmcs26-1-isp1.fra.expertcity.com | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TinyBanker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TinyBanker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?p=products` | Medium
3 | File | `/Account/login.php` | High
4 | File | `/actuator/heapdump` | High
5 | File | `/add_classes.php` | High
6 | File | `/add_members.php` | High
7 | File | `/admin` | Low
8 | File | `/admin-api/upload_image` | High
9 | File | `/admin-manage-user.php` | High
10 | File | `/admin.php?p=/Area/index#tab=t2` | High
11 | File | `/admin/` | Low
12 | File | `/admin/?page=borrow/view_borrow` | High
13 | File | `/admin/?page=user/list` | High
14 | File | `/admin/action/delete-vaccine.php` | High
15 | File | `/admin/action/edit_chicken.php` | High
16 | File | `/admin/add-ambulance.php` | High
17 | File | `/admin/add_postlogin.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/admin_user.php` | High
20 | File | `/admin/ajax.php?action=delete_user` | High
21 | File | `/admin/applicants/index.php` | High
22 | File | `/admin/booktime.php` | High
23 | File | `/admin/book_add.php` | High
24 | File | `/admin/borrow_add.php` | High
25 | File | `/admin/category_row.php` | High
26 | File | `/admin/client_user` | High
27 | File | `/admin/config_MT.php?action=delete` | High
28 | File | `/admin/content` | High
29 | File | `/admin/court` | Medium
30 | File | `/admin/doctors.php` | High
31 | File | `/Admin/edit-photo.php` | High
32 | File | `/admin/edit-services.php` | High
33 | File | `/admin/edit_categories.php` | High
34 | File | `/admin/edit_supplier.php` | High
35 | File | `/admin/employee/index.php` | High
36 | File | `/admin/expense-type` | High
37 | File | `/admin/foreigner-bwdates-reports-details.php` | High
38 | File | `/admin/foreigner-search.php` | High
39 | File | `/admin/forgot-password.php` | High
40 | File | `/admin/index.php` | High
41 | File | `/admin/index.php?page=categories` | High
42 | File | `/admin/judge` | Medium
43 | File | `/admin/list_crl_conf` | High
44 | File | `/admin/list_ipAddressPolicy.php` | High
45 | File | `/admin/login.php` | High
46 | File | `/admin/maintenance/manage_brand.php` | High
47 | File | `/admin/manage-ambulance.php` | High
48 | File | `/admin/manage-students.php` | High
49 | File | `/admin/menu/toEdit` | High
50 | File | `/admin/normal-bwdates-reports-details.php` | High
51 | File | `/admin/normal-search.php` | High
52 | File | `/admin/pages/edit_chicken.php` | High
53 | File | `/admin/pages/update_go.php` | High
54 | File | `/admin/receipt.php` | High
55 | File | `/admin/regester.php` | High
56 | File | `/admin/request-received-bydonar.php` | High
57 | File | `/admin/return_add.php` | High
58 | File | `/admin/role` | Medium
59 | File | `/admin/rooms.php` | High
60 | File | `/admin/tag.php` | High
61 | File | `/admin/tasks` | Medium
62 | File | `/admin/tax` | Medium
63 | File | `/admin/template` | High
64 | File | `/admin/twitter.php` | High
65 | File | `/admin/update-rooms.php` | High
66 | File | `/admin/update-users.php` | High
67 | File | `/admin/uploads/` | High
68 | File | `/Admin/user-record.php` | High
69 | File | `/admin/user/index.php` | High
70 | File | `/admin/users.php` | High
71 | File | `/admin/vacancy/index.php` | High
72 | File | `/admin/vendor` | High
73 | File | `/adminapi/system/file/openfile` | High
74 | File | `/adminPage/conf/reload` | High
75 | File | `/adminPage/conf/saveCmd` | High
76 | File | `/adminPage/main/upload` | High
77 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
78 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
79 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
80 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
81 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
82 | File | `/adminpanel/admin/query/loginExe.php` | High
83 | File | `/admin_route/dec_service_credits.php` | High
84 | File | `/ajax-api.php` | High
85 | File | `/ajax.php` | Medium
86 | File | `/ample/app/action/edit_product.php` | High
87 | File | `/api/controllers/admin/app/AppController.php` | High
88 | File | `/api/controllers/merchant/app/ComboController.php` | High
89 | File | `/api/controllers/merchant/design/MaterialController.php` | High
90 | File | `/api/v2/maps` | Medium
91 | File | `/app/ajax/search_sales_report.php` | High
92 | File | `/app/Http/Controllers/ImageController.php` | High
93 | File | `/app/uploading/upload-mp3.php` | High
94 | File | `/application/index/controller/Datament.php` | High
95 | File | `/application/index/controller/File.php` | High
96 | File | `/application/index/controller/Icon.php` | High
97 | File | `/application/index/controller/Screen.php` | High
98 | File | `/application/index/controller/Unity.php` | High
99 | File | `/application/pay/controller/Api.php` | High
100 | File | `/application/plugins/controller/Upload.php` | High
101 | File | `/application/websocket/controller/Setting.php` | High
102 | File | `/apply/index.php` | High
103 | File | `/apps/login_auth.php` | High
104 | File | `/apps/reg_go.php` | High
105 | File | `/apps/system/api/user.go` | High
106 | File | `/apps/system/services/role_menu.go` | High
107 | File | `/att_add.php` | Medium
108 | File | `/backend/register.php` | High
109 | File | `/boaform/device_reset.cgi` | High
110 | File | `/cancel.php` | Medium
111 | File | `/cap.js` | Low
112 | File | `/catalog/all-products` | High
113 | File | `/cgi-bin/cstecgi.cgi` | High
114 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
115 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
116 | File | `/cgi-bin/nas_sharing.cgi` | High
117 | ... | ... | ...

There are 1034 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0409-0416.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-for-july-9-to-july-16.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
