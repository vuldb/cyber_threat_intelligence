# Matanbuchus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Matanbuchus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Matanbuchus:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Matanbuchus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [BelialDemon](https://vuldb.com/?actor.belialdemon) | High
2 | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Matanbuchus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [34.94.151.129](https://vuldb.com/?ip.34.94.151.129) | 129.151.94.34.bc.googleusercontent.com | [BelialDemon](https://vuldb.com/?actor.belialdemon) | Medium
2 | [34.105.89.82](https://vuldb.com/?ip.34.105.89.82) | 82.89.105.34.bc.googleusercontent.com | [BelialDemon](https://vuldb.com/?actor.belialdemon) | Medium
3 | [34.106.243.174](https://vuldb.com/?ip.34.106.243.174) | 174.243.106.34.bc.googleusercontent.com | [BelialDemon](https://vuldb.com/?actor.belialdemon) | Medium
4 | [44.208.127.245](https://vuldb.com/?ip.44.208.127.245) | ec2-44-208-127-245.compute-1.amazonaws.com | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | Medium
5 | [185.11.61.169](https://vuldb.com/?ip.185.11.61.169) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
6 | [185.11.61.170](https://vuldb.com/?ip.185.11.61.170) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
7 | [185.11.61.171](https://vuldb.com/?ip.185.11.61.171) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
8 | [185.11.61.172](https://vuldb.com/?ip.185.11.61.172) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
9 | [185.217.1.23](https://vuldb.com/?ip.185.217.1.23) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
10 | [190.123.44.220](https://vuldb.com/?ip.190.123.44.220) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
11 | [193.109.85.27](https://vuldb.com/?ip.193.109.85.27) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
12 | [193.109.85.31](https://vuldb.com/?ip.193.109.85.31) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
13 | [193.109.85.43](https://vuldb.com/?ip.193.109.85.43) | - | [Matanbuchus](https://vuldb.com/?actor.matanbuchus) | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Matanbuchus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | ... | ... | ... | ...

There are 12 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Matanbuchus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/?page=user/manage_user&id=3` | High
2 | File | `/Admin/add-student.php` | High
3 | File | `/admin/attendance_row.php` | High
4 | File | `/admin/request-received-bydonar.php` | High
5 | File | `/admin/test_status.php` | High
6 | File | `/admin_route/inc_service_credits.php` | High
7 | File | `/cgi-bin/cstecgi.cgi` | High
8 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
9 | File | `/edituser.php` | High
10 | File | `/etc/shadow` | Medium
11 | File | `/goform/CertListInfo` | High
12 | ... | ... | ...

There are 95 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://circleid.com/posts/20220721-matanbuchus-with-cobalt-strike-not-your-favorite-combo
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-06-16%20Matanbuchus%20IOCs
* https://search.censys.io/hosts/193.109.85.27
* https://search.censys.io/hosts/193.109.85.31
* https://search.censys.io/hosts/194.67.193.66
* https://search.censys.io/hosts/194.67.193.68
* https://search.censys.io/hosts/194.67.193.70
* https://search.censys.io/hosts/194.67.193.71
* https://search.censys.io/hosts/194.67.193.234
* https://search.censys.io/hosts/194.67.193.235
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=193.109.85.54
* https://tracker.viriback.com/index.php?q=193.109.85.61
* https://tracker.viriback.com/index.php?q=193.109.85.78
* https://tracker.viriback.com/index.php?q=193.109.85.79
* https://tracker.viriback.com/index.php?q=194.67.193.205
* https://unit42.paloaltonetworks.com/matanbuchus-malware-as-a-service/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
