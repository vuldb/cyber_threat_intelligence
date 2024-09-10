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

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SolarWinds.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.57.152](https://vuldb.com/?ip.5.61.57.152) | - | [SilverFish](https://vuldb.com/?actor.silverfish) | High
2 | [23.106.61.74](https://vuldb.com/?ip.23.106.61.74) | - | [SilverFish](https://vuldb.com/?actor.silverfish) | High
3 | [74.72.74.142](https://vuldb.com/?ip.74.72.74.142) | cpe-74-72-74-142.nyc.res.rr.com | [SilverFish](https://vuldb.com/?actor.silverfish) | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SolarWinds. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
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
8 | File | `/cgi-bin/cstecgi.cgi` | High
9 | File | `/etc/config/rpcd` | High
10 | File | `/nidp/app/login` | High
11 | File | `/php/ping.php` | High
12 | File | `/proc` | Low
13 | File | `/rapi/read_url` | High
14 | File | `/sbin/conf.d/SuSEconfig.javarunt` | High
15 | File | `/scripts/unlock_tasks.php` | High
16 | File | `/setSystemAdmin` | High
17 | File | `/SysInfo1.htm` | High
18 | File | `/sysinfo_json.cgi` | High
19 | File | `/system/dictData/loadDictItem` | High
20 | File | `/system/user/modules/mod_users/controller.php` | High
21 | File | `/tmp` | Low
22 | File | `/usr/lib/utmp_update` | High
23 | File | `/view/vpn/autovpn/sub_commit.php` | High
24 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
25 | File | `admin/Login.php` | High
26 | File | `admin/plugin-index.php` | High
27 | File | `administration` | High
28 | File | `administrative` | High
29 | File | `aolfix.exe` | Medium
30 | File | `appserv/main.php` | High
31 | File | `awhost32.exe` | Medium
32 | File | `bidhistory.php` | High
33 | File | `browser/notifications/notification_ui_manager_impl.cc` | High
34 | File | `buffer.c` | Medium
35 | ... | ... | ...

There are 296 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/SunBurst/SilverFish_Solarwinds.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
