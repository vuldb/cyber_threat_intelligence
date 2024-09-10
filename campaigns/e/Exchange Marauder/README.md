# Exchange Marauder - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Exchange Marauder_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Exchange Marauder:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Exchange Marauder or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Exchange Marauder](https://vuldb.com/?actor.exchange_marauder) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Exchange Marauder.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.254.43.18](https://vuldb.com/?ip.5.254.43.18) | - | [Exchange Marauder](https://vuldb.com/?actor.exchange_marauder) | High
2 | [80.92.205.81](https://vuldb.com/?ip.80.92.205.81) | vm302679.pq.hosting | [Exchange Marauder](https://vuldb.com/?actor.exchange_marauder) | High
3 | [103.77.192.219](https://vuldb.com/?ip.103.77.192.219) | - | [Exchange Marauder](https://vuldb.com/?actor.exchange_marauder) | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Exchange Marauder. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Exchange Marauder. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/cgi-bin/luci/api/auth` | High
3 | File | `/filemanager/upload.php` | High
4 | File | `/resources//../` | High
5 | File | `/src/Illuminate/Laravel.php` | High
6 | File | `/usr/local/nagiosxi/html/includes/configwizards/switch/switch.inc.php` | High
7 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
8 | File | `/wp-json/oembed/1.0/embed?url` | High
9 | File | `about.php` | Medium
10 | File | `admin/modules/tools/ip_history_logs.php` | High
11 | File | `adminer.php` | Medium
12 | File | `admin_feature.php` | High
13 | File | `api_poller.php` | High
14 | ... | ... | ...

There are 115 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://vxug.fakedoma.in/archive/APTs/2021/2021.03.02(1)/Operation%20Exchange%20Marauder.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
