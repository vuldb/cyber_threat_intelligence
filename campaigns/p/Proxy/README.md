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
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/?page=tracks` | High
4 | File | `/abcd/opac/php/otros_sitios.php` | High
5 | File | `/Actions.php?a=login` | High
6 | File | `/addcategory.php` | High
7 | File | `/addclient1.php` | High
8 | File | `/addcompany.php` | High
9 | File | `/admin` | Low
10 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
11 | File | `/admin/` | Low
12 | File | `/admin/about_edit.php?action=modify` | High
13 | File | `/Admin/add-admin.php` | High
14 | File | `/admin/admin-add-employee.php` | High
15 | File | `/admin/admin-update-employee.php` | High
16 | File | `/admin/assets/` | High
17 | File | `/admin/blood/update/B+.php` | High
18 | File | `/admin/blood/update/o-.php` | High
19 | File | `/admin/categories/manage_category.php` | High
20 | File | `/admin/class.php?dowhat=modifyclass` | High
21 | File | `/admin/dialog/select_images_post.php` | High
22 | File | `/admin/edit_area.php` | High
23 | File | `/admin/edit_manufacturer.php` | High
24 | File | `/admin/educloud/videobind.html` | High
25 | File | `/admin/emp-profile-avatar.php` | High
26 | File | `/admin/inquiries/view_details.php` | High
27 | File | `/admin/inquiries/view_inquiry.php` | High
28 | File | `/admin/login.php` | High
29 | File | `/admin/maintenance/manage_department.php` | High
30 | File | `/Admin/registration.php` | High
31 | File | `/admin/robot.php` | High
32 | File | `/admin/system.html` | High
33 | File | `/admin/system.php` | High
34 | File | `/admin/template/edit` | High
35 | File | `/admin/template/update` | High
36 | File | `/admin/user/user-move-run.php` | High
37 | File | `/ajax.php?action=delete_deductions` | High
38 | File | `/ajax.php?action=save_category` | High
39 | File | `/ajax.php?action=signup` | High
40 | File | `/ajax.php?action=update_account` | High
41 | File | `/ajax/checkin.php` | High
42 | File | `/ajax/chpwd.php` | High
43 | File | `/ajax/getBasicInfo.php` | High
44 | File | `/api/blade-system/menu/list?updatexml` | High
45 | File | `/api/file/downloadfile` | High
46 | File | `/api/file/downloadUrl` | High
47 | File | `/api/file/multiDownload` | High
48 | File | `/api/files/recipepictures/` | High
49 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
50 | File | `/api/system/user?deptId=1&page=1&size=10` | High
51 | File | `/app/action/add_staff.php` | High
52 | File | `/app/admin/controller/file/File.php` | High
53 | File | `/apply/index.php` | High
54 | File | `/AttendanceMonitoring/report/attendance_print.php` | High
55 | File | `/buscar_integrada.php` | High
56 | File | `/candidate/controller.php` | High
57 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
58 | File | `/cgi-bin/apkg_mgr.cgi` | High
59 | File | `/cgi-bin/cstecgi.cgi` | High
60 | File | `/cgi-bin/hd_config.cgi` | High
61 | File | `/cgi-bin/p1_ftpserver.php` | High
62 | File | `/cgi-bin/photocenter_mgr.cgi` | High
63 | File | `/cgi-bin/s3.cgi` | High
64 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
65 | File | `/cgi-bin/tosei_kikai.php` | High
66 | File | `/cgi-bin/webdav_mgr.cgi` | High
67 | File | `/cgi-bin/webfile_mgr.cgi` | High
68 | File | `/cgi-bin/widget_api.cgi` | High
69 | File | `/classes/Master.php?f=delete_category` | High
70 | File | `/classes/Master.php?f=delete_record` | High
71 | File | `/classes/Master.php?f=save_package` | High
72 | ... | ... | ...

There are 631 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
