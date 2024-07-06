# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Wocao_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Wocao or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Wocao](https://vuldb.com/?actor.wocao) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | [Wocao](https://vuldb.com/?actor.wocao) | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | [Wocao](https://vuldb.com/?actor.wocao) | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | [Wocao](https://vuldb.com/?actor.wocao) | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | [Wocao](https://vuldb.com/?actor.wocao) | Medium
5 | [4.96.46.65](https://vuldb.com/?ip.4.96.46.65) | - | [Wocao](https://vuldb.com/?actor.wocao) | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
3 | File | `/Account/login.php` | High
4 | File | `/actuator/heapdump` | High
5 | File | `/addproduct.php` | High
6 | File | `/admin` | Low
7 | File | `/admin-manage-user.php` | High
8 | File | `/admin/` | Low
9 | File | `/admin/?page=user/list` | High
10 | File | `/admin/action/add_con.php` | High
11 | File | `/admin/action/new-father.php` | High
12 | File | `/admin/action/new-feed.php` | High
13 | File | `/admin/add-ambulance.php` | High
14 | File | `/admin/add_ikev2.php` | High
15 | File | `/admin/admin-profile.php` | High
16 | File | `/admin/ajax.php?action=delete_user` | High
17 | File | `/admin/ajax.php?action=save_settings` | High
18 | File | `/admin/app/product.php` | High
19 | File | `/admin/app/service_crud.php` | High
20 | File | `/admin/applicants/controller.php` | High
21 | File | `/admin/bookdate.php` | High
22 | File | `/admin/booktime.php` | High
23 | File | `/admin/category/controller.php` | High
24 | File | `/Admin/changepassword.php` | High
25 | File | `/admin/clients` | High
26 | File | `/admin/company/controller.php` | High
27 | File | `/admin/company/index.php` | High
28 | File | `/admin/config_ISCGroupNoCache.php` | High
29 | File | `/admin/config_MT.php?action=delete` | High
30 | File | `/admin/content` | High
31 | File | `/admin/court` | Medium
32 | File | `/admin/div_data/delete?divId=9` | High
33 | File | `/admin/edit-admin.php` | High
34 | File | `/admin/edit_supplier.php` | High
35 | File | `/admin/employee/controller.php` | High
36 | File | `/admin/employee/index.php` | High
37 | File | `/admin/expense-type` | High
38 | File | `/admin/foreigner-bwdates-reports-details.php` | High
39 | File | `/admin/forgot-password.php` | High
40 | File | `/admin/index.php` | High
41 | File | `/admin/index.php?page=manage_product` | High
42 | File | `/admin/list_crl_conf` | High
43 | File | `/admin/list_resource_icon.php?action=delete` | High
44 | File | `/Admin/login.php` | High
45 | File | `/admin/login.php` | High
46 | File | `/admin/maintenance/manage_brand.php` | High
47 | File | `/admin/maintenance/manage_category.php` | High
48 | File | `/admin/makehtml_freelist_action.php` | High
49 | File | `/admin/menu/toEdit` | High
50 | File | `/admin/mod_room/controller.php?action=add` | High
51 | File | `/admin/normal-search.php` | High
52 | File | `/admin/operations/expense_category.php` | High
53 | File | `/admin/orders/view_order.php` | High
54 | File | `/admin/pages/edit_chicken.php` | High
55 | File | `/admin/pages/update_go.php` | High
56 | File | `/admin/product/manage_product.php` | High
57 | File | `/admin/role` | Medium
58 | File | `/admin/rooms.php` | High
59 | File | `/admin/search-directory.php.` | High
60 | File | `/admin/search.php` | High
61 | File | `/admin/tasks` | Medium
62 | File | `/admin/tax` | Medium
63 | File | `/admin/template` | High
64 | File | `/admin/twitter.php` | High
65 | File | `/admin/update-rooms.php` | High
66 | File | `/admin/update-users.php` | High
67 | File | `/admin/user-search.php` | High
68 | File | `/admin/users.php` | High
69 | File | `/admin/view_sendlist.php` | High
70 | File | `/adminapi/system/crud` | High
71 | File | `/adminapi/system/file/openfile` | High
72 | File | `/adminPage/conf/reload` | High
73 | File | `/adminPage/conf/saveCmd` | High
74 | File | `/adminPage/main/upload` | High
75 | File | `/adminPage/www/addOver` | High
76 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
77 | File | `/adminpanel/admin/query/loginExe.php` | High
78 | File | `/admin_class.php` | High
79 | File | `/admin_route/dec_service_credits.php` | High
80 | File | `/api.php` | Medium
81 | File | `/api/controllers/admin/app/AppController.php` | High
82 | File | `/api/controllers/common/UploadsController.php` | High
83 | File | `/api/v1/toolbox/device/update/swap` | High
84 | File | `/api/v2/maps` | Medium
85 | File | `/application/controller/Pelanggan.php` | High
86 | File | `/application/controller/Pengeluaran.php` | High
87 | File | `/application/index/controller/Datament.php` | High
88 | File | `/application/index/controller/Pay.php` | High
89 | File | `/application/index/controller/Screen.php` | High
90 | File | `/application/pay/controller/Api.php` | High
91 | File | `/apply/index.php` | High
92 | File | `/apps/reg_go.php` | High
93 | File | `/apps/system/api/user.go` | High
94 | File | `/apps/system/router/upload.go` | High
95 | File | `/apps/system/services/role_menu.go` | High
96 | File | `/assoc_table.php` | High
97 | File | `/att_add.php` | Medium
98 | File | `/backend/register.php` | High
99 | File | `/billing/bill/edit/` | High
100 | File | `/bishe/register` | High
101 | File | `/boafrm/formMapDelDevice` | High
102 | File | `/book-services.php` | High
103 | File | `/bsenordering/index.php` | High
104 | File | `/cancel.php` | Medium
105 | File | `/catalog/all-products` | High
106 | File | `/cgi-bin/cstecgi.cgi` | High
107 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
108 | File | `/cgi-bin/nas_sharing.cgi` | High
109 | File | `/change-password.php` | High
110 | File | `/classes/Master.php?f=delete_category` | High
111 | File | `/classes/Master.php?f=load_registration` | High
112 | File | `/classes/Master.php?f=log_employee` | High
113 | File | `/classes/Master.php?f=log_visitor` | High
114 | File | `/classes/SystemSettings.php?f=update_settings` | High
115 | ... | ... | ...

There are 1023 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/fox-it/operation-wocao
* https://github.com/fox-it/operation-wocao/blob/master/hashes.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
