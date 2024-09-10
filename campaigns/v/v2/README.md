# v2 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _v2_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with v2:

* [US](https://vuldb.com/?country.us)
* [PL](https://vuldb.com/?country.pl)
* [ES](https://vuldb.com/?country.es)

## Actors

These _actors_ are associated with v2 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [MyKings](https://vuldb.com/?actor.mykings) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of v2.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [185.26.112.217](https://vuldb.com/?ip.185.26.112.217) | - | [MyKings](https://vuldb.com/?actor.mykings) | High
2 | [192.187.111.66](https://vuldb.com/?ip.192.187.111.66) | bee12.bumblebeeservers.com | [MyKings](https://vuldb.com/?actor.mykings) | High
3 | [﻿5.39.222.134](https://vuldb.com/?ip.﻿5.39.222.134) | - | [MyKings](https://vuldb.com/?actor.mykings) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within v2. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1202 | CWE-77 | Command Shell in Externally Accessible Directory | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during v2. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/download_frame.php` | High
2 | File | `ajax/api/hook/decodeArguments` | High
3 | File | `bits.c` | Low
4 | ... | ... | ...

There are 14 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/malware-MyKings-v2.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
