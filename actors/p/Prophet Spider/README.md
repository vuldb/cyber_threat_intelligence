# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [IO](https://vuldb.com/?country.io)
* [SC](https://vuldb.com/?country.sc)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

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
11 | File | `/admin/assets/` | High
12 | File | `/admin/categories/manage_category.php` | High
13 | File | `/admin/class.php?dowhat=modifyclass` | High
14 | File | `/admin/dialog/select_images_post.php` | High
15 | File | `/admin/edit_area.php` | High
16 | File | `/admin/educloud/videobind.html` | High
17 | File | `/admin/emp-profile-avatar.php` | High
18 | File | `/admin/index.php` | High
19 | File | `/admin/inquiries/view_inquiry.php` | High
20 | File | `/admin/login.php` | High
21 | File | `/admin/mod_reports/index.php` | High
22 | File | `/admin/mod_reports/printreport.php` | High
23 | File | `/admin/mod_reservation/controller.php` | High
24 | File | `/admin/mod_reservation/index.php` | High
25 | File | `/admin/mod_room/index.php` | High
26 | File | `/admin/mod_users/index.php` | High
27 | File | `/admin/orders/controller.php` | High
28 | File | `/admin/orders/index.php` | High
29 | File | `/admin/products/index.php` | High
30 | File | `/Admin/registration.php` | High
31 | File | `/admin/system.html` | High
32 | File | `/admin/system.php` | High
33 | File | `/admin/template/edit` | High
34 | File | `/admin/user/user-move-run.php` | High
35 | File | `/ajax.php` | Medium
36 | File | `/ajax.php?action=delete_deductions` | High
37 | File | `/ajax.php?action=load_answered` | High
38 | File | `/ajax.php?action=login` | High
39 | File | `/ajax.php?action=save_establishment` | High
40 | File | `/ajax.php?action=save_user` | High
41 | File | `/ajax/checkin.php` | High
42 | File | `/ajax/chpwd.php` | High
43 | File | `/ajax/getBasicInfo.php` | High
44 | File | `/api/deploy/upload` | High
45 | File | `/api/deploy/upload /api/database/upload` | High
46 | File | `/api/file/downloadfile` | High
47 | File | `/api/file/downloadUrl` | High
48 | File | `/api/file/multiDownload` | High
49 | File | `/api/files/recipepictures/` | High
50 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
51 | File | `/api/system/user?deptId=1&page=1&size=10` | High
52 | File | `/App/Core/Extend/Function/ydLib.php` | High
53 | File | `/apply/index.php` | High
54 | File | `/AttendanceMonitoring/department/index.php` | High
55 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
56 | File | `/authMonitCallcenter` | High
57 | File | `/bolt/editcontent/showcases` | High
58 | File | `/buscar_integrada.php` | High
59 | File | `/candidate/controller.php` | High
60 | File | `/cap.js` | Low
61 | File | `/cgi-bin/apkg_mgr.cgi` | High
62 | File | `/cgi-bin/cstecgi.cgi` | High
63 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
64 | File | `/cgi-bin/discovery.cgi` | High
65 | ... | ... | ...

There are 573 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
