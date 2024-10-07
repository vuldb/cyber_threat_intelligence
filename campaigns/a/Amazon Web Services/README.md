# Amazon Web Services - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Amazon Web Services_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Amazon Web Services:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Amazon Web Services or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TeamTNT](https://vuldb.com/?actor.teamtnt) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Amazon Web Services.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.125.10.23](https://vuldb.com/?ip.3.125.10.23) | ec2-3-125-10-23.eu-central-1.compute.amazonaws.com | [TeamTNT](https://vuldb.com/?actor.teamtnt) | Medium
2 | [15.236.100.141](https://vuldb.com/?ip.15.236.100.141) | ec2-15-236-100-141.eu-west-3.compute.amazonaws.com | [TeamTNT](https://vuldb.com/?actor.teamtnt) | Medium
3 | [45.9.148.108](https://vuldb.com/?ip.45.9.148.108) | mx1.dendrite.network | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Amazon Web Services. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Amazon Web Services. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/ajax.php?action=read_msg` | High
2 | File | `/debug/pprof` | Medium
3 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
4 | File | `/env` | Low
5 | File | `/goform/SetNetControlList` | High
6 | File | `/goform/SetStaticRouteCfg` | High
7 | File | `/src/chatbotapp/chatWindow.java` | High
8 | File | `/usr/bin/pkexec` | High
9 | File | `admin/categories_industry.php` | High
10 | ... | ... | ...

There are 77 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2022/04/teamtnt-targeting-aws-alibaba.html
* https://www.sentinelone.com/labs/cloudy-with-a-chance-of-credentials-aws-targeting-cred-stealer-expands-to-azure-gcp/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
