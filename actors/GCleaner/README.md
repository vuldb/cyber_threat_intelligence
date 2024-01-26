# GCleaner - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GCleaner](https://vuldb.com/?actor.gcleaner). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gcleaner](https://vuldb.com/?actor.gcleaner)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GCleaner:

* [RO](https://vuldb.com/?country.ro)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GCleaner.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.12.253.98](https://vuldb.com/?ip.5.12.253.98) | 5-12-253-98.residential.rdsnet.ro | - | High
2 | [45.12.253.51](https://vuldb.com/?ip.45.12.253.51) | - | - | High
3 | [45.12.253.56](https://vuldb.com/?ip.45.12.253.56) | - | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GCleaner_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1055 | CWE-74 | Injection | High
2 | T1059.007 | CWE-79 | Cross Site Scripting | High
3 | T1068 | CWE-269 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
4 | ... | ... | ... | ...

There are 3 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GCleaner. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `backend/base/Store.class.php` | High
2 | File | `swp/login/EJBRemoteService/` | High
3 | Argument | `PATH_INFO` | Medium

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/18e8a2e2-b2f5-4ca3-af48-05807b85c704
* https://threatfox.abuse.ch
* https://twitter.com/crep1x/status/1630992258584518656

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
