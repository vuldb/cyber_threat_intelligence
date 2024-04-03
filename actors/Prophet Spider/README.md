# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/Account/login.php` | High
3 | File | `/add_members.php` | High
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/action/add_con.php` | High
7 | File | `/admin/action/edit_chicken.php` | High
8 | File | `/admin/action/new-father.php` | High
9 | File | `/admin/action/new-feed.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/app/product.php` | High
12 | File | `/admin/app/profile_crud.php` | High
13 | File | `/admin/app/service_crud.php` | High
14 | File | `/admin/applicants/controller.php` | High
15 | File | `/admin/applicants/index.php` | High
16 | File | `/admin/application-bwdates-reports-details.php` | High
17 | File | `/admin/bookdate.php` | High
18 | File | `/admin/booking-bwdates-reports-details.php` | High
19 | File | `/admin/booktime.php` | High
20 | File | `/admin/category/controller.php` | High
21 | File | `/admin/clientview.php` | High
22 | File | `/admin/company/controller.php` | High
23 | File | `/admin/company/index.php` | High
24 | File | `/admin/div_data/delete?divId=9` | High
25 | File | `/admin/edit-admin.php` | High
26 | File | `/admin/edit_supplier.php` | High
27 | File | `/admin/edit_teacher.php` | High
28 | File | `/admin/employee/controller.php` | High
29 | File | `/admin/employee/index.php` | High
30 | File | `/admin/list_localuser.php` | High
31 | File | `/admin/list_resource_icon.php?action=delete` | High
32 | File | `/admin/login.php` | High
33 | File | `/Admin/login.php` | High
34 | File | `/admin/maintenance/manage_category.php` | High
35 | File | `/admin/makehtml_freelist_action.php` | High
36 | File | `/admin/manage-users.php` | High
37 | File | `/admin/menu/toEdit` | High
38 | File | `/Admin/News.php` | High
39 | File | `/admin/operations/expense_category.php` | High
40 | File | `/admin/orders/view_order.php` | High
41 | File | `/admin/pages/edit_chicken.php` | High
42 | File | `/admin/pages/student-print.php` | High
43 | File | `/admin/pages/update_go.php` | High
44 | File | `/admin/product/manage_product.php` | High
45 | File | `/admin/regester.php` | High
46 | File | `/admin/rooms.php` | High
47 | File | `/admin/search.php` | High
48 | File | `/admin/suppliers/view_details.php` | High
49 | File | `/admin/update-rooms.php` | High
50 | File | `/admin/update-users.php` | High
51 | File | `/admin/user-search.php` | High
52 | File | `/admin/user/controller.php` | High
53 | File | `/admin/users.php` | High
54 | File | `/admin/vacancy/index.php` | High
55 | File | `/adminapi/system/crud` | High
56 | File | `/adminapi/system/file/openfile` | High
57 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
58 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
59 | File | `/adminpanel/admin/query/loginExe.php` | High
60 | File | `/admin_ping.htm` | High
61 | File | `/admin_route/dec_service_credits.php` | High
62 | File | `/admin_route/inc_service_credits.php` | High
63 | File | `/ample/app/action/edit_product.php` | High
64 | File | `/api.php` | Medium
65 | File | `/api/client/editemedia.php` | High
66 | File | `/api/controllers/admin/app/AppController.php` | High
67 | File | `/api/controllers/common/UploadsController.php` | High
68 | File | `/api/controllers/merchant/design/MaterialController.php` | High
69 | File | `/api/controllers/merchant/shop/PosterController.php` | High
70 | File | `/api/sys/login` | High
71 | File | `/api/sys/set_passwd` | High
72 | File | `/api/v1/policies/validation/condition/` | High
73 | File | `/api/v1/toolbox/device/update/swap` | High
74 | File | `/app/api/controller/default/File.php` | High
75 | File | `/app/api/controller/default/Sqlite.php` | High
76 | File | `/app/index/controller/Common.php` | High
77 | File | `/app/middleware/TokenVerify.php` | High
78 | File | `/application/index/controller/Databasesource.php` | High
79 | File | `/application/index/controller/Datament.php` | High
80 | File | `/application/index/controller/File.php` | High
81 | File | `/application/index/controller/Icon.php` | High
82 | File | `/application/index/controller/Pay.php` | High
83 | File | `/application/index/controller/Screen.php` | High
84 | File | `/application/index/controller/Unity.php` | High
85 | File | `/application/pay/controller/Api.php` | High
86 | File | `/application/plugins/controller/Upload.php` | High
87 | File | `/application/websocket/controller/Setting.php` | High
88 | File | `/apply/index.php` | High
89 | File | `/apps/login_auth.php` | High
90 | File | `/apps/reg_go.php` | High
91 | File | `/apps/system/api/user.go` | High
92 | File | `/apps/system/router/upload.go` | High
93 | File | `/apps/system/services/role_menu.go` | High
94 | ... | ... | ...

There are 831 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
