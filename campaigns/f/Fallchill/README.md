# Fallchill - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fallchill_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fallchill:

* [VN](https://vuldb.com/?country.vn)

## Actors

These _actors_ are associated with Fallchill or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fallchill.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.79.99.169](https://vuldb.com/?ip.5.79.99.169) | nsg037-19.divide.nl | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [27.123.221.66](https://vuldb.com/?ip.27.123.221.66) | 66-221.fiber.net.id | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [36.71.90.4](https://vuldb.com/?ip.36.71.90.4) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [41.92.208.194](https://vuldb.com/?ip.41.92.208.194) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [41.92.208.196](https://vuldb.com/?ip.41.92.208.196) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [41.92.208.197](https://vuldb.com/?ip.41.92.208.197) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [50.62.168.157](https://vuldb.com/?ip.50.62.168.157) | p3nwvpweb145.shr.prod.phx3.secureserver.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
8 | [59.90.93.138](https://vuldb.com/?ip.59.90.93.138) | static.bb.knl.59.90.93.138.bsnl.in | [Lazarus](https://vuldb.com/?actor.lazarus) | High
9 | [62.243.45.227](https://vuldb.com/?ip.62.243.45.227) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
10 | [64.29.144.201](https://vuldb.com/?ip.64.29.144.201) | ntfw1c25.carrierzone.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
11 | [66.175.41.191](https://vuldb.com/?ip.66.175.41.191) | winVIPnatfl.hostopia.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
12 | [66.232.121.65](https://vuldb.com/?ip.66.232.121.65) | 66-232-121-65.static.hvvc.us | [Lazarus](https://vuldb.com/?actor.lazarus) | High
13 | [66.242.128.11](https://vuldb.com/?ip.66.242.128.11) | hdflns11.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
14 | [66.242.128.12](https://vuldb.com/?ip.66.242.128.12) | hdflns12.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
15 | [66.242.128.13](https://vuldb.com/?ip.66.242.128.13) | hdflns13.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
16 | [66.242.128.134](https://vuldb.com/?ip.66.242.128.134) | hdflsf03.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
17 | [66.242.128.140](https://vuldb.com/?ip.66.242.128.140) | hdflsf01.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reports` | High
2 | File | `/Actions.php?a=login` | High
3 | File | `/add-admin.php` | High
4 | File | `/add-product.php` | High
5 | File | `/admin` | Low
6 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
7 | File | `/admin/` | Low
8 | File | `/admin/add-normal-ticket.php` | High
9 | File | `/admin/addgiving.php` | High
10 | File | `/admin/add_postlogin.php` | High
11 | File | `/admin/add_visitor.php` | High
12 | File | `/admin/admin-profile.php` | High
13 | File | `/admin/app/product.php` | High
14 | File | `/admin/approve.php` | High
15 | File | `/admin/article/add/do` | High
16 | File | `/admin/article/article-add.php` | High
17 | File | `/admin/booking-details.php` | High
18 | File | `/admin/bwdates-report-result.php` | High
19 | File | `/admin/class.php` | High
20 | File | `/admin/content` | High
21 | File | `/admin/controller/student_controller.php` | High
22 | File | `/admin/delete_room.php` | High
23 | File | `/admin/delete_s6.php` | High
24 | File | `/admin/delete_student.php` | High
25 | File | `/admin/div/delete` | High
26 | File | `/admin/edit-doctor-specialization.php` | High
27 | File | `/admin/edit_admin_query.php` | High
28 | File | `/admin/edit_student_query.php` | High
29 | File | `/admin/employee/controller.php` | High
30 | File | `/admin/filemanager/view` | High
31 | File | `/admin/forgot-password.php` | High
32 | File | `/admin/index2.html` | High
33 | File | `/admin/indexConfigs/update` | High
34 | File | `/admin/inv-print.php` | High
35 | File | `/admin/judge` | Medium
36 | File | `/admin/login` | Medium
37 | File | `/admin/login.php` | High
38 | File | `/admin/manage_user.php` | High
39 | File | `/admin/member_save.php` | High
40 | File | `/admin/new-autoortaxi-entry-form.php` | High
41 | File | `/Admin/NewsReport.php` | High
42 | File | `/admin/password-recovery.php` | High
43 | File | `/admin/search-autoortaxi.php` | High
44 | File | `/admin/seo_setting.php` | High
45 | File | `/admin/singlelogin.php?submit=1` | High
46 | File | `/admin/sys/role/list` | High
47 | File | `/admin/tag.php` | High
48 | File | `/admin/tag/save` | High
49 | File | `/admin/theme/Upload.html` | High
50 | File | `/admin/view-user-queries.php` | High
51 | File | `/admin?do=admin:user:editPost` | High
52 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
53 | File | `/adminprofile.php` | High
54 | File | `/agenda_preferencias.php` | High
55 | File | `/ajax.php?action=login` | High
56 | File | `/api.php` | Medium
57 | File | `/api/logs/error/1` | High
58 | File | `/api /v3/auth` | High
59 | File | `/app/api/controller/default/Sqlite.php` | High
60 | File | `/appliance/shiftmgn.php` | High
61 | File | `/application/index/common.php` | High
62 | File | `/articles/welcome-to-your-site#comments-head` | High
63 | File | `/auth/userkey/logout.php` | High
64 | File | `/bilal final/login.php` | High
65 | File | `/bin/httpd` | Medium
66 | File | `/bin/mail` | Medium
67 | File | `/boafrm/formDMZ` | High
68 | File | `/boafrm/formPortFw` | High
69 | File | `/boafrm/formSysLog` | High
70 | File | `/book_car.php` | High
71 | File | `/bsenordering/index.php` | High
72 | File | `/bwdates-report-result.php` | High
73 | File | `/CDGServer3/UserAjax` | High
74 | File | `/cgi-bin/cstecgi.cgi` | High
75 | File | `/cgi-bin/hotspot-changepw.cgi` | High
76 | File | `/cgi-bin/nas_sharing.cgi` | High
77 | File | `/cgi-bin/sessions/get-temp-file` | High
78 | File | `/cgi-bin/wireless.cgi` | High
79 | File | `/cgi-bin/wlogin.cgi` | High
80 | File | `/checkout/confirm/` | High
81 | File | `/check_availability.php` | High
82 | File | `/check_profile.php` | High
83 | File | `/clinica/profile/updateSetting` | High
84 | File | `/Control/Api/Api.php` | High
85 | ... | ... | ...

There are 751 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/alerts/TA17-318A

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
