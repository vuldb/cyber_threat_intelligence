# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [AO](https://vuldb.com/?country.ao)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | - | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | - | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | Snake | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snake_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
2 | File | `/Account/login.php` | High
3 | File | `/actuator/heapdump` | High
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/add-ambulance.php` | High
8 | File | `/admin/add_ikev2.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/app/product.php` | High
11 | File | `/admin/app/service_crud.php` | High
12 | File | `/admin/applicants/controller.php` | High
13 | File | `/admin/bookdate.php` | High
14 | File | `/admin/booktime.php` | High
15 | File | `/admin/category/controller.php` | High
16 | File | `/Admin/changepassword.php` | High
17 | File | `/admin/clients` | High
18 | File | `/admin/company/controller.php` | High
19 | File | `/admin/company/index.php` | High
20 | File | `/admin/config_ISCGroupNoCache.php` | High
21 | File | `/admin/content` | High
22 | File | `/admin/content/data` | High
23 | File | `/admin/court` | Medium
24 | File | `/admin/div_data/delete?divId=9` | High
25 | File | `/admin/edit-admin.php` | High
26 | File | `/admin/edit_supplier.php` | High
27 | File | `/admin/employee/controller.php` | High
28 | File | `/admin/employee/index.php` | High
29 | File | `/admin/expense-type` | High
30 | File | `/admin/file/edit.do` | High
31 | File | `/admin/forgot-password.php` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/list_crl_conf` | High
34 | File | `/admin/list_resource_icon.php?action=delete` | High
35 | File | `/admin/login.php` | High
36 | File | `/admin/maintenance/manage_brand.php` | High
37 | File | `/admin/maintenance/manage_category.php` | High
38 | File | `/admin/menu/toEdit` | High
39 | File | `/admin/normal-search.php` | High
40 | File | `/admin/operations/expense_category.php` | High
41 | File | `/admin/orders/view_order.php` | High
42 | File | `/admin/product/manage_product.php` | High
43 | File | `/admin/role` | Medium
44 | File | `/admin/rooms.php` | High
45 | File | `/admin/search-directory.php.` | High
46 | File | `/admin/search.php` | High
47 | File | `/admin/tasks` | Medium
48 | File | `/admin/tax` | Medium
49 | File | `/admin/template` | High
50 | File | `/admin/twitter.php` | High
51 | File | `/admin/update-rooms.php` | High
52 | File | `/admin/update-users.php` | High
53 | File | `/admin/user-search.php` | High
54 | File | `/admin/users.php` | High
55 | File | `/adminapi/system/crud` | High
56 | File | `/adminapi/system/file/openfile` | High
57 | File | `/adminPage/conf/reload` | High
58 | File | `/adminPage/conf/saveCmd` | High
59 | File | `/adminPage/main/upload` | High
60 | File | `/adminPage/www/addOver` | High
61 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
62 | File | `/adminpanel/admin/query/loginExe.php` | High
63 | File | `/admin_class.php` | High
64 | File | `/alsdemo/ss/mediam.cgi` | High
65 | File | `/api/controllers/admin/app/ComboController.php` | High
66 | File | `/api/controllers/merchant/shop/PosterController.php` | High
67 | File | `/api/system/sessions` | High
68 | File | `/api/v1/toolbox/device/update/swap` | High
69 | File | `/application/controller/Pelanggan.php` | High
70 | File | `/application/controller/Pengeluaran.php` | High
71 | File | `/apply/index.php` | High
72 | File | `/apps/system/api/user.go` | High
73 | File | `/apps/system/router/upload.go` | High
74 | File | `/apps/system/services/role_menu.go` | High
75 | File | `/assoc_table.php` | High
76 | File | `/backend/register.php` | High
77 | File | `/billing/bill/edit/` | High
78 | File | `/bishe/register` | High
79 | File | `/bsenordering/index.php` | High
80 | File | `/cancel.php` | Medium
81 | File | `/catalog/all-products` | High
82 | File | `/cgi-bin/cstecgi.cgi` | High
83 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
84 | File | `/cgi-bin/nas_sharing.cgi` | High
85 | File | `/cgi-bin/reader` | High
86 | File | `/change-password.php` | High
87 | File | `/classes/Master.php?f=load_registration` | High
88 | File | `/classes/SystemSettings.php?f=update_settings` | High
89 | File | `/classes/Users.php?f=save` | High
90 | ... | ... | ...

There are 795 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
