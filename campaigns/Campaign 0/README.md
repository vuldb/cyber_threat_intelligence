# Campaign 0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 0_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 0:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)

## Actors

These _actors_ are associated with Campaign 0 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign 0.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.13.139.105](https://vuldb.com/?ip.5.13.139.105) | 5-13-139-105.residential.rdsnet.ro | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [5.59.65.104](https://vuldb.com/?ip.5.59.65.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [5.108.69.57](https://vuldb.com/?ip.5.108.69.57) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [6.70.116.102](https://vuldb.com/?ip.6.70.116.102) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [6.119.67.75](https://vuldb.com/?ip.6.119.67.75) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [8.47.71.43](https://vuldb.com/?ip.8.47.71.43) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [10.33.44.94](https://vuldb.com/?ip.10.33.44.94) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [10.118.75.18](https://vuldb.com/?ip.10.118.75.18) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [10.143.48.52](https://vuldb.com/?ip.10.143.48.52) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [12.40.29.71](https://vuldb.com/?ip.12.40.29.71) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | [13.65.24.145](https://vuldb.com/?ip.13.65.24.145) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
12 | [14.47.117.104](https://vuldb.com/?ip.14.47.117.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
13 | [16.9.79.28](https://vuldb.com/?ip.16.9.79.28) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
14 | [16.29.27.126](https://vuldb.com/?ip.16.29.27.126) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
15 | [16.95.70.136](https://vuldb.com/?ip.16.95.70.136) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
16 | [16.127.81.67](https://vuldb.com/?ip.16.127.81.67) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
17 | [16.127.136.51](https://vuldb.com/?ip.16.127.136.51) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
18 | [19.140.51.9](https://vuldb.com/?ip.19.140.51.9) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
19 | [23.24.92.121](https://vuldb.com/?ip.23.24.92.121) | 23-24-92-121-static.hfc.comcastbusiness.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
20 | [24.54.58.144](https://vuldb.com/?ip.24.54.58.144) | 24-54-58-144.resi.cgocable.ca | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
21 | ... | ... | ... | ...

There are 82 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign 0. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 0. This data is unique as it uses our predictive model for actor profiling.

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
15 | File | `/subtitles.php` | High
16 | File | `/tmp` | Low
17 | File | `/var/avamar/f_cache.dat` | High
18 | File | `/views/directive/sys/SysConfigDataDirective.java` | High
19 | File | `26.html` | Low
20 | File | `ActivityStarter.java` | High
21 | File | `add_postit.php` | High
22 | File | `admin.php` | Medium
23 | File | `admin/index.php?id=filesmanager&path=uploads/` | High
24 | File | `admin/manage-fields.php` | High
25 | File | `admin/shophelp.php` | High
26 | File | `admin/wp-security-blacklist-menu.php` | High
27 | File | `administration.jsp` | High
28 | File | `adminquery.php` | High
29 | File | `ajaxRequest/methodCall.do` | High
30 | File | `Alias.asmx` | Medium
31 | File | `ansfaq.asp` | Medium
32 | File | `api.php/List/index` | High
33 | File | `APKINDEX.tar.gz` | High
34 | File | `app/parameters/sipity/parameters/search_criteria_for_works_parameter.rb` | High
35 | File | `appconfig.ini` | High
36 | File | `appGet.cgi` | Medium
37 | File | `archivejson.cgi` | High
38 | File | `authpam.c` | Medium
39 | File | `autocms.php` | Medium
40 | File | `avahi-core/socket.c` | High
41 | File | `AvailableApps.php` | High
42 | File | `banner.php` | Medium
43 | File | `boundary_rules.jsp` | High
44 | File | `calendar.php` | Medium
45 | File | `calendar_scheduler.php` | High
46 | File | `cal_config.inc.php` | High
47 | File | `channels/chan_sip.c` | High
48 | File | `chrome-devtools-frontend.appspot.com` | High
49 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_0_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
