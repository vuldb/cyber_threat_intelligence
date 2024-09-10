# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 2 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\1E\Client\Tachyon.Performance.Metrics.exe` | High
2 | File | `/?import` | Medium
3 | File | `/Actions.php?a=login` | High
4 | File | `/add-students.php` | High
5 | File | `/admin` | Low
6 | File | `/admin/?page=categories/view_category` | High
7 | File | `/admin/?page=musics/manage_music` | High
8 | File | `/admin/admin-add-employee.php` | High
9 | File | `/admin/admin-update-employee.php` | High
10 | File | `/admin/ajax.php?action=delete_user` | High
11 | File | `/admin/ajax.php?action=save_settings` | High
12 | File | `/admin/assets/` | High
13 | File | `/admin/categories/manage_category.php` | High
14 | File | `/admin/clients/` | High
15 | File | `/admin/config_MT.php?action=delete` | High
16 | File | `/admin/config_time_sync.php` | High
17 | File | `/admin/dialog/select_images_post.php` | High
18 | File | `/admin/edit_area.php` | High
19 | File | `/admin/emp-profile-avatar.php` | High
20 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
21 | File | `/admin/get_price.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
24 | File | `/admin/index.php?r=user%2Fcreate` | High
25 | File | `/admin/manage_complaint.php` | High
26 | File | `/admin/manage_user.php` | High
27 | File | `/admin/pages/` | High
28 | File | `/admin/pages/list` | High
29 | File | `/admin/print_barcode.php` | High
30 | File | `/Admin/registration.php` | High
31 | File | `/admin/system.html` | High
32 | File | `/admin/system.php` | High
33 | File | `/admin/user/user-move-run.php` | High
34 | File | `/admin/view_reserved.php` | High
35 | File | `/ajax.php` | Medium
36 | File | `/ajax.php?action=login` | High
37 | File | `/ajax.php?action=save_establishment` | High
38 | File | `/ajax.php?action=save_quiz` | High
39 | File | `/ajax.php?action=save_user` | High
40 | File | `/api/blade-system/menu/list?updatexml` | High
41 | File | `/api/Common/uploadFile` | High
42 | File | `/api/dept` | Medium
43 | File | `/api/dept/build` | High
44 | File | `/api/role` | Medium
45 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
46 | File | `/api/system/user?deptId=1&page=1&size=10` | High
47 | File | `/api/test/download` | High
48 | File | `/api/user` | Medium
49 | File | `/api/v2/maps` | Medium
50 | File | `/apiclient/ember/index.jsp` | High
51 | File | `/App/Core/Extend/Function/ydLib.php` | High
52 | File | `/app/uploading/upload-mp3.php` | High
53 | File | `/authMonitCallcenter` | High
54 | File | `/bin/sh` | Low
55 | File | `/bolt/editcontent/showcases` | High
56 | File | `/branch_viewmore.php` | High
57 | File | `/cgi-bin/cstecgi.cgi` | High
58 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
59 | File | `/cgi-bin/hd_config.cgi` | High
60 | File | `/cgi-bin/myMusic.cgi` | High
61 | File | `/cgi-bin/nas_sharing.cgi` | High
62 | File | `/cgi-bin/p1_ftpserver.php` | High
63 | File | `/cgi-bin/photocenter_mgr.cgi` | High
64 | File | `/cgi-bin/s3.cgi` | High
65 | File | `/cgi-bin/webdav_mgr.cgi` | High
66 | File | `/cgi-bin/webfile_mgr.cgi` | High
67 | File | `/cgi-bin/wlogin.cgi` | High
68 | File | `/change_password.php` | High
69 | File | `/checkout` | Medium
70 | File | `/classes/Master.php` | High
71 | File | `/classes/Master.php?f=delete_category` | High
72 | File | `/classes/Master.php?f=delete_record` | High
73 | File | `/classes/Master.php?f=log_employee` | High
74 | File | `/classes/Master.php?f=log_visitor` | High
75 | File | `/classes/Master.php?f=save_medicine` | High
76 | File | `/classes/Master.php?f=save_package` | High
77 | File | `/classes/SystemSettings.php?f=update_settings` | High
78 | File | `/classes/Users.php?f=delete` | High
79 | File | `/classes/Users.php?f=register_user` | High
80 | File | `/classes/Users.php?f=save` | High
81 | File | `/classes/Users.php?f=save_client` | High
82 | File | `/cm/update_rows/page?id=2` | High
83 | File | `/conf/app.conf` | High
84 | File | `/config/getuser` | High
85 | File | `/control/add_act.php` | High
86 | ... | ... | ...

There are 756 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
