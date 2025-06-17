# Sandman - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sandman](https://vuldb.com/?actor.sandman). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sandman](https://vuldb.com/?actor.sandman)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sandman:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sandman.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.67.176](https://vuldb.com/?ip.5.2.67.176) | - | - | High
2 | [5.2.72.130](https://vuldb.com/?ip.5.2.72.130) | - | - | High
3 | [5.255.88.188](https://vuldb.com/?ip.5.255.88.188) | - | - | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sandman_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28, CWE-38, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandman. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tickets` | High
2 | File | `/abs.php` | Medium
3 | File | `/action/upload_file` | High
4 | File | `/add-students.php` | High
5 | File | `/addcategory.php` | High
6 | File | `/addcustcom.php` | High
7 | File | `/addcustind.php` | High
8 | File | `/addstock.php` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=product/manage_product&id=2` | High
11 | File | `/admin/?page=reports` | High
12 | File | `/admin/action/new-feed.php` | High
13 | File | `/admin/action/update-deworm.php` | High
14 | File | `/admin/add_postlogin.php` | High
15 | File | `/admin/admin_cl.php?mudi=revPwd` | High
16 | File | `/admin/application-bwdates-reports-details.php` | High
17 | File | `/admin/chatroom.php` | High
18 | File | `/admin/contact-us.php` | High
19 | File | `/admin/foreigner-search.php` | High
20 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
21 | File | `/admin/index.php` | High
22 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
23 | File | `/admin/invoice.php` | High
24 | File | `/admin/list_ipAddressPolicy.php` | High
25 | File | `/admin/login.php` | High
26 | File | `/admin/mod_room/controller.php?action=add` | High
27 | File | `/Admin/registration.php` | High
28 | File | `/admin/search-vehicle.php` | High
29 | File | `/admin/system.html` | High
30 | File | `/admin/template` | High
31 | File | `/admin/template/update` | High
32 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
33 | File | `/admin_ping.htm` | High
34 | File | `/admin_route/dec_service_credits.php` | High
35 | File | `/ajax.php` | Medium
36 | File | `/ajax.php?action=delete_deductions` | High
37 | File | `/ajax.php?action=login` | High
38 | File | `/ajax.php?action=signup` | High
39 | File | `/ajax/check_medicine_name.php` | High
40 | File | `/ajax/getBasicInfo.php` | High
41 | File | `/animalsupdate.php` | High
42 | File | `/api/authentication/login` | High
43 | File | `/api/controllers/admin/app/ComboController.php` | High
44 | File | `/api/file/multiDownload` | High
45 | File | `/api/files/recipepictures/` | High
46 | File | `/api/role` | Medium
47 | File | `/api/v2/open/tablesInfo` | High
48 | File | `/app/options.py` | High
49 | File | `/application/index/controller/Databasesource.php` | High
50 | File | `/application/index/controller/Screen.php` | High
51 | File | `/application/pay/controller/Api.php` | High
52 | File | `/apps/login_auth.php` | High
53 | File | `/apps/reg_go.php` | High
54 | File | `/assets/php/upload.php` | High
55 | File | `/auth_files/photo/` | High
56 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
57 | File | `/boafrm/formMapDelDevice` | High
58 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
59 | File | `/catalog/all-products` | High
60 | File | `/cgi-bin/adm.cgi` | High
61 | File | `/cgi-bin/cstecgi.cgi` | High
62 | File | `/cgi-bin/myMusic.cgi` | High
63 | File | `/cgi-bin/nas_sharing.cgi` | High
64 | File | `/cgi-bin/p1_ftpserver.php` | High
65 | File | `/cgi-bin/photocenter_mgr.cgi` | High
66 | File | `/cgi-bin/vitogate.cgi` | High
67 | File | `/check_image_and_trigger_recovery API` | High
68 | File | `/classes/Master.php?f=delete_category` | High
69 | File | `/classes/SystemSettings.php?f=update_settings` | High
70 | File | `/classes/Users.php?f=save` | High
71 | File | `/contact.php` | Medium
72 | File | `/controllers/add_client.php` | High
73 | File | `/crm/weixinmp/index.php?userid=123&module=Users&usid=1&action=UsersAjax&minipro_const_type=1` | High
74 | File | `/data/add_employee.php` | High
75 | File | `/debuginfo.htm` | High
76 | File | `/deletebird.php` | High
77 | File | `/deletefile.php` | High
78 | ... | ... | ...

There are 685 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.sentinelone.com/labs/sandman-apt-china-based-adversaries-embrace-lua/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
