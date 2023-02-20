# BlackEnergy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BlackEnergy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackEnergy:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 16 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin/submit-articles` | High
3 | File | `/ad_js.php` | Medium
4 | File | `/api/v2/cli/commands` | High
5 | File | `/app/options.py` | High
6 | File | `/attachments` | Medium
7 | File | `/bsms/?page=manage_account` | High
8 | File | `/bsms_ci/index.php/book` | High
9 | File | `/cgi-bin/login.cgi` | High
10 | File | `/cgi-bin/luci/api/wireless` | High
11 | File | `/ci_hms/massage_room/edit/1` | High
12 | File | `/context/%2e/WEB-INF/web.xml` | High
13 | File | `/dashboard/reports/logs/view` | High
14 | File | `/debian/patches/load_ppp_generic_if_needed` | High
15 | File | `/debug/pprof` | Medium
16 | File | `/etc/hosts` | Medium
17 | File | `/forum/away.php` | High
18 | File | `/goform/setmac` | High
19 | File | `/goform/wizard_end` | High
20 | File | `/hprms/admin/doctors/manage_doctor.php` | High
21 | File | `/index/jobfairol/show/` | High
22 | File | `/librarian/bookdetails.php` | High
23 | File | `/manage-apartment.php` | High
24 | File | `/medicines/profile.php` | High
25 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
26 | File | `/out.php` | Medium
27 | File | `/pages/apply_vacancy.php` | High
28 | File | `/pet_shop/admin/?page=maintenance/manage_category` | High
29 | File | `/proc/<PID>/mem` | High
30 | File | `/proxy` | Low
31 | File | `/spip.php` | Medium
32 | File | `/tmp` | Low
33 | ... | ... | ...

There are 285 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
