# Onyx Sleet - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Onyx Sleet](https://vuldb.com/?actor.onyx_sleet). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.onyx_sleet](https://vuldb.com/?actor.onyx_sleet)

## Campaigns

The following _campaigns_ are known and can be associated with Onyx Sleet:

* CVE-2023-42793
* Preft

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Onyx Sleet:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [BE](https://vuldb.com/?country.be)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Onyx Sleet.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.155.37.101](https://vuldb.com/?ip.45.155.37.101) | - | CVE-2023-42793 | High
2 | [51.81.168.157](https://vuldb.com/?ip.51.81.168.157) | ip157.ip-51-81-168.us | Preft | High
3 | [84.38.134.56](https://vuldb.com/?ip.84.38.134.56) | ip-134-56.dataclub.info | CVE-2023-42793 | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Onyx Sleet_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Onyx Sleet. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/Plugins/update.html` | High
2 | File | `/api/blade-log/api/list` | High
3 | File | `/api /v3/auth` | High
4 | File | `/classes/SystemSettings.php?f=update_settings` | High
5 | File | `/data/remove` | Medium
6 | File | `/dede/file_manage_control.php` | High
7 | File | `/files/list-file` | High
8 | File | `/forum/away.php` | High
9 | ... | ... | ...

There are 64 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://symantec-enterprise-blogs.security.com/threat-intelligence/stonefly-north-korea-extortion
* https://www.microsoft.com/en-us/security/blog/2023/10/18/multiple-north-korean-threat-actors-exploiting-the-teamcity-cve-2023-42793-vulnerability/
* https://www.microsoft.com/en-us/security/blog/2024/07/25/onyx-sleet-uses-array-of-malware-to-gather-intelligence-for-north-korea/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
