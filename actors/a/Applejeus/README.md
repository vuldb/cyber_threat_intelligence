# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?g=net_pro_keyword_import_save` | High
3 | File | `/?page=tracks` | High
4 | File | `/actuator/heapdump` | High
5 | File | `/admin` | Low
6 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
7 | File | `/admin/?page=categories/view_category` | High
8 | File | `/Admin/add-admin.php` | High
9 | File | `/admin/admin-add-employee.php` | High
10 | File | `/admin/admin_cl.php?mudi=revPwd` | High
11 | File | `/admin/admin_invt2.php` | High
12 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
13 | File | `/admin/ajax.php?action=login` | High
14 | File | `/admin/ajax.php?action=save_settings` | High
15 | File | `/admin/case-type` | High
16 | File | `/admin/config_MT.php?action=delete` | High
17 | File | `/Admin/edit-photo.php` | High
18 | File | `/admin/edit-post.php` | High
19 | File | `/admin/edit_area.php` | High
20 | File | `/Admin/edit_profile.php` | High
21 | File | `/admin/file_manager/export` | High
22 | File | `/admin/file_manager/files` | High
23 | File | `/admin/forgot-password.php` | High
24 | File | `/admin/general-setting` | High
25 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
26 | File | `/admin/index.php` | High
27 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
28 | File | `/admin/index2.html` | High
29 | File | `/admin/login.php` | High
30 | File | `/admin/maintenance/manage_brand.php` | High
31 | File | `/admin/media_folders` | High
32 | File | `/admin/pages/` | High
33 | File | `/admin/robot.php` | High
34 | File | `/admin/system.html` | High
35 | File | `/admin/template/edit` | High
36 | File | `/admin/template/update` | High
37 | File | `/admin/user/user-move-run.php` | High
38 | File | `/adminPage/conf/reload` | High
39 | File | `/adminPage/www/addOver` | High
40 | File | `/adminpanel/admin/query/addCourseExe.php` | High
41 | File | `/admin_class.php` | High
42 | File | `/ajax/chpwd.php` | High
43 | File | `/ajax/getBasicInfo.php` | High
44 | File | `/api/file/downloadfile` | High
45 | File | `/api/runscript` | High
46 | File | `/api/snapshots/` | High
47 | File | `/api/v1/snapshots` | High
48 | File | `/api/v2/maps` | Medium
49 | File | `/apply/index.php` | High
50 | File | `/authMonitCallcenter` | High
51 | File | `/branch_viewmore.php` | High
52 | File | `/buscar_integrada.php` | High
53 | File | `/candidate/index.php` | High
54 | File | `/cgi-bin/cstecgi.cgi` | High
55 | File | `/cgi-bin/discovery.cgi` | High
56 | File | `/cgi-bin/p1_ftpserver.php` | High
57 | File | `/cgi-bin/system_mgr.cgi` | High
58 | File | `/cgi-bin/tosei_kikai.php` | High
59 | File | `/cgi-bin/widget_api.cgi` | High
60 | File | `/cgi-bin/wlogin.cgi` | High
61 | File | `/classes/Master.php?f=delete_category` | High
62 | File | `/classes/Master.php?f=delete_record` | High
63 | File | `/classes/Master.php?f=log_visitor` | High
64 | File | `/classes/Master.php?f=save_medicine` | High
65 | File | `/classes/Master.php?f=save_package` | High
66 | File | `/classes/SystemSettings.php?f=update_settings` | High
67 | File | `/classes/Users.php?f=delete` | High
68 | File | `/classes/Users.php?f=save` | High
69 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
70 | File | `/cm/update_rows/page?id=2` | High
71 | File | `/cms/classes/Users.php?f=delete_client` | High
72 | File | `/controllers/add_client.php` | High
73 | File | `/controllers/add_user.php` | High
74 | File | `/DataSrvs/UCCGSrv.asmx` | High
75 | File | `/department_viewmore.php` | High
76 | File | `/designation_viewmore.php` | High
77 | File | `/detalheIdUra` | High
78 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
79 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
80 | File | `/doctor/view-appointment-detail.php` | High
81 | ... | ... | ...

There are 713 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
