# StealC and Amadey and Credential Flusher - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _StealC and Amadey and Credential Flusher_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with StealC and Amadey and Credential Flusher:

* [RU](https://vuldb.com/?country.ru)

## Actors

These _actors_ are associated with StealC and Amadey and Credential Flusher or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Autoit](https://vuldb.com/?actor.autoit) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of StealC and Amadey and Credential Flusher.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.41.244.11](https://vuldb.com/?ip.31.41.244.11) | - | [Autoit](https://vuldb.com/?actor.autoit) | High
2 | [185.215.113.103](https://vuldb.com/?ip.185.215.113.103) | - | [Autoit](https://vuldb.com/?actor.autoit) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within StealC and Amadey and Credential Flusher. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1505 | CWE-89 | SQL Injection | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during StealC and Amadey and Credential Flusher. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/show_news.php` | High
2 | Argument | `id` | Low
3 | Input Value | `AND (SELECT 1222 FROM(SELECT COUNT(*),CONCAT(0x71786b7a71,(SELECT (ELT(1222=1222,1))),0x717a627871,FLOOR(RAND(0)*2))x FROM INFORMATION_SCHEMA.CHARACTER_SETS GROUP BY x)a)` | High
4 | ... | ... | ...

There are 1 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://research.openanalysis.net/credflusher/kiosk/stealer/stealc/amadey/autoit/2024/09/11/cred-flusher.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
