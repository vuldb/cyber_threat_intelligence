# Iron - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Iron](https://vuldb.com/?actor.iron). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.iron](https://vuldb.com/?actor.iron)

## Campaigns

The following _campaigns_ are known and can be associated with Iron:

* XBash

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Iron:

* [ES](https://vuldb.com/?country.es)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Iron.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [142.44.215.177](https://vuldb.com/?ip.142.44.215.177) | ns554604.ip-142-44-215.net | XBash | High
2 | [144.217.61.147](https://vuldb.com/?ip.144.217.61.147) | ip147.ip-144-217-61.net | XBash | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Iron_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Iron. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\ASUS\GamingCenterLib` | High
2 | File | `/account/login` | High
3 | File | `/adherents/note.php?id=1` | High
4 | File | `/admin/ajax.php` | High
5 | File | `/Api/ASF` | Medium
6 | File | `/bin/sh` | Low
7 | File | `/cgi-bin/cgiServer.exx` | High
8 | File | `/cgi?1&5` | Medium
9 | File | `/clients/editclient.php` | High
10 | File | `/CommunitySSORedirect.jsp` | High
11 | File | `/dl/dl_sendmail.php` | High
12 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
13 | File | `/formStaticDHCP` | High
14 | File | `/formVirtualApp` | High
15 | File | `/formVirtualServ` | High
16 | File | `/goform/rlmswitchr_process` | High
17 | File | `/goforms/rlminfo` | High
18 | File | `/include/make.php` | High
19 | File | `/jsonrpc` | Medium
20 | File | `/magnoliaAuthor/.magnolia/` | High
21 | File | `/master/core/PostHandler.php` | High
22 | File | `/medianet/sgcontentset.aspx` | High
23 | File | `/Nodes-Traffic.php` | High
24 | File | `/proc` | Low
25 | File | `/proc/pid/syscall` | High
26 | File | `/restapi/v1/certificates/FFM-SSLInspect` | High
27 | File | `/rss.xml` | Medium
28 | File | `/send_join` | Medium
29 | File | `/settings/profile` | High
30 | File | `/SM8250_Q_Master/android/vendor/oppo_charger/oppo/charger_ic/oppo_mp2650.c` | High
31 | File | `/SM8250_Q_Master/android/vendor/oppo_charger/oppo/oppo_charger.c` | High
32 | File | `/SM8250_Q_Master/android/vendor/oppo_charger/oppo/oppo_vooc.c` | High
33 | ... | ... | ...

There are 284 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-xbash-combines-botnet-ransomware-coinmining-worm-targets-linux-windows/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
