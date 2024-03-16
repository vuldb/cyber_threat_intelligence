# Powload - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Powload](https://vuldb.com/?actor.powload). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powload](https://vuldb.com/?actor.powload)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Powload.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.29.155](https://vuldb.com/?ip.5.61.29.155) | 5-61-29-155.nrp.co | - | High
2 | [31.14.103.164](https://vuldb.com/?ip.31.14.103.164) | dns103164.phdns19.es | - | High
3 | [37.211.38.50](https://vuldb.com/?ip.37.211.38.50) | - | - | High
4 | [42.114.73.81](https://vuldb.com/?ip.42.114.73.81) | - | - | High
5 | [45.40.251.243](https://vuldb.com/?ip.45.40.251.243) | - | - | High
6 | [47.99.85.122](https://vuldb.com/?ip.47.99.85.122) | - | - | High
7 | [50.99.132.7](https://vuldb.com/?ip.50.99.132.7) | s50-99-132-7.ab.hsia.telus.net | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Powload_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Powload. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/Account/login.php` | High
3 | File | `/addbill.php` | Medium
4 | File | `/add_classes.php` | High
5 | File | `/admin` | Low
6 | File | `/admin.php?p=/Area/index#tab=t2` | High
7 | File | `/admin/` | Low
8 | File | `/admin/action/add_con.php` | High
9 | File | `/admin/action/delete-vaccine.php` | High
10 | File | `/admin/action/edit_chicken.php` | High
11 | File | `/admin/action/new-father.php` | High
12 | File | `/admin/action/new-feed.php` | High
13 | File | `/admin/action/update-deworm.php` | High
14 | File | `/admin/admin_login_process.php` | High
15 | File | `/admin/admin_user.php` | High
16 | File | `/admin/app/login_crud.php` | High
17 | File | `/admin/app/product.php` | High
18 | File | `/admin/app/profile_crud.php` | High
19 | File | `/admin/app/service_crud.php` | High
20 | File | `/admin/book_add.php` | High
21 | File | `/admin/book_row.php` | High
22 | File | `/admin/borrow_add.php` | High
23 | File | `/admin/bwdates-report-details.php` | High
24 | File | `/admin/category_row.php` | High
25 | File | `/admin/clientview.php` | High
26 | File | `/admin/edit-admin.php` | High
27 | File | `/admin/edit_categories.php` | High
28 | File | `/admin/edit_supplier.php` | High
29 | File | `/admin/edit_teacher.php` | High
30 | File | `/admin/index.php?act=reset_admin_psw` | High
31 | File | `/admin/list_ipAddressPolicy.php` | High
32 | File | `/admin/list_localuser.php` | High
33 | File | `/admin/login.php` | High
34 | File | `/Admin/login.php` | High
35 | File | `/admin/makehtml_freelist_action.php` | High
36 | File | `/admin/manage-users.php` | High
37 | File | `/Admin/News.php` | High
38 | File | `/admin/pages/edit_chicken.php` | High
39 | File | `/admin/pages/student-print.php` | High
40 | File | `/admin/pages/subjects.php` | High
41 | File | `/admin/pages/update_go.php` | High
42 | File | `/admin/pages/yearlevel.php` | High
43 | File | `/admin/php/crud.php` | High
44 | File | `/admin/regester.php` | High
45 | File | `/admin/request-received-bydonar.php` | High
46 | File | `/admin/return_add.php` | High
47 | File | `/admin/students.php` | High
48 | File | `/admin/update-clients.php` | High
49 | File | `/admin/uploads/` | High
50 | File | `/admin/view_sendlist.php` | High
51 | File | `/adminapi/system/crud` | High
52 | File | `/adminapi/system/file/openfile` | High
53 | File | `/admin_ping.htm` | High
54 | File | `/admin_route/dec_service_credits.php` | High
55 | File | `/admin_route/inc_service_credits.php` | High
56 | File | `/ajax-api.php` | High
57 | File | `/ample/app/action/edit_product.php` | High
58 | File | `/api.php` | Medium
59 | File | `/api/controllers/admin/app/AppController.php` | High
60 | File | `/api/controllers/admin/app/ComboController.php` | High
61 | File | `/api/controllers/common/UploadsController.php` | High
62 | File | `/api/controllers/merchant/app/ComboController.php` | High
63 | File | `/api/controllers/merchant/design/MaterialController.php` | High
64 | File | `/api/controllers/merchant/shop/PosterController.php` | High
65 | File | `/api/log/killJob` | High
66 | File | `/app/ajax/search_sales_report.php` | High
67 | File | `/app/ajax/sell_return_data.php` | High
68 | File | `/app/api/controller/caiji.php` | High
69 | File | `/app/api/controller/collect.php` | High
70 | File | `/app/api/controller/default/File.php` | High
71 | File | `/app/api/controller/default/Sqlite.php` | High
72 | File | `/app/controller/Setup.php` | High
73 | File | `/app/Http/Controllers/ImageController.php` | High
74 | File | `/app/index/controller/Common.php` | High
75 | File | `/app/middleware/TokenVerify.php` | High
76 | File | `/application/index/common.php` | High
77 | File | `/application/index/controller/Databasesource.php` | High
78 | File | `/application/index/controller/Datament.php` | High
79 | File | `/application/index/controller/File.php` | High
80 | File | `/application/index/controller/Icon.php` | High
81 | File | `/application/index/controller/Pay.php` | High
82 | File | `/application/index/controller/Screen.php` | High
83 | File | `/application/index/controller/Service.php` | High
84 | File | `/application/index/controller/Unity.php` | High
85 | File | `/application/pay/controller/Api.php` | High
86 | File | `/application/plugins/controller/Upload.php` | High
87 | File | `/application/websocket/controller/Setting.php` | High
88 | File | `/apply/index.php` | High
89 | File | `/apps/login_auth.php` | High
90 | File | `/apps/reg_go.php` | High
91 | File | `/assets/php/upload.php` | High
92 | File | `/att_add.php` | Medium
93 | File | `/auth/user/all.api` | High
94 | File | `/bin/boa` | Medium
95 | ... | ... | ...

There are 844 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0921-0928.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1207-1214.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0419-to-0426.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0503-0510.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
