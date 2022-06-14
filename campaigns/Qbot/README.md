# Qbot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Qbot_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Qbot:

* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Qbot or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA570](https://vuldb.com/?actor.ta570) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Qbot.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [85.239.55.228](https://vuldb.com/?ip.85.239.55.228) | - | [TA570](https://vuldb.com/?actor.ta570) | High
2 | [104.36.229.139](https://vuldb.com/?ip.104.36.229.139) | - | [TA570](https://vuldb.com/?actor.ta570) | High
3 | [185.234.247.119](https://vuldb.com/?ip.185.234.247.119) | - | [TA570](https://vuldb.com/?actor.ta570) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Qbot. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Qbot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `admin/vqmods.app/vqmods.inc.php` | High
2 | File | `index.php` | Medium
3 | Argument | `SSPI_HEADER` | Medium

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.proofpoint.com/us/blog/threat-insight/first-step-initial-access-leads-ransomware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
