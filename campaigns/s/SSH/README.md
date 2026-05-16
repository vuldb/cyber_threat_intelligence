# SSH - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SSH_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SSH:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [IO](https://vuldb.com/?country.io)
* ...

There are 5 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SSH or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [asterzeu](https://vuldb.com/?actor.asterzeu) | High
2 | [SSHNET](https://vuldb.com/?actor.sshnet) | High
3 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SSH.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [37.59.181.219](https://vuldb.com/?ip.37.59.181.219) | gateway.tcparmor.com | [SSHNET](https://vuldb.com/?actor.sshnet) | High
2 | [45.156.87.105](https://vuldb.com/?ip.45.156.87.105) | - | [SSHNET](https://vuldb.com/?actor.sshnet) | High
3 | [61.14.210.71](https://vuldb.com/?ip.61.14.210.71) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [70.34.220.100](https://vuldb.com/?ip.70.34.220.100) | 70.34.220.100.vultrusercontent.com | [asterzeu](https://vuldb.com/?actor.asterzeu) | Medium
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SSH. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-35 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SSH. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin-cp/media` | High
2 | File | `/admin/` | Low
3 | File | `/admin/admin-area.php` | High
4 | File | `/admin/curriculum/view_curriculum.php` | High
5 | File | `/admin/edit-subcategory.php` | High
6 | File | `/admin/index3.php` | High
7 | File | `/admin/login.php` | High
8 | File | `/admin/offenses/view_details.php` | High
9 | File | `/admin/request-received-bydonar.php` | High
10 | File | `/admin/tag.php` | High
11 | File | `/admin/voters_delete.php` | High
12 | File | `/api/wizard/getBasicInfo` | High
13 | File | `/bwdates-report-result.php` | High
14 | File | `/cgformTemplateController.do?doAdd` | High
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/sysconf.cgi` | High
17 | File | `/cgi-bin/wireless.cgi` | High
18 | File | `/ecommerce/admin/login.php` | High
19 | ... | ... | ...

There are 155 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/59972/
* https://asec.ahnlab.com/en/92004/
* https://isc.sans.edu/diary/32536
* https://isc.sans.edu/diary/32708
* https://threatfox.abuse.ch
* https://www.microsoft.com/en-us/security/blog/2023/06/22/iot-devices-and-linux-based-systems-targeted-by-openssh-trojan-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
