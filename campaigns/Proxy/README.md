# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 18 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Proxy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Proxy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
6 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Proxy. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/ajax.php?action=confirm_order` | High
11 | File | `/admin/app/product.php` | High
12 | File | `/admin/app/service_crud.php` | High
13 | File | `/admin/applicants/controller.php` | High
14 | File | `/admin/bookdate.php` | High
15 | File | `/admin/booktime.php` | High
16 | File | `/admin/book_add.php` | High
17 | File | `/admin/book_row.php` | High
18 | File | `/admin/borrow_add.php` | High
19 | File | `/admin/bwdates-report-details.php` | High
20 | File | `/admin/category/controller.php` | High
21 | File | `/admin/category_row.php` | High
22 | File | `/admin/cms_admin.php` | High
23 | File | `/admin/company/controller.php` | High
24 | File | `/admin/company/index.php` | High
25 | File | `/admin/course.php` | High
26 | File | `/admin/courses/manage_course.php` | High
27 | File | `/admin/div_data/delete?divId=9` | High
28 | File | `/admin/edit-admin.php` | High
29 | File | `/admin/edit_supplier.php` | High
30 | File | `/admin/edit_teacher.php` | High
31 | File | `/admin/employee/controller.php` | High
32 | File | `/admin/employee/index.php` | High
33 | File | `/admin/leancloud.php` | High
34 | File | `/admin/list_resource_icon.php?action=delete` | High
35 | File | `/Admin/login.php` | High
36 | File | `/admin/login.php` | High
37 | File | `/admin/maintenance/manage_category.php` | High
38 | File | `/admin/makehtml_freelist_action.php` | High
39 | File | `/admin/manage-pages.php` | High
40 | File | `/admin/menu/toEdit` | High
41 | File | `/Admin/News.php` | High
42 | File | `/admin/operations/expense_category.php` | High
43 | File | `/admin/orders/view_order.php` | High
44 | File | `/admin/pages/edit_chicken.php` | High
45 | File | `/admin/pages/update_go.php` | High
46 | File | `/admin/pages/yearlevel.php` | High
47 | File | `/admin/php/crud.php` | High
48 | File | `/admin/product/manage_product.php` | High
49 | File | `/admin/rooms.php` | High
50 | File | `/admin/search.php` | High
51 | File | `/admin/settings/` | High
52 | File | `/admin/students/manage_academic.php` | High
53 | File | `/admin/students/update_status.php` | High
54 | File | `/admin/subject.php` | High
55 | File | `/admin/theme-edit.php` | High
56 | File | `/admin/update-rooms.php` | High
57 | File | `/admin/update-users.php` | High
58 | File | `/admin/user-search.php` | High
59 | File | `/admin/users.php` | High
60 | File | `/adminapi/system/crud` | High
61 | File | `/adminapi/system/file/openfile` | High
62 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
63 | File | `/adminpanel/admin/query/loginExe.php` | High
64 | File | `/admin_route/dec_service_credits.php` | High
65 | File | `/adplanet/PlanetUser` | High
66 | File | `/ample/app/action/edit_product.php` | High
67 | File | `/ample/app/ajax/member_data.php` | High
68 | File | `/api.php` | Medium
69 | File | `/api/authentication/login` | High
70 | File | `/api/clusters/local/topics/{topic}/messages` | High
71 | File | `/api/controllers/admin/app/AppController.php` | High
72 | File | `/api/controllers/common/UploadsController.php` | High
73 | File | `/api/DataDictionary/GetItemList` | High
74 | File | `/api/runscript` | High
75 | File | `/api/v1/toolbox/device/update/swap` | High
76 | File | `/application/index/controller/Datament.php` | High
77 | File | `/application/index/controller/Pay.php` | High
78 | File | `/application/index/controller/Screen.php` | High
79 | File | `/application/pay/controller/Api.php` | High
80 | File | `/apply/index.php` | High
81 | File | `/apps/reg_go.php` | High
82 | File | `/apps/system/api/user.go` | High
83 | File | `/apps/system/router/upload.go` | High
84 | File | `/apps/system/services/role_menu.go` | High
85 | File | `/att_add.php` | Medium
86 | File | `/b2b-supermarket/catalog/all-products` | High
87 | File | `/billing/bill/edit/` | High
88 | File | `/bin/boa` | Medium
89 | File | `/bishe/register` | High
90 | File | `/boaform/device_reset.cgi` | High
91 | File | `/boaform/wlan_basic_set.cgi` | High
92 | File | `/boafrm/formMapDelDevice` | High
93 | File | `/bsenordering/index.php` | High
94 | File | `/cancel.php` | Medium
95 | File | `/category.php` | High
96 | File | `/cgi-bin/` | Medium
97 | File | `/cgi-bin/cstecgi.cgi` | High
98 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
99 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
100 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
101 | File | `/change-password.php` | High
102 | ... | ... | ...

There are 906 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/vishalyadav70/Proxy-Server/blob/main/proxy/blacklist.txt
* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
