# Pony - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pony](https://vuldb.com/?actor.pony). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pony](https://vuldb.com/?actor.pony)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pony:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pony.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.15.199](https://vuldb.com/?ip.5.39.15.199) | - | - | High
2 | [5.135.8.71](https://vuldb.com/?ip.5.135.8.71) | - | - | High
3 | [45.58.116.102](https://vuldb.com/?ip.45.58.116.102) | - | - | High
4 | [46.161.1.172](https://vuldb.com/?ip.46.161.1.172) | free.gbnhost.com | - | High
5 | [50.56.223.113](https://vuldb.com/?ip.50.56.223.113) | 50-56-223-113.static.cloud-ips.com | - | High
6 | [50.116.13.230](https://vuldb.com/?ip.50.116.13.230) | 50-116-13-230.ip.linodeusercontent.com | - | High
7 | [62.112.130.165](https://vuldb.com/?ip.62.112.130.165) | - | - | High
8 | [64.85.169.189](https://vuldb.com/?ip.64.85.169.189) | - | - | High
9 | [64.85.169.190](https://vuldb.com/?ip.64.85.169.190) | - | - | High
10 | [66.175.212.25](https://vuldb.com/?ip.66.175.212.25) | 66-175-212-25.ip.linodeusercontent.com | - | High
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pony_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pony. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/` | Low
2 | File | `/admin/?page=categories/view_category` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/bookings/view_details.php` | High
5 | File | `/Admin/changepassword.php` | High
6 | File | `/admin/court` | Medium
7 | File | `/Admin/createClass.php` | High
8 | File | `/admin/curriculum/view_curriculum.php` | High
9 | File | `/admin/del_service.php` | High
10 | File | `/admin/div_data/data` | High
11 | File | `/admin/edit_category.php` | High
12 | File | `/admin/maintenance/manage_brand.php` | High
13 | File | `/admin/maintenance/view_designation.php` | High
14 | File | `/admin/media_folders` | High
15 | File | `/admin/memberOnline_deal.php?mudi=del&dataType=&dataID=6` | High
16 | File | `/admin/orders/update_status.php` | High
17 | File | `/admin/orders/view_order.php` | High
18 | File | `/admin/problem_judge.php` | High
19 | File | `/admin/product/manage_product.php` | High
20 | File | `/admin/reg.php` | High
21 | File | `/admin/robot.php` | High
22 | File | `/admin/save.php` | High
23 | File | `/admin/settings/` | High
24 | File | `/admin/users.php` | High
25 | File | `/adminapi/system/file/openfile` | High
26 | File | `/ajax.php` | Medium
27 | File | `/api/controllers/common/UploadsController.php` | High
28 | File | `/app/api/controller/default/File.php` | High
29 | File | `/app/api/controller/default/Sqlite.php` | High
30 | File | `/app/Http/Controllers/ImageController.php` | High
31 | File | `/apps/login_auth.php` | High
32 | File | `/AttendanceMonitoring/report/index.php` | High
33 | File | `/auth/user/all.api` | High
34 | File | `/authMonitCallcenter` | High
35 | File | `/b2b-supermarket/shopping-cart` | High
36 | File | `/backend/register.php` | High
37 | File | `/blog-single.php` | High
38 | File | `/blog/blog.php` | High
39 | File | `/boaform/wlan_basic_set.cgi` | High
40 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
41 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
42 | File | `/cgi-bin/cstecgi.cgi` | High
43 | File | `/cgi-bin/hd_config.cgi` | High
44 | File | `/cgi-bin/nas_sharing.cgi` | High
45 | File | `/cgi-bin/wlogin.cgi` | High
46 | File | `/classes/Master.php` | High
47 | File | `/classes/Master.php?f=delete_inquiry` | High
48 | File | `/classes/Master.php?f=log_employee` | High
49 | File | `/classes/Master.php?f=save_medicine` | High
50 | File | `/classes/Master.php?f=save_package` | High
51 | File | `/classes/SystemSettings.php?f=update_settings` | High
52 | File | `/classes/Users.php?f=save` | High
53 | File | `/College/admin/teacher.php` | High
54 | File | `/conf/app.conf` | High
55 | File | `/course/filterRecords/` | High
56 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
57 | File | `/E-mobile/App/System/File/downfile.php` | High
58 | File | `/Electron/download` | High
59 | File | `/endpoint/add-faq.php` | High
60 | File | `/endpoint/add-guest.php` | High
61 | File | `/endpoint/add-task.php` | High
62 | File | `/endpoint/delete-calorie.php` | High
63 | File | `/file-manager/rename.php` | High
64 | File | `/file-manager/upload.php` | High
65 | File | `/file/upload/1` | High
66 | File | `/forum/away.php` | High
67 | File | `/geoserver/gwc/rest.html` | High
68 | File | `/goform/RgTime` | High
69 | File | `/goform/SetIpMacBind` | High
70 | ... | ... | ...

There are 611 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/forums/diary/Malicious+spam+Subject+RE+Bill/20417/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
