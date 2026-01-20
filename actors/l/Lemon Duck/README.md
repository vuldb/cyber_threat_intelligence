# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lemon Duck.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.202.15.246](https://vuldb.com/?ip.1.202.15.246) | 246.15.202.1.static.bjtelecom.net | - | High
2 | [27.195.157.70](https://vuldb.com/?ip.27.195.157.70) | - | - | High
3 | [36.48.94.254](https://vuldb.com/?ip.36.48.94.254) | - | - | High
4 | [36.110.1.222](https://vuldb.com/?ip.36.110.1.222) | 222.1.110.36.static.bjtelecom.net | - | High
5 | [40.68.42.171](https://vuldb.com/?ip.40.68.42.171) | - | - | High
6 | [42.7.4.88](https://vuldb.com/?ip.42.7.4.88) | - | - | High
7 | [42.7.31.243](https://vuldb.com/?ip.42.7.31.243) | - | - | High
8 | [42.176.133.183](https://vuldb.com/?ip.42.176.133.183) | - | - | High
9 | [49.71.208.124](https://vuldb.com/?ip.49.71.208.124) | - | - | High
10 | [49.147.72.67](https://vuldb.com/?ip.49.147.72.67) | dsl.49.148.72.67.pldt.net | - | High
11 | [51.36.170.221](https://vuldb.com/?ip.51.36.170.221) | - | - | High
12 | [58.56.135.198](https://vuldb.com/?ip.58.56.135.198) | - | - | High
13 | [58.62.125.245](https://vuldb.com/?ip.58.62.125.245) | - | - | High
14 | [58.221.24.178](https://vuldb.com/?ip.58.221.24.178) | - | - | High
15 | [58.251.2.115](https://vuldb.com/?ip.58.251.2.115) | reverse.gdsz.cncnet.net | - | High
16 | [59.111.181.116](https://vuldb.com/?ip.59.111.181.116) | - | - | High
17 | [59.175.154.97](https://vuldb.com/?ip.59.175.154.97) | - | - | High
18 | [60.10.56.169](https://vuldb.com/?ip.60.10.56.169) | hebei.10.60.in-addr.arpa | - | High
19 | [60.10.134.93](https://vuldb.com/?ip.60.10.134.93) | hebei.10.60.in-addr.arpa | - | High
20 | [60.19.236.50](https://vuldb.com/?ip.60.19.236.50) | - | - | High
21 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lemon Duck_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/academy/home/courses` | High
4 | File | `/AcceptZip.ashx` | High
5 | File | `/action.php` | Medium
6 | File | `/add-admin.php` | High
7 | File | `/addpayment.php` | High
8 | File | `/addrecord.php` | High
9 | File | `/add_new_invoice.php` | High
10 | File | `/admin-api/bpm/model/deploy` | High
11 | File | `/admin-cp/file-manager/upload` | High
12 | File | `/admin-cp/theme/install` | High
13 | File | `/admin-panel1.php` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/add-directory.php` | High
16 | File | `/admin/add-team.php` | High
17 | File | `/admin/add_cars.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/AdminLogin.php` | High
20 | File | `/admin/admin_running.php` | High
21 | File | `/admin/ajax.php?action=login` | High
22 | File | `/admin/ajax.php?action=save_settings` | High
23 | File | `/admin/app/login_crud.php` | High
24 | File | `/admin/app/role_crud.php` | High
25 | File | `/admin/bookdate.php` | High
26 | File | `/admin/bookings/manage_booking.php` | High
27 | File | `/admin/cashadvance_row.php` | High
28 | File | `/admin/chart1.php` | High
29 | File | `/admin/clients/manage.php` | High
30 | File | `/admin/create_product.php` | High
31 | File | `/admin/department.php` | High
32 | File | `/admin/edit-accepted-appointment.php` | High
33 | File | `/admin/edit-category.php` | High
34 | File | `/admin/edit-subcategory.php` | High
35 | File | `/admin/edit-user-profile.php` | High
36 | File | `/admin/editsite.php` | High
37 | File | `/admin/edit_categories.php` | High
38 | File | `/admin/edit_member.php` | High
39 | File | `/admin/edit_student_query.php` | High
40 | File | `/admin/edit_supplier.php` | High
41 | File | `/admin/eligibility.php` | High
42 | File | `/admin/employee/index.php` | High
43 | File | `/admin/extensions/download.php` | High
44 | File | `/admin/freelist_main.php` | High
45 | File | `/admin/home/index.html` | High
46 | File | `/admin/index.php?language=en&nv=upload` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/manage_theater.php` | High
49 | File | `/admin/menus/view_menu.php` | High
50 | File | `/admin/newsletterdel.php` | High
51 | File | `/admin/offenses/view_details.php` | High
52 | File | `/admin/save_teacher.php` | High
53 | File | `/admin/search-vehicle.php` | High
54 | File | `/admin/search.php` | High
55 | File | `/admin/templets_one_edit.php` | High
56 | File | `/admin/test_status.php` | High
57 | File | `/admin/update_s5.php` | High
58 | File | `/admin/update_user.php` | High
59 | File | `/admin/upload/authorImg/` | High
60 | File | `/admin/v1/link/edit` | High
61 | File | `/admin/view_vacancy.php` | High
62 | File | `/adminac.php` | Medium
63 | File | `/admin_class.php` | High
64 | File | `/admin_link.php?action=delall` | High
65 | File | `/agenda_preferencias.php` | High
66 | File | `/ajax.php?action=delete_product` | High
67 | File | `/ajax.php?action=delete_receiving` | High
68 | File | `/ajax.php?action=delete_user` | High
69 | File | `/ajax.php?action=read_msg` | High
70 | File | `/ajax.php?action=save_payment` | High
71 | File | `/allocate_room.php` | High
72 | File | `/ample/app/action/edit_product.php` | High
73 | File | `/api/` | Low
74 | File | `/api/2.0/rest/aggregator/xml` | High
75 | File | `/api/backend/core/web-file-upload/upload` | High
76 | File | `/api/upload/image` | High
77 | File | `/api/v2.0/users` | High
78 | File | `/app/sae/design/desktop/flat` | High
79 | File | `/App/Tpl/Admin/Default/Log/index.html` | High
80 | File | `/Applications/Steal/main.cpp` | High
81 | File | `/b2b-supermarket/catalog/all-products` | High
82 | File | `/base/safe_setting/` | High
83 | File | `/boafrm/formDebugDiagnosticRun` | High
84 | File | `/boafrm/formIpQoS` | High
85 | File | `/boafrm/formMapDel` | High
86 | File | `/boafrm/formPortFw` | High
87 | File | `/boafrm/formReflashClientTbl` | High
88 | File | `/boafrm/formStaticDHCP` | High
89 | File | `/boafrm/formWlanMultipleAP` | High
90 | File | `/boafrm/formWsc` | High
91 | File | `/boat-details.php` | High
92 | ... | ... | ...

There are 814 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/10/lemon-duck-brings-cryptocurrency-miners.html
* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
