# Storm-1175 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Storm-1175](https://vuldb.com/?actor.storm-1175). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.storm-1175](https://vuldb.com/?actor.storm-1175)

## Campaigns

The following _campaigns_ are known and can be associated with Storm-1175:

* CVE-2025-10035

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Storm-1175:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Storm-1175.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.220.45.120](https://vuldb.com/?ip.31.220.45.120) | rhel9-satellite.vincenzomele.it | CVE-2025-10035 | High
2 | [45.11.183.123](https://vuldb.com/?ip.45.11.183.123) | - | CVE-2025-10035 | High
3 | [213.183.63.41](https://vuldb.com/?ip.213.183.63.41) | virt.reserved.ds | CVE-2025-10035 | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Storm-1175_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Storm-1175. This data is unique as it uses our predictive model for actor profiling.

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

There are 107 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.microsoft.com/en-us/security/blog/2025/10/06/investigating-active-exploitation-of-cve-2025-10035-goanywhere-managed-file-transfer-vulnerability/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
