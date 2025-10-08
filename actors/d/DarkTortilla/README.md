# DarkTortilla - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [DarkTortilla](https://vuldb.com/?actor.darktortilla). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.darktortilla](https://vuldb.com/?actor.darktortilla)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DarkTortilla:

* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* [ID](https://vuldb.com/?country.id)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DarkTortilla.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [87.120.222.208](https://vuldb.com/?ip.87.120.222.208) | - | - | High
2 | [161.35.226.71](https://vuldb.com/?ip.161.35.226.71) | - | - | High
3 | [178.73.192.18](https://vuldb.com/?ip.178.73.192.18) | c-178-73-192-18.ip4.frootvpn.com | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _DarkTortilla_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
2 | T1505 | CWE-89 | SQL Injection | High
3 | T1600.001 | CWE-321 | Key Management Error | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by DarkTortilla. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `admin/adminlogin.php` | High
2 | File | `cgReportController.do` | High
3 | Argument | `begin_date` | Medium
4 | ... | ... | ...

There are 2 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/fb1da262a06ff9c8e4b1ef5687e2b5556e4d422356053b7d6922238ecb578e19/
* https://urlhaus.abuse.ch/url/3562903/
* https://urlhaus.abuse.ch/url/3597922/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
