# PovertyStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PovertyStealer](https://vuldb.com/?actor.povertystealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.povertystealer](https://vuldb.com/?actor.povertystealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PovertyStealer:

* [US](https://vuldb.com/?country.us)
* [NO](https://vuldb.com/?country.no)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 28 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PovertyStealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [62.60.226.165](https://vuldb.com/?ip.62.60.226.165) | - | - | High
2 | [185.39.17.162](https://vuldb.com/?ip.185.39.17.162) | - | - | High
3 | [185.244.212.106](https://vuldb.com/?ip.185.244.212.106) | no-mans-land.m247.com | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PovertyStealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PovertyStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/?ajax-request=jnews` | High
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/action.php` | Medium
5 | File | `/add-students.php` | High
6 | File | `/addstock.php` | High
7 | File | `/add_new_supplier.php` | High
8 | File | `/admin/?page=reports` | High
9 | File | `/admin/?page=system_info/contact_info` | High
10 | File | `/admin/?page=user/list` | High
11 | File | `/admin/?page=user/manage_user&id=3` | High
12 | File | `/admin/about-us.php` | High
13 | File | `/admin/action/new-father.php` | High
14 | File | `/admin/add-boat.php` | High
15 | File | `/admin/adddoctorclinic.php` | High
16 | File | `/admin/admin_class.php` | High
17 | File | `/admin/app/service_crud.php` | High
18 | File | `/admin/betweendates-detailsreports.php` | High
19 | File | `/admin/book-details.php` | High
20 | File | `/admin/create_product.php` | High
21 | File | `/admin/del_category.php` | High
22 | File | `/admin/del_service.php` | High
23 | File | `/admin/edit-accepted-appointment.php` | High
24 | File | `/admin/edit-admin.php` | High
25 | File | `/admin/edit-brand.php` | High
26 | File | `/admin/edit-services.php` | High
27 | File | `/admin/edit_category.php` | High
28 | File | `/admin/edit_subject.php` | High
29 | File | `/admin/forgot-password.php` | High
30 | File | `/admin/index.php` | High
31 | File | `/admin/list_crl_conf` | High
32 | File | `/Admin/login.php` | High
33 | File | `/admin/manage_user.php` | High
34 | File | `/admin/massage.php` | High
35 | File | `/admin/network/ajax_getChannelList` | High
36 | File | `/admin/pages/list` | High
37 | File | `/admin/password-recovery.php` | High
38 | File | `/admin/products/manage_product.php` | High
39 | File | `/admin/profile.php` | High
40 | File | `/admin/reg.php` | High
41 | File | `/admin/search-appointment.php` | High
42 | File | `/admin/search.php` | High
43 | File | `/admin/system.html` | High
44 | File | `/admin/sys_sql_query.php` | High
45 | File | `/admin/voters_row.php` | High
46 | File | `/animalsupdate.php` | High
47 | File | `/api/authentication/login` | High
48 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
49 | File | `/api/v4/teams//channels/deleted` | High
50 | File | `/api/wizard/networkSetup` | High
51 | File | `/app/admin/controller/api/Plugs.php` | High
52 | File | `/app/admin/controller/Upload.php` | High
53 | File | `/app/ajax/search_sales_report.php` | High
54 | File | `/app/controller/Setup.php` | High
55 | File | `/app/middleware/TokenVerify.php` | High
56 | File | `/appliance/users?action=edit` | High
57 | File | `/application/index/controller/Screen.php` | High
58 | File | `/application/websocket/controller/Setting.php` | High
59 | File | `/apply/index.php` | High
60 | File | `/b2b-supermarket/catalog/all-products` | High
61 | File | `/backup.pl` | Medium
62 | File | `/bin/boa` | Medium
63 | File | `/blog` | Low
64 | File | `/boafrm/formMapDelDevice` | High
65 | File | `/boafrm/formMultiAP` | High
66 | File | `/boafrm/formSysTel` | High
67 | File | `/booking/show_bookings/` | High
68 | File | `/cgi-bin/cstecgi.cgi` | High
69 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
70 | File | `/cgi-bin/myMusic.cgi` | High
71 | File | `/cgi-bin/nas_sharing.cgi` | High
72 | File | `/cgi-bin/photocenter_mgr.cgi` | High
73 | File | `/cgi-bin/system_mgr.cgi` | High
74 | File | `/classes/Master.php?f=save_medicine` | High
75 | File | `/classes/Users.php?f=save` | High
76 | File | `/collection/all` | High
77 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
78 | File | `/com/esafenet/servlet/ajax/NetSecPolicyAjax.java` | High
79 | File | `/com/esafenet/servlet/client/MailDecryptApplicationService.java` | High
80 | File | `/com/esafenet/servlet/policy/EncryptPolicyService.java` | High
81 | File | `/com/esafenet/servlet/policy/HookWhiteListService.java` | High
82 | ... | ... | ...

There are 720 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3523843/
* https://urlhaus.abuse.ch/url/3547958/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
