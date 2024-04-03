# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
2 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
3 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
4 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
5 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/Account/login.php` | High
3 | File | `/add_members.php` | High
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/action/add_con.php` | High
8 | File | `/admin/action/new-father.php` | High
9 | File | `/admin/action/new-feed.php` | High
10 | File | `/admin/add-ambulance.php` | High
11 | File | `/admin/admin-profile.php` | High
12 | File | `/admin/ajax.php?action=confirm_order` | High
13 | File | `/admin/app/product.php` | High
14 | File | `/admin/app/service_crud.php` | High
15 | File | `/admin/applicants/controller.php` | High
16 | File | `/admin/applicants/index.php` | High
17 | File | `/admin/article/article-edit-run.php` | High
18 | File | `/admin/bookdate.php` | High
19 | File | `/admin/booking-bwdates-reports-details.php` | High
20 | File | `/admin/booktime.php` | High
21 | File | `/admin/book_add.php` | High
22 | File | `/admin/book_row.php` | High
23 | File | `/admin/borrow_add.php` | High
24 | File | `/admin/bwdates-report-details.php` | High
25 | File | `/admin/category/controller.php` | High
26 | File | `/admin/category_row.php` | High
27 | File | `/admin/cms_admin.php` | High
28 | File | `/admin/company/controller.php` | High
29 | File | `/admin/company/index.php` | High
30 | File | `/admin/course.php` | High
31 | File | `/admin/courses/manage_course.php` | High
32 | File | `/admin/div_data/delete?divId=9` | High
33 | File | `/admin/edit-admin.php` | High
34 | File | `/admin/edit_supplier.php` | High
35 | File | `/admin/edit_teacher.php` | High
36 | File | `/admin/employee/controller.php` | High
37 | File | `/admin/employee/index.php` | High
38 | File | `/admin/forgot-password.php` | High
39 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
40 | File | `/admin/leancloud.php` | High
41 | File | `/admin/list_resource_icon.php?action=delete` | High
42 | File | `/Admin/login.php` | High
43 | File | `/admin/login.php` | High
44 | File | `/admin/maintenance/manage_category.php` | High
45 | File | `/admin/makehtml_freelist_action.php` | High
46 | File | `/admin/manage-pages.php` | High
47 | File | `/admin/menu/toEdit` | High
48 | File | `/Admin/News.php` | High
49 | File | `/admin/operations/expense_category.php` | High
50 | File | `/admin/orders/view_order.php` | High
51 | File | `/admin/pages/edit_chicken.php` | High
52 | File | `/admin/pages/update_go.php` | High
53 | File | `/admin/pages/yearlevel.php` | High
54 | File | `/admin/php/crud.php` | High
55 | File | `/admin/product/manage_product.php` | High
56 | File | `/admin/regester.php` | High
57 | File | `/admin/rooms.php` | High
58 | File | `/admin/search.php` | High
59 | File | `/admin/settings/` | High
60 | File | `/admin/students.php` | High
61 | File | `/admin/students/manage_academic.php` | High
62 | File | `/admin/students/update_status.php` | High
63 | File | `/admin/subject.php` | High
64 | File | `/admin/theme-edit.php` | High
65 | File | `/admin/update-rooms.php` | High
66 | File | `/admin/update-users.php` | High
67 | File | `/admin/user-search.php` | High
68 | File | `/admin/user/controller.php` | High
69 | File | `/admin/users.php` | High
70 | File | `/adminapi/system/crud` | High
71 | File | `/adminapi/system/file/openfile` | High
72 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
73 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
74 | File | `/adminpanel/admin/query/loginExe.php` | High
75 | File | `/admin_route/dec_service_credits.php` | High
76 | File | `/adplanet/PlanetUser` | High
77 | File | `/ample/app/action/edit_product.php` | High
78 | File | `/ample/app/ajax/member_data.php` | High
79 | File | `/api.php` | Medium
80 | File | `/api/authentication/login` | High
81 | File | `/api/client/editemedia.php` | High
82 | File | `/api/controllers/admin/app/AppController.php` | High
83 | File | `/api/controllers/common/UploadsController.php` | High
84 | File | `/api/controllers/merchant/design/MaterialController.php` | High
85 | File | `/api/DataDictionary/GetItemList` | High
86 | File | `/api/v1/toolbox/device/update/swap` | High
87 | File | `/app/middleware/TokenVerify.php` | High
88 | File | `/application/index/controller/Datament.php` | High
89 | File | `/application/index/controller/Pay.php` | High
90 | File | `/application/index/controller/Screen.php` | High
91 | File | `/application/pay/controller/Api.php` | High
92 | File | `/apply/index.php` | High
93 | File | `/apps/login_auth.php` | High
94 | File | `/apps/reg_go.php` | High
95 | File | `/apps/system/api/user.go` | High
96 | File | `/apps/system/router/upload.go` | High
97 | File | `/apps/system/services/role_menu.go` | High
98 | File | `/att_add.php` | Medium
99 | File | `/autheditpwd.php` | High
100 | File | `/b2b-supermarket/catalog/all-products` | High
101 | File | `/billing/bill/edit/` | High
102 | File | `/bin/boa` | Medium
103 | File | `/bishe/register` | High
104 | File | `/boaform/device_reset.cgi` | High
105 | File | `/boaform/wlan_basic_set.cgi` | High
106 | File | `/boafrm/formMapDelDevice` | High
107 | File | `/bsenordering/index.php` | High
108 | File | `/cancel.php` | Medium
109 | File | `/category.php` | High
110 | File | `/cgi-bin/` | Medium
111 | File | `/cgi-bin/cstecgi.cgi` | High
112 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
113 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
114 | ... | ... | ...

There are 1015 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.bleepingcomputer.com/news/security/medusalocker-ransomware-wants-its-share-of-your-money/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
