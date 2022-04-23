# Campaign 0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 0_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 0:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 4 more country items available. Please use our online service to access the data.

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
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 0. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `.htaccess` | Medium
3 | File | `/#/CampaignManager/users` | High
4 | File | `//` | Low
5 | File | `/admin.php?action=themeinstall` | High
6 | File | `/admin/?setting-base.htm` | High
7 | File | `/admin/admin_login.php` | High
8 | File | `/admin/login.php` | High
9 | File | `/apply_noauth.cgi` | High
10 | File | `/audit/log/log_management.php` | High
11 | File | `/backup/lispbx-CONF-YYYY-MM-DD.tar` | High
12 | File | `/bin/login` | Medium
13 | File | `/bin/sh` | Low
14 | File | `/cgi-bin/login` | High
15 | File | `/classes/profile.class.php` | High
16 | File | `/dev/tty` | Medium
17 | File | `/doorgets/app/requests/user/modulecategoryRequest.php` | High
18 | File | `/downloads/` | Medium
19 | File | `/IISADMPWD` | Medium
20 | File | `/inc/session.php` | High
21 | File | `/index.php` | Medium
22 | File | `/magnoliaPublic/travel/members/login.html` | High
23 | File | `/member/index/login.html` | High
24 | File | `/modules/certinfo/index.php` | High
25 | File | `/post/editing` | High
26 | File | `/public/plugins/` | High
27 | File | `/restful-services/publish` | High
28 | File | `/ScadaBR/login.htm` | High
29 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
30 | File | `/system/tool/ping.php` | High
31 | File | `/upload` | Low
32 | File | `/usr/bin/pkexec` | High
33 | File | `?location=search` | High
34 | File | `account/login.php` | High
35 | File | `add.asp` | Low
36 | File | `add.php` | Low
37 | File | `admin.home.php` | High
38 | File | `admin.php` | Medium
39 | File | `admin.php?m=backup&c=backup&a=doback` | High
40 | File | `admin/conf_users_edit.php` | High
41 | ... | ... | ...

There are 355 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_0_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
