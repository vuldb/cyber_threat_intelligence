# Pulsepack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Pulsepack_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pulsepack:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Pulsepack or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Earth Lamia](https://vuldb.com/?actor.earth_lamia) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pulsepack.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [104.233.140.135](https://vuldb.com/?ip.104.233.140.135) | - | [Earth Lamia](https://vuldb.com/?actor.earth_lamia) | High
2 | [134.122.176.156](https://vuldb.com/?ip.134.122.176.156) | - | [Earth Lamia](https://vuldb.com/?actor.earth_lamia) | High
3 | [141.11.149.124](https://vuldb.com/?ip.141.11.149.124) | - | [Earth Lamia](https://vuldb.com/?actor.earth_lamia) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Pulsepack. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
3 | T1068 | CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Pulsepack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/class.php?dowhat=modifyclass` | High
2 | File | `/Admin/registration.php` | High
3 | File | `/adminPage/www/addOver` | High
4 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
5 | File | `/cgi-bin/nas_sharing.cgi` | High
6 | File | `/control/login.php` | High
7 | File | `/decoration/admin/userregister.php` | High
8 | ... | ... | ...

There are 52 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://documents.trendmicro.com/assets/txt/earth_lamia_iocs_v2CeWlPie.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
