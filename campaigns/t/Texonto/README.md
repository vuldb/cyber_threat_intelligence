# Texonto - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Texonto_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Texonto:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Texonto or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Texonto](https://vuldb.com/?actor.texonto) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Texonto.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.9.148.165](https://vuldb.com/?ip.45.9.148.165) | - | [Texonto](https://vuldb.com/?actor.texonto) | High
2 | [45.9.148.207](https://vuldb.com/?ip.45.9.148.207) | - | [Texonto](https://vuldb.com/?actor.texonto) | High
3 | [45.9.150.58](https://vuldb.com/?ip.45.9.150.58) | - | [Texonto](https://vuldb.com/?actor.texonto) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Texonto. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Texonto. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config_time_sync.php` | High
2 | File | `/ajax.php?action=read_msg` | High
3 | File | `/api /v3/auth` | High
4 | File | `/cgi-bin/cstecgi.cgi` | High
5 | File | `/change_password_process` | High
6 | File | `/debug/pprof` | Medium
7 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
8 | File | `/devinfo` | Medium
9 | File | `/env` | Low
10 | File | `/etc/shadow.sample` | High
11 | File | `/goform/SetNetControlList` | High
12 | File | `/goform/SetStaticRouteCfg` | High
13 | File | `/index.php/newsletter/subscriber/new/` | High
14 | File | `/my_photo_gallery/image.php` | High
15 | File | `/product.php` | Medium
16 | File | `/src/chatbotapp/chatWindow.java` | High
17 | ... | ... | ...

There are 137 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/operation_texonto
* https://www.welivesecurity.com/en/eset-research/operation-texonto-information-operation-targeting-ukrainian-speakers-context-war/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
