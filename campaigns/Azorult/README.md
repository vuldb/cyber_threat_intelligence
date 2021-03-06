# Azorult - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Azorult_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Azorult:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Azorult or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Ramnit](https://vuldb.com/?actor.ramnit) | High
2 | [Amadey Bot](https://vuldb.com/?actor.amadey_bot) | High
3 | [Azorult](https://vuldb.com/?actor.azorult) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Azorult.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.59.42.63](https://vuldb.com/?ip.2.59.42.63) | vds-cw08597.timeweb.ru | [Amadey Bot](https://vuldb.com/?actor.amadey_bot) | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | [Azorult](https://vuldb.com/?actor.azorult) | High
3 | [23.106.124.148](https://vuldb.com/?ip.23.106.124.148) | - | [Azorult](https://vuldb.com/?actor.azorult) | High
4 | [37.140.192.153](https://vuldb.com/?ip.37.140.192.153) | scp59.hosting.reg.ru | [Azorult](https://vuldb.com/?actor.azorult) | High
5 | [37.140.192.166](https://vuldb.com/?ip.37.140.192.166) | scp46.hosting.reg.ru | [Azorult](https://vuldb.com/?actor.azorult) | High
6 | [45.76.18.39](https://vuldb.com/?ip.45.76.18.39) | 45.76.18.39.vultrusercontent.com | [Azorult](https://vuldb.com/?actor.azorult) | High
7 | [45.139.236.14](https://vuldb.com/?ip.45.139.236.14) | - | [Azorult](https://vuldb.com/?actor.azorult) | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Azorult. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Azorult. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/deluser.php` | High
3 | File | `/administration/theme.php` | High
4 | File | `/BindAccount/SuccessTips.js` | High
5 | File | `/home/httpd/cgi-bin/cgi.cgi` | High
6 | File | `/login.html` | Medium
7 | File | `/medical/inventories.php` | High
8 | File | `/pages.php` | Medium
9 | File | `/uncpath/` | Medium
10 | File | `/usr/local/psa/admin/sbin/wrapper` | High
11 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
12 | File | `/vloggers_merch/classes/Master.php?f=delete_order` | High
13 | File | `abm.aspx` | Medium
14 | File | `actions/ChangeConfiguration.html` | High
15 | ... | ... | ...

There are 119 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.cyble.com/2021/10/26/a-deep-dive-analysis-of-azorult-stealer/
* https://blog.talosintelligence.com/2020/01/threat-roundup-0117-0124.html
* https://blogs.blackberry.com/en/2020/01/threat-spotlight-amadey-bot
* https://isc.sans.edu/forums/diary/More+malspam+pushing+passwordprotected+Word+docs+for+AZORult+and+Hermes+Ransomware/23992/
* https://research.checkpoint.com/2018/new-ramnit-campaign-spreads-azorult-malware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
