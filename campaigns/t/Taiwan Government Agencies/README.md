# Taiwan Government Agencies - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Taiwan Government Agencies_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Taiwan Government Agencies:

* [MS](https://vuldb.com/?country.ms)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Taiwan Government Agencies or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [BlackTech](https://vuldb.com/?actor.blacktech) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Taiwan Government Agencies.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [43.240.12.81](https://vuldb.com/?ip.43.240.12.81) | mail.terascape.net | [BlackTech](https://vuldb.com/?actor.blacktech) | High
2 | [45.124.25.31](https://vuldb.com/?ip.45.124.25.31) | hkhdc.laws.ms | [BlackTech](https://vuldb.com/?actor.blacktech) | High
3 | [45.124.25.226](https://vuldb.com/?ip.45.124.25.226) | hkhdc.laws.ms | [BlackTech](https://vuldb.com/?actor.blacktech) | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Taiwan Government Agencies. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Taiwan Government Agencies. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
2 | File | `/mifs/c/i/reg/reg.html` | High
3 | File | `/server-info` | Medium
4 | File | `/system/dept/edit` | High
5 | File | `/wp-json/oembed/1.0/embed?url` | High
6 | File | `a2billing/customer/iridium_threed.php` | High
7 | File | `admin.php?s=/Channel/add.html` | High
8 | File | `admin/class-bulk-editor-list-table.php` | High
9 | File | `administrator/components/com_media/helpers/media.php` | High
10 | File | `auth.asp` | Medium
11 | ... | ... | ...

There are 79 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.ithome.com.tw/news/139504

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
