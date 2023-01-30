# Windigo - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Windigo_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Windigo:

* [FR](https://vuldb.com/?country.fr)
* [DE](https://vuldb.com/?country.de)

## Actors

These _actors_ are associated with Windigo or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Windigo](https://vuldb.com/?actor.windigo) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Windigo.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [77.67.80.31](https://vuldb.com/?ip.77.67.80.31) | - | [Windigo](https://vuldb.com/?actor.windigo) | High
2 | [85.214.80.4](https://vuldb.com/?ip.85.214.80.4) | h2463956.stratoserver.net | [Windigo](https://vuldb.com/?actor.windigo) | High
3 | [94.23.208.20](https://vuldb.com/?ip.94.23.208.20) | ns321476.ip-94-23-208.eu | [Windigo](https://vuldb.com/?actor.windigo) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1505 | CWE-89 | SQL Injection | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/uncpath/` | Medium
2 | File | `/var/log/restjavad.0.log` | High
3 | File | `init.php` | Medium
4 | ... | ... | ...

There are 5 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/windigo

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
