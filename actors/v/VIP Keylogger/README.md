# VIP Keylogger - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [VIP Keylogger](https://vuldb.com/?actor.vip_keylogger). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.vip_keylogger](https://vuldb.com/?actor.vip_keylogger)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with VIP Keylogger:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of VIP Keylogger.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [185.244.151.84](https://vuldb.com/?ip.185.244.151.84) | hosting2.ro.hostsailor.com | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _VIP Keylogger_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1204.001 | CWE-601 | Open Redirect | High
2 | T1505 | CWE-89 | SQL Injection | High
3 | T1608.002 | CWE-434 | Incomplete Identification of Uploaded File Variables | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by VIP Keylogger. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/wlogin.cgi` | High
2 | Argument | `aa/ab` | Low

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/b29b1d2de4ad836a8551b757c2e134cbcb1248f50e1e5eeb75c6efcd49d73380/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
