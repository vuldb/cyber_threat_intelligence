# RansomHub - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _RansomHub_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RansomHub:

* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with RansomHub or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
2 | [Scattered Spider](https://vuldb.com/?actor.scattered_spider) | High
3 | [ShadowSyndicate](https://vuldb.com/?actor.shadowsyndicate) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RansomHub.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.8.63.178](https://vuldb.com/?ip.5.8.63.178) | 5-8-63-178.static.x5x.tech | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
2 | [8.211.2.97](https://vuldb.com/?ip.8.211.2.97) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
3 | [20.37.139.187](https://vuldb.com/?ip.20.37.139.187) | - | [Scattered Spider](https://vuldb.com/?actor.scattered_spider) | High
4 | [23.92.31.138](https://vuldb.com/?ip.23.92.31.138) | 23-92-31-138.ip.linodeusercontent.com | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
5 | [23.227.193.172](https://vuldb.com/?ip.23.227.193.172) | 23-227-193-172.static.hvvc.us | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
6 | [31.216.148.33](https://vuldb.com/?ip.31.216.148.33) | 31-216-148-33.ip.dclux.com | [ShadowSyndicate](https://vuldb.com/?actor.shadowsyndicate) | High
7 | [37.1.212.18](https://vuldb.com/?ip.37.1.212.18) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
8 | [38.146.28.93](https://vuldb.com/?ip.38.146.28.93) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
9 | [38.180.81.153](https://vuldb.com/?ip.38.180.81.153) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
10 | [38.180.195.187](https://vuldb.com/?ip.38.180.195.187) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/add-category.php` | High
4 | File | `/adfs/ls` | Medium
5 | File | `/admin.php?p=/Area/index#tab=t2` | High
6 | File | `/admin/add_ikev2.php` | High
7 | File | `/admin/add_student.php` | High
8 | File | `/admin/category_save.php` | High
9 | File | `/admin/file_manage_view` | High
10 | File | `/admin/index2.html` | High
11 | File | `/admin/list_ipAddressPolicy.php` | High
12 | File | `/admin/manage_model.php` | High
13 | File | `/admin/manage_user.php` | High
14 | File | `/admin/profile.php` | High
15 | File | `/admin/search-vehicle.php` | High
16 | File | `/admin/student.php` | High
17 | File | `/admin/subject.php` | High
18 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
19 | File | `/admin/twitter.php` | High
20 | File | `/admins/{adminId}` | High
21 | File | `/api/dept` | Medium
22 | File | `/api/v1/public-chatflows/id` | High
23 | File | `/api/v1/settings` | High
24 | File | `/api/v1/toolbox/device/update/swap` | High
25 | File | `/app/admin/controller/Upload.php` | High
26 | File | `/app/zentao/module/repo/model.php` | High
27 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
28 | File | `/backend/admin/his_admin_register_patient.php` | High
29 | File | `/bin/httpd` | Medium
30 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
31 | File | `/catalog/all-products` | High
32 | File | `/cgi` | Low
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/ExportSettings.sh` | High
35 | File | `/classes/Master.php` | High
36 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
37 | File | `/com/esafenet/servlet/policy/HookService.java` | High
38 | File | `/download` | Medium
39 | File | `/edit-subject.php` | High
40 | File | `/endpoint/add-user.php` | High
41 | File | `/etc/postfix/sender_login` | High
42 | ... | ... | ...

There are 361 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://darktrace.com/blog/ransomhub-ransomware-darktraces-investigation-of-the-newest-tool-in-shadowsyndicates-arsenal
* https://darktrace.com/blog/ransomhub-revisited-new-front-runner-in-the-ransomware-as-a-service-marketplace
* https://search.censys.io/hosts/162.252.173.12
* https://search.censys.io/hosts/185.33.86.15
* https://search.censys.io/hosts/185.219.220.175
* https://search.censys.io/hosts/193.203.49.90
* https://threatfox.abuse.ch
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-242a
* https://www.guidepointsecurity.com/blog/ransomhub-affiliate-leverage-python-based-backdoor/
* https://www.reliaquest.com/blog/scattered-spider-x-ransomhub-a-new-partnership/
* https://www.trendmicro.com/en_us/research/24/i/how-ransomhub-ransomware-uses-edrkillshifter-to-disable-edr-and-.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
