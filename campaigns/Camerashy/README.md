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

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-40 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.dbshell` | Medium
2 | File | `/action/import_firmware/` | High
3 | File | `/action/import_sdk_file/` | High
4 | File | `/Admin/add-student.php` | High
5 | File | `/admin/addemployee.php` | High
6 | File | `/admin/admin.php` | High
7 | File | `/admin/budget.php` | High
8 | File | `/Admin/createClass.php` | High
9 | File | `/Admin/login.php` | High
10 | File | `/admin/sign/out` | High
11 | File | `/admin/students/manage.php` | High
12 | File | `/admin/update_currency.php` | High
13 | File | `/api/discoveries/` | High
14 | File | `/api/public/signup` | High
15 | File | `/api/v1/attack` | High
16 | File | `/api/v1/attack/falco` | High
17 | File | `/api/v1/attack/token` | High
18 | File | `/api/v1/bait/set` | High
19 | File | `/api/v2/cli/commands` | High
20 | File | `/api/v2/open/rowsInfo` | High
21 | File | `/api/v2/open/tablesInfo` | High
22 | File | `/asms/admin/mechanics/manage_mechanic.php` | High
23 | File | `/attachments` | Medium
24 | File | `/balance/service/list` | High
25 | File | `/baseOpLog.do` | High
26 | File | `/bits/stl_vector.h` | High
27 | File | `/category.php` | High
28 | File | `/cgi-bin/ExportSettings.sh` | High
29 | File | `/csms/?page=contact_us` | High
30 | File | `/csms/admin/?page=system_info` | High
31 | File | `/csms/admin/?page=user/list` | High
32 | File | `/csms/admin/?page=user/manage_user` | High
33 | File | `/depotHead/list` | High
34 | File | `/dishes.php` | Medium
35 | File | `/ebics-server/ebics.aspx` | High
36 | File | `/etc/ciel.cfg` | High
37 | File | `/etc/version` | Medium
38 | File | `/goform/wizard_end` | High
39 | ... | ... | ...

There are 337 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
