# Cactus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cactus](https://vuldb.com/?actor.cactus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cactus](https://vuldb.com/?actor.cactus)

## Campaigns

The following _campaigns_ are known and can be associated with Cactus:

* CVE-2023-38035
* CVE-2023-41266 / CVE-2023-41265 / CVE-2023-48365

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cactus:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cactus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.227.203.210](https://vuldb.com/?ip.23.227.203.210) | 23-227-203-210.static.hvvc.us | - | High
2 | [45.61.136.79](https://vuldb.com/?ip.45.61.136.79) | - | CVE-2023-38035 | High
3 | [45.61.136.127](https://vuldb.com/?ip.45.61.136.127) | - | CVE-2023-38035 | High
4 | [45.61.137.65](https://vuldb.com/?ip.45.61.137.65) | - | - | High
5 | [45.61.138.99](https://vuldb.com/?ip.45.61.138.99) | - | CVE-2023-38035 | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cactus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cactus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
2 | File | `/actuator/heapdump` | High
3 | File | `/admin-manage-user.php` | High
4 | File | `/admin/?page=user/list` | High
5 | File | `/Admin/add-admin.php` | High
6 | File | `/admin/add-ambulance.php` | High
7 | File | `/admin/add_ikev2.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/admin.php` | High
10 | File | `/admin/applicants/controller.php` | High
11 | File | `/admin/applicants/index.php` | High
12 | File | `/admin/bookdate.php` | High
13 | File | `/admin/booking-bwdates-reports-details.php` | High
14 | File | `/admin/booktime.php` | High
15 | File | `/admin/case-status` | High
16 | File | `/admin/case-type` | High
17 | File | `/admin/category/controller.php` | High
18 | File | `/Admin/changepassword.php` | High
19 | File | `/admin/clients` | High
20 | File | `/admin/company/controller.php` | High
21 | File | `/admin/company/index.php` | High
22 | File | `/admin/config_Anticrack.php` | High
23 | File | `/admin/config_ISCGroupNoCache.php` | High
24 | File | `/admin/content` | High
25 | File | `/admin/court` | Medium
26 | File | `/admin/court-type` | High
27 | File | `/admin/div_data/delete?divId=9` | High
28 | File | `/admin/employee/controller.php` | High
29 | File | `/admin/employee/index.php` | High
30 | File | `/admin/expense-type` | High
31 | File | `/admin/foreigner-bwdates-reports-details.php` | High
32 | File | `/admin/foreigner-search.php` | High
33 | File | `/admin/forgot-password.php` | High
34 | File | `/admin/index.php` | High
35 | File | `/admin/index.php?page=categories` | High
36 | File | `/admin/index.php?page=manage_product` | High
37 | File | `/admin/list_crl_conf` | High
38 | File | `/admin/list_resource_icon.php?action=delete` | High
39 | File | `/admin/login.php` | High
40 | File | `/admin/maintenance/manage_brand.php` | High
41 | File | `/admin/maintenance/manage_category.php` | High
42 | File | `/admin/menu/toEdit` | High
43 | File | `/admin/normal-bwdates-reports-details.php` | High
44 | File | `/admin/normal-search.php` | High
45 | File | `/admin/role` | Medium
46 | File | `/admin/rooms.php` | High
47 | File | `/admin/search-directory.php.` | High
48 | File | `/admin/search.php` | High
49 | File | `/admin/tasks` | Medium
50 | File | `/admin/tax` | Medium
51 | File | `/admin/template` | High
52 | File | `/admin/twitter.php` | High
53 | File | `/admin/update-rooms.php` | High
54 | File | `/admin/update-users.php` | High
55 | File | `/Admin/user-record.php` | High
56 | File | `/admin/user-search.php` | High
57 | File | `/admin/user/controller.php` | High
58 | File | `/admin/user/index.php` | High
59 | File | `/admin/users.php` | High
60 | File | `/admin/vendor` | High
61 | File | `/adminPage/conf/reload` | High
62 | File | `/adminPage/conf/saveCmd` | High
63 | File | `/adminPage/main/upload` | High
64 | File | `/adminPage/www/addOver` | High
65 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
66 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
67 | File | `/adminpanel/admin/query/loginExe.php` | High
68 | File | `/admin_class.php` | High
69 | File | `/ajax.php` | Medium
70 | File | `/api/client/editemedia.php` | High
71 | File | `/application/controller/Pelanggan.php` | High
72 | File | `/application/controller/Pengeluaran.php` | High
73 | File | `/apply/index.php` | High
74 | File | `/apps/system/api/user.go` | High
75 | File | `/apps/system/router/upload.go` | High
76 | File | `/apps/system/services/role_menu.go` | High
77 | File | `/assoc_table.php` | High
78 | File | `/backend/register.php` | High
79 | File | `/billing/bill/edit/` | High
80 | File | `/bishe/register` | High
81 | File | `/bsenordering/index.php` | High
82 | File | `/cancel.php` | Medium
83 | File | `/catalog/all-products` | High
84 | File | `/cgi-bin/cstecgi.cgi` | High
85 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
86 | File | `/cgi-bin/nas_sharing.cgi` | High
87 | File | `/cgi-bin/wlogin.cgi` | High
88 | File | `/change-password.php` | High
89 | File | `/classes/Master.php?f=load_registration` | High
90 | File | `/classes/Master.php?f=save_category` | High
91 | File | `/classes/SystemSettings.php?f=update_settings` | High
92 | File | `/classes/Users.php?f=save` | High
93 | File | `/control/addcase_stage.php` | High
94 | ... | ... | ...

There are 830 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://northwave-cybersecurity.com/whitepapers-articles/pricksense-how-cactus-exploits-qlik-sense
* https://www.arcticwolf.com/resources/blog/qlik-sense-exploited-in-cactus-ransomware-campaign/
* https://www.bitdefender.com/blog/businessinsights/cactus-analyzing-a-coordinated-ransomware-attack-on-corporate-networks/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
