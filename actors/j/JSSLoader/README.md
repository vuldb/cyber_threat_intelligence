# JSSLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [JSSLoader](https://vuldb.com/?actor.jssloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.jssloader](https://vuldb.com/?actor.jssloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JSSLoader:

* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JSSLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.61.184.75](https://vuldb.com/?ip.45.61.184.75) | - | - | High
2 | [45.61.185.72](https://vuldb.com/?ip.45.61.185.72) | - | - | High
3 | [45.61.188.10](https://vuldb.com/?ip.45.61.188.10) | - | - | High
4 | [104.244.76.67](https://vuldb.com/?ip.104.244.76.67) | - | - | High
5 | [104.244.77.97](https://vuldb.com/?ip.104.244.77.97) | - | - | High
6 | [107.189.1.145](https://vuldb.com/?ip.107.189.1.145) | woshipikaqiu.top | - | High
7 | [107.189.4.31](https://vuldb.com/?ip.107.189.4.31) | bing.com | - | High
8 | [107.189.12.93](https://vuldb.com/?ip.107.189.12.93) | max-need.cloud | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _JSSLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by JSSLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=tickets` | High
3 | File | `/activation.php` | High
4 | File | `/add_new_supplier.php` | High
5 | File | `/admin` | Low
6 | File | `/admin-manage-user.php` | High
7 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
8 | File | `/admin/action/delete-vaccine.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/admin_members.php?ac=search` | High
11 | File | `/admin/ajax.php?action=delete_user` | High
12 | File | `/admin/ajax.php?action=login` | High
13 | File | `/admin/article.php` | High
14 | File | `/admin/assets/` | High
15 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
16 | File | `/admin/blood/update/B+.php` | High
17 | File | `/admin/booking-bwdates-reports-details.php` | High
18 | File | `/admin/contact-us.php` | High
19 | File | `/admin/doctor-specilization.php` | High
20 | File | `/admin/edit-subcategory.php` | High
21 | File | `/Admin/EditCategory` | High
22 | File | `/admin/emp-profile-avatar.php` | High
23 | File | `/admin/home.php?con=add` | High
24 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
25 | File | `/admin/index.php` | High
26 | File | `/admin/inquiries/view_inquiry.php` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/maintenance/manage_brand.php` | High
29 | File | `/admin/normal-bwdates-reports-details.php` | High
30 | File | `/admin/password-recovery.php` | High
31 | File | `/admin/profile.php` | High
32 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
33 | File | `/admin/search-booking-request.php` | High
34 | File | `/admin/service` | High
35 | File | `/admin/twitter.php` | High
36 | File | `/admin/update_room.php` | High
37 | File | `/Admin/user-record.php` | High
38 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
39 | File | `/admin_class.php` | High
40 | File | `/ajax.php?action=signup` | High
41 | File | `/api/admin/user?id` | High
42 | File | `/api/file/downloadfile` | High
43 | File | `/api/runscript` | High
44 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
45 | File | `/apps/api/views/deploy_api.py` | High
46 | File | `/apps/system/api/user.go` | High
47 | File | `/apps/system/router/upload.go` | High
48 | File | `/apps/system/services/role_menu.go` | High
49 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
50 | File | `/billing/bill/edit/` | High
51 | File | `/bookingconfirm.php` | High
52 | File | `/cap.js` | Low
53 | File | `/cfgFile/fileContent` | High
54 | File | `/cgi-bin/cstecgi.cgi` | High
55 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
56 | File | `/cgi-bin/info.cgi` | High
57 | File | `/cgi-bin/myMusic.cgi` | High
58 | File | `/cgi-bin/nas_sharing.cgi` | High
59 | File | `/cgi-bin/system_mgr.cgi` | High
60 | File | `/cgi-bin/tosei_kikai.php` | High
61 | File | `/cgi-bin/webviewer_login_page` | High
62 | File | `/classes/Master.php` | High
63 | File | `/classes/Master.php?f=load_registration` | High
64 | ... | ... | ...

There are 563 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
