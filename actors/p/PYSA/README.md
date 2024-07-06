# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PYSA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/ad-list` | Medium
3 | File | `/add_members.php` | High
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/action/add_con.php` | High
9 | File | `/admin/ajax.php?action=save_settings` | High
10 | File | `/admin/app/profile_crud.php` | High
11 | File | `/admin/applicants/controller.php` | High
12 | File | `/admin/applicants/index.php` | High
13 | File | `/admin/booking-bwdates-reports-details.php` | High
14 | File | `/admin/book_row.php` | High
15 | File | `/admin/court-type` | High
16 | File | `/admin/edit_teacher.php` | High
17 | File | `/admin/employee/controller.php` | High
18 | File | `/admin/foreigner-search.php` | High
19 | File | `/admin/index.php?page=categories` | High
20 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
21 | File | `/admin/login.php` | High
22 | File | `/admin/maintenance/manage_category.php` | High
23 | File | `/admin/modules/product/controller.php?action=add` | High
24 | File | `/admin/mod_room/controller.php?action=add` | High
25 | File | `/admin/normal-bwdates-reports-details.php` | High
26 | File | `/admin/php/crud.php` | High
27 | File | `/admin/return_add.php` | High
28 | File | `/admin/settings/` | High
29 | File | `/admin/students.php` | High
30 | File | `/admin/tasks` | Medium
31 | File | `/admin/tax` | Medium
32 | File | `/admin/template` | High
33 | File | `/admin/theme-edit.php` | High
34 | File | `/Admin/user-record.php` | High
35 | File | `/admin/user/controller.php` | High
36 | File | `/admin/user/manage_user.php` | High
37 | File | `/admin/users` | Medium
38 | File | `/admin/vendor` | High
39 | File | `/adminPage/conf/saveCmd` | High
40 | File | `/adminPage/www/addOver` | High
41 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
42 | File | `/adplanet/PlanetUser` | High
43 | File | `/ample/app/action/edit_product.php` | High
44 | File | `/api/client/editemedia.php` | High
45 | File | `/api/controllers/merchant/design/MaterialController.php` | High
46 | File | `/api/cron/settings/setJob/` | High
47 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
48 | File | `/api/sys/login` | High
49 | File | `/api/v1/policies/validation/condition/` | High
50 | File | `/api/v2/maps` | Medium
51 | File | `/app/api/controller/default/File.php` | High
52 | File | `/app/middleware/TokenVerify.php` | High
53 | File | `/application/index/controller/Screen.php` | High
54 | File | `/apps/login_auth.php` | High
55 | File | `/apps/system/router/upload.go` | High
56 | File | `/backend/register.php` | High
57 | File | `/bin/sh` | Low
58 | File | `/blog` | Low
59 | File | `/catalog/all-products` | High
60 | File | `/ccm/system/dialogs/file/delete/1/submit` | High
61 | File | `/cgi-bin/cstecgi.cgi` | High
62 | File | `/cgi-bin/nas_sharing.cgi` | High
63 | File | `/claire_blake` | High
64 | File | `/classes/Master.php?f=delete_inquiry` | High
65 | File | `/classes/Master.php?f=load_registration` | High
66 | File | `/classes/Users.php` | High
67 | File | `/classes/Users.php?f=delete` | High
68 | File | `/control/deactivate_case.php` | High
69 | File | `/control/register_case.php` | High
70 | File | `/core/config-revisions` | High
71 | File | `/dashboard/Cinvoice/manage_invoice` | High
72 | File | `/dashboard/message` | High
73 | File | `/debug/pprof` | Medium
74 | File | `/deletefile.php` | High
75 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
76 | File | `/doctor/view-appointment-detail.php` | High
77 | File | `/edit-task.php` | High
78 | File | `/edit_user.php` | High
79 | File | `/emgui/rest/preferences/PREF_HOME_PAGE/sponsor/3/` | High
80 | File | `/Employer/EditProfile.php` | High
81 | File | `/endpoint/add-guest.php` | High
82 | File | `/endpoint/add-image.php` | High
83 | File | `/endpoint/add-user.php` | High
84 | File | `/endpoint/delete-mark.php` | High
85 | File | `/etc/hosts.deny` | High
86 | File | `/etc/init.d/update_notifications.sh` | High
87 | ... | ... | ...

There are 768 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
