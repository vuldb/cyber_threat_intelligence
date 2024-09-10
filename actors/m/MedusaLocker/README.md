# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/add-students.php` | High
3 | File | `/addproduct.php` | High
4 | File | `/admin` | Low
5 | File | `/admin-cp/theme/editor/default` | High
6 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
7 | File | `/admin/?page=user/list` | High
8 | File | `/admin/admin-add-employee.php` | High
9 | File | `/admin/ajax.php?action=delete_user` | High
10 | File | `/admin/ajax.php?action=login` | High
11 | File | `/admin/ajax.php?action=save_settings` | High
12 | File | `/admin/category_save.php` | High
13 | File | `/admin/clients/` | High
14 | File | `/admin/config_ISCGroupNoCache.php` | High
15 | File | `/admin/config_MT.php?action=delete` | High
16 | File | `/admin/config_time_sync.php` | High
17 | File | `/admin/content` | High
18 | File | `/admin/foreigner-bwdates-reports-details.php` | High
19 | File | `/admin/foreigner-search.php` | High
20 | File | `/admin/forgot-password.php` | High
21 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
22 | File | `/admin/forms/option_lists/edit.php` | High
23 | File | `/admin/get_balance.php` | High
24 | File | `/admin/get_price.php` | High
25 | File | `/admin/index.php` | High
26 | File | `/admin/index.php?page=categories` | High
27 | File | `/admin/index.php?page=manage_product` | High
28 | File | `/admin/login.php` | High
29 | File | `/admin/manage_complaint.php` | High
30 | File | `/admin/manage_model.php` | High
31 | File | `/admin/manage_user.php` | High
32 | File | `/admin/media_folders` | High
33 | File | `/admin/member_save.php` | High
34 | File | `/admin/menu.php` | High
35 | File | `/admin/modules/product/controller.php?action=add` | High
36 | File | `/admin/mod_reports/index.php` | High
37 | File | `/admin/mod_reports/printreport.php` | High
38 | File | `/admin/mod_reservation/controller.php` | High
39 | File | `/admin/mod_reservation/index.php` | High
40 | File | `/admin/mod_room/controller.php?action=add` | High
41 | File | `/admin/mod_room/index.php` | High
42 | File | `/admin/mod_users/index.php` | High
43 | File | `/admin/normal-bwdates-reports-details.php` | High
44 | File | `/admin/normal-search.php` | High
45 | File | `/admin/orders/controller.php` | High
46 | File | `/admin/orders/index.php` | High
47 | File | `/admin/pages/` | High
48 | File | `/admin/products/index.php` | High
49 | File | `/admin/settings/index.php?page=accounts` | High
50 | File | `/admin/system.html` | High
51 | File | `/admin/template` | High
52 | File | `/admin/view_reserved.php` | High
53 | File | `/admin/view_sendlist.php` | High
54 | File | `/ajax.php` | Medium
55 | File | `/ajax.php?action=delete_block` | High
56 | File | `/ajax.php?action=load_answered` | High
57 | File | `/ajax.php?action=login` | High
58 | File | `/ajax.php?action=save_establishment` | High
59 | File | `/ajax.php?action=save_user` | High
60 | File | `/api/Common/uploadFile` | High
61 | File | `/api/deploy/upload` | High
62 | File | `/api/deploy/upload /api/database/upload` | High
63 | File | `/api/dept` | Medium
64 | File | `/api/dept/build` | High
65 | File | `/api/file/downloadfile` | High
66 | File | `/api/file/downloadUrl` | High
67 | File | `/api/file/multiDownload` | High
68 | File | `/api/role` | Medium
69 | File | `/api/v2/maps` | Medium
70 | File | `/App/Core/Extend/Function/ydLib.php` | High
71 | File | `/apply/index.php` | High
72 | File | `/assoc_table.php` | High
73 | File | `/AttendanceMonitoring/department/index.php` | High
74 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
75 | File | `/authMonitCallcenter` | High
76 | File | `/bolt/editcontent/showcases` | High
77 | File | `/book-services.php` | High
78 | File | `/branch_viewmore.php` | High
79 | File | `/candidate/controller.php` | High
80 | File | `/cap.js` | Low
81 | File | `/cgi-bin/cstecgi.cgi` | High
82 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
83 | File | `/cgi-bin/ExportSettings.sh` | High
84 | File | `/cgi-bin/photocenter_mgr.cgi` | High
85 | File | `/change_password.php` | High
86 | File | `/classes/Master.php` | High
87 | File | `/classes/Master.php?f=delete_category` | High
88 | ... | ... | ...

There are 780 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
