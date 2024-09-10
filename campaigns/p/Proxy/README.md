# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Proxy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Proxy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
6 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=tracks` | High
3 | File | `/abcd/opac/php/otros_sitios.php` | High
4 | File | `/Actions.php?a=login` | High
5 | File | `/add-students.php` | High
6 | File | `/addcategory.php` | High
7 | File | `/addclient1.php` | High
8 | File | `/admin-cp/theme/editor/default` | High
9 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
10 | File | `/admin.php?p=/Area/index#tab=t2` | High
11 | File | `/admin/` | Low
12 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
13 | File | `/admin/about_edit.php?action=modify` | High
14 | File | `/admin/admin-add-employee.php` | High
15 | File | `/admin/admin-update-employee.php` | High
16 | File | `/admin/ajax.php?action=login` | High
17 | File | `/admin/ajax.php?action=save_settings` | High
18 | File | `/admin/assets/` | High
19 | File | `/admin/categories/manage_category.php` | High
20 | File | `/admin/category_save.php` | High
21 | File | `/admin/class.php?dowhat=modifyclass` | High
22 | File | `/admin/clients/` | High
23 | File | `/admin/config_ISCGroupNoCache.php` | High
24 | File | `/admin/config_time_sync.php` | High
25 | File | `/admin/dialog/select_images_post.php` | High
26 | File | `/admin/edit_area.php` | High
27 | File | `/admin/educloud/videobind.html` | High
28 | File | `/admin/emp-profile-avatar.php` | High
29 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
30 | File | `/admin/forms/option_lists/edit.php` | High
31 | File | `/admin/get_balance.php` | High
32 | File | `/admin/get_price.php` | High
33 | File | `/admin/inquiries/view_inquiry.php` | High
34 | File | `/admin/login.php` | High
35 | File | `/admin/manage_model.php` | High
36 | File | `/admin/manage_user.php` | High
37 | File | `/admin/media_folders` | High
38 | File | `/admin/member_save.php` | High
39 | File | `/admin/menu.php` | High
40 | File | `/admin/mod_reports/index.php` | High
41 | File | `/admin/mod_reports/printreport.php` | High
42 | File | `/admin/mod_reservation/controller.php` | High
43 | File | `/admin/mod_reservation/index.php` | High
44 | File | `/admin/mod_room/index.php` | High
45 | File | `/admin/mod_users/index.php` | High
46 | File | `/admin/orders/controller.php` | High
47 | File | `/admin/orders/index.php` | High
48 | File | `/admin/pages/` | High
49 | File | `/admin/products/index.php` | High
50 | File | `/Admin/registration.php` | High
51 | File | `/admin/settings/index.php?page=accounts` | High
52 | File | `/admin/system.html` | High
53 | File | `/admin/system.php` | High
54 | File | `/admin/template/edit` | High
55 | File | `/admin/user/user-move-run.php` | High
56 | File | `/admin/view_reserved.php` | High
57 | File | `/ajax.php` | Medium
58 | File | `/ajax.php?action=load_answered` | High
59 | File | `/ajax.php?action=login` | High
60 | File | `/ajax.php?action=save_establishment` | High
61 | File | `/ajax.php?action=save_user` | High
62 | File | `/ajax/checkin.php` | High
63 | File | `/ajax/chpwd.php` | High
64 | File | `/ajax/getBasicInfo.php` | High
65 | File | `/api/blade-system/menu/list?updatexml` | High
66 | File | `/api/Common/uploadFile` | High
67 | File | `/api/deploy/upload` | High
68 | File | `/api/deploy/upload /api/database/upload` | High
69 | File | `/api/file/downloadfile` | High
70 | File | `/api/file/downloadUrl` | High
71 | File | `/api/file/multiDownload` | High
72 | File | `/api/files/recipepictures/` | High
73 | File | `/api/role` | Medium
74 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
75 | File | `/api/system/user?deptId=1&page=1&size=10` | High
76 | File | `/App/Core/Extend/Function/ydLib.php` | High
77 | File | `/apply/index.php` | High
78 | File | `/AttendanceMonitoring/department/index.php` | High
79 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
80 | File | `/authMonitCallcenter` | High
81 | File | `/bolt/editcontent/showcases` | High
82 | File | `/branch_viewmore.php` | High
83 | File | `/buscar_integrada.php` | High
84 | ... | ... | ...

There are 742 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/vishalyadav70/Proxy-Server/blob/main/proxy/blacklist.txt
* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
