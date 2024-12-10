# RastaFarEye - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RastaFarEye](https://vuldb.com/?actor.rastafareye). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rastafareye](https://vuldb.com/?actor.rastafareye)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RastaFarEye:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RastaFarEye.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.34.178.21](https://vuldb.com/?ip.5.34.178.21) | node240816.us | - | High
2 | [5.188.87.58](https://vuldb.com/?ip.5.188.87.58) | - | - | High
3 | [5.252.177.213](https://vuldb.com/?ip.5.252.177.213) | no-rdns.mivocloud.com | - | High
4 | [45.61.156.3](https://vuldb.com/?ip.45.61.156.3) | - | - | High
5 | [45.63.52.184](https://vuldb.com/?ip.45.63.52.184) | 45.63.52.184.vultrusercontent.com | - | Medium
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RastaFarEye_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RastaFarEye. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/ipcamSetParamPost` | High
2 | File | `/admin/?page=orders/view_order` | High
3 | File | `/admin/add_exercises.php` | High
4 | File | `/admin/baojia_list.php` | High
5 | File | `/admin/index.php?page=manage_product` | High
6 | File | `/admin/maintenance/view_designation.php` | High
7 | File | `/adminui/history_log.php` | High
8 | File | `/ajax/remove_sniffer_raw_log/` | High
9 | File | `/api/RecordingList/DownloadRecord?file=` | High
10 | File | `/apply.cgi` | Medium
11 | File | `/apply/index.php` | High
12 | File | `/bin/httpd` | Medium
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/nas_sharing.cgi` | High
15 | File | `/check_availability.php` | High
16 | File | `/dacomponentui/profiles/profileitems/outlooksettings/Insertimage.aspx` | High
17 | File | `/foms/routers/place-order.php` | High
18 | File | `/forum/away.php` | High
19 | File | `/gena.cgi` | Medium
20 | File | `/general/email/outbox/delete.php` | High
21 | File | `/goform/AddSysLogRule` | High
22 | File | `/goform/delDhcpRules/` | High
23 | File | `/goform/SysToolReboot` | High
24 | File | `/h/search?action` | High
25 | File | `/Home/Index` | Medium
26 | File | `/horde/util/go.php` | High
27 | File | `/index.php?module=entities/entities` | High
28 | File | `/manage_sy.php` | High
29 | File | `/meetings/listmeetings.php` | High
30 | File | `/mhds/clinic/view_details.php` | High
31 | File | `/oauth/idp/.well-known/openid-configuration` | High
32 | File | `/php/ping.php` | High
33 | File | `/PreviewHandler.ashx` | High
34 | File | `/rapi/read_url` | High
35 | File | `/resourceNode/jdbcResourceEdit.jsf` | High
36 | File | `/resourceNode/resources.jsf` | High
37 | File | `/resources//../` | High
38 | File | `/Script/admin/core/update_policy` | High
39 | File | `/scripts/unlock_tasks.php` | High
40 | File | `/sec/content/sec_asa_users_local_db_add.html` | High
41 | File | `/see_more_details.php` | High
42 | File | `/spip.php` | Medium
43 | File | `/student/bookdetails.php` | High
44 | File | `/SysInfo1.htm` | High
45 | File | `/sysinfo_json.cgi` | High
46 | File | `/system/dictData/loadDictItem` | High
47 | File | `/system/user/modules/mod_users/controller.php` | High
48 | File | `/view/student_exam_mark_insert_form1.php` | High
49 | File | `/view/vpn/autovpn/sub_commit.php` | High
50 | File | `/wmiwizard.jsp` | High
51 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
52 | File | `/wp-json` | Medium
53 | File | `/wp-json/wc/v3/webhooks` | High
54 | File | `3.6.cpj` | Low
55 | ... | ... | ...

There are 482 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trellix.com/blogs/research/darkgate-again-but-improved/
* https://www.trellix.com/blogs/research/the-continued-evolution-of-the-darkgate-malware-as-a-service/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
