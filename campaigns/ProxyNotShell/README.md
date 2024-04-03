# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/Account/login.php` | High
3 | File | `/admin-manage-user.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=user/manage_user&id=3` | High
6 | File | `/admin/action/add_con.php` | High
7 | File | `/admin/action/new-father.php` | High
8 | File | `/admin/action/new-feed.php` | High
9 | File | `/admin/add_user_modal.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/ajax.php?action=confirm_order` | High
12 | File | `/admin/app/product.php` | High
13 | File | `/admin/app/service_crud.php` | High
14 | File | `/admin/applicants/controller.php` | High
15 | File | `/admin/article/article-edit-run.php` | High
16 | File | `/admin/bookdate.php` | High
17 | File | `/admin/booktime.php` | High
18 | File | `/admin/book_add.php` | High
19 | File | `/admin/book_row.php` | High
20 | File | `/admin/borrow_add.php` | High
21 | File | `/admin/bwdates-report-details.php` | High
22 | File | `/admin/category/cate-edit-run.php` | High
23 | File | `/admin/category/controller.php` | High
24 | File | `/admin/category_row.php` | High
25 | File | `/admin/cms_admin.php` | High
26 | File | `/admin/company/controller.php` | High
27 | File | `/admin/company/index.php` | High
28 | File | `/admin/course.php` | High
29 | File | `/admin/courses/manage_course.php` | High
30 | File | `/admin/div_data/delete?divId=9` | High
31 | File | `/admin/edit-admin.php` | High
32 | File | `/admin/edit_supplier.php` | High
33 | File | `/admin/edit_teacher.php` | High
34 | File | `/admin/employee/controller.php` | High
35 | File | `/admin/employee/index.php` | High
36 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
37 | File | `/admin/leancloud.php` | High
38 | File | `/admin/list_resource_icon.php?action=delete` | High
39 | File | `/Admin/login.php` | High
40 | File | `/admin/login.php` | High
41 | File | `/admin/maintenance/manage_category.php` | High
42 | File | `/admin/makehtml_freelist_action.php` | High
43 | File | `/admin/manage-pages.php` | High
44 | File | `/admin/menu/toEdit` | High
45 | File | `/admin/modal_add_product.php` | High
46 | File | `/Admin/News.php` | High
47 | File | `/admin/operations/expense_category.php` | High
48 | File | `/admin/orders/view_order.php` | High
49 | File | `/admin/pages/edit_chicken.php` | High
50 | File | `/admin/pages/update_go.php` | High
51 | File | `/admin/pages/yearlevel.php` | High
52 | File | `/admin/php/crud.php` | High
53 | File | `/admin/product/manage_product.php` | High
54 | File | `/admin/read.php?mudi=announContent` | High
55 | File | `/admin/rooms.php` | High
56 | File | `/admin/search.php` | High
57 | File | `/admin/settings/` | High
58 | File | `/admin/students/manage_academic.php` | High
59 | File | `/admin/students/update_status.php` | High
60 | File | `/admin/subject.php` | High
61 | File | `/admin/theme-edit.php` | High
62 | File | `/admin/update-rooms.php` | High
63 | File | `/admin/update-users.php` | High
64 | File | `/admin/upload.php` | High
65 | File | `/admin/user-search.php` | High
66 | File | `/admin/users.php` | High
67 | File | `/adminapi/system/crud` | High
68 | File | `/adminapi/system/file/openfile` | High
69 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
70 | File | `/adminpanel/admin/query/loginExe.php` | High
71 | File | `/admin_route/dec_service_credits.php` | High
72 | File | `/adplanet/PlanetUser` | High
73 | File | `/ample/app/action/edit_product.php` | High
74 | File | `/ample/app/ajax/member_data.php` | High
75 | File | `/api.php` | Medium
76 | File | `/api/authentication/login` | High
77 | File | `/api/controllers/admin/app/AppController.php` | High
78 | File | `/api/controllers/common/UploadsController.php` | High
79 | File | `/api/DataDictionary/GetItemList` | High
80 | File | `/api/es/admin/v3/security/user/1` | High
81 | File | `/api/ping` | Medium
82 | File | `/api/runscript` | High
83 | File | `/api/sys/login` | High
84 | File | `/api/sys/set_passwd` | High
85 | File | `/api/v1/toolbox/device/update/swap` | High
86 | File | `/application/index/controller/Datament.php` | High
87 | File | `/application/index/controller/Pay.php` | High
88 | File | `/application/index/controller/Screen.php` | High
89 | File | `/application/pay/controller/Api.php` | High
90 | File | `/apply/index.php` | High
91 | File | `/apps/reg_go.php` | High
92 | File | `/apps/system/api/user.go` | High
93 | File | `/apps/system/router/upload.go` | High
94 | File | `/apps/system/services/role_menu.go` | High
95 | File | `/att_add.php` | Medium
96 | File | `/autheditpwd.php` | High
97 | File | `/b2b-supermarket/catalog/all-products` | High
98 | File | `/billing/bill/edit/` | High
99 | File | `/bin/boa` | Medium
100 | File | `/bishe/register` | High
101 | File | `/boaform/device_reset.cgi` | High
102 | File | `/boaform/wlan_basic_set.cgi` | High
103 | File | `/boafrm/formMapDelDevice` | High
104 | File | `/bsenordering/index.php` | High
105 | File | `/cancel.php` | Medium
106 | File | `/category.php` | High
107 | File | `/cgi-bin/` | Medium
108 | ... | ... | ...

There are 955 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
