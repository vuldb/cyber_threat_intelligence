# Holmium - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Holmium_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Holmium:

* [CO](https://vuldb.com/?country.co)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)

## Actors

These _actors_ are associated with Holmium or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Peach Sandstorm](https://vuldb.com/?actor.peach_sandstorm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Holmium.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [76.8.60.64](https://vuldb.com/?ip.76.8.60.64) | - | [Peach Sandstorm](https://vuldb.com/?actor.peach_sandstorm) | High
2 | [102.129.215.40](https://vuldb.com/?ip.102.129.215.40) | concernedguid.sbs | [Peach Sandstorm](https://vuldb.com/?actor.peach_sandstorm) | High
3 | [108.62.118.240](https://vuldb.com/?ip.108.62.118.240) | static-108-62-118-240.nextroute.co | [Peach Sandstorm](https://vuldb.com/?actor.peach_sandstorm) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Holmium. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Holmium. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `Dynamiccontenttags.php` | High
2 | File | `internal/advanced_comment_system/admin.php` | High
3 | File | `member/member_order.php` | High
4 | ... | ... | ...

There are 11 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.microsoft.com/en-us/security/blog/2023/09/14/peach-sandstorm-password-spray-campaigns-enable-intelligence-collection-at-high-value-targets/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
