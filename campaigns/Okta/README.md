# Okta - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Okta_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Okta:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 17 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Okta or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Okta.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.105.182.19](https://vuldb.com/?ip.23.105.182.19) | warodism19.prescamawipe.com | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [23.106.56.11](https://vuldb.com/?ip.23.106.56.11) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [23.106.56.21](https://vuldb.com/?ip.23.106.56.21) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [23.106.56.36](https://vuldb.com/?ip.23.106.56.36) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Okta. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80, CWE-83 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-272, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Okta. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin/maintenance/view_designation.php` | High
3 | File | `/admin/students/update_status.php` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/bin/sh` | Low
6 | File | `/bitrix/admin/ldap_server_edit.php` | High
7 | File | `/collection/all` | High
8 | File | `/detail` | Low
9 | File | `/edoc/doctor/patient.php` | High
10 | File | `/goform/SysToolReboot` | High
11 | File | `/home/get_tasks_list` | High
12 | File | `/info.xml` | Medium
13 | File | `/lists/admin/` | High
14 | File | `/log/decodmail.php` | High
15 | File | `/Main_AdmStatus_Content.asp` | High
16 | File | `/mgmt/tm/util/bash` | High
17 | File | `/mygym/admin/login.php` | High
18 | File | `/owa/auth/logon.aspx` | High
19 | File | `/plain` | Low
20 | File | `/proc/self/setgroups` | High
21 | File | `/products/view_product.php` | High
22 | File | `/rest/synchronizer/1.0/technicalUser` | High
23 | File | `/scripts/cpan_config` | High
24 | File | `/sysmanage/updateos.php` | High
25 | File | `/var/run/cloudera-scm-agent` | High
26 | ... | ... | ...

There are 219 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://sec.okta.com/harfiles

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
