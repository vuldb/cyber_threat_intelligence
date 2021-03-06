# IcedID - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _IcedID_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with IcedID:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 20 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with IcedID or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [IcedID](https://vuldb.com/?actor.icedid) | High
2 | [UAC-0098](https://vuldb.com/?actor.uac-0098) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of IcedID.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.46.161](https://vuldb.com/?ip.5.61.46.161) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
2 | [5.149.252.179](https://vuldb.com/?ip.5.149.252.179) | hnh7.arenal.xyz | [IcedID](https://vuldb.com/?actor.icedid) | High
3 | [31.24.224.12](https://vuldb.com/?ip.31.24.224.12) | 1f18e00c.setaptr.net | [IcedID](https://vuldb.com/?actor.icedid) | High
4 | [31.24.228.170](https://vuldb.com/?ip.31.24.228.170) | 31.24.228.170.static.midphase.com | [IcedID](https://vuldb.com/?actor.icedid) | High
5 | [31.184.199.11](https://vuldb.com/?ip.31.184.199.11) | dalesmanager.com | [IcedID](https://vuldb.com/?actor.icedid) | High
6 | [37.120.222.100](https://vuldb.com/?ip.37.120.222.100) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
7 | [45.129.99.241](https://vuldb.com/?ip.45.129.99.241) | 354851-vds-mamozw.gmhost.pp.ua | [IcedID](https://vuldb.com/?actor.icedid) | High
8 | [45.138.172.179](https://vuldb.com/?ip.45.138.172.179) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
9 | [45.147.228.198](https://vuldb.com/?ip.45.147.228.198) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
10 | [45.147.230.82](https://vuldb.com/?ip.45.147.230.82) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
11 | [45.147.230.88](https://vuldb.com/?ip.45.147.230.88) | mailnode7.bulletproof-mail.biz | [IcedID](https://vuldb.com/?actor.icedid) | High
12 | [45.147.231.113](https://vuldb.com/?ip.45.147.231.113) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
13 | [45.153.240.135](https://vuldb.com/?ip.45.153.240.135) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
14 | [45.153.241.115](https://vuldb.com/?ip.45.153.241.115) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
15 | [46.17.98.191](https://vuldb.com/?ip.46.17.98.191) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
16 | [46.249.62.199](https://vuldb.com/?ip.46.249.62.199) | - | [IcedID](https://vuldb.com/?actor.icedid) | High
17 | [79.141.161.176](https://vuldb.com/?ip.79.141.161.176) | zzs7bp73.copycomdigital.com | [IcedID](https://vuldb.com/?actor.icedid) | High
18 | [79.141.164.241](https://vuldb.com/?ip.79.141.164.241) | x6ts.mtsgamingpro.fun | [IcedID](https://vuldb.com/?actor.icedid) | High
19 | [79.141.166.39](https://vuldb.com/?ip.79.141.166.39) | webimpa.com | [IcedID](https://vuldb.com/?actor.icedid) | High
20 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within IcedID. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during IcedID. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/admin-document/@@share` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/inquiries/view_details.php` | High
5 | File | `/anony/mjpg.cgi` | High
6 | File | `/bin/sh` | Low
7 | File | `/cgi-bin/editBookmark` | High
8 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
9 | File | `/etc/shadow` | Medium
10 | File | `/EXCU_SHELL` | Medium
11 | File | `/export` | Low
12 | File | `/GetSimpleCMS-3.3.15/admin/log.php` | High
13 | File | `/goform/addressNat` | High
14 | File | `/iisadmpwd` | Medium
15 | File | `/include/menu_v.inc.php` | High
16 | File | `/lms/admin.php` | High
17 | File | `/mc` | Low
18 | File | `/mgmt/tm/util/bash` | High
19 | File | `/my_photo_gallery/image.php` | High
20 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
21 | File | `/out.php` | Medium
22 | File | `/proc/*/cmdline"` | High
23 | File | `/proc/pid/syscall` | High
24 | File | `/reps/classes/Users.php?f=delete_agent` | High
25 | File | `/rest/review-coverage-chart/1.0/data/<repository_name>/.json` | High
26 | File | `/TeamMate/Upload/DomainObjectDocumentUpload.ashx` | High
27 | File | `/uncpath/` | Medium
28 | File | `/usr/bin/pkexec` | High
29 | File | `/var/log/pcp/configs.sh` | High
30 | File | `/webconsole/APIController` | High
31 | File | `/wp-admin/admin-ajax.php` | High
32 | File | `/WWW//app/admin/controller/admincontroller.php` | High
33 | File | `a-b-membres.php` | High
34 | File | `action.php` | Medium
35 | File | `admin-search.php` | High
36 | File | `admin.jcomments.php` | High
37 | File | `admin/adminsignin.html` | High
38 | File | `admin/index.php` | High
39 | File | `admin/infoclass_update.php` | High
40 | File | `admin/plugin.php` | High
41 | File | `admin/versions.html` | High
42 | File | `administrator/index.php?option=com_pago&view=comments` | High
43 | File | `Adminlog.asp` | Medium
44 | File | `admin_iplog.php` | High
45 | File | `ajax.php` | Medium
46 | File | `ajax_admin_apis.php` | High
47 | File | `ajax_php_pecl.php` | High
48 | ... | ... | ...

There are 412 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2018/04/icedid-banking-trojan.html
* https://cert.gov.ua/article/39609
* https://isc.sans.edu/forums/diary/Analysis+from+March+2021+Traffic+Analysis+Quiz/27232/
* https://isc.sans.edu/forums/diary/Emotet+infection+with+IcedID+banking+Trojan/24312/
* https://isc.sans.edu/forums/diary/Emotet+infections+and+followup+malware/24532/
* https://isc.sans.edu/forums/diary/Malspam+links+to+passwordprotected+Word+docs+that+push+IcedID+Bokbot/24428/
* https://isc.sans.edu/forums/diary/Malspam+with+links+to+Word+docs+pushes+IcedID+Bokbot/25640/
* https://isc.sans.edu/forums/diary/Malspam+with+passwordprotected+word+docs+still+pushing+IcedID+Bokbot+with+Trickbot/24708/
* https://isc.sans.edu/forums/diary/Microsoft+Word+document+with+malicious+macro+pushes+IcedID+Bokbot/26146/
* https://isc.sans.edu/forums/diary/One+Emotet+infection+leads+to+three+followup+malware+infections/24140/
* https://research.checkpoint.com/2021/melting-ice-tracking-icedid-servers-with-a-few-simple-steps/
* https://thedfirreport.com/2021/07/19/icedid-and-cobalt-strike-vs-antivirus/
* https://thedfirreport.com/2021/10/18/icedid-to-xinglocker-ransomware-in-24-hours/
* https://www.cybereason.com/blog/cybereason-vs.-quantum-locker-ransomware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
