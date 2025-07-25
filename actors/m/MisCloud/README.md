# MisCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MisCloud](https://vuldb.com/?actor.miscloud). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.miscloud](https://vuldb.com/?actor.miscloud)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MisCloud:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 35 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MisCloud.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [169.150.196.101](https://vuldb.com/?ip.169.150.196.101) | unn-169-150-196-101.datapacket.com | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MisCloud_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-26 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MisCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/ajax.php` | High
3 | File | `/admin/assign/assign.php` | High
4 | File | `/admin/bookings/manage_booking.php` | High
5 | File | `/admin/bookings/view_booking.php` | High
6 | File | `/admin/curriculum/view_curriculum.php` | High
7 | File | `/admin/deduction_row.php` | High
8 | File | `/admin/employee_row.php` | High
9 | File | `/admin/inquiries/view_inquiry.php` | High
10 | File | `/admin/login.php` | High
11 | File | `/admin/maintenance/manage_category.php` | High
12 | File | `/admin/modal_add_product.php` | High
13 | File | `/admin/orders/view_order.php` | High
14 | File | `/admin/products/view_product.php` | High
15 | File | `/admin/sales/view_details.php` | High
16 | File | `/admin/service_requests/manage_inventory.php` | High
17 | File | `/admin/sign/out` | High
18 | File | `/admin/stats` | Medium
19 | File | `/admin/students/view_student.php` | High
20 | File | `/admin/update_s6.php` | High
21 | File | `/admin/user/manage_user.php` | High
22 | File | `/api/baskets/{name}` | High
23 | File | `/api/cron/settings/setJob/` | High
24 | File | `/api/v4/channels/stats/member_count` | High
25 | File | `/api/v4/users` | High
26 | File | `/apply/index.php` | High
27 | File | `/bitrix/admin/ldap_server_edit.php` | High
28 | File | `/boaform/device_reset.cgi` | High
29 | File | `/cap.js` | Low
30 | File | `/Car_Rental/booking.php` | High
31 | File | `/categorypage.php` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/sessions/get-temp-file` | High
34 | File | `/cgi-bin/web_index.cgi?lang=en&src=AwSystem.html&ertqVvnKV4TjU9Vt` | High
35 | File | `/cgi-bin/wlogin.cgi` | High
36 | File | `/classes/Users.php` | High
37 | File | `/classes/Users.php?f=save` | High
38 | File | `/common/DownController.java` | High
39 | File | `/common/logViewer/logViewer.jsf` | High
40 | File | `/core/config-revisions` | High
41 | File | `/diag/eval` | Medium
42 | File | `/edoc/doctor/patient.php` | High
43 | File | `/Employer/ManageJob.php` | High
44 | File | `/forgotpw.php` | High
45 | File | `/forum/away.php` | High
46 | File | `/garage/editcategory.php` | High
47 | File | `/general/attendance/manage/ask_duty/delete.php` | High
48 | File | `/goform/execCommand` | High
49 | File | `/goform/setcfm` | High
50 | File | `/goform/telnet` | High
51 | File | `/html/ad/adconexaooffice365/request/testaConexaoOffice365.php` | High
52 | File | `/iissamples/sdk/asp/interaction/Form_JScript.asp` | High
53 | File | `/includes/cart.inc.php` | High
54 | File | `/includes/login.php` | High
55 | File | `/index.php` | Medium
56 | File | `/iniFile/config.ini` | High
57 | File | `/install/` | Medium
58 | File | `/librarian/bookdetails.php` | High
59 | File | `/login.php` | Medium
60 | File | `/manager/system/nlog_down.php` | High
61 | File | `/medicines/profile.php` | High
62 | ... | ... | ...

There are 546 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://infosecwriteups.com/miscloud-hackthebox-sherlock-writeup-bea5403dbcc2

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
