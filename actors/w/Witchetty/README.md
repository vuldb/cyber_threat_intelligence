# Witchetty - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Witchetty](https://vuldb.com/?actor.witchetty). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.witchetty](https://vuldb.com/?actor.witchetty)

## Campaigns

The following _campaigns_ are known and can be associated with Witchetty:

* LookBack

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Witchetty:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Witchetty.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.252.176.3](https://vuldb.com/?ip.5.252.176.3) | no-rdns.mivocloud.com | LookBack | High
2 | [153.92.1.125](https://vuldb.com/?ip.153.92.1.125) | - | - | High
3 | [185.225.19.55](https://vuldb.com/?ip.185.225.19.55) | no-rdns.mivocloud.com | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Witchetty_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Witchetty. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/RecordingList/DownloadRecord?file=` | High
2 | File | `/apply.cgi` | Medium
3 | File | `/cgi-bin/cstecgi.cgi` | High
4 | File | `/etc/openstack-dashboard/local_settings` | High
5 | File | `/php/ping.php` | High
6 | File | `/rapi/read_url` | High
7 | File | `/scripts/unlock_tasks.php` | High
8 | File | `/SysInfo1.htm` | High
9 | File | `/sysinfo_json.cgi` | High
10 | File | `/system/dictData/loadDictItem` | High
11 | File | `/system/user/modules/mod_users/controller.php` | High
12 | File | `/uncpath/` | Medium
13 | ... | ... | ...

There are 97 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/witchetty-steganography-espionage

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
