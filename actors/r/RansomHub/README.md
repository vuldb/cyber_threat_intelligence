# RansomHub - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RansomHub](https://vuldb.com/?actor.ransomhub). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ransomhub](https://vuldb.com/?actor.ransomhub)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RansomHub:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RansomHub.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.63.178](https://vuldb.com/?ip.5.8.63.178) | 5-8-63-178.static.x5x.tech | - | High
2 | [5.181.86.158](https://vuldb.com/?ip.5.181.86.158) | - | - | High
3 | [8.211.2.97](https://vuldb.com/?ip.8.211.2.97) | - | - | High
4 | [23.92.31.138](https://vuldb.com/?ip.23.92.31.138) | 23-92-31-138.ip.linodeusercontent.com | - | High
5 | [23.227.193.172](https://vuldb.com/?ip.23.227.193.172) | 23-227-193-172.static.hvvc.us | - | High
6 | [37.1.212.18](https://vuldb.com/?ip.37.1.212.18) | - | - | High
7 | [37.120.143.202](https://vuldb.com/?ip.37.120.143.202) | - | - | High
8 | [38.146.28.93](https://vuldb.com/?ip.38.146.28.93) | - | - | High
9 | [38.180.81.153](https://vuldb.com/?ip.38.180.81.153) | - | - | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RansomHub_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-44 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/add-category.php` | High
4 | File | `/adfs/ls` | Medium
5 | File | `/admin.php?p=/Area/index#tab=t2` | High
6 | File | `/admin/add_ikev2.php` | High
7 | File | `/admin/add_student.php` | High
8 | File | `/admin/admin_action.php` | High
9 | File | `/admin/category_save.php` | High
10 | File | `/admin/file_manage_view` | High
11 | File | `/admin/index.php` | High
12 | File | `/admin/index2.html` | High
13 | File | `/admin/list_ipAddressPolicy.php` | High
14 | File | `/admin/login.php` | High
15 | File | `/admin/manage-pages.php` | High
16 | File | `/admin/manage_model.php` | High
17 | File | `/admin/manage_user.php` | High
18 | File | `/admin/new-content` | High
19 | File | `/admin/profile.php` | High
20 | File | `/admin/search-vehicle.php` | High
21 | File | `/admin/student.php` | High
22 | File | `/admin/subject.php` | High
23 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
24 | File | `/admin/twitter.php` | High
25 | File | `/admin/voters_add.php` | High
26 | File | `/admin/voters_delete.php` | High
27 | File | `/admins/{adminId}` | High
28 | File | `/api/dept` | Medium
29 | File | `/api/v1/public-chatflows/id` | High
30 | File | `/api/v1/settings` | High
31 | File | `/api/v1/toolbox/device/update/swap` | High
32 | File | `/app/admin/controller/Upload.php` | High
33 | File | `/app/zentao/module/repo/model.php` | High
34 | File | `/authentication/logout.php` | High
35 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
36 | File | `/backend/admin/his_admin_register_patient.php` | High
37 | File | `/bin/httpd` | Medium
38 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
39 | File | `/catalog/all-products` | High
40 | File | `/cgi` | Low
41 | File | `/cgi-bin/cstecgi.cgi` | High
42 | File | `/cgi-bin/ExportSettings.sh` | High
43 | File | `/classes/Master.php` | High
44 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
45 | File | `/com/esafenet/servlet/policy/HookService.java` | High
46 | File | `/dashboard/admin/submit_plan_new.php` | High
47 | File | `/doctor/appointment-bwdates-reports-details.php` | High
48 | File | `/download` | Medium
49 | File | `/edit-subject.php` | High
50 | ... | ... | ...

There are 435 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/162.252.173.12
* https://search.censys.io/hosts/185.33.86.15
* https://search.censys.io/hosts/185.219.220.175
* https://search.censys.io/hosts/193.203.49.90
* https://thedfirreport.com/2025/06/30/hide-your-rdp-password-spray-leads-to-ransomhub-deployment/
* https://threatfox.abuse.ch
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-242a
* https://www.guidepointsecurity.com/blog/ransomhub-affiliate-leverage-python-based-backdoor/
* https://www.trendmicro.com/en_us/research/24/i/how-ransomhub-ransomware-uses-edrkillshifter-to-disable-edr-and-.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
