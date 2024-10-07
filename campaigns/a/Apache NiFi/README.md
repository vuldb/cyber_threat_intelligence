# Apache NiFi - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Apache NiFi_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Apache NiFi:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [UA](https://vuldb.com/?country.ua)

## Actors

These _actors_ are associated with Apache NiFi or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Apache NiFi.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.184.240.34](https://vuldb.com/?ip.31.184.240.34) | 106863.web.hosting-russia.ru | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [93.189.46.81](https://vuldb.com/?ip.93.189.46.81) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [185.122.204.197](https://vuldb.com/?ip.185.122.204.197) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Apache NiFi. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Apache NiFi. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config_time_sync.php` | High
2 | File | `/forum/away.php` | High
3 | File | `/includes/event-management/index.php` | High
4 | File | `/lua/set-passwd.lua` | High
5 | ... | ... | ...

There are 27 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://exchange.xforce.ibmcloud.com/threats/guid:f2289a3500a18206c66ea957c56442af
* https://isc.sans.edu/diary/Your+Business+Data+and+Machine+Learning+at+Risk+Attacks+Against+Apache+NiFi/29900

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
