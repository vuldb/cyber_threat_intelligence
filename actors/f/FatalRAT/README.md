# FatalRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FatalRAT](https://vuldb.com/?actor.fatalrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fatalrat](https://vuldb.com/?actor.fatalrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FatalRAT:

* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FatalRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [103.119.44.93](https://vuldb.com/?ip.103.119.44.93) | - | - | High
2 | [103.119.44.100](https://vuldb.com/?ip.103.119.44.100) | - | - | High
3 | [103.119.44.152](https://vuldb.com/?ip.103.119.44.152) | - | - | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FatalRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1068 | CWE-264 | Execution with Unnecessary Privileges | High
2 | T1505 | CWE-89 | SQL Injection | High
3 | T1608.002 | CWE-434 | Incomplete Identification of Uploaded File Variables | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FatalRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `json_reader.cpp` | High
2 | File | `web/jquery/uploader/uploadify.php` | High
3 | Argument | `capability_type` | High

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/66/fatalrat-backdoor-ioc/
* https://community.blueliv.com/#!/s/6107d20982df4141693319a7
* https://threatfox.abuse.ch
* https://www.welivesecurity.com/2023/02/16/these-arent-apps-youre-looking-for-fake-installers/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
