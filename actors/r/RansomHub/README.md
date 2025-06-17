# RansomHub - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RansomHub](https://vuldb.com/?actor.ransomhub). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ransomhub](https://vuldb.com/?actor.ransomhub)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RansomHub:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RansomHub.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.63.178](https://vuldb.com/?ip.5.8.63.178) | 5-8-63-178.static.x5x.tech | - | High
2 | [8.211.2.97](https://vuldb.com/?ip.8.211.2.97) | - | - | High
3 | [23.92.31.138](https://vuldb.com/?ip.23.92.31.138) | 23-92-31-138.ip.linodeusercontent.com | - | High
4 | [23.227.193.172](https://vuldb.com/?ip.23.227.193.172) | 23-227-193-172.static.hvvc.us | - | High
5 | [37.1.212.18](https://vuldb.com/?ip.37.1.212.18) | - | - | High
6 | [38.146.28.93](https://vuldb.com/?ip.38.146.28.93) | - | - | High
7 | [38.180.81.153](https://vuldb.com/?ip.38.180.81.153) | - | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RansomHub_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/about.php` | Medium
3 | File | `/add-category.php` | High
4 | File | `/admin/add_student.php` | High
5 | File | `/admin/file_manage_view` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/maintenance/brand.php` | High
8 | File | `/admin/profile.php` | High
9 | File | `/admin/search-vehicle.php` | High
10 | File | `/admin/student.php` | High
11 | File | `/admins/{adminId}` | High
12 | File | `/api/dept` | Medium
13 | File | `/api/RecordingList/DownloadRecord?file=` | High
14 | File | `/api/v1/public-chatflows/id` | High
15 | File | `/app/admin/controller/Upload.php` | High
16 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
17 | File | `/backend/admin/his_admin_register_patient.php` | High
18 | File | `/blog/blog.php` | High
19 | File | `/category.php` | High
20 | File | `/cgi` | Low
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/classes/Master.php` | High
23 | File | `/cms/classes/Master.php?f=delete_service` | High
24 | File | `/download` | Medium
25 | File | `/etc/shadow` | Medium
26 | File | `/expcatedit.php` | High
27 | File | `/forum/away.php` | High
28 | File | `/goform/SetNetControlList` | High
29 | File | `/hedwig.cgi` | Medium
30 | File | `/homeaction.php` | High
31 | File | `/ims/login.php` | High
32 | File | `/index.php` | Medium
33 | File | `/index.php?menu=asterisk_cli` | High
34 | File | `/labvantage/rc?command=file&file=WEB-OPAL/pagetypes/bulletins/sendbulletin.jsp` | High
35 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
36 | File | `/librarian/bookdetails.php` | High
37 | File | `/login/index.php` | High
38 | File | `/lot_details.php` | High
39 | File | `/mhds/clinic/view_details.php` | High
40 | File | `/online` | Low
41 | File | `/php_action/createUser.php` | High
42 | File | `/preview.php` | Medium
43 | File | `/resource/addgood.php` | High
44 | ... | ... | ...

There are 384 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/162.252.173.12
* https://search.censys.io/hosts/185.33.86.15
* https://search.censys.io/hosts/185.219.220.175
* https://search.censys.io/hosts/193.203.49.90
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
