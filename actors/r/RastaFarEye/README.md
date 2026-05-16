# RastaFarEye - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RastaFarEye](https://vuldb.com/?actor.rastafareye). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rastafareye](https://vuldb.com/?actor.rastafareye)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RastaFarEye:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RastaFarEye. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/ipcamSetParamPost` | High
2 | File | `/admin/?page=orders/view_order` | High
3 | File | `/admin/add_exercises.php` | High
4 | File | `/admin/baojia_list.php` | High
5 | File | `/admin/create_product.php` | High
6 | File | `/admin/index.php?page=manage_product` | High
7 | File | `/admin/maintenance/view_designation.php` | High
8 | File | `/adminui/history_log.php` | High
9 | File | `/ajax/remove_sniffer_raw_log/` | High
10 | File | `/api/RecordingList/DownloadRecord?file=` | High
11 | File | `/api/v1/serve/awel/flow/import` | High
12 | File | `/apply.cgi` | Medium
13 | File | `/apply/index.php` | High
14 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
15 | File | `/backend/admin/his_admin_register_patient.php` | High
16 | File | `/bin/httpd` | Medium
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/nas_sharing.cgi` | High
19 | File | `/check_availability.php` | High
20 | File | `/config/pw_changeusers.html` | High
21 | File | `/dacomponentui/profiles/profileitems/outlooksettings/Insertimage.aspx` | High
22 | File | `/dm/dispatch/user/add` | High
23 | File | `/equipment/get_Information` | High
24 | File | `/foms/routers/place-order.php` | High
25 | File | `/forum/away.php` | High
26 | File | `/gena.cgi` | Medium
27 | File | `/general/email/outbox/delete.php` | High
28 | File | `/goform/AddSysLogRule` | High
29 | File | `/goform/delDhcpRules/` | High
30 | File | `/goform/SysToolReboot` | High
31 | File | `/h/search?action` | High
32 | File | `/Home/Index` | Medium
33 | File | `/horde/util/go.php` | High
34 | File | `/index.php?module=entities/entities` | High
35 | File | `/manage_sy.php` | High
36 | File | `/meetings/listmeetings.php` | High
37 | File | `/mhds/clinic/view_details.php` | High
38 | File | `/oauth/idp/.well-known/openid-configuration` | High
39 | File | `/php/ping.php` | High
40 | File | `/PreviewHandler.ashx` | High
41 | File | `/rapi/read_url` | High
42 | File | `/resourceNode/jdbcResourceEdit.jsf` | High
43 | File | `/resourceNode/resources.jsf` | High
44 | File | `/resources//../` | High
45 | File | `/script/academic/announcement` | High
46 | File | `/Script/admin/core/update_policy` | High
47 | File | `/scripts/unlock_tasks.php` | High
48 | File | `/sec/content/sec_asa_users_local_db_add.html` | High
49 | File | `/see_more_details.php` | High
50 | File | `/spgpm/updateListing` | High
51 | File | `/spip.php` | Medium
52 | File | `/student/bookdetails.php` | High
53 | File | `/SysInfo1.htm` | High
54 | File | `/sysinfo_json.cgi` | High
55 | File | `/system/dictData/loadDictItem` | High
56 | File | `/system/user/modules/mod_users/controller.php` | High
57 | File | `/usr/bin/pkexec` | High
58 | File | `/view/student_exam_mark_insert_form1.php` | High
59 | ... | ... | ...

There are 518 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trellix.com/blogs/research/darkgate-again-but-improved/
* https://www.trellix.com/blogs/research/the-continued-evolution-of-the-darkgate-malware-as-a-service/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
