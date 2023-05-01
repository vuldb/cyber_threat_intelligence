# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [ES](https://vuldb.com/?country.es)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
3 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
4 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
5 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
7 | [51.79.175.139](https://vuldb.com/?ip.51.79.175.139) | vps-dc8b0481.vps.ovh.ca | Log4Shell | High
8 | [51.222.121.180](https://vuldb.com/?ip.51.222.121.180) | ip180.ip-51-222-121.net | Log4Shell | High
9 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | Log4Shell | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/?p=products` | Medium
3 | File | `/admin` | Low
4 | File | `/admin.php/accessory/filesdel.html` | High
5 | File | `/admin/attendance_row.php` | High
6 | File | `/admin/bookings/manage_booking.php` | High
7 | File | `/admin/bookings/view_booking.php` | High
8 | File | `/admin/cashadvance_row.php` | High
9 | File | `/admin/deduction_row.php` | High
10 | File | `/admin/employee_row.php` | High
11 | File | `/admin/index.php` | High
12 | File | `/admin/index3.php` | High
13 | File | `/admin/inquiries/view_inquiry.php` | High
14 | File | `/admin/login.php` | High
15 | File | `/admin/maintenance/brand.php` | High
16 | File | `/admin/maintenance/manage_category.php` | High
17 | File | `/admin/maintenance/view_designation.php` | High
18 | File | `/admin/mechanics/manage_mechanic.php` | High
19 | File | `/admin/offenses/view_details.php` | High
20 | File | `/admin/orders/update_status.php` | High
21 | File | `/admin/products/manage_product.php` | High
22 | File | `/admin/products/view_product.php` | High
23 | File | `/admin/reminders/manage_reminder.php` | High
24 | File | `/admin/report/index.php` | High
25 | File | `/admin/sales/manage_sale.php` | High
26 | File | `/admin/services/manage_service.php` | High
27 | File | `/admin/services/view_service.php` | High
28 | File | `/admin/service_requests/manage_inventory.php` | High
29 | File | `/admin/user/manage_user.php` | High
30 | File | `/admin/userprofile.php` | High
31 | File | `/admin_area/login_transfer.php` | High
32 | File | `/adms/admin/?page=user/manage_user` | High
33 | File | `/adms/admin/?page=vehicles/view_transaction` | High
34 | File | `/ajax/update_certificate` | High
35 | File | `/alphaware/details.php` | High
36 | File | `/apply.cgi` | Medium
37 | File | `/bsms_ci/index.php/book` | High
38 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
39 | File | `/cgi-bin/touchlist_sync.cgi` | High
40 | File | `/cgi-bin/wlogin.cgi` | High
41 | File | `/classes/Login.php` | High
42 | File | `/classes/Master.php` | High
43 | ... | ... | ...

There are 373 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
