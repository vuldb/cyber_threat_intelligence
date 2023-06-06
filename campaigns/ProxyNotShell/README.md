# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.authlie` | Medium
2 | File | `/admin/ajax.php?action=delete_user` | High
3 | File | `/admin/ajax.php?action=save_queue` | High
4 | File | `/admin/bookings/manage_booking.php` | High
5 | File | `/admin/bookings/view_booking.php` | High
6 | File | `/admin/budget/manage_budget.php` | High
7 | File | `/admin/cashadvance_row.php` | High
8 | File | `/admin/curriculum/view_curriculum.php` | High
9 | File | `/admin/deduction_row.php` | High
10 | File | `/admin/departments/view_department.php` | High
11 | File | `/admin/edit_subject.php` | High
12 | File | `/admin/employee_row.php` | High
13 | File | `/admin/index.php` | High
14 | File | `/admin/inquiries/view_inquiry.php` | High
15 | File | `/admin/login.php` | High
16 | File | `/admin/maintenance/manage_category.php` | High
17 | File | `/admin/maintenance/view_designation.php` | High
18 | File | `/admin/mechanics/manage_mechanic.php` | High
19 | File | `/admin/offenses/view_details.php` | High
20 | File | `/admin/orders/update_status.php` | High
21 | File | `/admin/products/manage_product.php` | High
22 | File | `/admin/products/view_product.php` | High
23 | File | `/admin/reminders/manage_reminder.php` | High
24 | File | `/admin/report/index.php` | High
25 | File | `/admin/service.php` | High
26 | File | `/admin/services/manage_service.php` | High
27 | File | `/admin/services/view_service.php` | High
28 | File | `/admin/service_requests/manage_inventory.php` | High
29 | File | `/admin/suppliers/view_details.php` | High
30 | File | `/admin/transactions/track_shipment.php` | High
31 | File | `/admin/user/manage_user.php` | High
32 | File | `/admin/userprofile.php` | High
33 | File | `/ajax/myshop` | Medium
34 | File | `/alarm_pi/alarmService.php` | High
35 | File | `/api/stl/actions/search` | High
36 | File | `/apply.cgi` | Medium
37 | File | `/bsms_ci/index.php/book` | High
38 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
39 | File | `/cgi-bin/ping.cgi` | High
40 | File | `/classes/Login.php` | High
41 | File | `/classes/Master.php` | High
42 | File | `/classes/Master.php?f=delete_category` | High
43 | File | `/classes/Master.php?f=delete_inquiry` | High
44 | File | `/classes/Master.php?f=delete_item` | High
45 | File | `/classes/Master.php?f=delete_service` | High
46 | File | `/classes/Master.php?f=delete_sub_category` | High
47 | File | `/classes/Master.php?f=save_course` | High
48 | ... | ... | ...

There are 418 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
