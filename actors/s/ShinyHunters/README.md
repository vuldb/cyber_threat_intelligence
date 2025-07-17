# ShinyHunters - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ShinyHunters](https://vuldb.com/?actor.shinyhunters). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shinyhunters](https://vuldb.com/?actor.shinyhunters)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ShinyHunters:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ShinyHunters.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.47.87.202](https://vuldb.com/?ip.5.47.87.202) | - | - | High
2 | [37.19.210.21](https://vuldb.com/?ip.37.19.210.21) | unn-37-19-210-21.datapacket.com | - | High
3 | [37.19.210.34](https://vuldb.com/?ip.37.19.210.34) | unn-37-19-210-34.datapacket.com | - | High
4 | [45.86.221.146](https://vuldb.com/?ip.45.86.221.146) | - | - | High
5 | [45.134.140.144](https://vuldb.com/?ip.45.134.140.144) | unn-45-134-140-144.datapacket.com | - | High
6 | [45.134.142.200](https://vuldb.com/?ip.45.134.142.200) | unn-45-134-142-200.datapacket.com | - | High
7 | [45.155.91.99](https://vuldb.com/?ip.45.155.91.99) | - | - | High
8 | [66.63.167.147](https://vuldb.com/?ip.66.63.167.147) | 66.63.167.147.static.quadranet.com | - | High
9 | [66.115.189.247](https://vuldb.com/?ip.66.115.189.247) | - | - | High
10 | [79.127.217.44](https://vuldb.com/?ip.79.127.217.44) | unn-79-127-217-44.datapacket.com | - | High
11 | [87.249.134.11](https://vuldb.com/?ip.87.249.134.11) | unn-87-249-134-11.datapacket.com | - | High
12 | [93.115.0.49](https://vuldb.com/?ip.93.115.0.49) | - | - | High
13 | [96.44.191.140](https://vuldb.com/?ip.96.44.191.140) | 96.44.191.140.static.quadranet.com | - | High
14 | ... | ... | ... | ...

There are 53 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ShinyHunters_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-25, CWE-36, CWE-37, CWE-44 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ShinyHunters. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abs.php` | Medium
2 | File | `/academy/tutor/filter` | High
3 | File | `/accessdenied` | High
4 | File | `/action/import_file/` | High
5 | File | `/add-category.php` | High
6 | File | `/admin` | Low
7 | File | `/admin/add-customer.php` | High
8 | File | `/admin/add-nurse.php` | High
9 | File | `/admin/add_student.php` | High
10 | File | `/admin/assign_save.php` | High
11 | File | `/admin/attendance_action.php` | High
12 | File | `/admin/check_admin_login.php` | High
13 | File | `/admin/create_product.php` | High
14 | File | `/admin/doctor-specilization.php` | High
15 | File | `/admin/edit-category.php` | High
16 | File | `/admin/gallery.php` | High
17 | File | `/admin/index2.html` | High
18 | File | `/admin/link.php` | High
19 | File | `/admin/login.php` | High
20 | File | `/admin/manage-pages.php` | High
21 | File | `/admin/member_save.php` | High
22 | File | `/admin/menu_update.php` | High
23 | File | `/admin/mod_reservation/controller.php` | High
24 | File | `/admin/profile.php` | High
25 | File | `/admin/reservation_view.php` | High
26 | File | `/admin/return_add.php` | High
27 | File | `/admin/tag/save` | High
28 | File | `/admin/user-search.php` | High
29 | File | `/admin/user_save.php` | High
30 | File | `/admin_user.php` | High
31 | File | `/ajax.php?action=read_msg` | High
32 | File | `/api/blade-log/api/list` | High
33 | File | `/api/blade-system/menu/list?updatexml` | High
34 | File | `/api/blade-user/submit` | High
35 | File | `/api/crontab` | Medium
36 | File | `/api/database/testConnect` | High
37 | File | `/api/mjkj-chat/cgform-api/addData/` | High
38 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
39 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
40 | File | `/api/pipelines/upload` | High
41 | File | `/api/school/registerSchool` | High
42 | File | `/api/system/dept/update` | High
43 | File | `/api/upload.php` | High
44 | File | `/api/v1/documents/` | High
45 | File | `/api/v1/memories/{id}/update` | High
46 | File | `/app/admin/controller/api/Plugs.php` | High
47 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
48 | File | `/App/Tpl/Admin/Default/Log/index.html` | High
49 | File | `/approve_lawyer.php` | High
50 | File | `/authenticate.php` | High
51 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
52 | File | `/backend/admin/his_admin_register_patient.php` | High
53 | File | `/bin/webs` | Medium
54 | File | `/biurl_grou` | Medium
55 | File | `/boafrm/formWlanMultipleAP` | High
56 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/threat-advisory-snowflake-data-breach-impacts-its-clients/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
