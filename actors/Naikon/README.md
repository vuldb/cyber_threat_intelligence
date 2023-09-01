# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Naikon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [47.241.127.190](https://vuldb.com/?ip.47.241.127.190) | - | - | High
2 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | Camerashy | High
3 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | Camerashy | High
4 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | Camerashy | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Naikon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-27, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.cpr/` | Low
2 | File | `/?p=products` | Medium
3 | File | `/?r=report/api/getlist` | High
4 | File | `/admin.php/appcenter/local.html?type=addon` | High
5 | File | `/admin.php?action=deletepage&var1` | High
6 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
7 | File | `/admin/?page=maintenance/brand` | High
8 | File | `/admin/?page=user` | High
9 | File | `/admin/addproduct.php` | High
10 | File | `/admin/add_user_modal.php` | High
11 | File | `/admin/ajax.php` | High
12 | File | `/admin/api/theme-edit/` | High
13 | File | `/admin/assign/assign.php` | High
14 | File | `/admin/ballot_up.php` | High
15 | File | `/admin/bookings/manage_booking.php` | High
16 | File | `/admin/bookings/view_booking.php` | High
17 | File | `/admin/bookings/view_details.php` | High
18 | File | `/admin/candidates_row.php` | High
19 | File | `/admin/cashadvance_row.php` | High
20 | File | `/admin/categories/manage_category.php` | High
21 | File | `/admin/configurations/userInfo` | High
22 | File | `/admin/curriculum/view_curriculum.php` | High
23 | File | `/admin/deduction_edit.php` | High
24 | File | `/admin/departments/view_department.php` | High
25 | File | `/admin/edit_product.php` | High
26 | File | `/admin/fields/manage_field.php` | High
27 | File | `/admin/forgot-password.php` | High
28 | File | `/admin/getallarticleinfo` | High
29 | File | `/admin/index.php` | High
30 | File | `/admin/inquiries/view_inquiry.php` | High
31 | File | `/admin/login.php` | High
32 | File | `/admin/maintenance/brand.php` | High
33 | File | `/admin/maintenance/manage_category.php` | High
34 | File | `/admin/modal_add_product.php` | High
35 | File | `/admin/offenses/view_details.php` | High
36 | File | `/admin/positions_row.php` | High
37 | File | `/admin/product/manage.php` | High
38 | File | `/admin/products/manage_product.php` | High
39 | File | `/admin/project/update/2` | High
40 | File | `/admin/read.php?mudi=announContent` | High
41 | File | `/admin/reg.php` | High
42 | File | `/admin/reportupload.aspx` | High
43 | File | `/admin/robot/approval/list` | High
44 | File | `/admin/router.php` | High
45 | File | `/admin/sales/view_details.php` | High
46 | File | `/admin/save_teacher.php` | High
47 | File | `/admin/services/manage_service.php` | High
48 | File | `/admin/services/view_service.php` | High
49 | File | `/admin/students/view_details.php` | High
50 | File | `/admin/sys_sql_query.php` | High
51 | File | `/admin/transactions/track_shipment.php` | High
52 | File | `/admin/upload` | High
53 | File | `/admin/user/manage_user.php` | High
54 | File | `/admin/vote_edit.php` | High
55 | File | `/admin_system/api.php` | High
56 | File | `/analysisProject/pagingQueryData` | High
57 | File | `/api/admin/store/product/save` | High
58 | File | `/api/admin/system/store/order/list` | High
59 | File | `/api/ping` | Medium
60 | File | `/api/upload` | Medium
61 | File | `/api/wechat/app_auth` | High
62 | File | `/api?path=files` | High
63 | File | `/Applications/Utilities/Terminal` | High
64 | File | `/arch/x86/mm/cpu_entry_area.c` | High
65 | File | `/author_posts.php` | High
66 | File | `/back/index.php/user/User/?1` | High
67 | File | `/bin/boa` | Medium
68 | File | `/blog` | Low
69 | File | `/blog-single.php` | High
70 | File | `/booking/show_bookings/` | High
71 | File | `/boot` | Low
72 | File | `/browse` | Low
73 | File | `/bsenordering/index.php` | High
74 | File | `/category.php` | High
75 | File | `/cgi-bin/adm.cgi` | High
76 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
77 | File | `/change-language/de_DE` | High
78 | File | `/classes/Login.php` | High
79 | File | `/classes/Master.php` | High
80 | File | `/classes/Master.php?f=delete_category` | High
81 | File | `/classes/Master.php?f=delete_inquiry` | High
82 | File | `/classes/Master.php?f=delete_item` | High
83 | File | `/classes/Master.php?f=save_category` | High
84 | File | `/classes/Master.php?f=save_inquiry` | High
85 | File | `/classes/Master.php?f=save_item` | High
86 | File | `/classes/Master.php?f=save_service` | High
87 | File | `/classes/Master.php?f=save_sub_category` | High
88 | File | `/classes/Master.php?f=update_order_status` | High
89 | ... | ... | ...

There are 786 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf
* https://1275.ru/ioc/164/lotus-panda-apt-iocs/
* https://research.checkpoint.com/2020/naikon-apt-cyber-espionage-reloaded/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.04.23(1)/NAIKON.pdf
* https://www.threatminer.org/report.php?q=TheNaikonAPT-MsnMM1.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
