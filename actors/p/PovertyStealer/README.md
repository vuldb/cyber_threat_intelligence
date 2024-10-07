# PovertyStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PovertyStealer](https://vuldb.com/?actor.povertystealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.povertystealer](https://vuldb.com/?actor.povertystealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PovertyStealer:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [NO](https://vuldb.com/?country.no)
* ...

There are 34 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PovertyStealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [185.244.212.106](https://vuldb.com/?ip.185.244.212.106) | no-mans-land.m247.com | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PovertyStealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-87 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PovertyStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.../gogo/` | Medium
2 | File | `.procmailrc` | Medium
3 | File | `/.env` | Low
4 | File | `/?ajax-request=jnews` | High
5 | File | `/?r=recruit/resume/edit&op=status` | High
6 | File | `/add-students.php` | High
7 | File | `/admin/` | Low
8 | File | `/admin/?page=user/list` | High
9 | File | `/admin/?page=user/manage_user&id=3` | High
10 | File | `/admin/about-us.php` | High
11 | File | `/admin/action/new-father.php` | High
12 | File | `/admin/app/service_crud.php` | High
13 | File | `/admin/communitymanagement.php` | High
14 | File | `/admin/del_category.php` | High
15 | File | `/admin/del_service.php` | High
16 | File | `/admin/edit-accepted-appointment.php` | High
17 | File | `/admin/edit-admin.php` | High
18 | File | `/admin/edit-services.php` | High
19 | File | `/admin/edit_category.php` | High
20 | File | `/admin/edit_subject.php` | High
21 | File | `/admin/extended` | High
22 | File | `/admin/featured.php` | High
23 | File | `/admin/forgot-password.php` | High
24 | File | `/admin/generalsettings.php` | High
25 | File | `/admin/index.php` | High
26 | File | `/admin/list_crl_conf` | High
27 | File | `/admin/login.php` | High
28 | File | `/Admin/login.php` | High
29 | File | `/admin/manage_user.php` | High
30 | File | `/admin/newsletter1.php` | High
31 | File | `/admin/pages/list` | High
32 | File | `/admin/payment.php` | High
33 | File | `/admin/products/manage_product.php` | High
34 | File | `/admin/reg.php` | High
35 | File | `/admin/search-appointment.php` | High
36 | File | `/admin/search.php` | High
37 | File | `/admin/students/manage.php` | High
38 | File | `/admin/students/view_student.php` | High
39 | File | `/admin/system.html` | High
40 | File | `/admin/sys_sql_query.php` | High
41 | File | `/admin/usermanagement.php` | High
42 | File | `/api/addusers` | High
43 | File | `/api/user/upsert/<uuid>` | High
44 | File | `/api/v4/teams//channels/deleted` | High
45 | File | `/app/admin/controller/Upload.php` | High
46 | File | `/app/ajax/search_sales_report.php` | High
47 | File | `/app/controller/Setup.php` | High
48 | File | `/app/middleware/TokenVerify.php` | High
49 | File | `/appliance/users?action=edit` | High
50 | File | `/application/index/controller/Screen.php` | High
51 | File | `/application/websocket/controller/Setting.php` | High
52 | File | `/apply/index.php` | High
53 | File | `/backup.pl` | Medium
54 | File | `/bin/boa` | Medium
55 | File | `/blog` | Low
56 | File | `/boafrm/formMapDelDevice` | High
57 | File | `/booking/show_bookings/` | High
58 | File | `/cgi-bin/cstecgi.cgi` | High
59 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
60 | File | `/cgi-bin/myMusic.cgi` | High
61 | File | `/cgi-bin/nas_sharing.cgi` | High
62 | File | `/cgi-bin/photocenter_mgr.cgi` | High
63 | File | `/cgi-bin/wlogin.cgi` | High
64 | File | `/classes/Master.php?f=save_medicine` | High
65 | File | `/classes/Users.php?f=save` | High
66 | File | `/collection/all` | High
67 | File | `/dashboard/updatelogo.php` | High
68 | File | `/description.php` | High
69 | File | `/designer/add/layout` | High
70 | File | `/dipam/athlete-profile.php` | High
71 | File | `/E-mobile/App/System/File/downfile.php` | High
72 | File | `/edoc/doctor/patient.php` | High
73 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
74 | File | `/Employer/ManageWalkin.php` | High
75 | File | `/endpoint/add-faq.php` | High
76 | File | `/endpoint/delete-account.php` | High
77 | File | `/endpoint/delete-computer.php` | High
78 | File | `/endpoint/update-resident.php` | High
79 | File | `/endpoint/update-tracker.php` | High
80 | ... | ... | ...

There are 709 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
