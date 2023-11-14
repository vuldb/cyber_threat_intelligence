# SectopRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SectopRAT](https://vuldb.com/?actor.sectoprat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sectoprat](https://vuldb.com/?actor.sectoprat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SectopRAT:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SectopRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.75.147.135](https://vuldb.com/?ip.5.75.147.135) | static.135.147.75.5.clients.your-server.de | - | High
2 | [5.75.149.1](https://vuldb.com/?ip.5.75.149.1) | static.1.149.75.5.clients.your-server.de | - | High
3 | [5.75.153.165](https://vuldb.com/?ip.5.75.153.165) | s92.vorarlberghosting.com | - | High
4 | [34.27.150.38](https://vuldb.com/?ip.34.27.150.38) | 38.150.27.34.bc.googleusercontent.com | - | Medium
5 | [34.27.176.144](https://vuldb.com/?ip.34.27.176.144) | 144.176.27.34.bc.googleusercontent.com | - | Medium
6 | [34.91.185.62](https://vuldb.com/?ip.34.91.185.62) | 62.185.91.34.bc.googleusercontent.com | - | Medium
7 | [34.107.35.186](https://vuldb.com/?ip.34.107.35.186) | 186.35.107.34.bc.googleusercontent.com | - | Medium
8 | [34.107.84.7](https://vuldb.com/?ip.34.107.84.7) | 7.84.107.34.bc.googleusercontent.com | - | Medium
9 | [34.141.92.1](https://vuldb.com/?ip.34.141.92.1) | 1.92.141.34.bc.googleusercontent.com | - | Medium
10 | [34.141.167.33](https://vuldb.com/?ip.34.141.167.33) | 33.167.141.34.bc.googleusercontent.com | - | Medium
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SectopRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SectopRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/api/CONFIG/backup` | High
3 | File | `/api/v1/bait/set` | High
4 | File | `/asms/classes/Master.php?f=delete_img` | High
5 | File | `/banner/add.html` | High
6 | File | `/coreframe/app/pay/admin/index.php` | High
7 | File | `/forum/away.php` | High
8 | File | `/itplus/FileStorage/302/shell.jsp` | High
9 | File | `/lawyer-list` | Medium
10 | File | `/librarian/bookdetails.php` | High
11 | File | `/login.php?recoverme=` | High
12 | File | `/mics/j_spring_security_check` | High
13 | File | `/opac/Actions.php?a=login` | High
14 | File | `/public/launchNewWindow.jsp` | High
15 | File | `/public/login.htm` | High
16 | File | `/rpc/membership/setProfile` | High
17 | File | `/search` | Low
18 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
19 | File | `/sendKey` | Medium
20 | File | `/setSystemAdmin` | High
21 | File | `/simple_chat_bot/admin/?page=responses/manage_response` | High
22 | File | `/spip.php` | Medium
23 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
24 | File | `/staff/bookdetails.php` | High
25 | File | `/~user_handler` | High
26 | File | `2345MPCSafe.exe/2345SafeTray.exe/2345Speedup.exe` | High
27 | File | `about.php` | Medium
28 | File | `adclick.php` | Medium
29 | File | `add_comment.php` | High
30 | File | `admin.color.php` | High
31 | File | `admin/addons/archive/archive.php` | High
32 | File | `admin/admin.php` | High
33 | File | `admin/members_view.php` | High
34 | File | `admin/users` | Medium
35 | File | `admincp/auth/secure.php` | High
36 | File | `advsearch.php` | High
37 | ... | ... | ...

There are 322 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/602f934182df413eaf345e6a
* https://threatfox.abuse.ch
* https://twitter.com/AnFam17/status/1658666291308163072

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
