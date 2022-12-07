# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PYSA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.129.64.190](https://vuldb.com/?ip.23.129.64.190) | - | - | High
2 | [45.147.231.210](https://vuldb.com/?ip.45.147.231.210) | - | - | High
3 | [185.220.100.240](https://vuldb.com/?ip.185.220.100.240) | tor-exit-13.zbau.f3netze.de | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PYSA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-40 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PYSA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/import_https_cert_file/` | High
2 | File | `/admin/?page=bookings/view_details` | High
3 | File | `/admin/?page=orders/view_order` | High
4 | File | `/Admin/add-student.php` | High
5 | File | `/Admin/createClass.php` | High
6 | File | `/Admin/dashboard.php` | High
7 | File | `/admin/pages/sections_save.php` | High
8 | File | `/admin/settings.php` | High
9 | File | `/admin/update_currency.php` | High
10 | File | `/admin/up_booking.php` | High
11 | File | `/api/geojson` | Medium
12 | File | `/api/v1/attack` | High
13 | File | `/api/v1/attack/token` | High
14 | File | `/apiv1/` | Low
15 | File | `/asms/admin/?page=transactions/manage_transaction` | High
16 | File | `/authUserAction!edit.action` | High
17 | File | `/bsms_ci/index.php/user/edit_user/` | High
18 | File | `/buspassms/download-pass.php` | High
19 | File | `/calendar/viewcalendar.php` | High
20 | File | `/classes/Users.php?f=delete_client` | High
21 | File | `/clearance/clearance.php` | High
22 | File | `/clients/listclients.php` | High
23 | File | `/College/admin/teacher.php` | High
24 | File | `/dede/file_manage_control.php` | High
25 | File | `/DesignTools/CssEditor.aspx` | High
26 | File | `/dev/shm` | Medium
27 | File | `/device/` | Medium
28 | File | `/diagnostic/edittest.php` | High
29 | File | `/file/upload/1` | High
30 | File | `/forums/editforum.php` | High
31 | File | `/general/search.php?searchtype=simple` | High
32 | File | `/gfxpoly/stroke.c` | High
33 | File | `/goform/AddSysLogRule` | High
34 | File | `/goform/setDiagnoseInfo` | High
35 | File | `/goform/SetIpMacBind` | High
36 | File | `/hrm/controller/employee.php` | High
37 | File | `/hrm/employeeadd.php` | High
38 | File | `/hrm/employeeview.php` | High
39 | File | `/index.php/admins/Fields/get_fields.html` | High
40 | File | `/index.php?module=entities/listing_types&entities_id=24` | High
41 | ... | ... | ...

There are 351 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/120/pysa-ransomware-iocs/
* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
