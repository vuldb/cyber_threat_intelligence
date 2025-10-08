# SimpleHelp - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SimpleHelp_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SimpleHelp:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SimpleHelp or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Medusa](https://vuldb.com/?actor.medusa) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SimpleHelp.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [89.36.161.17](https://vuldb.com/?ip.89.36.161.17) | - | [Medusa](https://vuldb.com/?actor.medusa) | High
2 | [143.110.243.154](https://vuldb.com/?ip.143.110.243.154) | - | [Medusa](https://vuldb.com/?actor.medusa) | High
3 | [213.183.63.41](https://vuldb.com/?ip.213.183.63.41) | virt.reserved.ds | [Medusa](https://vuldb.com/?actor.medusa) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SimpleHelp. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SimpleHelp. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/edit-card-detail.php` | High
2 | File | `/admin/index.php` | High
3 | File | `/admin/maintenance/view_designation.php` | High
4 | File | `/admin/reg.php` | High
5 | File | `/api /v3/auth` | High
6 | File | `/classes/SystemSettings.php?f=update_settings` | High
7 | File | `/filemanager/upload` | High
8 | File | `/forum/away.php` | High
9 | File | `/kortex_lite/control/edit_profile.php` | High
10 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
11 | File | `/novel/bookSetting/list` | High
12 | File | `/out.php` | Medium
13 | File | `/php/ping.php` | High
14 | ... | ... | ...

There are 106 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/talos-ir-ransomware-engagements-and-the-significance-of-timeliness-in-incident-response/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
