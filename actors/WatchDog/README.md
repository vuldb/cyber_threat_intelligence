# WatchDog - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WatchDog](https://vuldb.com/?actor.watchdog). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.watchdog](https://vuldb.com/?actor.watchdog)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WatchDog:

* [SC](https://vuldb.com/?country.sc)
* [US](https://vuldb.com/?country.us)
* [MO](https://vuldb.com/?country.mo)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WatchDog.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [39.100.33.209](https://vuldb.com/?ip.39.100.33.209) | - | - | High
2 | [45.9.148.37](https://vuldb.com/?ip.45.9.148.37) | - | - | High
3 | [45.153.240.58](https://vuldb.com/?ip.45.153.240.58) | - | - | High
4 | [47.253.42.213](https://vuldb.com/?ip.47.253.42.213) | - | - | High
5 | [80.211.206.105](https://vuldb.com/?ip.80.211.206.105) | 105.206.forpsi.net | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WatchDog_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WatchDog. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/admin` | Low
3 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
4 | File | `/cgi-bin/editBookmark` | High
5 | File | `/chat_im/chat_window.php` | High
6 | File | `/cloud_config/router_post/get_reg_verify_code` | High
7 | File | `/etc/openstack-dashboard/local_settings` | High
8 | File | `/etc/passwd` | Medium
9 | File | `/filemanager/upload.php` | High
10 | File | `/goform/addressNat` | High
11 | File | `/goform/SetNetControlList` | High
12 | File | `/include/menu_v.inc.php` | High
13 | File | `/MagickCore/statistic.c` | High
14 | File | `/proc/pid/syscall` | High
15 | File | `/Search-Results` | High
16 | File | `/var/log/pcp/configs.sh` | High
17 | File | `/visualizza_tabelle.php` | High
18 | File | `a2m.cpp` | Low
19 | File | `admin.php` | Medium
20 | ... | ... | ...

There are 164 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/watchdog-cryptojacking/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
