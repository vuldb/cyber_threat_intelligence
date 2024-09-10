# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Applejeus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | - | High
2 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | - | High
3 | [95.213.232.170](https://vuldb.com/?ip.95.213.232.170) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Applejeus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?g=net_pro_keyword_import_save` | High
3 | File | `/actuator/heapdump` | High
4 | File | `/admin` | Low
5 | File | `/admin/?page=categories/view_category` | High
6 | File | `/Admin/add-admin.php` | High
7 | File | `/admin/addgiving.php` | High
8 | File | `/admin/addTithes.php` | High
9 | File | `/admin/add_ikev2.php` | High
10 | File | `/admin/add_postlogin.php` | High
11 | File | `/admin/add_sundaysch.php` | High
12 | File | `/admin/admin-add-employee.php` | High
13 | File | `/admin/adminHome.php` | High
14 | File | `/admin/admin_cl.php?mudi=revPwd` | High
15 | File | `/admin/admin_user.php` | High
16 | File | `/admin/ajax.php?action=save_settings` | High
17 | File | `/admin/case-type` | High
18 | File | `/admin/config_Anticrack.php` | High
19 | File | `/admin/config_ISCGroupNoCache.php` | High
20 | File | `/admin/config_MT.php?action=delete` | High
21 | File | `/admin/delete_log.php` | High
22 | File | `/Admin/edit-photo.php` | High
23 | File | `/admin/edit-post.php` | High
24 | File | `/Admin/edit_profile.php` | High
25 | File | `/admin/forgot-password.php` | High
26 | File | `/admin/general-setting` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/index2.html` | High
29 | File | `/admin/list_crl_conf` | High
30 | File | `/admin/login.php` | High
31 | File | `/admin/maintenance/manage_brand.php` | High
32 | File | `/admin/manage-ambulance.php` | High
33 | File | `/admin/media_folders` | High
34 | File | `/admin/pages/` | High
35 | File | `/admin/system.html` | High
36 | File | `/adminPage/conf/reload` | High
37 | File | `/adminPage/main/upload` | High
38 | File | `/adminPage/www/addOver` | High
39 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
40 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
41 | File | `/adminpanel/admin/query/addCourseExe.php` | High
42 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
43 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
44 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
45 | File | `/adminpanel/admin/query/loginExe.php` | High
46 | File | `/admin_class.php` | High
47 | File | `/api/blade-user/export-user` | High
48 | File | `/api/file/downloadfile` | High
49 | File | `/api/process.php` | High
50 | File | `/api/runscript` | High
51 | File | `/api/snapshots/` | High
52 | File | `/api/v1/snapshots` | High
53 | File | `/api/v2/maps` | Medium
54 | File | `/application/controller/Pelanggan.php` | High
55 | File | `/application/controller/Pengeluaran.php` | High
56 | File | `/application/controller/Transaki.php` | High
57 | File | `/authMonitCallcenter` | High
58 | File | `/backend/register.php` | High
59 | File | `/branch_viewmore.php` | High
60 | File | `/cart.php` | Medium
61 | File | `/cgi-bin/cstecgi.cgi` | High
62 | File | `/cgi-bin/nas_sharing.cgi` | High
63 | File | `/cgi-bin/p1_ftpserver.php` | High
64 | File | `/cgi-bin/system_mgr.cgi` | High
65 | File | `/cgi-bin/tosei_kikai.php` | High
66 | File | `/cgi-bin/wlogin.cgi` | High
67 | File | `/classes/Master.php?f=log_visitor` | High
68 | File | `/classes/Master.php?f=save_medicine` | High
69 | File | `/classes/Master.php?f=save_package` | High
70 | File | `/classes/SystemSettings.php?f=update_settings` | High
71 | File | `/classes/Users.php?f=delete` | High
72 | File | `/classes/Users.php?f=save` | High
73 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
74 | File | `/cm/update_rows/page?id=2` | High
75 | File | `/cms/classes/Users.php?f=delete_client` | High
76 | File | `/control/activate_case.php` | High
77 | ... | ... | ...

There are 674 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
