# SolarWinds - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SolarWinds_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SolarWinds:

* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SolarWinds or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [SilverFish](https://vuldb.com/?actor.silverfish) | High
2 | [SolarWinds](https://vuldb.com/?actor.solarwinds) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SolarWinds.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.57.152](https://vuldb.com/?ip.5.61.57.152) | - | [SilverFish](https://vuldb.com/?actor.silverfish) | High
2 | [23.106.61.74](https://vuldb.com/?ip.23.106.61.74) | - | [SilverFish](https://vuldb.com/?actor.silverfish) | High
3 | [74.72.74.142](https://vuldb.com/?ip.74.72.74.142) | cpe-74-72-74-142.nyc.res.rr.com | [SilverFish](https://vuldb.com/?actor.silverfish) | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SolarWinds. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SolarWinds. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/.asp` | Low
3 | File | `/admin/admin_login.php` | High
4 | File | `/advanced/adv_dns.xgi` | High
5 | File | `/api/RecordingList/DownloadRecord?file=` | High
6 | File | `/apply.cgi` | Medium
7 | File | `/CFIDE/probe.cfm` | High
8 | File | `/etc/config/rpcd` | High
9 | File | `/MicroStrategyWS/happyaxis.jsp` | High
10 | File | `/nidp/app/login` | High
11 | File | `/proc` | Low
12 | File | `/rapi/read_url` | High
13 | File | `/sbin/conf.d/SuSEconfig.javarunt` | High
14 | File | `/setSystemAdmin` | High
15 | File | `/start_apply.htm` | High
16 | File | `/tmp` | Low
17 | File | `/uncpath/` | Medium
18 | File | `/upload` | Low
19 | File | `/usr/lib/utmp_update` | High
20 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
21 | File | `admin.php` | Medium
22 | File | `admin/graph_trend.php` | High
23 | File | `admin/Login.php` | High
24 | File | `admin/plugin-index.php` | High
25 | File | `administration` | High
26 | File | `administrative` | High
27 | File | `aolfix.exe` | Medium
28 | File | `Ap4DecoderConfigDescriptor.cpp` | High
29 | File | `appserv/main.php` | High
30 | File | `awhost32.exe` | Medium
31 | File | `bidhistory.php` | High
32 | File | `browser/notifications/notification_ui_manager_impl.cc` | High
33 | File | `buffer.c` | Medium
34 | File | `c:\aux` | Low
35 | File | `C:\Wamp64` | Medium
36 | ... | ... | ...

There are 304 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-threat-advisory/solarwinds-third-update/
* https://github.com/blackorbird/APT_REPORT/blob/master/SunBurst/SilverFish_Solarwinds.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
