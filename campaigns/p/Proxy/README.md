# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

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

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
2 | File | `/Account/login.php` | High
3 | File | `/actuator/heapdump` | High
4 | File | `/admin` | Low
5 | File | `/admin-manage-user.php` | High
6 | File | `/admin/` | Low
7 | File | `/admin/?page=user/list` | High
8 | File | `/admin/add-ambulance.php` | High
9 | File | `/admin/add_ikev2.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/app/product.php` | High
12 | File | `/admin/app/profile_crud.php` | High
13 | File | `/admin/app/service_crud.php` | High
14 | File | `/admin/applicants/controller.php` | High
15 | File | `/admin/bookdate.php` | High
16 | File | `/admin/booktime.php` | High
17 | File | `/admin/category/controller.php` | High
18 | File | `/Admin/changepassword.php` | High
19 | File | `/admin/clients` | High
20 | File | `/admin/company/controller.php` | High
21 | File | `/admin/company/index.php` | High
22 | File | `/admin/config_ISCGroupNoCache.php` | High
23 | File | `/admin/config_MT.php?action=delete` | High
24 | File | `/admin/content` | High
25 | File | `/admin/court` | Medium
26 | File | `/admin/div_data/delete?divId=9` | High
27 | File | `/admin/edit-admin.php` | High
28 | File | `/admin/edit_supplier.php` | High
29 | File | `/admin/employee/controller.php` | High
30 | File | `/admin/employee/index.php` | High
31 | File | `/admin/expense-type` | High
32 | File | `/admin/foreigner-bwdates-reports-details.php` | High
33 | File | `/admin/forgot-password.php` | High
34 | File | `/admin/index.php` | High
35 | File | `/admin/index.php?page=manage_product` | High
36 | File | `/admin/list_crl_conf` | High
37 | File | `/admin/list_resource_icon.php?action=delete` | High
38 | File | `/admin/login.php` | High
39 | File | `/admin/maintenance/manage_brand.php` | High
40 | File | `/admin/maintenance/manage_category.php` | High
41 | File | `/admin/menu/toEdit` | High
42 | File | `/admin/mod_room/controller.php?action=add` | High
43 | File | `/admin/normal-search.php` | High
44 | File | `/admin/operations/expense_category.php` | High
45 | File | `/admin/orders/view_order.php` | High
46 | File | `/admin/product/manage_product.php` | High
47 | File | `/admin/role` | Medium
48 | File | `/admin/rooms.php` | High
49 | File | `/admin/search-directory.php.` | High
50 | File | `/admin/search.php` | High
51 | File | `/admin/tasks` | Medium
52 | File | `/admin/tax` | Medium
53 | File | `/admin/template` | High
54 | File | `/admin/twitter.php` | High
55 | File | `/admin/update-rooms.php` | High
56 | File | `/admin/update-users.php` | High
57 | File | `/admin/user-search.php` | High
58 | File | `/admin/users.php` | High
59 | File | `/adminapi/system/crud` | High
60 | File | `/adminapi/system/file/openfile` | High
61 | File | `/adminPage/conf/reload` | High
62 | File | `/adminPage/conf/saveCmd` | High
63 | File | `/adminPage/main/upload` | High
64 | File | `/adminPage/www/addOver` | High
65 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
66 | File | `/adminpanel/admin/query/loginExe.php` | High
67 | File | `/admin_class.php` | High
68 | File | `/api/clusters/local/topics/{topic}/messages` | High
69 | File | `/api/controllers/admin/app/AppController.php` | High
70 | File | `/api/controllers/common/UploadsController.php` | High
71 | File | `/API/info` | Medium
72 | File | `/api/v1/toolbox/device/update/swap` | High
73 | File | `/api/v2/maps` | Medium
74 | File | `/application/controller/Pelanggan.php` | High
75 | File | `/application/controller/Pengeluaran.php` | High
76 | File | `/application/index/controller/Pay.php` | High
77 | File | `/application/index/controller/Screen.php` | High
78 | File | `/apply/index.php` | High
79 | File | `/apps/system/api/user.go` | High
80 | File | `/apps/system/router/upload.go` | High
81 | File | `/apps/system/services/role_menu.go` | High
82 | File | `/assoc_table.php` | High
83 | File | `/att_add.php` | Medium
84 | File | `/backend/register.php` | High
85 | File | `/billing/bill/edit/` | High
86 | File | `/bishe/register` | High
87 | File | `/book-services.php` | High
88 | File | `/bsenordering/index.php` | High
89 | File | `/cancel.php` | Medium
90 | File | `/catalog/all-products` | High
91 | File | `/cgi-bin/cstecgi.cgi` | High
92 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
93 | File | `/cgi-bin/nas_sharing.cgi` | High
94 | File | `/change-password.php` | High
95 | File | `/Cinema-Reservation/booking.php` | High
96 | File | `/classes/Master.php?f=load_registration` | High
97 | File | `/classes/Master.php?f=log_employee` | High
98 | File | `/classes/Master.php?f=log_visitor` | High
99 | File | `/classes/SystemSettings.php?f=update_settings` | High
100 | File | `/classes/Users.php?f=delete` | High
101 | File | `/classes/Users.php?f=save` | High
102 | ... | ... | ...

There are 901 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
