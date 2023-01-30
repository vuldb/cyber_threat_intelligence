# Darkside - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Darkside_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Darkside:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)

## Actors

These _actors_ are associated with Darkside or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DarkSide](https://vuldb.com/?actor.darkside) | High
2 | [UNC2465](https://vuldb.com/?actor.unc2465) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Darkside.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [81.91.177.54](https://vuldb.com/?ip.81.91.177.54) | free.example.com | [UNC2465](https://vuldb.com/?actor.unc2465) | High
2 | [99.83.154.118](https://vuldb.com/?ip.99.83.154.118) | a51062ecadbb5a26e.awsglobalaccelerator.com | [DarkSide](https://vuldb.com/?actor.darkside) | High
3 | [176.103.62.217](https://vuldb.com/?ip.176.103.62.217) | - | [DarkSide](https://vuldb.com/?actor.darkside) | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Darkside. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1059 | CWE-94 | Cross Site Scripting | High
3 | T1068 | CWE-264 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Darkside. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/wapopen` | High
2 | File | `/cgi-bin/wlogin.cgi` | High
3 | File | `addentry.php` | Medium
4 | ... | ... | ...

There are 9 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-189a
* https://us-cert.cisa.gov/sites/default/files/publications/AA21-131A.stix.xml
* https://www.fireeye.com/blog/threat-research/2021/06/darkside-affiliate-supply-chain-software-compromise.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
