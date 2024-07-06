# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
2 | File | `/actuator/heapdump` | High
3 | File | `/addproduct.php` | High
4 | File | `/admin` | Low
5 | File | `/admin-manage-user.php` | High
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/add-ambulance.php` | High
8 | File | `/admin/add_ikev2.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/ajax.php?action=delete_user` | High
11 | File | `/admin/ajax.php?action=save_settings` | High
12 | File | `/admin/applicants/controller.php` | High
13 | File | `/admin/applicants/index.php` | High
14 | File | `/admin/bookdate.php` | High
15 | File | `/admin/booking-bwdates-reports-details.php` | High
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
43 | File | `/admin/modules/product/controller.php?action=add` | High
44 | File | `/admin/mod_room/controller.php?action=add` | High
45 | File | `/admin/normal-bwdates-reports-details.php` | High
46 | File | `/admin/normal-search.php` | High
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
57 | File | `/Admin/user-record.php` | High
58 | File | `/admin/user-search.php` | High
59 | File | `/admin/user/controller.php` | High
60 | File | `/admin/users.php` | High
61 | File | `/admin/vendor` | High
62 | File | `/admin/view_sendlist.php` | High
63 | File | `/adminPage/conf/reload` | High
64 | File | `/adminPage/conf/saveCmd` | High
65 | File | `/adminPage/main/upload` | High
66 | File | `/adminPage/www/addOver` | High
67 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
68 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
69 | File | `/adminpanel/admin/query/loginExe.php` | High
70 | File | `/admin_class.php` | High
71 | File | `/api/client/editemedia.php` | High
72 | File | `/api/v1/toolbox/device/update/swap` | High
73 | File | `/api/v2/maps` | Medium
74 | File | `/application/controller/Pelanggan.php` | High
75 | File | `/application/controller/Pengeluaran.php` | High
76 | File | `/apply/index.php` | High
77 | File | `/apps/system/api/user.go` | High
78 | File | `/apps/system/router/upload.go` | High
79 | File | `/apps/system/services/role_menu.go` | High
80 | File | `/assoc_table.php` | High
81 | File | `/backend/register.php` | High
82 | File | `/billing/bill/edit/` | High
83 | File | `/bishe/register` | High
84 | File | `/book-services.php` | High
85 | File | `/bsenordering/index.php` | High
86 | File | `/cancel.php` | Medium
87 | File | `/catalog/all-products` | High
88 | File | `/cgi-bin/cstecgi.cgi` | High
89 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
90 | File | `/cgi-bin/nas_sharing.cgi` | High
91 | File | `/change-password.php` | High
92 | File | `/classes/Master.php?f=delete_category` | High
93 | File | `/classes/Master.php?f=load_registration` | High
94 | File | `/classes/Master.php?f=log_employee` | High
95 | File | `/classes/Master.php?f=log_visitor` | High
96 | File | `/classes/SystemSettings.php?f=update_settings` | High
97 | File | `/classes/Users.php?f=delete` | High
98 | File | `/classes/Users.php?f=register_user` | High
99 | File | `/classes/Users.php?f=save` | High
100 | File | `/conf/app.conf` | High
101 | File | `/control/addcase_stage.php` | High
102 | File | `/control/deactivate_case.php` | High
103 | File | `/control/register_case.php` | High
104 | ... | ... | ...

There are 918 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
