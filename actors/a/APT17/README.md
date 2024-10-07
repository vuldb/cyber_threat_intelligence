# APT17 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT17](https://vuldb.com/?actor.apt17). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt17](https://vuldb.com/?actor.apt17)

## Campaigns

The following _campaigns_ are known and can be associated with APT17:

* CCleaner

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT17:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT17.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.52.111](https://vuldb.com/?ip.1.234.52.111) | - | - | High
2 | [8.9.11.130](https://vuldb.com/?ip.8.9.11.130) | 8.9.11.130.vultr.com | - | Medium
3 | [45.76.6.149](https://vuldb.com/?ip.45.76.6.149) | 45.76.6.149.vultr.com | - | Medium
4 | [45.76.31.159](https://vuldb.com/?ip.45.76.31.159) | 45.76.31.159.vultr.com | - | Medium
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT17_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT17. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/api/cron/settings/setJob/` | High
3 | File | `/api/DownloadUrlResponse.ashx` | High
4 | File | `/wbg/core/_includes/authorization.inc.php` | High
5 | File | `addentry.php` | Medium
6 | File | `burl.c` | Low
7 | File | `data/gbconfiguration.dat` | High
8 | ... | ... | ...

There are 58 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q2
* https://github.com/fireeye/iocs/blob/master/APT17/7b9e87c5-b619-4a13-b862-0145614d359a.ioc
* https://www.threatminer.org/report.php?q=EvidenceAuroraOperationStillActive_SupplyChainAttackThroughCCleaner-Intezer.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
