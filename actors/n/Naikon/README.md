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
1 | T1006 | CWE-22, CWE-35 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/AccountMaster/GetCurrentUserInfo` | High
2 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
3 | File | `/admin/admin_invt2.php` | High
4 | File | `/admin/config/save` | High
5 | File | `/admin/edit_manufacturer.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/inquiries/view_details.php` | High
8 | File | `/admin/maintenance/manage_department.php` | High
9 | File | `/admin/reports/index.php` | High
10 | File | `/admin/template/update` | High
11 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
12 | File | `/ajax.php?action=delete_deductions` | High
13 | File | `/ajax.php?action=update_account` | High
14 | File | `/app/action/add_staff.php` | High
15 | File | `/app/uploading/upload-mp3.php` | High
16 | File | `/cgi-bin/cstecgi.cgi` | High
17 | File | `/chat/completions` | High
18 | File | `/control/forgot_pass.php` | High
19 | File | `/control/login.php` | High
20 | File | `/core/config-revisions/` | High
21 | File | `/detailed.php` | High
22 | File | `/download/file` | High
23 | File | `/edit1.php` | Medium
24 | File | `/endpoint/add-timesheet.php` | High
25 | File | `/endpoint/delete-timesheet.php` | High
26 | File | `/endpoint/update.php` | High
27 | File | `/etc/passwd` | Medium
28 | File | `/event/admin/login.php` | High
29 | File | `/filter.php` | Medium
30 | File | `/forgot.php` | Medium
31 | File | `/fx/baseinfo/SearchInfo` | High
32 | File | `/goform/exeCommand` | High
33 | File | `/goform/frmL7ProtForm` | High
34 | File | `/index.php` | Medium
35 | File | `/index.php/dashboard/save` | High
36 | File | `/index.php?page=tenants` | High
37 | File | `/info.cgi` | Medium
38 | File | `/mfeedback.php` | High
39 | File | `/model/viewProduct.php` | High
40 | ... | ... | ...

There are 349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
