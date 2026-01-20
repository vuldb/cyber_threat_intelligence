# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | - | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | - | High
3 | [24.88.87.29](https://vuldb.com/?ip.24.88.87.29) | syn-024-088-087-029.res.spectrum.com | - | High
4 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | - | High
5 | [32.143.50.222](https://vuldb.com/?ip.32.143.50.222) | - | - | High
6 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | - | High
7 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | - | High
8 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | - | High
9 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | - | High
10 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | - | High
11 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | - | High
12 | [68.76.150.97](https://vuldb.com/?ip.68.76.150.97) | 68-76-150-97.lightspeed.hstntx.sbcglobal.net | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pawn Storm_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/academy/home/courses` | High
4 | File | `/AcceptZip.ashx` | High
5 | File | `/action.php` | Medium
6 | File | `/actuator` | Medium
7 | File | `/add-admin.php` | High
8 | File | `/addpayment.php` | High
9 | File | `/addrecord.php` | High
10 | File | `/add_new_invoice.php` | High
11 | File | `/admin-api/bpm/model/deploy` | High
12 | File | `/admin-cp/file-manager/upload` | High
13 | File | `/admin-cp/theme/install` | High
14 | File | `/admin-panel1.php` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/add-directory.php` | High
17 | File | `/admin/add-team.php` | High
18 | File | `/admin/add_cars.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/AdminLogin.php` | High
21 | File | `/admin/admin_running.php` | High
22 | File | `/admin/ajax.php?action=login` | High
23 | File | `/admin/ajax.php?action=save_settings` | High
24 | File | `/admin/app/login_crud.php` | High
25 | File | `/admin/app/role_crud.php` | High
26 | File | `/admin/bookdate.php` | High
27 | File | `/admin/bookings/manage_booking.php` | High
28 | File | `/admin/cashadvance_row.php` | High
29 | File | `/admin/chart1.php` | High
30 | File | `/admin/clients/manage.php` | High
31 | File | `/admin/create_product.php` | High
32 | File | `/admin/department.php` | High
33 | File | `/admin/edit-accepted-appointment.php` | High
34 | File | `/admin/edit-category.php` | High
35 | File | `/admin/edit-subcategory.php` | High
36 | File | `/admin/edit-user-profile.php` | High
37 | File | `/admin/editsite.php` | High
38 | File | `/admin/edit_categories.php` | High
39 | File | `/admin/edit_member.php` | High
40 | File | `/admin/edit_student_query.php` | High
41 | File | `/admin/edit_supplier.php` | High
42 | File | `/admin/eligibility.php` | High
43 | File | `/admin/employee/index.php` | High
44 | File | `/admin/extensions/download.php` | High
45 | File | `/admin/freelist_main.php` | High
46 | File | `/admin/home/index.html` | High
47 | File | `/admin/index.php?language=en&nv=upload` | High
48 | File | `/admin/login.php` | High
49 | File | `/admin/manage_theater.php` | High
50 | File | `/admin/menus/view_menu.php` | High
51 | File | `/admin/newsletterdel.php` | High
52 | File | `/admin/offenses/view_details.php` | High
53 | File | `/admin/save_teacher.php` | High
54 | File | `/admin/search-vehicle.php` | High
55 | File | `/admin/search.php` | High
56 | File | `/admin/templets_one_edit.php` | High
57 | File | `/admin/test_status.php` | High
58 | File | `/admin/update_s5.php` | High
59 | File | `/admin/update_user.php` | High
60 | File | `/admin/upload/authorImg/` | High
61 | File | `/admin/v1/link/edit` | High
62 | File | `/admin/view_vacancy.php` | High
63 | File | `/adminac.php` | Medium
64 | File | `/admin_class.php` | High
65 | File | `/admin_link.php?action=delall` | High
66 | File | `/agenda_preferencias.php` | High
67 | File | `/ajax.php?action=delete_product` | High
68 | File | `/ajax.php?action=delete_receiving` | High
69 | File | `/ajax.php?action=delete_user` | High
70 | File | `/ajax.php?action=read_msg` | High
71 | File | `/ajax.php?action=save_payment` | High
72 | File | `/allocate_room.php` | High
73 | File | `/ample/app/action/edit_product.php` | High
74 | File | `/api/` | Low
75 | File | `/api/2.0/rest/aggregator/xml` | High
76 | File | `/api/backend/core/web-file-upload/upload` | High
77 | File | `/api/upload/image` | High
78 | File | `/api/v2.0/users` | High
79 | File | `/app/sae/design/desktop/flat` | High
80 | File | `/App/Tpl/Admin/Default/Log/index.html` | High
81 | File | `/Applications/Steal/main.cpp` | High
82 | File | `/b2b-supermarket/catalog/all-products` | High
83 | File | `/base/safe_setting/` | High
84 | File | `/boafrm/formDebugDiagnosticRun` | High
85 | File | `/boafrm/formIpQoS` | High
86 | File | `/boafrm/formMapDel` | High
87 | File | `/boafrm/formPortFw` | High
88 | File | `/boafrm/formReflashClientTbl` | High
89 | File | `/boafrm/formStaticDHCP` | High
90 | File | `/boafrm/formWlanMultipleAP` | High
91 | File | `/boafrm/formWsc` | High
92 | File | `/boat-details.php` | High
93 | ... | ... | ...

There are 817 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
