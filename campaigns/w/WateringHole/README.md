# WateringHole - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _WateringHole_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WateringHole:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with WateringHole or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WateringHole.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [104.248.144.136](https://vuldb.com/?ip.104.248.144.136) | - | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
2 | [104.248.144.178](https://vuldb.com/?ip.104.248.144.178) | gamesbar.vn | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
3 | [128.199.159.60](https://vuldb.com/?ip.128.199.159.60) | - | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
4 | [142.93.71.92](https://vuldb.com/?ip.142.93.71.92) | - | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
5 | [142.93.75.161](https://vuldb.com/?ip.142.93.75.161) | - | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
6 | [142.93.75.172](https://vuldb.com/?ip.142.93.75.172) | - | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
7 | [142.93.75.192](https://vuldb.com/?ip.142.93.75.192) | - | [OceanLotus](https://vuldb.com/?actor.oceanlotus) | High
8 | ... | ... | ... | ...

There are 28 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within WateringHole. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during WateringHole. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/store.php` | High
4 | File | `/admin_system/api.php` | High
5 | File | `/api/swaggerui/static` | High
6 | File | `/article/DelectArticleById/` | High
7 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/forum/away.php` | High
10 | File | `/maint/index.php` | High
11 | File | `/oauth/idp/.well-known/openid-configuration` | High
12 | File | `/planet` | Low
13 | File | `/see_more_details.php` | High
14 | ... | ... | ...

There are 112 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/oceanlotus

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
