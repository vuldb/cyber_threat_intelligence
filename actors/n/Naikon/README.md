# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Naikon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [47.241.127.190](https://vuldb.com/?ip.47.241.127.190) | - | - | High
2 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | Camerashy | High
3 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | Camerashy | High
4 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | Camerashy | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Naikon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-35, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-272, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academy/home/courses` | High
2 | File | `/academy/tutor/filter` | High
3 | File | `/admin/?/page/add` | High
4 | File | `/admin/?/page/delete/10` | High
5 | File | `/admin/?/snippet/add` | High
6 | File | `/admin/about_edit.php?action=modify` | High
7 | File | `/admin/add_room_controller.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/admin_editor.php` | High
10 | File | `/admin/admin_group.php?mode=delete/group_id=3` | High
11 | File | `/admin/admin_log.php?clear=1` | High
12 | File | `/admin/ajax.php?action=save_settings` | High
13 | File | `/admin/bookings/view_details.php` | High
14 | File | `/admin/category/cate-edit-run.php` | High
15 | File | `/admin/class.php?dowhat=modifyclass` | High
16 | File | `/admin/del_category.php` | High
17 | File | `/admin/del_service.php` | High
18 | File | `/admin/domain_management.php?id=0&list=whitelist&remove=pligg.com` | High
19 | File | `/admin/index.php` | High
20 | File | `/admin/mod_reports/index.php` | High
21 | File | `/admin/mod_reports/printreport.php` | High
22 | File | `/admin/mod_room/index.php` | High
23 | File | `/admin/offenses/view_details.php` | High
24 | File | `/admin/report/index.php` | High
25 | File | `/ajax.php?action=save_company` | High
26 | File | `/api/test/download` | High
27 | File | `/api/upload` | Medium
28 | File | `/api/v1` | Low
29 | File | `/bolt/editcontent/showcases` | High
30 | File | `/cgi-bin/cstecgi.cgi` | High
31 | File | `/cgi-bin/ExportSettings.sh` | High
32 | File | `/cgi-bin/glc` | Medium
33 | File | `/cgi-bin/photocenter_mgr.cgi` | High
34 | File | `/cgi-bin/s3.cgi` | High
35 | File | `/changeimage.php` | High
36 | File | `/classes/Master.php?f=log_employee` | High
37 | File | `/classes/Master.php?f=save_inquiry` | High
38 | File | `/classes/Master.php?f=save_package` | High
39 | File | `/classes/Master.php?f=update_order_status` | High
40 | File | `/classes/SystemSettings.php?f=update_settings` | High
41 | File | `/classes/Users.php?f=save` | High
42 | File | `/config` | Low
43 | File | `/core/signup_user.php` | High
44 | File | `/edit_account.php` | High
45 | File | `/en/blog-comment-4` | High
46 | File | `/endpoint/delete-task.php` | High
47 | File | `/etc/initab` | Medium
48 | File | `/etc/shadow` | Medium
49 | File | `/find-a-match` | High
50 | File | `/friends` | Medium
51 | File | `/general/ipanel/menu_code.php?MENU_TYPE=FAV` | High
52 | File | `/getcfg.php` | Medium
53 | File | `/goform/apPortalAuth` | High
54 | File | `/goform/apPortalOneKeyAuth` | High
55 | File | `/goform/DhcpListClient` | High
56 | File | `/goform/edit_lf_get_data` | High
57 | File | `/goform/GstDhcpSetSer` | High
58 | File | `/goform/qossetting` | High
59 | File | `/h.php/general/config?ref=addtabs` | High
60 | File | `/I/list.php` | Medium
61 | File | `/incedit.php?id=4` | High
62 | File | `/index.php` | Medium
63 | File | `/index.php/basedata/contact/delete?action=delete` | High
64 | File | `/index.php/client/message/message_read/xxxxxxxx[random-msg-hash]` | High
65 | File | `/index.php?action=editManager` | High
66 | File | `/listplace/user/coverPhotoUpdate` | High
67 | ... | ... | ...

There are 588 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf
* https://1275.ru/ioc/164/lotus-panda-apt-iocs/
* https://research.checkpoint.com/2020/naikon-apt-cyber-espionage-reloaded/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.04.23(1)/NAIKON.pdf
* https://www.threatminer.org/report.php?q=TheNaikonAPT-MsnMM1.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
