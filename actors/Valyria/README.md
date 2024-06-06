# Valyria - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Valyria](https://vuldb.com/?actor.valyria). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.valyria](https://vuldb.com/?actor.valyria)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Valyria:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Valyria.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.248.159.254](https://vuldb.com/?ip.8.248.159.254) | - | - | High
2 | [8.249.221.254](https://vuldb.com/?ip.8.249.221.254) | - | - | High
3 | [8.253.45.248](https://vuldb.com/?ip.8.253.45.248) | - | - | High
4 | [8.253.131.111](https://vuldb.com/?ip.8.253.131.111) | - | - | High
5 | [12.139.45.113](https://vuldb.com/?ip.12.139.45.113) | - | - | High
6 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
7 | [45.60.22.20](https://vuldb.com/?ip.45.60.22.20) | - | - | High
8 | [50.62.26.129](https://vuldb.com/?ip.50.62.26.129) | ip-50-62-26-129.ip.secureserver.net | - | High
9 | [54.164.54.19](https://vuldb.com/?ip.54.164.54.19) | ec2-54-164-54-19.compute-1.amazonaws.com | - | Medium
10 | [64.185.227.155](https://vuldb.com/?ip.64.185.227.155) | 64-185-227-155.static.webnx.com | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Valyria_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Valyria. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
3 | File | `/Account/login.php` | High
4 | File | `/actuator/heapdump` | High
5 | File | `/admin-manage-user.php` | High
6 | File | `/admin/` | Low
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/action/add_con.php` | High
9 | File | `/admin/action/new-father.php` | High
10 | File | `/admin/action/new-feed.php` | High
11 | File | `/admin/add-ambulance.php` | High
12 | File | `/admin/add_ikev2.php` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/admin/ajax.php?action=confirm_order` | High
15 | File | `/admin/app/product.php` | High
16 | File | `/admin/app/service_crud.php` | High
17 | File | `/admin/applicants/controller.php` | High
18 | File | `/admin/article/article-edit-run.php` | High
19 | File | `/admin/bookdate.php` | High
20 | File | `/admin/booktime.php` | High
21 | File | `/admin/book_add.php` | High
22 | File | `/admin/book_row.php` | High
23 | File | `/admin/borrow_add.php` | High
24 | File | `/admin/bwdates-report-details.php` | High
25 | File | `/admin/category/controller.php` | High
26 | File | `/admin/category_row.php` | High
27 | File | `/Admin/changepassword.php` | High
28 | File | `/admin/cms_admin.php` | High
29 | File | `/admin/company/controller.php` | High
30 | File | `/admin/company/index.php` | High
31 | File | `/admin/config_ISCGroupNoCache.php` | High
32 | File | `/admin/course.php` | High
33 | File | `/admin/courses/manage_course.php` | High
34 | File | `/admin/div_data/delete?divId=9` | High
35 | File | `/admin/edit-admin.php` | High
36 | File | `/admin/edit_supplier.php` | High
37 | File | `/admin/edit_teacher.php` | High
38 | File | `/admin/employee/controller.php` | High
39 | File | `/admin/employee/index.php` | High
40 | File | `/admin/forgot-password.php` | High
41 | File | `/admin/leancloud.php` | High
42 | File | `/admin/list_crl_conf` | High
43 | File | `/admin/list_resource_icon.php?action=delete` | High
44 | File | `/Admin/login.php` | High
45 | File | `/admin/login.php` | High
46 | File | `/admin/maintenance/manage_category.php` | High
47 | File | `/admin/makehtml_freelist_action.php` | High
48 | File | `/admin/manage-pages.php` | High
49 | File | `/admin/menu/toEdit` | High
50 | File | `/Admin/News.php` | High
51 | File | `/admin/operations/expense_category.php` | High
52 | File | `/admin/orders/view_order.php` | High
53 | File | `/admin/pages/edit_chicken.php` | High
54 | File | `/admin/pages/update_go.php` | High
55 | File | `/admin/pages/yearlevel.php` | High
56 | File | `/admin/php/crud.php` | High
57 | File | `/admin/product/manage_product.php` | High
58 | File | `/admin/rooms.php` | High
59 | File | `/admin/search.php` | High
60 | File | `/admin/settings/` | High
61 | File | `/admin/students/manage_academic.php` | High
62 | File | `/admin/students/update_status.php` | High
63 | File | `/admin/subject.php` | High
64 | File | `/admin/theme-edit.php` | High
65 | File | `/admin/twitter.php` | High
66 | File | `/admin/update-rooms.php` | High
67 | File | `/admin/update-users.php` | High
68 | File | `/admin/user-search.php` | High
69 | File | `/admin/users.php` | High
70 | File | `/adminapi/system/crud` | High
71 | File | `/adminapi/system/file/openfile` | High
72 | File | `/adminPage/conf/reload` | High
73 | File | `/adminPage/conf/saveCmd` | High
74 | File | `/adminPage/main/upload` | High
75 | File | `/adminPage/www/addOver` | High
76 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
77 | File | `/adminpanel/admin/query/loginExe.php` | High
78 | File | `/admin_route/dec_service_credits.php` | High
79 | File | `/adplanet/PlanetUser` | High
80 | File | `/ample/app/action/edit_product.php` | High
81 | File | `/ample/app/ajax/member_data.php` | High
82 | File | `/api.php` | Medium
83 | File | `/api/authentication/login` | High
84 | File | `/api/controllers/admin/app/AppController.php` | High
85 | File | `/api/controllers/common/UploadsController.php` | High
86 | File | `/api/DataDictionary/GetItemList` | High
87 | File | `/api/v1/toolbox/device/update/swap` | High
88 | File | `/application/controller/Pelanggan.php` | High
89 | File | `/application/controller/Pengeluaran.php` | High
90 | File | `/application/index/controller/Datament.php` | High
91 | File | `/application/index/controller/Pay.php` | High
92 | File | `/application/index/controller/Screen.php` | High
93 | File | `/application/pay/controller/Api.php` | High
94 | File | `/apply/index.php` | High
95 | File | `/apps/reg_go.php` | High
96 | File | `/apps/system/api/user.go` | High
97 | File | `/apps/system/router/upload.go` | High
98 | File | `/apps/system/services/role_menu.go` | High
99 | File | `/att_add.php` | Medium
100 | File | `/autheditpwd.php` | High
101 | File | `/b2b-supermarket/catalog/all-products` | High
102 | File | `/backend/register.php` | High
103 | File | `/billing/bill/edit/` | High
104 | File | `/bin/boa` | Medium
105 | File | `/bishe/register` | High
106 | File | `/boaform/device_reset.cgi` | High
107 | File | `/boaform/wlan_basic_set.cgi` | High
108 | File | `/boafrm/formMapDelDevice` | High
109 | File | `/bsenordering/index.php` | High
110 | File | `/cancel.php` | Medium
111 | File | `/catalog/all-products` | High
112 | File | `/category.php` | High
113 | File | `/cgi-bin/` | Medium
114 | File | `/cgi-bin/cstecgi.cgi` | High
115 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
116 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
117 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
118 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
119 | File | `/cgi-bin/nas_sharing.cgi` | High
120 | File | `/change-password.php` | High
121 | File | `/classes/Master.php` | High
122 | ... | ... | ...

There are 1081 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-0928-1005.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-1005-1012.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1214-1221.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0118-0125.html
* https://blog.talosintelligence.com/2019/02/threat-roundup-0208-0215.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0221-0228.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-0925-1002.html
* https://blog.talosintelligence.com/threat-roundup-0505-0512-3/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
