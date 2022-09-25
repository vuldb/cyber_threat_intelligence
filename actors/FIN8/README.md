# FIN8 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FIN8](https://vuldb.com/?actor.fin8). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fin8](https://vuldb.com/?actor.fin8)

## Campaigns

The following _campaigns_ are known and can be associated with FIN8:

* Badhatch

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FIN8:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FIN8.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.1.204.87](https://vuldb.com/?ip.37.1.204.87) | - | - | High
2 | [104.168.145.204](https://vuldb.com/?ip.104.168.145.204) | hwsrv-836597.hostwindsdns.com | Badhatch | High
3 | [104.168.237.21](https://vuldb.com/?ip.104.168.237.21) | hwsrv-850035.hostwindsdns.com | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FIN8_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FIN8. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/ad_js.php` | Medium
3 | File | `/Ap4RtpAtom.cpp` | High
4 | File | `/app/options.py` | High
5 | File | `/bcms/admin/?page=user/list` | High
6 | File | `/bsms/?page=manage_account` | High
7 | File | `/cgi-bin/login.cgi` | High
8 | File | `/ci_hms/massage_room/edit/1` | High
9 | File | `/context/%2e/WEB-INF/web.xml` | High
10 | File | `/dashboard/reports/logs/view` | High
11 | File | `/debian/patches/load_ppp_generic_if_needed` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/etc/hosts` | Medium
14 | File | `/fuel/index.php/fuel/logs/items` | High
15 | File | `/fuel/sitevariables/delete/4` | High
16 | File | `/hprms/admin/doctors/manage_doctor.php` | High
17 | File | `/index/jobfairol/show/` | High
18 | File | `/librarian/bookdetails.php` | High
19 | File | `/manage-apartment.php` | High
20 | File | `/mgmt/tm/util/bash` | High
21 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
22 | File | `/new` | Low
23 | File | `/pages/apply_vacancy.php` | High
24 | File | `/proc/<PID>/mem` | High
25 | File | `/proc/<pid>/status` | High
26 | File | `/public/plugins/` | High
27 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
28 | File | `/secure/QueryComponent!Default.jspa` | High
29 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
30 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
31 | ... | ... | ...

There are 266 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.morphisec.com/security-alert-fin8-is-back
* https://businessinsights.bitdefender.com/deep-dive-into-a-fin8-attack-a-forensic-investigation
* https://vxug.fakedoma.in/archive/APTs/2021/2021.03.10/BADHATCH.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
