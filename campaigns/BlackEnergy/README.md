# BlackEnergy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BlackEnergy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackEnergy:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BlackEnergy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
2 | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackEnergy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.9.32.230](https://vuldb.com/?ip.5.9.32.230) | static.230.32.9.5.clients.your-server.de | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
2 | [5.61.38.31](https://vuldb.com/?ip.5.61.38.31) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
3 | [5.79.80.166](https://vuldb.com/?ip.5.79.80.166) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
4 | [5.149.254.114](https://vuldb.com/?ip.5.149.254.114) | mail1.auditoriavanzada.info | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
5 | [5.255.87.39](https://vuldb.com/?ip.5.255.87.39) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
6 | [31.210.111.154](https://vuldb.com/?ip.31.210.111.154) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/dl_sendmail.php` | High
3 | File | `/Ap4RtpAtom.cpp` | High
4 | File | `/app/options.py` | High
5 | File | `/bcms/admin/?page=user/list` | High
6 | File | `/bsms/?page=manage_account` | High
7 | File | `/cgi-bin/login.cgi` | High
8 | File | `/ci_hms/massage_room/edit/1` | High
9 | File | `/context/%2e/WEB-INF/web.xml` | High
10 | File | `/dashboard/reports/logs/view` | High
11 | File | `/debug/pprof` | Medium
12 | File | `/etc/hosts` | Medium
13 | File | `/fuel/index.php/fuel/logs/items` | High
14 | File | `/fuel/sitevariables/delete/4` | High
15 | File | `/hprms/admin/doctors/manage_doctor.php` | High
16 | File | `/index/jobfairol/show/` | High
17 | File | `/librarian/bookdetails.php` | High
18 | File | `/mgmt/tm/util/bash` | High
19 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
20 | File | `/new` | Low
21 | File | `/proc/<PID>/mem` | High
22 | File | `/proc/<pid>/status` | High
23 | File | `/public/plugins/` | High
24 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
25 | File | `/secure/QueryComponent!Default.jspa` | High
26 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
27 | File | `/spip.php` | Medium
28 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
29 | File | `/tmp` | Low
30 | File | `/uncpath/` | Medium
31 | ... | ... | ...

There are 263 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://blogs.mcafee.jp/blackenergy-cb6d
* https://www.threatminer.org/report.php?q=BlackEnergy2_Plugins_Router.pdf&y=2014
* https://www.welivesecurity.com/2016/01/03/blackenergy-sshbeardoor-details-2015-attacks-ukrainian-news-media-electric-industry/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
