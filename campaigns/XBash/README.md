# XBash - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _XBash_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XBash:

* [ES](https://vuldb.com/?country.es)

## Actors

These _actors_ are associated with XBash or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Iron](https://vuldb.com/?actor.iron) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XBash.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [142.44.215.177](https://vuldb.com/?ip.142.44.215.177) | ns554604.ip-142-44-215.net | [Iron](https://vuldb.com/?actor.iron) | High
2 | [144.217.61.147](https://vuldb.com/?ip.144.217.61.147) | ip147.ip-144-217-61.net | [Iron](https://vuldb.com/?actor.iron) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used within XBash. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during XBash. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\ASUS\GamingCenterLib` | High
2 | File | `/account/login` | High
3 | File | `/adherents/note.php?id=1` | High
4 | File | `/admin/gallery.php` | High
5 | File | `/Api/ASF` | Medium
6 | File | `/bin/sh` | Low
7 | File | `/cgi-bin/cgiServer.exx` | High
8 | File | `/cgi?1&5` | Medium
9 | File | `/clients/editclient.php` | High
10 | File | `/dl/dl_sendmail.php` | High
11 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
12 | File | `/formStaticDHCP` | High
13 | File | `/formVirtualApp` | High
14 | File | `/formVirtualServ` | High
15 | File | `/jsonrpc` | Medium
16 | File | `/magnoliaAuthor/.magnolia/` | High
17 | File | `/master/core/PostHandler.php` | High
18 | File | `/medianet/sgcontentset.aspx` | High
19 | File | `/Nodes-Traffic.php` | High
20 | File | `/proc` | Low
21 | File | `/proc/pid/syscall` | High
22 | File | `/restapi/v1/certificates/FFM-SSLInspect` | High
23 | File | `/rss.xml` | Medium
24 | File | `/send_join` | Medium
25 | File | `/settings/profile` | High
26 | File | `/SM8250_Q_Master/android/vendor/oppo_charger/oppo/charger_ic/oppo_mp2650.c` | High
27 | File | `/SM8250_Q_Master/android/vendor/oppo_charger/oppo/oppo_charger.c` | High
28 | File | `/SM8250_Q_Master/android/vendor/oppo_charger/oppo/oppo_vooc.c` | High
29 | File | `/sys/net/gnrc/routing/rpl/gnrc_rpl_control_messages.c` | High
30 | File | `/sysworkflow/en/neoclassic/reportTables/reportTables_Ajax` | High
31 | File | `/tools/network-trace` | High
32 | File | `/user/release.html` | High
33 | ... | ... | ...

There are 277 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-xbash-combines-botnet-ransomware-coinmining-worm-targets-linux-windows/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
