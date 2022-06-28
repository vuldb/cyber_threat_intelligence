# Nemucod - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nemucod](https://vuldb.com/?actor.nemucod). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nemucod](https://vuldb.com/?actor.nemucod)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nemucod:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nemucod.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [24.96.108.157](https://vuldb.com/?ip.24.96.108.157) | static-24-96-108-157.knology.net | - | High
2 | [61.134.39.188](https://vuldb.com/?ip.61.134.39.188) | - | - | High
3 | [62.173.145.104](https://vuldb.com/?ip.62.173.145.104) | sadovaya-mebel.com | - | High
4 | [76.73.17.194](https://vuldb.com/?ip.76.73.17.194) | - | - | High
5 | [78.129.150.54](https://vuldb.com/?ip.78.129.150.54) | - | - | High
6 | [82.192.94.125](https://vuldb.com/?ip.82.192.94.125) | - | - | High
7 | [85.93.145.251](https://vuldb.com/?ip.85.93.145.251) | mail.boanywhere.com | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nemucod_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nemucod. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/acms/admin/?page=transactions/manage_transaction` | High
3 | File | `/admin-panel1.php` | High
4 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
5 | File | `/Ap4RtpAtom.cpp` | High
6 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
7 | File | `/bcms/admin/?page=user/list` | High
8 | File | `/car-rental-management-system/admin/manage_user.php` | High
9 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
10 | File | `/cgi-bin/login.cgi` | High
11 | File | `/context/%2e/WEB-INF/web.xml` | High
12 | File | `/ctpms/admin/?page=applications/view_application` | High
13 | File | `/debug/pprof` | Medium
14 | File | `/extensionsinstruction` | High
15 | File | `/fuel/index.php/fuel/logs/items` | High
16 | File | `/fuel/sitevariables/delete/4` | High
17 | File | `/ifs` | Low
18 | File | `/include/chart_generator.php` | High
19 | File | `/mgmt/tm/util/bash` | High
20 | File | `/monitoring` | Medium
21 | File | `/mtms/admin/?page=transaction/send` | High
22 | File | `/new` | Low
23 | File | `/proc/<pid>/status` | High
24 | File | `/public/login.htm` | High
25 | File | `/public/plugins/` | High
26 | File | `/question/ask` | High
27 | File | `/reps/admin/?page=agents/manage_agent` | High
28 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
29 | File | `/secure/QueryComponent!Default.jspa` | High
30 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
31 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
32 | File | `/student-grading-system/rms.php?page=school_year` | High
33 | File | `/tmp` | Low
34 | File | `/tos/index.php?app/del` | High
35 | File | `/uncpath/` | Medium
36 | File | `/views/directive/sys/SysConfigDataDirective.java` | High
37 | File | `/wordpress-gallery-transformation/gallery.php` | High
38 | ... | ... | ...

There are 323 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/12/threat-roundup-1207-1214.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0524-0531.html
* https://isc.sans.edu/forums/diary/NemucodAES+and+the+malspam+that+distributes+it/22614/
* https://unit42.paloaltonetworks.com/unit42-practice-makes-perfect-nemucod-evolves-delivery-obfuscation-techniques-harvest-credentials/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
