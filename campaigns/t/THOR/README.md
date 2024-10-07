# THOR - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _THOR_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with THOR:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)

## Actors

These _actors_ are associated with THOR or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [PKPLUG](https://vuldb.com/?actor.pkplug) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of THOR.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [42.99.117.92](https://vuldb.com/?ip.42.99.117.92) | - | [PKPLUG](https://vuldb.com/?actor.pkplug) | High
2 | [42.99.117.95](https://vuldb.com/?ip.42.99.117.95) | - | [PKPLUG](https://vuldb.com/?actor.pkplug) | High
3 | [43.254.217.165](https://vuldb.com/?ip.43.254.217.165) | - | [PKPLUG](https://vuldb.com/?actor.pkplug) | High
4 | [45.142.166.112](https://vuldb.com/?ip.45.142.166.112) | - | [PKPLUG](https://vuldb.com/?actor.pkplug) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within THOR. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during THOR. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?action=themeinstall` | High
2 | File | `/admin/ajax/avatar.php` | High
3 | File | `/admin/uploads.php` | High
4 | File | `/admin/users.php?source=edit_user&id=1` | High
5 | File | `/cgi-bin/p1_ftpserver.php` | High
6 | File | `/cgi-bin/portal` | High
7 | File | `/cgi-bin/tosei_kikai.php` | High
8 | File | `/etc/passwd` | Medium
9 | File | `/etc/shadow` | Medium
10 | File | `/htmlcode/html/indexdefault.asp` | High
11 | File | `/include/config.cache.php` | High
12 | ... | ... | ...

There are 94 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/thor-plugx-variant/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
