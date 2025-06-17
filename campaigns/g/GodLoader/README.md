# GodLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _GodLoader_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GodLoader:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## Actors

These _actors_ are associated with GodLoader or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Stargazers Ghost](https://vuldb.com/?actor.stargazers_ghost) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GodLoader.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [147.45.44.83](https://vuldb.com/?ip.147.45.44.83) | - | [Stargazers Ghost](https://vuldb.com/?actor.stargazers_ghost) | High
2 | [185.196.9.26](https://vuldb.com/?ip.185.196.9.26) | - | [Stargazers Ghost](https://vuldb.com/?actor.stargazers_ghost) | High
3 | [192.168.15.10](https://vuldb.com/?ip.192.168.15.10) | - | [Stargazers Ghost](https://vuldb.com/?actor.stargazers_ghost) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within GodLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1204.001 | CWE-601 | Open Redirect | High
2 | T1505 | CWE-89 | SQL Injection | High
3 | T1611 | CWE-265 | Containment Errors | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during GodLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/src/vmir_wasm_parser.c` | High
2 | File | `Login.php` | Medium
3 | File | `page.php` | Medium
4 | ... | ... | ...

There are 5 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://research.checkpoint.com/2024/gaming-engines-an-undetected-playground-for-malware-loaders/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
