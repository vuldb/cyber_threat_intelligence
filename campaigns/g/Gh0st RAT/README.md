# Gh0st RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Gh0st RAT_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gh0st RAT:

* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Gh0st RAT or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TG-3390](https://vuldb.com/?actor.tg-3390) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gh0st RAT.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [43.242.35.13](https://vuldb.com/?ip.43.242.35.13) | - | [TG-3390](https://vuldb.com/?actor.tg-3390) | High
2 | [43.242.35.16](https://vuldb.com/?ip.43.242.35.16) | - | [TG-3390](https://vuldb.com/?actor.tg-3390) | High
3 | [103.85.27.78](https://vuldb.com/?ip.103.85.27.78) | - | [TG-3390](https://vuldb.com/?actor.tg-3390) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Gh0st RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1068 | CWE-284 | Execution with Unnecessary Privileges | High
2 | T1222 | CWE-275 | Permission Issues | High
3 | T1505 | CWE-89 | SQL Injection | High
4 | ... | ... | ... | ...

There are 1 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Gh0st RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/usr/bin/pkexec` | High
2 | File | `base/sbcp.c` | Medium
3 | Library | `ssl/t1_lib.c` | Medium
4 | ... | ... | ...

There are 1 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.secureworks.com/research/a-peek-into-bronze-unions-toolbox

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
