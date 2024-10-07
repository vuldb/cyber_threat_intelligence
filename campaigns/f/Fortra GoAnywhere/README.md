# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/?actor.clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/?actor.clop) | Medium
2 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/?actor.clop) | High
3 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/?actor.clop) | High
4 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | [Clop](https://vuldb.com/?actor.clop) | High
5 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/?actor.clop) | High
6 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/?actor.clop) | High
7 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/?actor.clop) | High
8 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | [Clop](https://vuldb.com/?actor.clop) | High
9 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/?actor.clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/Actions.php?a=login` | High
4 | File | `/add-students.php` | High
5 | File | `/addcompany.php` | High
6 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
7 | File | `/admin/` | Low
8 | File | `/admin/?page=categories/view_category` | High
9 | File | `/admin/?page=musics/manage_music` | High
10 | File | `/Admin/add-admin.php` | High
11 | File | `/admin/admin-add-employee.php` | High
12 | File | `/admin/admin-update-employee.php` | High
13 | File | `/admin/admin_invt2.php` | High
14 | File | `/admin/ajax.php?action=save_settings` | High
15 | File | `/admin/assets/` | High
16 | File | `/admin/blood/update/B+.php` | High
17 | File | `/admin/blood/update/o-.php` | High
18 | File | `/admin/categories/manage_category.php` | High
19 | File | `/admin/clients/` | High
20 | File | `/admin/config_time_sync.php` | High
21 | File | `/admin/dialog/select_images_post.php` | High
22 | File | `/admin/edit_area.php` | High
23 | File | `/admin/edit_manufacturer.php` | High
24 | File | `/admin/emp-profile-avatar.php` | High
25 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
26 | File | `/admin/get_price.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
29 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
30 | File | `/admin/index.php?r=user%2Fcreate` | High
31 | File | `/admin/login.php` | High
32 | File | `/admin/maintenance/manage_department.php` | High
33 | File | `/admin/manage_complaint.php` | High
34 | File | `/admin/manage_user.php` | High
35 | File | `/admin/pages/` | High
36 | File | `/admin/pages/list` | High
37 | File | `/admin/print_barcode.php` | High
38 | File | `/Admin/registration.php` | High
39 | File | `/admin/robot.php` | High
40 | File | `/admin/system.html` | High
41 | File | `/admin/system.php` | High
42 | File | `/admin/template/edit` | High
43 | File | `/admin/user/user-move-run.php` | High
44 | File | `/admin/view_reserved.php` | High
45 | File | `/admin_class.php` | High
46 | File | `/ajax.php` | Medium
47 | File | `/ajax.php?action=delete_deductions` | High
48 | File | `/ajax.php?action=login` | High
49 | File | `/ajax.php?action=save_category` | High
50 | File | `/ajax.php?action=save_establishment` | High
51 | File | `/ajax.php?action=save_quiz` | High
52 | File | `/ajax.php?action=save_user` | High
53 | File | `/ajax.php?action=signup` | High
54 | File | `/ajax.php?action=update_account` | High
55 | File | `/api/blade-system/menu/list?updatexml` | High
56 | File | `/api/files/recipepictures/` | High
57 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
58 | File | `/api/system/user?deptId=1&page=1&size=10` | High
59 | File | `/api/test/download` | High
60 | File | `/apiclient/ember/index.jsp` | High
61 | File | `/app/action/add_staff.php` | High
62 | File | `/app/admin/controller/file/File.php` | High
63 | File | `/App/Core/Extend/Function/ydLib.php` | High
64 | File | `/authMonitCallcenter` | High
65 | File | `/bin/sh` | Low
66 | File | `/bitrix/admin/ldap_server_edit.php` | High
67 | File | `/bolt/editcontent/showcases` | High
68 | File | `/branch_viewmore.php` | High
69 | File | `/cgi-bin/cstecgi.cgi` | High
70 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
71 | File | `/cgi-bin/hd_config.cgi` | High
72 | File | `/cgi-bin/myMusic.cgi` | High
73 | File | `/cgi-bin/nas_sharing.cgi` | High
74 | File | `/cgi-bin/p1_ftpserver.php` | High
75 | File | `/cgi-bin/photocenter_mgr.cgi` | High
76 | File | `/cgi-bin/s3.cgi` | High
77 | File | `/cgi-bin/webdav_mgr.cgi` | High
78 | File | `/cgi-bin/webfile_mgr.cgi` | High
79 | File | `/cgi-bin/widget_api.cgi` | High
80 | File | `/change_password.php` | High
81 | File | `/classes/Master.php` | High
82 | File | `/classes/Master.php?f=delete_category` | High
83 | ... | ... | ...

There are 735 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
