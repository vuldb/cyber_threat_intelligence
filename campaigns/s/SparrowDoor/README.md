# SparrowDoor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SparrowDoor_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SparrowDoor:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [BR](https://vuldb.com/?country.br)

## Actors

These _actors_ are associated with SparrowDoor or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FamousSparrow](https://vuldb.com/?actor.famoussparrow) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SparrowDoor.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [43.254.216.195](https://vuldb.com/?ip.43.254.216.195) | - | [FamousSparrow](https://vuldb.com/?actor.famoussparrow) | High
2 | [45.131.179.24](https://vuldb.com/?ip.45.131.179.24) | - | [FamousSparrow](https://vuldb.com/?actor.famoussparrow) | High
3 | [103.85.25.166](https://vuldb.com/?ip.103.85.25.166) | - | [FamousSparrow](https://vuldb.com/?actor.famoussparrow) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SparrowDoor. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
3 | T1068 | CWE-269 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SparrowDoor. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `administrator/components/com_media/helpers/media.php` | High
2 | File | `cds-fpdf.php` | Medium
3 | File | `index.php?g=admin&m=index&a=index` | High
4 | ... | ... | ...

There are 13 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.welivesecurity.com/en/eset-research/you-will-always-remember-this-as-the-day-you-finally-caught-famoussparrow/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
