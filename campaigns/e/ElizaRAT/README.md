# ElizaRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ElizaRAT_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ElizaRAT:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)

## Actors

These _actors_ are associated with ElizaRAT or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT36](https://vuldb.com/?actor.apt36) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ElizaRAT.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [38.54.84.83](https://vuldb.com/?ip.38.54.84.83) | - | [APT36](https://vuldb.com/?actor.apt36) | High
2 | [64.227.134.248](https://vuldb.com/?ip.64.227.134.248) | - | [APT36](https://vuldb.com/?actor.apt36) | High
3 | [83.171.248.67](https://vuldb.com/?ip.83.171.248.67) | vmi1548375.contaboserver.net | [APT36](https://vuldb.com/?actor.apt36) | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ElizaRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ElizaRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.asp` | Low
2 | File | `/nidp/idff/sso` | High
3 | File | `/search` | Low
4 | File | `/var/run/.inetd.uds` | High
5 | File | `about` | Low
6 | File | `addressbook.php` | High
7 | File | `admin-ajax.php` | High
8 | File | `admin/` | Low
9 | File | `afd.sys` | Low
10 | File | `aolfix.exe` | Medium
11 | File | `api.php` | Low
12 | File | `apply.cgi` | Medium
13 | File | `auth-options.c` | High
14 | File | `bcbadmSettings.jsp` | High
15 | File | `calendar.php` | Medium
16 | ... | ... | ...

There are 132 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://research.checkpoint.com/2024/the-evolution-of-transparent-tribes-new-malware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!