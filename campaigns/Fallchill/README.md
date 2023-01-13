# Fallchill - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fallchill_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fallchill:

* [VN](https://vuldb.com/?country.vn)
* [ES](https://vuldb.com/?country.es)

## Actors

These _actors_ are associated with Fallchill or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fallchill.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.79.99.169](https://vuldb.com/?ip.5.79.99.169) | nsg037-19.divide.nl | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [27.123.221.66](https://vuldb.com/?ip.27.123.221.66) | 66-221.fiber.net.id | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [36.71.90.4](https://vuldb.com/?ip.36.71.90.4) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [41.92.208.194](https://vuldb.com/?ip.41.92.208.194) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [41.92.208.196](https://vuldb.com/?ip.41.92.208.196) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [41.92.208.197](https://vuldb.com/?ip.41.92.208.197) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [50.62.168.157](https://vuldb.com/?ip.50.62.168.157) | p3nwvpweb145.shr.prod.phx3.secureserver.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
8 | [59.90.93.138](https://vuldb.com/?ip.59.90.93.138) | static.bb.knl.59.90.93.138.bsnl.in | [Lazarus](https://vuldb.com/?actor.lazarus) | High
9 | [62.243.45.227](https://vuldb.com/?ip.62.243.45.227) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
10 | [64.29.144.201](https://vuldb.com/?ip.64.29.144.201) | ntfw1c25.carrierzone.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
11 | [66.175.41.191](https://vuldb.com/?ip.66.175.41.191) | winVIPnatfl.hostopia.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
12 | [66.232.121.65](https://vuldb.com/?ip.66.232.121.65) | 66-232-121-65.static.hvvc.us | [Lazarus](https://vuldb.com/?actor.lazarus) | High
13 | [66.242.128.11](https://vuldb.com/?ip.66.242.128.11) | hdflns11.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
14 | [66.242.128.12](https://vuldb.com/?ip.66.242.128.12) | hdflns12.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
15 | [66.242.128.13](https://vuldb.com/?ip.66.242.128.13) | hdflns13.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
16 | [66.242.128.134](https://vuldb.com/?ip.66.242.128.134) | hdflsf03.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
17 | [66.242.128.140](https://vuldb.com/?ip.66.242.128.140) | hdflsf01.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/audits` | Medium
2 | File | `/bsms_ci/index.php` | High
3 | File | `/bsms_ci/index.php/user/edit_user/` | High
4 | File | `/env` | Low
5 | File | `/face-recognition-php/facepay-master/camera.php` | High
6 | File | `/forum/away.php` | High
7 | File | `/FreshRSS/p/ext.php` | High
8 | File | `/goform/addressNat` | High
9 | File | `/goform/CertListInfo` | High
10 | File | `/goform/fast_setting_wifi_set` | High
11 | File | `/goform/IPSECsave` | High
12 | File | `/goform/L7Im` | Medium
13 | File | `/goform/NatStaticSetting` | High
14 | File | `/goform/qossetting` | High
15 | File | `/goform/SafeClientFilter` | High
16 | File | `/goform/SafeMacFilter` | High
17 | File | `/goform/SafeUrlFilter` | High
18 | File | `/goform/setMacFilterCfg` | High
19 | File | `/goform/SysToolReboot` | High
20 | File | `/goform/SysToolRestoreSet` | High
21 | File | `/goform/VirtualSer` | High
22 | File | `/gpac/src/bifs/unquantize.c` | High
23 | File | `/hrm/controller/employee.php` | High
24 | File | `/hrm/employeeadd.php` | High
25 | File | `/hrm/employeeview.php` | High
26 | File | `/leave_system/admin/?page=maintenance/department` | High
27 | File | `/lib` | Low
28 | ... | ... | ...

There are 233 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/alerts/TA17-318A

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
