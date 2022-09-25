# LinuxMoose - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LinuxMoose](https://vuldb.com/?actor.linuxmoose). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.linuxmoose](https://vuldb.com/?actor.linuxmoose)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LinuxMoose:

* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LinuxMoose.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.124.41.11](https://vuldb.com/?ip.27.124.41.11) | - | - | High
2 | [27.124.41.31](https://vuldb.com/?ip.27.124.41.31) | - | - | High
3 | [27.124.41.33](https://vuldb.com/?ip.27.124.41.33) | - | - | High
4 | [27.124.41.52](https://vuldb.com/?ip.27.124.41.52) | - | - | High
5 | [42.119.173.138](https://vuldb.com/?ip.42.119.173.138) | - | - | High
6 | [62.210.6.34](https://vuldb.com/?ip.62.210.6.34) | 62-210-6-34.rev.poneytelecom.eu | - | High
7 | [77.247.177.31](https://vuldb.com/?ip.77.247.177.31) | - | - | High
8 | [77.247.177.36](https://vuldb.com/?ip.77.247.177.36) | - | - | High
9 | [77.247.177.87](https://vuldb.com/?ip.77.247.177.87) | - | - | High
10 | [77.247.178.177](https://vuldb.com/?ip.77.247.178.177) | - | - | High
11 | [79.176.26.142](https://vuldb.com/?ip.79.176.26.142) | bzq-79-176-26-142.red.bezeqint.net | - | High
12 | [82.146.63.15](https://vuldb.com/?ip.82.146.63.15) | ebay2.com | - | High
13 | [85.159.237.0](https://vuldb.com/?ip.85.159.237.0) | - | - | High
14 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LinuxMoose_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LinuxMoose. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/core/conditions/AbstractWrapper.java` | High
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
22 | File | `/pages/apply_vacancy.php` | High
23 | File | `/plugin/LiveChat/getChat.json.php` | High
24 | File | `/proc/<PID>/mem` | High
25 | File | `/recordings/index.php` | High
26 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
27 | File | `/tmp/zarafa-vacation-*` | High
28 | File | `/uncpath/` | Medium
29 | ... | ... | ...

There are 244 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/moose
* https://ioc.hatenablog.com/entry/2015/05/28/000000
* https://www.threatminer.org/report.php?q=Dissecting-LinuxMoose.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
