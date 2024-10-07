# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PYSA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.129.64.190](https://vuldb.com/?ip.23.129.64.190) | - | - | High
2 | [45.147.231.210](https://vuldb.com/?ip.45.147.231.210) | - | - | High
3 | [185.220.100.240](https://vuldb.com/?ip.185.220.100.240) | tor-exit-13.zbau.f3netze.de | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PYSA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PYSA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/add_members.php` | High
3 | File | `/admin-manage-user.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=musics/manage_music` | High
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/action/add_con.php` | High
8 | File | `/admin/ajax.php?action=save_settings` | High
9 | File | `/admin/ajax.php?action=save_student` | High
10 | File | `/admin/app/profile_crud.php` | High
11 | File | `/admin/applicants/controller.php` | High
12 | File | `/admin/applicants/index.php` | High
13 | File | `/admin/booking-bwdates-reports-details.php` | High
14 | File | `/admin/book_row.php` | High
15 | File | `/admin/categories/manage_category.php` | High
16 | File | `/admin/court-type` | High
17 | File | `/admin/dialog/select_images_post.php` | High
18 | File | `/admin/edit_area.php` | High
19 | File | `/admin/edit_teacher.php` | High
20 | File | `/admin/emp-profile-avatar.php` | High
21 | File | `/admin/employee/controller.php` | High
22 | File | `/admin/foreigner-search.php` | High
23 | File | `/admin/index.php` | High
24 | File | `/admin/index.php?page=categories` | High
25 | File | `/admin/login.php` | High
26 | File | `/admin/maintenance/manage_category.php` | High
27 | File | `/admin/manage_complaint.php` | High
28 | File | `/admin/manage_user.php` | High
29 | File | `/admin/modules/product/controller.php?action=add` | High
30 | File | `/admin/mod_room/controller.php?action=add` | High
31 | File | `/admin/normal-bwdates-reports-details.php` | High
32 | File | `/admin/pass-bwdates-reports-details.php` | High
33 | File | `/admin/return_add.php` | High
34 | File | `/admin/robot.php` | High
35 | File | `/admin/students.php` | High
36 | File | `/admin/system.php` | High
37 | File | `/admin/tasks` | Medium
38 | File | `/admin/tax` | Medium
39 | File | `/admin/template` | High
40 | File | `/Admin/user-record.php` | High
41 | File | `/admin/user/controller.php` | High
42 | File | `/admin/users` | Medium
43 | File | `/admin/vendor` | High
44 | File | `/adminPage/conf/saveCmd` | High
45 | File | `/adminPage/www/addOver` | High
46 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
47 | File | `/ajax.php?action=delete_block` | High
48 | File | `/ajax.php?action=delete_deductions` | High
49 | File | `/ajax.php?action=save_category` | High
50 | File | `/ample/app/action/edit_product.php` | High
51 | File | `/api/client/editemedia.php` | High
52 | File | `/api/controllers/merchant/design/MaterialController.php` | High
53 | File | `/api/cron/settings/setJob/` | High
54 | File | `/api/v1/policies/validation/condition/` | High
55 | File | `/api/v2/maps` | Medium
56 | File | `/app/api/controller/default/File.php` | High
57 | File | `/app/middleware/TokenVerify.php` | High
58 | File | `/application/index/controller/Screen.php` | High
59 | File | `/apply/index.php` | High
60 | File | `/apps/login_auth.php` | High
61 | File | `/apps/system/router/upload.go` | High
62 | File | `/authMonitCallcenter` | High
63 | File | `/backend/register.php` | High
64 | File | `/catalog/all-products` | High
65 | File | `/ccm/system/dialogs/file/delete/1/submit` | High
66 | File | `/cgi-bin/apkg_mgr.cgi` | High
67 | File | `/cgi-bin/cstecgi.cgi` | High
68 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
69 | File | `/cgi-bin/discovery.cgi` | High
70 | File | `/cgi-bin/glc` | Medium
71 | File | `/cgi-bin/hd_config.cgi` | High
72 | File | `/cgi-bin/nas_sharing.cgi` | High
73 | File | `/cgi-bin/photocenter_mgr.cgi` | High
74 | File | `/cgi-bin/s3.cgi` | High
75 | File | `/cgi-bin/tosei_kikai.php` | High
76 | File | `/cgi-bin/webfile_mgr.cgi` | High
77 | File | `/change_password.php` | High
78 | File | `/classes/Master.php` | High
79 | File | `/classes/Master.php?f=delete_category` | High
80 | File | `/classes/Master.php?f=load_registration` | High
81 | File | `/classes/SystemSettings.php?f=update_settings` | High
82 | File | `/classes/Users.php` | High
83 | File | `/classes/Users.php?f=delete` | High
84 | File | `/classes/Users.php?f=save` | High
85 | File | `/classes/Users.php?f=save_client` | High
86 | File | `/common/show_image.php` | High
87 | File | `/control/deactivate_case.php` | High
88 | File | `/control/register_case.php` | High
89 | File | `/controllers/add_user.php` | High
90 | File | `/core/config-revisions` | High
91 | File | `/dashboard/Cinvoice/manage_invoice` | High
92 | File | `/dashboard/message` | High
93 | File | `/debug/pprof` | Medium
94 | File | `/deletefile.php` | High
95 | ... | ... | ...

There are 837 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/120/pysa-ransomware-iocs/
* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
