# Koi Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Koi Stealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Koi Stealer:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Koi Stealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Koi Loader](https://vuldb.com/?actor.koi_loader) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Koi Stealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.90.58.1](https://vuldb.com/?ip.45.90.58.1) | vds1337517.hosted-by-itldc.com | [Koi Loader](https://vuldb.com/?actor.koi_loader) | High
2 | [91.202.233.209](https://vuldb.com/?ip.91.202.233.209) | - | [Koi Loader](https://vuldb.com/?actor.koi_loader) | High
3 | [121.127.33.20](https://vuldb.com/?ip.121.127.33.20) | - | [Koi Loader](https://vuldb.com/?actor.koi_loader) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Koi Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Koi Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api /v3/auth` | High
2 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
3 | File | `epan/dissectors/asn1/tcap/tcap.cnf` | High
4 | ... | ... | ...

There are 7 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/esThreatIntelligence/iocs/blob/main/Koi/iocs_4-4-2024.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
