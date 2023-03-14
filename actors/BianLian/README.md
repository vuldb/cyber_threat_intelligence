# BianLian - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BianLian](https://vuldb.com/?actor.bianlian). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bianlian](https://vuldb.com/?actor.bianlian)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BianLian:

* [SC](https://vuldb.com/?country.sc)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BianLian.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.79.138](https://vuldb.com/?ip.5.2.79.138) | - | - | High
2 | [5.188.6.118](https://vuldb.com/?ip.5.188.6.118) | subnet.local | - | High
3 | [5.230.67.2](https://vuldb.com/?ip.5.230.67.2) | - | - | High
4 | [13.49.57.110](https://vuldb.com/?ip.13.49.57.110) | ec2-13-49-57-110.eu-north-1.compute.amazonaws.com | - | Medium
5 | [16.162.137.220](https://vuldb.com/?ip.16.162.137.220) | ec2-16-162-137-220.ap-east-1.compute.amazonaws.com | - | Medium
6 | [18.130.242.71](https://vuldb.com/?ip.18.130.242.71) | ec2-18-130-242-71.eu-west-2.compute.amazonaws.com | - | Medium
7 | [23.94.56.154](https://vuldb.com/?ip.23.94.56.154) | 23-94-56-154-host.colocrossing.com | - | High
8 | [23.227.198.243](https://vuldb.com/?ip.23.227.198.243) | 23-227-198-243.static.hvvc.us | - | High
9 | [37.235.54.81](https://vuldb.com/?ip.37.235.54.81) | 81.54.235.37.in-addr.arpa | - | High
10 | [43.155.116.250](https://vuldb.com/?ip.43.155.116.250) | - | - | High
11 | [45.9.150.132](https://vuldb.com/?ip.45.9.150.132) | - | - | High
12 | [45.92.156.105](https://vuldb.com/?ip.45.92.156.105) | - | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BianLian_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BianLian. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/addQuestion.php` | High
3 | File | `/admin/conferences/get-all-status/` | High
4 | File | `/admin/conferences/list/` | High
5 | File | `/admin/countrymanagement.php` | High
6 | File | `/admin/general/change-lang` | High
7 | File | `/admin/group/list/` | High
8 | File | `/admin/renewaldue.php` | High
9 | File | `/admin/usermanagement.php` | High
10 | File | `/admin/ztliuyan_sendmail.php` | High
11 | File | `/api/RecordingList/DownloadRecord?file=` | High
12 | File | `/api/v1/chat.getThreadsList` | High
13 | File | `/app1/admin#foo` | High
14 | File | `/aya/module/admin/ust_tab_e.inc.php` | High
15 | File | `/backups/` | Medium
16 | File | `/bl-plugins/backup/plugin.php` | High
17 | File | `/category.php` | High
18 | File | `/cgi-bin/editBookmark` | High
19 | File | `/chart` | Low
20 | File | `/classes/Master.php?f=delete_appointment` | High
21 | File | `/Core/Ap4Utils.h` | High
22 | File | `/ctpms/classes/Master.php?f=delete_application` | High
23 | File | `/front/roomtype-details.php` | High
24 | File | `/goform/aspForm` | High
25 | File | `/hdf5/src/H5T.c` | High
26 | File | `/homeaction.php` | High
27 | File | `/horde/imp/search.php` | High
28 | File | `/index.php` | Medium
29 | File | `/installer/upgrade_start` | High
30 | File | `/Items/*/RemoteImages/Download` | High
31 | File | `/items/view_item.php` | High
32 | File | `/lan.asp` | Medium
33 | File | `/librarian/bookdetails.php` | High
34 | File | `/lists/admin/` | High
35 | File | `/login/index.php` | High
36 | File | `/mail/index.html` | High
37 | File | `/navigate/navigate_download.php` | High
38 | File | `/public/plugins/` | High
39 | File | `/rapi/read_url` | High
40 | File | `/reps/admin/?page=agents/manage_agent` | High
41 | File | `/rest/api/1.0/render` | High
42 | File | `/rest/api/latest/projectvalidate/key` | High
43 | File | `/rest/jpo/1.0/hierarchyConfiguration` | High
44 | ... | ... | ...

There are 377 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://rhisac.org/threat-intelligence/bianlian-ransomware-expanding-c2-infrastructure-and-operational-tempo/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
