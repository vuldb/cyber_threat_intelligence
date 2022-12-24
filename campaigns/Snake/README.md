# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Snake_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [DE](https://vuldb.com/?country.de)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Snake or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Snake](https://vuldb.com/?actor.snake) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | [Snake](https://vuldb.com/?actor.snake) | High
2 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | [Snake](https://vuldb.com/?actor.snake) | High
3 | [31.170.164.249](https://vuldb.com/?ip.31.170.164.249) | ns4.hostinger.com | [Snake](https://vuldb.com/?actor.snake) | High
4 | [34.122.197.93](https://vuldb.com/?ip.34.122.197.93) | 93.197.122.34.bc.googleusercontent.com | [Snake](https://vuldb.com/?actor.snake) | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/&quot` | Low
2 | File | `/Admin/add-student.php` | High
3 | File | `/admin/transactions/update_status.php` | High
4 | File | `/admin/users/index.php` | High
5 | File | `/apiv1/` | Low
6 | File | `/asms/admin/products/manage_product.php` | High
7 | File | `/asms/products/view_product.php` | High
8 | File | `/auth/register` | High
9 | File | `/back/index.php/user/User/?1` | High
10 | File | `/binbloom-master/src/helpers.c` | High
11 | File | `/blog/comment` | High
12 | File | `/bsms_ci/index.php` | High
13 | File | `/bsms_ci/index.php/user/edit_user/` | High
14 | File | `/calendar/viewcalendar.php` | High
15 | File | `/Default/Bd` | Medium
16 | File | `/dev/kmem` | Medium
17 | File | `/dev/tty` | Medium
18 | File | `/device/` | Medium
19 | File | `/env` | Low
20 | File | `/etc/passwd` | Medium
21 | File | `/event/admin/?page=user/list` | High
22 | File | `/face-recognition-php/facepay-master/camera.php` | High
23 | File | `/garage/php_action/createBrand.php` | High
24 | File | `/goform/addressNat` | High
25 | File | `/goform/AdvSetWrlsafeset` | High
26 | File | `/goform/CertListInfo` | High
27 | File | `/goform/exeCommand` | High
28 | File | `/goform/IPSECsave` | High
29 | File | `/goform/L7Im` | Medium
30 | File | `/goform/NatStaticSetting` | High
31 | File | `/goform/qossetting` | High
32 | File | `/goform/SafeClientFilter` | High
33 | File | `/goform/setDiagnoseInfo` | High
34 | File | `/goform/setSysPwd` | High
35 | File | `/goform/setUplinkInfo` | High
36 | File | `/goform/SysToolRestoreSet` | High
37 | ... | ... | ...

There are 318 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
