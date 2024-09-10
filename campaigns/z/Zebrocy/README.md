# Zebrocy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Zebrocy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zebrocy:

* [US](https://vuldb.com/?country.us)
* [BR](https://vuldb.com/?country.br)

## Actors

These _actors_ are associated with Zebrocy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Sofacy](https://vuldb.com/?actor.sofacy) | High
2 | [Zebrocy](https://vuldb.com/?actor.zebrocy) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zebrocy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [86.106.131.177](https://vuldb.com/?ip.86.106.131.177) | slot0.rilzcarlton.com | [Sofacy](https://vuldb.com/?actor.sofacy) | High
2 | [92.114.92.102](https://vuldb.com/?ip.92.114.92.102) | oracleupdatenews.com | [Sofacy](https://vuldb.com/?actor.sofacy) | High
3 | [92.222.136.105](https://vuldb.com/?ip.92.222.136.105) | - | [Sofacy](https://vuldb.com/?actor.sofacy) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Zebrocy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1505 | CWE-89 | SQL Injection | High
2 | T1592 | CWE-200 | Invocation of Process Using Visible Sensitive Information | High
3 | T1600 | CWE-310 | Cryptographic Issues | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Zebrocy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `at/create_job.cgi` | High
2 | File | `tunnel/link.cgi` | High
3 | File | `XMLRPC.PHP` | Medium
4 | ... | ... | ...

There are 2 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-sofacy-groups-parallel-attacks/
* https://www.welivesecurity.com/2019/09/24/no-summer-vacations-zebrocy/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
