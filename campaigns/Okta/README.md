# Okta - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Okta_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Okta:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 23 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Okta. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/accounts_con/register_account` | High
3 | File | `/admin/app/product.php` | High
4 | File | `/admin/app/service_crud.php` | High
5 | File | `/admin/edit_categories.php` | High
6 | File | `/admin/list_ipAddressPolicy.php` | High
7 | File | `/Admin/login.php` | High
8 | File | `/admin/students/update_status.php` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/app/api/controller/default/File.php` | High
11 | File | `/app/api/controller/default/Sqlite.php` | High
12 | File | `/app/controller/Setup.php` | High
13 | File | `/assets/php/upload.php` | High
14 | File | `/bin/boa` | Medium
15 | File | `/bin/sh` | Low
16 | File | `/bitrix/admin/ldap_server_edit.php` | High
17 | File | `/cancel.php` | Medium
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/luci;stok=/locale` | High
20 | File | `/cgi-bin/nas_sharing.cgi` | High
21 | File | `/collection/all` | High
22 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
23 | File | `/detail` | Low
24 | File | `/devinfo` | Medium
25 | File | `/edoc/doctor/patient.php` | High
26 | File | `/endpoint/update-tracker.php` | High
27 | File | `/general/email/outbox/delete.php` | High
28 | File | `/get_membership_amount.php` | High
29 | File | `/goform/addIpMacBind` | High
30 | File | `/goform/wifiSSIDset` | High
31 | File | `/goform/WifiWpsOOB` | High
32 | File | `/home/get_tasks_list` | High
33 | File | `/index.php` | Medium
34 | ... | ... | ...

There are 289 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://sec.okta.com/harfiles

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
