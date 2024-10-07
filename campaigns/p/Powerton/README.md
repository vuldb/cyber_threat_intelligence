# Powerton - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Powerton_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Powerton:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Powerton or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT33](https://vuldb.com/?actor.apt33) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Powerton.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.79.66.241](https://vuldb.com/?ip.5.79.66.241) | - | [APT33](https://vuldb.com/?actor.apt33) | High
2 | [51.254.71.223](https://vuldb.com/?ip.51.254.71.223) | ip223.ip-51-254-71.eu | [APT33](https://vuldb.com/?actor.apt33) | High
3 | [85.206.161.216](https://vuldb.com/?ip.85.206.161.216) | 216-161-206-85.bacloud.info | [APT33](https://vuldb.com/?actor.apt33) | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Powerton. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Powerton. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/maintenance/view_designation.php` | High
2 | File | `/admin/orders/update_status.php` | High
3 | File | `/admin/sys_sql_query.php` | High
4 | File | `/ajax.php?action=delete_block` | High
5 | File | `/application/index/common.php` | High
6 | File | `/cgi-bin/cstecgi.cgi` | High
7 | File | `/cgi-bin/wapopen` | High
8 | File | `/etc/fstab` | Medium
9 | ... | ... | ...

There are 66 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.fireeye.com/blog/threat-research/2018/12/overruled-containing-a-potentially-destructive-adversary.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
