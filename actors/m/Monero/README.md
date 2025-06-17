# Monero - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Monero](https://vuldb.com/?actor.monero). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.monero](https://vuldb.com/?actor.monero)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Monero:

* [GB](https://vuldb.com/?country.gb)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Monero.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.187.74.171](https://vuldb.com/?ip.37.187.74.171) | ns3365046.ip-37-187-74.eu | - | High
2 | [37.187.154.37](https://vuldb.com/?ip.37.187.154.37) | ns320368.ip-37-187-154.eu | - | High
3 | [39.99.146.107](https://vuldb.com/?ip.39.99.146.107) | - | - | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Monero_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Monero. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/action/import_authorized_keys/` | High
3 | File | `/action/import_https_cert_file/` | High
4 | File | `/action/import_xml_file/` | High
5 | File | `/admin/?page=reminders/view_reminder` | High
6 | File | `/admin/?page=system_info/contact_info` | High
7 | File | `/admin/addemployee.php` | High
8 | File | `/admin/bookings/manage_booking.php` | High
9 | File | `/admin/bookings/view_booking.php` | High
10 | File | `/admin/controller/JobLogController.java` | High
11 | File | `/Admin/dashboard.php` | High
12 | File | `/admin/delete.php` | High
13 | File | `/Admin/login.php` | High
14 | File | `/admin/newsletter1.php` | High
15 | File | `/admin/reports.php` | High
16 | File | `/admin/searchview.php` | High
17 | File | `/admin/select.php` | High
18 | File | `/admin/settings.php` | High
19 | File | `/admin/user/manage_user.php` | High
20 | File | `/admin/users_add.php` | High
21 | File | `/api/admin/user` | High
22 | File | `/api/common/ping` | High
23 | File | `/api/geojson` | Medium
24 | File | `/api/sys_username_passwd.cmd` | High
25 | File | `/api/user/password/sent-reset-email` | High
26 | File | `/asms/classes/Master.php?f=delete_service` | High
27 | File | `/assets` | Low
28 | File | `/balance/service/list` | High
29 | File | `/bibliography/marcsru.php` | High
30 | File | `/bsms_ci/index.php/user/edit_user/` | High
31 | File | `/card/in-card.php` | High
32 | File | `/catcompany.php` | High
33 | File | `/chat/completions` | High
34 | File | `/ci_hms/massage_room/edit/1` | High
35 | File | `/ci_spms/admin/category` | High
36 | File | `/classes/Master.php?f=delete_reservation` | High
37 | File | `/classes/Master.php?f=delete_service` | High
38 | File | `/classes/Master.php?f=delete_train` | High
39 | File | `/cms/admin/?page=user/manage_user` | High
40 | File | `/College_Management_System/admin/display-teacher.php` | High
41 | File | `/controller/FileController.java` | High
42 | File | `/ctpms/classes/Master.php?f=delete_application` | High
43 | ... | ... | ...

There are 372 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.trendmicro.com/trendlabs-security-intelligence/almost-hollow-and-innocent-monero-miner-remains-undetected-via-process-hollowing/
* https://blog.trendmicro.com/trendlabs-security-intelligence/cve-2019-2725-exploited-and-certificate-files-used-for-obfuscation-to-deliver-monero-miner/
* https://primal.net/e/note1389mysmdam63wcra03uct7tua8ac6q2el6xkfsqrthshsu7en95sacry5j

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
