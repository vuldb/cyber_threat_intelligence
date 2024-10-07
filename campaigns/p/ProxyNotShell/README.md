# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [DE](https://vuldb.com/?country.de)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/abcd/opac/php/otros_sitios.php` | High
3 | File | `/Actions.php?a=login` | High
4 | File | `/addcategory.php` | High
5 | File | `/addclient1.php` | High
6 | File | `/admin` | Low
7 | File | `/admin-cp/theme/editor/default` | High
8 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
9 | File | `/admin/about_edit.php?action=modify` | High
10 | File | `/Admin/add-admin.php` | High
11 | File | `/admin/admin-add-employee.php` | High
12 | File | `/admin/assets/` | High
13 | File | `/admin/blood/update/o-.php` | High
14 | File | `/admin/categories/manage_category.php` | High
15 | File | `/admin/class.php?dowhat=modifyclass` | High
16 | File | `/admin/dialog/select_images_post.php` | High
17 | File | `/admin/edit_area.php` | High
18 | File | `/admin/educloud/videobind.html` | High
19 | File | `/admin/emp-profile-avatar.php` | High
20 | File | `/admin/inquiries/view_inquiry.php` | High
21 | File | `/admin/login.php` | High
22 | File | `/admin/mod_reports/index.php` | High
23 | File | `/admin/mod_reports/printreport.php` | High
24 | File | `/admin/mod_reservation/controller.php` | High
25 | File | `/admin/mod_reservation/index.php` | High
26 | File | `/admin/mod_room/index.php` | High
27 | File | `/admin/mod_users/index.php` | High
28 | File | `/admin/orders/controller.php` | High
29 | File | `/admin/orders/index.php` | High
30 | File | `/admin/products/index.php` | High
31 | File | `/Admin/registration.php` | High
32 | File | `/admin/robot.php` | High
33 | File | `/admin/system.html` | High
34 | File | `/admin/system.php` | High
35 | File | `/admin/template/edit` | High
36 | File | `/admin/template/update` | High
37 | File | `/admin/user/user-move-run.php` | High
38 | File | `/ajax.php` | Medium
39 | File | `/ajax.php?action=delete_deductions` | High
40 | File | `/ajax.php?action=load_answered` | High
41 | File | `/ajax.php?action=login` | High
42 | File | `/ajax.php?action=save_category` | High
43 | File | `/ajax.php?action=save_establishment` | High
44 | File | `/ajax.php?action=save_user` | High
45 | File | `/ajax.php?action=signup` | High
46 | File | `/ajax.php?action=update_account` | High
47 | File | `/ajax/checkin.php` | High
48 | File | `/ajax/chpwd.php` | High
49 | File | `/ajax/getBasicInfo.php` | High
50 | File | `/api/blade-system/menu/list?updatexml` | High
51 | File | `/api/deploy/upload` | High
52 | File | `/api/deploy/upload /api/database/upload` | High
53 | File | `/api/file/downloadfile` | High
54 | File | `/api/file/downloadUrl` | High
55 | File | `/api/file/multiDownload` | High
56 | File | `/api/files/recipepictures/` | High
57 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
58 | File | `/api/system/user?deptId=1&page=1&size=10` | High
59 | File | `/App/Core/Extend/Function/ydLib.php` | High
60 | File | `/apply/index.php` | High
61 | File | `/AttendanceMonitoring/department/index.php` | High
62 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
63 | File | `/authMonitCallcenter` | High
64 | File | `/bolt/editcontent/showcases` | High
65 | File | `/buscar_integrada.php` | High
66 | File | `/candidate/controller.php` | High
67 | File | `/cap.js` | Low
68 | File | `/cgi-bin/apkg_mgr.cgi` | High
69 | File | `/cgi-bin/cstecgi.cgi` | High
70 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
71 | File | `/cgi-bin/hd_config.cgi` | High
72 | File | `/cgi-bin/p1_ftpserver.php` | High
73 | File | `/cgi-bin/photocenter_mgr.cgi` | High
74 | File | `/cgi-bin/s3.cgi` | High
75 | ... | ... | ...

There are 661 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
