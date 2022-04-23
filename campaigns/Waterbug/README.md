# Waterbug - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Waterbug_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Waterbug:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)
* [RO](https://vuldb.com/?country.ro)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Waterbug or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Turla](https://vuldb.com/?actor.turla) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Waterbug.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [62.12.39.117](https://vuldb.com/?ip.62.12.39.117) | - | [Turla](https://vuldb.com/?actor.turla) | High
2 | [62.68.73.57](https://vuldb.com/?ip.62.68.73.57) | - | [Turla](https://vuldb.com/?actor.turla) | High
3 | [62.212.226.118](https://vuldb.com/?ip.62.212.226.118) | - | [Turla](https://vuldb.com/?actor.turla) | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Waterbug. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Waterbug. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%APPDATA%\Securepoint SSL VPN` | High
2 | File | `/Api/ASF` | Medium
3 | File | `/etc/shadow` | Medium
4 | File | `/etc/target/saveconfig.json` | High
5 | File | `/exec` | Low
6 | File | `/form/index.php?module=getjson` | High
7 | File | `/hcms/admin/index.php/language/ajax` | High
8 | File | `/jsonrpc` | Medium
9 | File | `/product.php` | Medium
10 | File | `/ram/pckg/advanced-tools/nova/bin/netwatch` | High
11 | File | `/registerCpe` | Medium
12 | File | `/system?action=ServiceAdmin` | High
13 | File | `/uncpath/` | Medium
14 | File | `/Uploads` | Medium
15 | File | `/User/saveUser` | High
16 | ... | ... | ...

There are 126 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.threatminer.org/report.php?q=waterbug-attack-group.pdf&y=2015#gsc.tab=0&gsc.q=waterbug-attack-group.pdf&gsc.page=1

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
