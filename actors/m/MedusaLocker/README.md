# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
2 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
3 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
4 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
5 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/abcd/opac/php/otros_sitios.php` | High
3 | File | `/Actions.php?a=login` | High
4 | File | `/addcategory.php` | High
5 | File | `/addclient1.php` | High
6 | File | `/admin-cp/theme/editor/default` | High
7 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
8 | File | `/admin/?page=musics/manage_music` | High
9 | File | `/admin/about_edit.php?action=modify` | High
10 | File | `/admin/admin-add-employee.php` | High
11 | File | `/admin/ajax.php?action=login` | High
12 | File | `/admin/ajax.php?action=save_settings` | High
13 | File | `/admin/assets/` | High
14 | File | `/admin/categories/manage_category.php` | High
15 | File | `/admin/category_save.php` | High
16 | File | `/admin/class.php?dowhat=modifyclass` | High
17 | File | `/admin/dialog/select_images_post.php` | High
18 | File | `/admin/edit_area.php` | High
19 | File | `/admin/educloud/videobind.html` | High
20 | File | `/admin/emp-profile-avatar.php` | High
21 | File | `/admin/get_price.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/inquiries/view_inquiry.php` | High
24 | File | `/admin/login.php` | High
25 | File | `/admin/manage_complaint.php` | High
26 | File | `/admin/manage_model.php` | High
27 | File | `/admin/manage_user.php` | High
28 | File | `/admin/member_save.php` | High
29 | File | `/admin/menu.php` | High
30 | File | `/admin/mod_reports/index.php` | High
31 | File | `/admin/mod_reports/printreport.php` | High
32 | File | `/admin/mod_reservation/controller.php` | High
33 | File | `/admin/mod_reservation/index.php` | High
34 | File | `/admin/mod_room/index.php` | High
35 | File | `/admin/mod_users/index.php` | High
36 | File | `/admin/orders/controller.php` | High
37 | File | `/admin/orders/index.php` | High
38 | File | `/admin/products/index.php` | High
39 | File | `/Admin/registration.php` | High
40 | File | `/admin/robot.php` | High
41 | File | `/admin/system.html` | High
42 | File | `/admin/system.php` | High
43 | File | `/admin/template/edit` | High
44 | File | `/admin/template/update` | High
45 | File | `/admin/user/user-move-run.php` | High
46 | File | `/admin/view_reserved.php` | High
47 | File | `/ajax.php` | Medium
48 | File | `/ajax.php?action=delete_block` | High
49 | File | `/ajax.php?action=delete_deductions` | High
50 | File | `/ajax.php?action=load_answered` | High
51 | File | `/ajax.php?action=login` | High
52 | File | `/ajax.php?action=save_establishment` | High
53 | File | `/ajax.php?action=save_user` | High
54 | File | `/ajax/checkin.php` | High
55 | File | `/ajax/chpwd.php` | High
56 | File | `/ajax/getBasicInfo.php` | High
57 | File | `/api/deploy/upload` | High
58 | File | `/api/deploy/upload /api/database/upload` | High
59 | File | `/api/file/downloadfile` | High
60 | File | `/api/file/downloadUrl` | High
61 | File | `/api/file/multiDownload` | High
62 | File | `/api/files/recipepictures/` | High
63 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
64 | File | `/api/system/user?deptId=1&page=1&size=10` | High
65 | File | `/App/Core/Extend/Function/ydLib.php` | High
66 | File | `/apply/index.php` | High
67 | File | `/AttendanceMonitoring/department/index.php` | High
68 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
69 | File | `/authMonitCallcenter` | High
70 | File | `/bolt/editcontent/showcases` | High
71 | File | `/buscar_integrada.php` | High
72 | File | `/candidate/controller.php` | High
73 | File | `/cap.js` | Low
74 | File | `/cgi-bin/apkg_mgr.cgi` | High
75 | File | `/cgi-bin/cstecgi.cgi` | High
76 | ... | ... | ...

There are 666 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.bleepingcomputer.com/news/security/medusalocker-ransomware-wants-its-share-of-your-money/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
