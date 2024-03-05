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
* [FR](https://vuldb.com/?country.fr)
* [SC](https://vuldb.com/?country.sc)
* ...

There are 3 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1059 | CWE-88, CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/Account/login.php` | High
3 | File | `/admin/` | Low
4 | File | `/admin/action/add_con.php` | High
5 | File | `/admin/action/edit_chicken.php` | High
6 | File | `/admin/action/new-father.php` | High
7 | File | `/admin/action/new-feed.php` | High
8 | File | `/admin/book_add.php` | High
9 | File | `/admin/book_row.php` | High
10 | File | `/admin/borrow_add.php` | High
11 | File | `/admin/bwdates-report-details.php` | High
12 | File | `/admin/category_row.php` | High
13 | File | `/admin/clientview.php` | High
14 | File | `/admin/course.php` | High
15 | File | `/admin/edit-admin.php` | High
16 | File | `/admin/edit_teacher.php` | High
17 | File | `/admin/login.php` | High
18 | File | `/Admin/login.php` | High
19 | File | `/admin/makehtml_freelist_action.php` | High
20 | File | `/admin/manage-pages.php` | High
21 | File | `/admin/manage-users.php` | High
22 | File | `/Admin/News.php` | High
23 | File | `/admin/pages/edit_chicken.php` | High
24 | File | `/admin/pages/student-print.php` | High
25 | File | `/admin/pages/update_go.php` | High
26 | File | `/admin/pages/yearlevel.php` | High
27 | File | `/admin/php/crud.php` | High
28 | File | `/admin/regester.php` | High
29 | File | `/admin/return_add.php` | High
30 | File | `/admin/settings/` | High
31 | File | `/admin/students.php` | High
32 | File | `/admin/subject.php` | High
33 | File | `/admin/theme-edit.php` | High
34 | File | `/admin/user/manage_user.php` | High
35 | File | `/admin/users` | Medium
36 | File | `/adminapi/system/crud` | High
37 | File | `/adminapi/system/file/openfile` | High
38 | File | `/admin_ping.htm` | High
39 | File | `/admin_route/dec_service_credits.php` | High
40 | File | `/admin_route/inc_service_credits.php` | High
41 | File | `/adplanet/PlanetUser` | High
42 | File | `/ample/app/action/edit_product.php` | High
43 | File | `/ample/app/ajax/member_data.php` | High
44 | File | `/api.php` | Medium
45 | File | `/api/controllers/admin/app/AppController.php` | High
46 | File | `/api/controllers/common/UploadsController.php` | High
47 | File | `/api/controllers/merchant/design/MaterialController.php` | High
48 | File | `/api/controllers/merchant/shop/PosterController.php` | High
49 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
50 | File | `/app/api/controller/default/File.php` | High
51 | File | `/app/api/controller/default/Sqlite.php` | High
52 | File | `/app/index/controller/Common.php` | High
53 | File | `/app/middleware/TokenVerify.php` | High
54 | File | `/application/index/controller/Databasesource.php` | High
55 | File | `/application/index/controller/Datament.php` | High
56 | File | `/application/index/controller/File.php` | High
57 | File | `/application/index/controller/Icon.php` | High
58 | File | `/application/index/controller/Pay.php` | High
59 | File | `/application/index/controller/Screen.php` | High
60 | File | `/application/index/controller/Unity.php` | High
61 | File | `/application/pay/controller/Api.php` | High
62 | File | `/application/plugins/controller/Upload.php` | High
63 | File | `/application/websocket/controller/Setting.php` | High
64 | File | `/apply/index.php` | High
65 | File | `/apps/login_auth.php` | High
66 | File | `/apps/reg_go.php` | High
67 | File | `/article/DelectArticleById/` | High
68 | File | `/assets/php/upload.php` | High
69 | File | `/att_add.php` | Medium
70 | File | `/auth/auth.php?user=1` | High
71 | File | `/b2b-supermarket/catalog/all-products` | High
72 | File | `/b2b-supermarket/shopping-cart` | High
73 | File | `/bin/boa` | Medium
74 | File | `/boaform/device_reset.cgi` | High
75 | File | `/boaform/wlan_basic_set.cgi` | High
76 | File | `/boafrm/formMapDelDevice` | High
77 | File | `/category.php` | High
78 | File | `/ccm/system/dialogs/file/delete/1/submit` | High
79 | File | `/cgi-bin/cstecgi.cgi` | High
80 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
81 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
82 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
83 | File | `/claire_blake` | High
84 | File | `/classes/Users.php?f=save` | High
85 | File | `/config,admin.jsp` | High
86 | File | `/core/config-revisions` | High
87 | File | `/currentsetting.htm` | High
88 | File | `/dashboard/message` | High
89 | ... | ... | ...

There are 789 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
