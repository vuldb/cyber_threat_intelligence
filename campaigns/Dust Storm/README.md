# Dust Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Dust Storm_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dust Storm:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Dust Storm or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dust Storm.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [6.9.2.1](https://vuldb.com/?ip.6.9.2.1) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
2 | [23.238.229.128](https://vuldb.com/?ip.23.238.229.128) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
3 | [27.255.72.68](https://vuldb.com/?ip.27.255.72.68) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
4 | [27.255.72.69](https://vuldb.com/?ip.27.255.72.69) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
5 | [27.255.72.78](https://vuldb.com/?ip.27.255.72.78) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
6 | [59.120.59.2](https://vuldb.com/?ip.59.120.59.2) | 59-120-59-2.hinet-ip.hinet.net | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
7 | [59.188.13.133](https://vuldb.com/?ip.59.188.13.133) | - | [Dust Storm](https://vuldb.com/?actor.dust_storm) | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Dust Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Dust Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\1E\Client\Tachyon.Performance.Metrics.exe` | High
2 | File | `.kss.pid` | Medium
3 | File | `.qpopper-options` | High
4 | File | `/api/v1/containers` | High
5 | File | `/apply_noauth.cgi` | High
6 | File | `/apps/` | Low
7 | File | `/backupsettings.conf` | High
8 | File | `/bin/sh` | Low
9 | File | `/debug/pprof` | Medium
10 | File | `/modules/snf/index.php` | High
11 | File | `/Online%20Course%20Registration/my-profile.php` | High
12 | File | `/opt/mysql` | Medium
13 | File | `/private/sessions` | High
14 | File | `/root/*.db` | Medium
15 | File | `/tmp` | Low
16 | File | `/var/avamar/f_cache.dat` | High
17 | File | `26.html` | Low
18 | File | `ActivityStarter.java` | High
19 | File | `add_postit.php` | High
20 | File | `admin.php` | Medium
21 | File | `admin/index.php?id=filesmanager&path=uploads/` | High
22 | File | `admin/manage-fields.php` | High
23 | File | `admin/shophelp.php` | High
24 | File | `admin/wp-security-blacklist-menu.php` | High
25 | File | `administration.jsp` | High
26 | File | `adminquery.php` | High
27 | File | `ajaxRequest/methodCall.do` | High
28 | File | `Alias.asmx` | Medium
29 | File | `ansfaq.asp` | Medium
30 | File | `api.php/List/index` | High
31 | File | `app/parameters/sipity/parameters/search_criteria_for_works_parameter.rb` | High
32 | File | `appGet.cgi` | Medium
33 | File | `application/core/Survey_Common_Action.php` | High
34 | File | `archivejson.cgi` | High
35 | File | `authpam.c` | Medium
36 | File | `autocms.php` | Medium
37 | File | `avahi-core/socket.c` | High
38 | File | `AvailableApps.php` | High
39 | File | `banner.php` | Medium
40 | File | `boundary_rules.jsp` | High
41 | File | `calendar.php` | Medium
42 | File | `calendar_scheduler.php` | High
43 | File | `cal_config.inc.php` | High
44 | File | `channels/chan_sip.c` | High
45 | File | `chrome-devtools-frontend.appspot.com` | High
46 | File | `claro_init_global.inc.php` | High
47 | File | `class/class.php` | High
48 | File | `cloud.php` | Medium
49 | ... | ... | ...

There are 428 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.threatminer.org/report.php?q=Op_Dust_Storm_Report.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
