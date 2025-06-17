# Secret Blizzard - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Secret Blizzard](https://vuldb.com/?actor.secret_blizzard). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.secret_blizzard](https://vuldb.com/?actor.secret_blizzard)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Secret Blizzard:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [IT](https://vuldb.com/?country.it)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Secret Blizzard.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.189.183.63](https://vuldb.com/?ip.5.189.183.63) | vmi559729.contaboserver.net | - | High
2 | [23.88.26.187](https://vuldb.com/?ip.23.88.26.187) | static.187.26.88.23.clients.your-server.de | - | High
3 | [37.60.236.186](https://vuldb.com/?ip.37.60.236.186) | vmi2222530.contaboserver.net | - | High
4 | [38.242.207.36](https://vuldb.com/?ip.38.242.207.36) | server1.saralk.com | - | High
5 | [38.242.211.87](https://vuldb.com/?ip.38.242.211.87) | vmi2221390.contaboserver.net | - | High
6 | [38.242.219.13](https://vuldb.com/?ip.38.242.219.13) | vmi1478608.contaboserver.net | - | High
7 | [45.14.194.253](https://vuldb.com/?ip.45.14.194.253) | vmi2280453.contaboserver.net | - | High
8 | [46.249.58.201](https://vuldb.com/?ip.46.249.58.201) | alrs.foxtailorchidy.net | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Secret Blizzard_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Secret Blizzard. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/admin/?page=inmates/view_inmate` | High
3 | File | `/admin/?page=system_info` | High
4 | File | `/admin/?page=system_info/contact_info` | High
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/addemployee.php` | High
7 | File | `/admin/add_exercises.php` | High
8 | File | `/admin/edit.php` | High
9 | File | `/admin/lab.php` | High
10 | File | `/admin/maintenance/view_designation.php` | High
11 | File | `/admin/new-content` | High
12 | File | `/admin/settings.php` | High
13 | File | `/ad_js.php` | Medium
14 | File | `/api/discoveries/` | High
15 | File | `/api/v2/open/rowsInfo` | High
16 | File | `/api /v3/auth` | High
17 | File | `/aqpg/users/login.php` | High
18 | File | `/backups/` | Medium
19 | File | `/bcms/admin/?page=user/list` | High
20 | File | `/cgi-bin/editBookmark` | High
21 | File | `/cgi-bin/touchlist_sync.cgi` | High
22 | File | `/ci_spms/admin/category` | High
23 | File | `/classes/Users.php?f=save` | High
24 | File | `/csms/admin/?page=user/list` | High
25 | File | `/cwms/admin/?page=articles/view_article/` | High
26 | File | `/cwms/classes/Master.php?f=save_contact` | High
27 | File | `/dashboard/add-blog.php` | High
28 | File | `/dashboard/add-portfolio.php` | High
29 | File | `/dashboard/settings` | High
30 | File | `/debug/pprof` | Medium
31 | File | `/devinfo` | Medium
32 | File | `/download` | Medium
33 | File | `/ebics-server/ebics.aspx` | High
34 | File | `/filemanager/upload.php` | High
35 | File | `/forum/away.php` | High
36 | File | `/goform/RgDdns` | High
37 | File | `/goform/RgDhcp` | High
38 | File | `/goform/RGFirewallEL` | High
39 | File | `/goform/RgTime` | High
40 | File | `/goform/RgUrlBlock.asp` | High
41 | ... | ... | ...

There are 349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.lumen.com/snowblind-the-invisible-hand-of-secret-blizzard/
* https://www.microsoft.com/en-us/security/blog/2024/12/04/frequent-freeloader-part-i-secret-blizzard-compromising-storm-0156-infrastructure-for-espionage/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
