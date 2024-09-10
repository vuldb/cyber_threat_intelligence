# WannaCry - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WannaCry](https://vuldb.com/?actor.wannacry). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wannacry](https://vuldb.com/?actor.wannacry)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WannaCry:

* [US](https://vuldb.com/?country.us)
* [HU](https://vuldb.com/?country.hu)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WannaCry.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.3.69.209](https://vuldb.com/?ip.2.3.69.209) | lfbn-cle-1-223-209.w2-3.abo.wanadoo.fr | - | High
2 | [5.35.251.247](https://vuldb.com/?ip.5.35.251.247) | rs209896.rs.hosteurope.de | - | High
3 | [23.254.167.231](https://vuldb.com/?ip.23.254.167.231) | hwsrv-985873.hostwindsdns.com | - | High
4 | [38.229.72.16](https://vuldb.com/?ip.38.229.72.16) | - | - | High
5 | [46.101.166.19](https://vuldb.com/?ip.46.101.166.19) | - | - | High
6 | [50.7.161.218](https://vuldb.com/?ip.50.7.161.218) | - | - | High
7 | [62.210.124.124](https://vuldb.com/?ip.62.210.124.124) | leavenged.best | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WannaCry_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WannaCry. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/action/import_https_cert_file/` | High
3 | File | `/ad-list` | Medium
4 | File | `/addnews.html` | High
5 | File | `/admin/?page=inmates/view_inmate` | High
6 | File | `/admin/?page=system_info` | High
7 | File | `/admin/?page=system_info/contact_info` | High
8 | File | `/admin/action/add_con.php` | High
9 | File | `/admin/addemployee.php` | High
10 | File | `/admin/add_exercises.php` | High
11 | File | `/admin/attendance_row.php` | High
12 | File | `/admin/categories/manage_category.php` | High
13 | File | `/admin/categories/view_category.php` | High
14 | File | `/admin/courses/manage_course.php` | High
15 | File | `/admin/del.php` | High
16 | File | `/admin/departments/manage_department.php` | High
17 | File | `/admin/edit-services.php` | High
18 | File | `/admin/edit.php` | High
19 | File | `/admin/edit_subject.php` | High
20 | File | `/admin/emp-profile-avatar.php` | High
21 | File | `/admin/employee_row.php` | High
22 | File | `/admin/folderrollpicture/list` | High
23 | File | `/admin/index.php` | High
24 | File | `/admin/lab.php` | High
25 | File | `/Admin/login.php` | High
26 | File | `/admin/maintenance/brand.php` | High
27 | File | `/admin/maintenance/view_designation.php` | High
28 | File | `/admin/mechanics/manage_mechanic.php` | High
29 | File | `/admin/member_save.php` | High
30 | File | `/admin/new-content` | High
31 | File | `/admin/normal-bwdates-reports-details.php` | High
32 | File | `/admin/reportupload.aspx` | High
33 | File | `/admin/service.php` | High
34 | File | `/admin/sign/out` | High
35 | File | `/admin/students/manage_academic.php` | High
36 | File | `/admin/transactions/track_shipment.php` | High
37 | File | `/admin/usermanagement.php` | High
38 | File | `/admin/video/list` | High
39 | File | `/api/controllers/merchant/shop/PosterController.php` | High
40 | File | `/api/log/killJob` | High
41 | File | `/api/plugin/uninstall` | High
42 | File | `/api/user` | Medium
43 | File | `/app/controller/Setup.php` | High
44 | File | `/aqpg/users/login.php` | High
45 | File | `/bcms/admin/?page=user/list` | High
46 | File | `/bin/httpd` | Medium
47 | File | `/blog` | Low
48 | File | `/blog/edit` | Medium
49 | File | `/cardo/api` | Medium
50 | File | `/cgi-bin/cstecgi.cgi` | High
51 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
52 | File | `/cgi-bin/hd_config.cgi` | High
53 | File | `/cgi-bin/touchlist_sync.cgi` | High
54 | File | `/cgi-bin/webfile_mgr.cgi` | High
55 | File | `/change-language/de_DE` | High
56 | File | `/change_password.php` | High
57 | File | `/ci_spms/admin/category` | High
58 | File | `/classes/Master.php` | High
59 | File | `/classes/Master.php?f=delete_account` | High
60 | File | `/classes/Master.php?f=save_item` | High
61 | File | `/classes/Master.php?f=save_package` | High
62 | File | `/classes/SystemSettings.php?f=update_settings` | High
63 | File | `/classes/Users.php?f=save` | High
64 | File | `/collection/all` | High
65 | File | `/company/down_resume/total/nature` | High
66 | File | `/controllers/add_client.php` | High
67 | File | `/cwms/admin/?page=articles/view_article/` | High
68 | File | `/cwms/classes/Master.php?f=save_contact` | High
69 | File | `/dashboard/add-blog.php` | High
70 | File | `/dashboard/add-portfolio.php` | High
71 | File | `/dashboard/settings` | High
72 | File | `/debuginfo.htm` | High
73 | File | `/download.php?file=author.png` | High
74 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
75 | File | `/ecommerce/admin/products/controller.php` | High
76 | File | `/edit-subject.php` | High
77 | File | `/etc/passwd` | Medium
78 | File | `/foms/routers/cancel-order.php` | High
79 | File | `/forum/away.php` | High
80 | File | `/friends` | Medium
81 | ... | ... | ...

There are 710 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/212/wannacry-ransomware-iocs/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
