# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [FR](https://vuldb.com/?country.fr)
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

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Naikon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-27, CWE-28, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/?r=email/api/mark&op=delFromSend` | High
3 | File | `/?r=report/api/getlist` | High
4 | File | `/admin` | Low
5 | File | `/admin.php/appcenter/local.html?type=addon` | High
6 | File | `/admin/?page=maintenance/brand` | High
7 | File | `/admin/?page=product/manage_product&id=2` | High
8 | File | `/admin/?page=reminders/view_reminder` | High
9 | File | `/admin/?page=system_info` | High
10 | File | `/admin/?page=user` | High
11 | File | `/admin/ajax.php` | High
12 | File | `/admin/ajax.php?action=login` | High
13 | File | `/admin/assign/assign.php` | High
14 | File | `/admin/attendance_row.php` | High
15 | File | `/admin/ballot_down.php` | High
16 | File | `/admin/ballot_up.php` | High
17 | File | `/admin/bookings/manage_booking.php` | High
18 | File | `/admin/bookings/view_booking.php` | High
19 | File | `/admin/candidates_row.php` | High
20 | File | `/admin/casedetails.php` | High
21 | File | `/admin/cashadvance_row.php` | High
22 | File | `/admin/categories/view_category.php` | High
23 | File | `/admin/configurations/userInfo` | High
24 | File | `/admin/config_save.php` | High
25 | File | `/admin/deduction_edit.php` | High
26 | File | `/admin/departments/view_department.php` | High
27 | File | `/admin/edit-doc.php` | High
28 | File | `/admin/employee_add.php` | High
29 | File | `/admin/employee_edit.php` | High
30 | File | `/admin/employee_row.php` | High
31 | File | `/admin/fields/manage_field.php` | High
32 | File | `/admin/forgot-password.php` | High
33 | File | `/admin/getallarticleinfo` | High
34 | File | `/admin/index3.php` | High
35 | File | `/admin/info_deal.php` | High
36 | File | `/admin/inquiries/view_inquiry.php` | High
37 | File | `/admin/inventory/manage_stock.php` | High
38 | File | `/admin/login.php` | High
39 | File | `/admin/maintenance/brand.php` | High
40 | File | `/admin/maintenance/manage_category.php` | High
41 | File | `/admin/maintenance/view_designation.php` | High
42 | File | `/admin/mechanics/manage_mechanic.php` | High
43 | File | `/admin/offenses/view_details.php` | High
44 | File | `/admin/positions_add.php` | High
45 | File | `/admin/positions_delete.php` | High
46 | File | `/admin/positions_row.php` | High
47 | File | `/admin/product/manage.php` | High
48 | File | `/admin/products/index.php` | High
49 | File | `/admin/products/manage_product.php` | High
50 | File | `/admin/products/view_product.php` | High
51 | File | `/admin/reminders/manage_reminder.php` | High
52 | File | `/admin/report/index.php` | High
53 | File | `/admin/robot/approval/list` | High
54 | File | `/admin/sales/index.php` | High
55 | File | `/admin/sales/manage_sale.php` | High
56 | File | `/admin/sales/view_details.php` | High
57 | File | `/admin/services/manage_service.php` | High
58 | File | `/admin/services/view_service.php` | High
59 | File | `/admin/service_requests/manage_inventory.php` | High
60 | File | `/admin/students/view_details.php` | High
61 | File | `/admin/upload` | High
62 | File | `/admin/user/manage_user.php` | High
63 | File | `/admin/userprofile.php` | High
64 | File | `/admin/voters_row.php` | High
65 | File | `/admin_system/api.php` | High
66 | File | `/ajax/myshop` | Medium
67 | File | `/analysisProject/pagingQueryData` | High
68 | File | `/api/admin/store/product/list` | High
69 | File | `/api/admin/store/product/save` | High
70 | File | `/api/admin/system/store/order/list` | High
71 | File | `/api/baskets/{name}` | High
72 | ... | ... | ...

There are 631 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
