# Chafer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Chafer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chafer:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [ES](https://vuldb.com/?country.es)
* ...

There are 32 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Chafer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT39](https://vuldb.com/?actor.apt39) | High
2 | [Chafer](https://vuldb.com/?actor.chafer) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chafer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [83.142.230.113](https://vuldb.com/?ip.83.142.230.113) | - | [Chafer](https://vuldb.com/?actor.chafer) | High
2 | [89.38.97.112](https://vuldb.com/?ip.89.38.97.112) | 89-38-97-112.hosted-by-worldstream.net | [Chafer](https://vuldb.com/?actor.chafer) | High
3 | [89.38.97.115](https://vuldb.com/?ip.89.38.97.115) | 89-38-97-115.hosted-by-worldstream.net | [Chafer](https://vuldb.com/?actor.chafer) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Chafer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Chafer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//etc/RT2870STA.dat` | High
2 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
3 | File | `/api/login` | Medium
4 | File | `/appConfig/userDB.json` | High
5 | File | `/bin/boa` | Medium
6 | File | `/cgi-bin/wapopen` | High
7 | File | `/cgi-bin/widget_api.cgi` | High
8 | File | `/CPE` | Low
9 | File | `/cwp_{SESSION_HASH}/admin/loader_ajax.php` | High
10 | File | `/jquery_file_upload/server/php/index.php` | High
11 | File | `/librarian/bookdetails.php` | High
12 | File | `/magnoliaPublic/travel/members/login.html` | High
13 | File | `/Main_AdmStatus_Content.asp` | High
14 | File | `/public/login.htm` | High
15 | File | `/requests.php` | High
16 | File | `/self.key` | Medium
17 | ... | ... | ...

There are 139 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/chafer-used-remexi-malware/89538/
* https://unit42.paloaltonetworks.com/new-python-based-payload-mechaflounder-used-by-chafer/
* https://www.threatminer.org/report.php?q=Chafer_LatestAttacksRevealHeightenedAmbitions_SymantecBlogs.pdf&y=2018
* https://www.threatminer.org/_reports/2019/NewPython-BasedPayloadMechaFlounderUsedbyChafer.pdf#viewer.action=download

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
