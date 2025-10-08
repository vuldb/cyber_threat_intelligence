# Miner - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Miner](https://vuldb.com/?actor.miner). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.miner](https://vuldb.com/?actor.miner)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Miner:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Miner.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.27](https://vuldb.com/?ip.5.9.116.27) | static.27.116.9.5.clients.your-server.de | - | High
2 | [5.9.175.19](https://vuldb.com/?ip.5.9.175.19) | static.19.175.9.5.clients.your-server.de | - | High
3 | [5.9.176.3](https://vuldb.com/?ip.5.9.176.3) | static.3.176.9.5.clients.your-server.de | - | High
4 | [5.9.198.83](https://vuldb.com/?ip.5.9.198.83) | static.83.198.9.5.clients.your-server.de | - | High
5 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
6 | [23.6.70.227](https://vuldb.com/?ip.23.6.70.227) | a23-6-70-227.deploy.static.akamaitechnologies.com | - | High
7 | [23.13.208.26](https://vuldb.com/?ip.23.13.208.26) | a23-13-208-26.deploy.static.akamaitechnologies.com | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Miner_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Miner. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/admin/?setting-base.htm` | High
3 | File | `/admin/add-category.php` | High
4 | File | `/admin/edit-admin.php` | High
5 | File | `/admin/edit-subcategory.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/list_resource_icon.php?action=delete` | High
8 | File | `/admin/serverinfo` | High
9 | File | `/admin/singlelogin.php` | High
10 | File | `/admin/view-patient.php` | High
11 | File | `/admin/voters_delete.php` | High
12 | File | `/ajax/check_medicine_name.php` | High
13 | File | `/alphaware/summary.php` | High
14 | File | `/api/blade-user/export-user` | High
15 | File | `/api/geojson` | Medium
16 | File | `/api/sys/login` | High
17 | File | `/app/sys1.php` | High
18 | File | `/bcms/admin/?page=user/manage_user` | High
19 | File | `/book_list.php` | High
20 | File | `/cgi-bin/downloadFile.cgi` | High
21 | File | `/cgi-bin/ExportAllSettings.sh` | High
22 | File | `/cgi-bin/kerbynet` | High
23 | File | `/cgi-bin/nas_sharing.cgi` | High
24 | File | `/cgi/networkDiag.cgi` | High
25 | File | `/classes/Master.php` | High
26 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
27 | File | `/com/esafenet/servlet/policy/HookService.java` | High
28 | File | `/controller/OnlinePreviewController.java` | High
29 | File | `/debug/pprof` | Medium
30 | File | `/em/console/logon/logon` | High
31 | File | `/env` | Low
32 | File | `/file` | Low
33 | File | `/general/email/inbox/delete_webmail.php` | High
34 | File | `/goform/SetNetControlList` | High
35 | File | `/list` | Low
36 | File | `/login.php` | Medium
37 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
38 | File | `/net/sched/cls_fw.c` | High
39 | File | `/oews/admin/` | Medium
40 | File | `/photo-gallery` | High
41 | ... | ... | ...

There are 349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/08/threat-roundup-0726-0802.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0304-0311.html
* https://blog.talosintelligence.com/2022/07/threat-roundup-0701-0708.html
* https://urlhaus.abuse.ch/url/3560727/
* https://urlhaus.abuse.ch/url/3576213/
* https://urlhaus.abuse.ch/url/3577017/
* https://urlhaus.abuse.ch/url/3577021/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
