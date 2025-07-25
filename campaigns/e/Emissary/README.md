# Emissary - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Emissary_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Emissary:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Emissary or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Emissary](https://vuldb.com/?actor.emissary) | High
2 | [Lotus Blossom](https://vuldb.com/?actor.lotus_blossom) | High
3 | [TG-3390](https://vuldb.com/?actor.tg-3390) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Emissary.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [101.55.33.92](https://vuldb.com/?ip.101.55.33.92) | - | [Lotus Blossom](https://vuldb.com/?actor.lotus_blossom) | High
2 | [101.55.33.95](https://vuldb.com/?ip.101.55.33.95) | - | [Lotus Blossom](https://vuldb.com/?actor.lotus_blossom) | High
3 | [101.55.121.79](https://vuldb.com/?ip.101.55.121.79) | - | [Lotus Blossom](https://vuldb.com/?actor.lotus_blossom) | High
4 | [103.59.144.183](https://vuldb.com/?ip.103.59.144.183) | - | [TG-3390](https://vuldb.com/?actor.tg-3390) | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Emissary. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Emissary. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/live_api.cgi` | High
2 | File | `/etc/shadow` | Medium
3 | File | `/infusions/shoutbox_panel/shoutbox_admin.php` | High
4 | File | `/oscommerce/admin/currencies.php` | High
5 | File | `/proc/pid/syscall` | High
6 | File | `/session/list/allActiveSession` | High
7 | File | `/syslog_rules` | High
8 | File | `/upload` | Low
9 | File | `/users/{id}` | Medium
10 | File | `/video` | Low
11 | File | `ActivityManagerService.java` | High
12 | File | `adaptmap_reg.c` | High
13 | File | `admin.cgi` | Medium
14 | File | `admin.php?action=files` | High
15 | File | `app/dialplans/dialplan_detail_edit.php` | High
16 | ... | ... | ...

There are 128 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/emissary-panda-attacks-middle-east-government-sharepoint-servers/
* https://unit42.paloaltonetworks.com/emissary-trojan-changelog-did-operation-lotus-blossom-cause-it-to-evolve/
* https://www.nccgroup.com/uk/about-us/newsroom-and-events/blogs/2018/may/emissary-panda-a-potential-new-malicious-tool/
* https://www.threatminer.org/report.php?q=EmissaryTrojanChangelog_DidOperationLotusBlossomCauseIttoEvolve_-PaloAltoNetworksBlogPaloAltoNetworksBlog.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
