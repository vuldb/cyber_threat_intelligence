# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Camerashy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Naikon](https://vuldb.com/?actor.naikon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Camerashy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
2 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
3 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | [Naikon](https://vuldb.com/?actor.naikon) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-35, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-270, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/?r=report/api/getlist` | High
3 | File | `/admin` | Low
4 | File | `/admin.php/appcenter/local.html?type=addon` | High
5 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
6 | File | `/admin/?page=product/manage_product&id=2` | High
7 | File | `/admin/?page=reminders/view_reminder` | High
8 | File | `/admin/?page=system_info` | High
9 | File | `/admin/admin.php` | High
10 | File | `/admin/ajax.php` | High
11 | File | `/admin/assign/assign.php` | High
12 | File | `/admin/attendance_row.php` | High
13 | File | `/admin/ballot_up.php` | High
14 | File | `/admin/bookings/manage_booking.php` | High
15 | File | `/admin/bookings/view_details.php` | High
16 | File | `/admin/budget/manage_budget.php` | High
17 | File | `/admin/casedetails.php` | High
18 | File | `/admin/cashadvance_row.php` | High
19 | File | `/admin/categories/manage_category.php` | High
20 | File | `/admin/categories/view_category.php` | High
21 | File | `/admin/config_save.php` | High
22 | File | `/admin/deduction_edit.php` | High
23 | File | `/admin/departments/view_department.php` | High
24 | File | `/admin/doctors.php` | High
25 | File | `/admin/edit-doc.php` | High
26 | File | `/admin/employee_add.php` | High
27 | File | `/admin/employee_row.php` | High
28 | File | `/admin/fields/manage_field.php` | High
29 | File | `/admin/forgot-password.php` | High
30 | File | `/admin/getallarticleinfo` | High
31 | File | `/admin/index3.php` | High
32 | File | `/admin/info_deal.php` | High
33 | File | `/admin/inquiries/view_inquiry.php` | High
34 | File | `/admin/login.php` | High
35 | File | `/admin/maintenance/brand.php` | High
36 | File | `/admin/maintenance/view_designation.php` | High
37 | File | `/admin/manage_academic.php` | High
38 | File | `/admin/offenses/view_details.php` | High
39 | File | `/admin/orders/update_status.php` | High
40 | File | `/admin/pictures` | High
41 | File | `/admin/positions_add.php` | High
42 | File | `/admin/positions_row.php` | High
43 | File | `/admin/products/manage_product.php` | High
44 | File | `/admin/products/view_product.php` | High
45 | File | `/admin/reminders/manage_reminder.php` | High
46 | File | `/admin/report/index.php` | High
47 | File | `/admin/robot/approval/list` | High
48 | File | `/admin/sales/index.php` | High
49 | File | `/admin/sales/manage_sale.php` | High
50 | File | `/admin/save_teacher.php` | High
51 | File | `/admin/service.php` | High
52 | File | `/admin/services/manage_service.php` | High
53 | File | `/admin/students/view_details.php` | High
54 | File | `/admin/transactions/track_shipment.php` | High
55 | File | `/admin/upload` | High
56 | File | `/admin/user/manage_user.php` | High
57 | File | `/admin/userprofile.php` | High
58 | File | `/admin_system/api.php` | High
59 | File | `/analysisProject/pagingQueryData` | High
60 | File | `/api/admin/system/store/order/list` | High
61 | File | `/api/stl/actions/search` | High
62 | File | `/api/upload` | Medium
63 | File | `/bin/ate` | Medium
64 | File | `/bin/httpd` | Medium
65 | File | `/boafrm/formFilter` | High
66 | File | `/category/list?limit=10&offset=0&order=desc` | High
67 | File | `/classes/Login.php` | High
68 | File | `/classes/Master.php` | High
69 | File | `/classes/Master.php?f=delete_category` | High
70 | File | `/classes/Master.php?f=delete_img` | High
71 | File | `/classes/Master.php?f=delete_inquiry` | High
72 | File | `/classes/Master.php?f=delete_item` | High
73 | File | `/classes/Master.php?f=delete_service` | High
74 | File | `/classes/Master.php?f=delete_sub_category` | High
75 | File | `/classes/Master.php?f=save_course` | High
76 | File | `/classes/Master.php?f=save_service` | High
77 | File | `/classes/Users.php` | High
78 | File | `/classes/Users.phpp` | High
79 | ... | ... | ...

There are 697 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
