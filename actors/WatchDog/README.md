# WatchDog - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WatchDog](https://vuldb.com/?actor.watchdog). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.watchdog](https://vuldb.com/?actor.watchdog)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WatchDog:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [MO](https://vuldb.com/?country.mo)
* ...

There are 9 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WatchDog. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/admin` | Low
3 | File | `/admin/uesrs.php&action=display&value=Hide` | High
4 | File | `/asms/classes/Master.php?f=delete_transaction` | High
5 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
6 | File | `/cgi-bin/editBookmark` | High
7 | File | `/chat_im/chat_window.php` | High
8 | File | `/cloud_config/router_post/get_reg_verify_code` | High
9 | File | `/etc/openstack-dashboard/local_settings` | High
10 | File | `/etc/passwd` | Medium
11 | File | `/filemanager/upload.php` | High
12 | File | `/FreshRSS/p/ext.php` | High
13 | File | `/goform/addressNat` | High
14 | File | `/goform/addRouting` | High
15 | File | `/goform/SetNetControlList` | High
16 | File | `/include/menu_v.inc.php` | High
17 | File | `/Interface/DevManage/EC.php?cmd=upload` | High
18 | File | `/librarian/lab.php` | High
19 | File | `/MagickCore/statistic.c` | High
20 | File | `/omos/admin/?page=user/list` | High
21 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
22 | File | `/panel/fields/add` | High
23 | File | `/patient/settings.php` | High
24 | File | `/proc/*/cmdline"` | High
25 | File | `/proc/pid/syscall` | High
26 | File | `/release-x64/otfccdump+0x4fe9a7` | High
27 | ... | ... | ...

There are 224 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/watchdog-cryptojacking/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
