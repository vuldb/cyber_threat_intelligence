# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?g=net_pro_keyword_import_save` | High
3 | File | `/?page=tracks` | High
4 | File | `/actuator/heapdump` | High
5 | File | `/admin` | Low
6 | File | `/admin/?page=categories/view_category` | High
7 | File | `/Admin/add-admin.php` | High
8 | File | `/admin/addgiving.php` | High
9 | File | `/admin/addTithes.php` | High
10 | File | `/admin/add_ikev2.php` | High
11 | File | `/admin/add_postlogin.php` | High
12 | File | `/admin/add_sundaysch.php` | High
13 | File | `/admin/admin-add-employee.php` | High
14 | File | `/admin/adminHome.php` | High
15 | File | `/admin/admin_cl.php?mudi=revPwd` | High
16 | File | `/admin/admin_user.php` | High
17 | File | `/admin/ajax.php?action=save_settings` | High
18 | File | `/admin/case-type` | High
19 | File | `/admin/config_Anticrack.php` | High
20 | File | `/admin/config_ISCGroupNoCache.php` | High
21 | File | `/admin/config_MT.php?action=delete` | High
22 | File | `/admin/delete_log.php` | High
23 | File | `/Admin/edit-photo.php` | High
24 | File | `/admin/edit-post.php` | High
25 | File | `/admin/edit_area.php` | High
26 | File | `/Admin/edit_profile.php` | High
27 | File | `/admin/file_manager/export` | High
28 | File | `/admin/file_manager/files` | High
29 | File | `/admin/forgot-password.php` | High
30 | File | `/admin/general-setting` | High
31 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/index2.html` | High
34 | File | `/admin/list_crl_conf` | High
35 | File | `/admin/login.php` | High
36 | File | `/admin/maintenance/manage_brand.php` | High
37 | File | `/admin/manage-ambulance.php` | High
38 | File | `/admin/media_folders` | High
39 | File | `/admin/pages/` | High
40 | File | `/admin/system.html` | High
41 | File | `/admin/template/edit` | High
42 | File | `/admin/user/user-move-run.php` | High
43 | File | `/adminPage/conf/reload` | High
44 | File | `/adminPage/main/upload` | High
45 | File | `/adminPage/www/addOver` | High
46 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
47 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
48 | File | `/adminpanel/admin/query/addCourseExe.php` | High
49 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
50 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
51 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
52 | File | `/adminpanel/admin/query/loginExe.php` | High
53 | File | `/admin_class.php` | High
54 | File | `/ajax/chpwd.php` | High
55 | File | `/ajax/getBasicInfo.php` | High
56 | File | `/api/blade-user/export-user` | High
57 | File | `/api/file/downloadfile` | High
58 | File | `/api/process.php` | High
59 | File | `/api/runscript` | High
60 | File | `/api/snapshots/` | High
61 | File | `/api/v1/snapshots` | High
62 | File | `/api/v2/maps` | Medium
63 | File | `/application/controller/Pelanggan.php` | High
64 | File | `/application/controller/Pengeluaran.php` | High
65 | File | `/application/controller/Transaki.php` | High
66 | File | `/authMonitCallcenter` | High
67 | File | `/backend/register.php` | High
68 | File | `/branch_viewmore.php` | High
69 | File | `/cart.php` | Medium
70 | File | `/cgi-bin/cstecgi.cgi` | High
71 | File | `/cgi-bin/nas_sharing.cgi` | High
72 | File | `/cgi-bin/p1_ftpserver.php` | High
73 | File | `/cgi-bin/system_mgr.cgi` | High
74 | File | `/cgi-bin/tosei_kikai.php` | High
75 | File | `/cgi-bin/wlogin.cgi` | High
76 | File | `/classes/Master.php?f=delete_category` | High
77 | File | `/classes/Master.php?f=delete_record` | High
78 | File | `/classes/Master.php?f=log_visitor` | High
79 | File | `/classes/Master.php?f=save_medicine` | High
80 | ... | ... | ...

There are 709 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
