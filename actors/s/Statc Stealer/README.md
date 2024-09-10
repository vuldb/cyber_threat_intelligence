# Statc Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Statc Stealer](https://vuldb.com/?actor.statc_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.statc_stealer](https://vuldb.com/?actor.statc_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Statc Stealer:

* [DE](https://vuldb.com/?country.de)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Statc Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [95.217.5.87](https://vuldb.com/?ip.95.217.5.87) | static.87.5.217.95.clients.your-server.de | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Statc Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Statc Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/?page=user/list` | High
3 | File | `/admin/admin_user.php` | High
4 | File | `/admin/settings/index.php?page=accounts` | High
5 | File | `/adminapi/system/crud` | High
6 | File | `/adminPage/main/upload` | High
7 | File | `/api/blade-system/menu/list?updatexml` | High
8 | File | `/attendancelist.php` | High
9 | File | `/catalog/all-products` | High
10 | File | `/cgi-bin/cstecgi.cgi` | High
11 | File | `/cgi-bin/hd_config.cgi` | High
12 | File | `/change_password.php` | High
13 | File | `/control/deactivate_case.php` | High
14 | File | `/ecommerce/admin/products/controller.php` | High
15 | File | `/endpoint/add-computer.php` | High
16 | ... | ... | ...

There are 125 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.zscaler.com/blogs/security-research/statc-stealer-decoding-elusive-malware-threat

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
