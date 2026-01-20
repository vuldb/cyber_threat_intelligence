# Banshee - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Banshee_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Banshee:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [DE](https://vuldb.com/?country.de)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Banshee or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [BANSHEE](https://vuldb.com/?actor.banshee) | High
2 | [Russia Unknown](https://vuldb.com/?actor.russia_unknown) | High
3 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Banshee.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [41.216.183.49](https://vuldb.com/?ip.41.216.183.49) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [45.142.122.92](https://vuldb.com/?ip.45.142.122.92) | BUILDER.aeza.network | [BANSHEE](https://vuldb.com/?actor.banshee) | High
3 | [195.24.236.129](https://vuldb.com/?ip.195.24.236.129) | - | [BANSHEE](https://vuldb.com/?actor.banshee) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Banshee. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Banshee. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config_ISCGroupNoCache.php` | High
2 | File | `/admin/search-booking-request.php` | High
3 | File | `/admin/suppliers/view_details.php` | High
4 | File | `/admin/users.php` | High
5 | File | `/application/websocket/controller/Setting.php` | High
6 | File | `/booklist.php?subcatid=1` | High
7 | File | `/detail.php` | Medium
8 | File | `/editar-produto.php` | High
9 | File | `/endpoint/delete.php` | High
10 | File | `/enquiry.php` | Medium
11 | File | `/file/accept.php` | High
12 | File | `/forget.php` | Medium
13 | File | `/forgot.php` | Medium
14 | File | `/librarian/bookdetails.php` | High
15 | File | `/member/chat.php` | High
16 | ... | ... | ...

There are 127 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://research.checkpoint.com/2025/banshee-macos-stealer-that-stole-code-from-macos-xprotect/
* https://www.elastic.co/security-labs/beyond-the-wail
* https://x.com/malwrhunterteam/status/1997959762541994292

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
