# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [US](https://vuldb.com/?country.us)

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
1 | T1006 | CWE-22, CWE-23, CWE-29, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/3/ParseSetup` | High
2 | File | `/add-teacher.php` | High
3 | File | `/add_reserve.php` | High
4 | File | `/admin/add-animals.php` | High
5 | File | `/admin/adddoctorclinic.php` | High
6 | File | `/admin/add_query_account.php` | High
7 | File | `/admin/admin-area.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/admin_class.php` | High
10 | File | `/admin/ajax.php?action=delete_application` | High
11 | File | `/admin/approve_reservation.php` | High
12 | File | `/admin/candidates_add.php` | High
13 | File | `/admin/candidates_row.php` | High
14 | File | `/admin/changepassword.php` | High
15 | File | `/admin/complaint-details.php` | High
16 | File | `/admin/completed-requests.php` | High
17 | File | `/admin/delete-doctor.php` | High
18 | File | `/admin/delete_s1.php` | High
19 | File | `/admin/delete_s2.php` | High
20 | File | `/admin/delete_s6.php` | High
21 | File | `/admin/displayable_links.js` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/lastsevendays-reg-users.php` | High
24 | File | `/admin/login-back.php` | High
25 | File | `/admin/manage-incomingvehicle.php` | High
26 | File | `/admin/manage-normal-ticket.php` | High
27 | File | `/admin/manage-outgoingvehicle.php` | High
28 | File | `/admin/manage-site.php` | High
29 | File | `/admin/manage-users.php` | High
30 | File | `/admin/password-recovery.php` | High
31 | File | `/admin/positions_edit.php` | High
32 | File | `/admin/positions_row.php` | High
33 | File | `/admin/product-update.php` | High
34 | File | `/admin/product.php` | High
35 | File | `/admin/reg-users.php` | High
36 | File | `/admin/search-autoortaxi.php` | High
37 | File | `/admin/search-vehicle.php` | High
38 | File | `/admin/slideupdate.php` | High
39 | File | `/admin/student-history.php` | High
40 | File | `/admin/ueditor?action=catchimage` | High
41 | File | `/admin/update_s2.php` | High
42 | File | `/admin/update_s4.php` | High
43 | File | `/admin/update_s7.php` | High
44 | File | `/admin/update_s8.php` | High
45 | File | `/admin/users_photo.php` | High
46 | File | `/admin/view-user-queries.php` | High
47 | File | `/admin/voters_add.php` | High
48 | File | `/admin/voters_delete.php` | High
49 | File | `/admin/voters_row.php` | High
50 | File | `/admin/yesterday-reg-users.php` | High
51 | File | `/adminac.php` | Medium
52 | File | `/ajax.php?action=calculate_payroll` | High
53 | File | `/ajax.php?action=delete_employee_attendance_single` | High
54 | File | `/ajax.php?action=delete_position` | High
55 | File | `/ajax.php?action=save_deductions` | High
56 | File | `/ajax.php?action=save_position` | High
57 | File | `/api/system/upload-logo` | High
58 | File | `/api/v1/editor/chart/run` | High
59 | File | `/application/user/controller/Index.php` | High
60 | File | `/boafrm/formIpQoS` | High
61 | File | `/boafrm/formMapDel` | High
62 | File | `/boafrm/formOneKeyAccessButton` | High
63 | File | `/boafrm/formPortFw` | High
64 | File | `/boafrm/formRoute` | High
65 | File | `/c6/Jhsoft.Web.message/ToolBar/DelTemp.aspx` | High
66 | ... | ... | ...

There are 576 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
