# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Camerashy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Naikon](https://vuldb.com/?actor.naikon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Camerashy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
2 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
3 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | [Naikon](https://vuldb.com/?actor.naikon) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin-edit.php` | High
2 | File | `/admin.php/appcenter/local.html?type=addon` | High
3 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=maintenance/brand` | High
6 | File | `/admin/admin_login_process.php` | High
7 | File | `/admin/admin_user.php` | High
8 | File | `/admin/ajax.php` | High
9 | File | `/admin/assign/assign.php` | High
10 | File | `/admin/ballot_down.php` | High
11 | File | `/admin/book_add.php` | High
12 | File | `/admin/borrow_add.php` | High
13 | File | `/admin/cashadvance_row.php` | High
14 | File | `/admin/categories/view_category.php` | High
15 | File | `/admin/category_row.php` | High
16 | File | `/admin/configurations/userInfo` | High
17 | File | `/admin/database/backup` | High
18 | File | `/admin/edit_teacher.php` | High
19 | File | `/admin/getallarticleinfo` | High
20 | File | `/admin/inquiries/view_inquiry.php` | High
21 | File | `/admin/inventory/manage_stock.php` | High
22 | File | `/admin/login.php` | High
23 | File | `/admin/markdown` | High
24 | File | `/admin/options-theme.php` | High
25 | File | `/admin/pages/student-print.php` | High
26 | File | `/admin/pages/update_go.php` | High
27 | File | `/admin/pages/yearlevel.php` | High
28 | File | `/admin/positions_row.php` | High
29 | File | `/admin/products/manage_product.php` | High
30 | File | `/admin/regester.php` | High
31 | File | `/admin/report/index.php` | High
32 | File | `/admin/request-received-bydonar.php` | High
33 | File | `/admin/robot/approval/list` | High
34 | File | `/admin/sales/index.php` | High
35 | File | `/admin/save_teacher.php` | High
36 | File | `/admin/services/manage_service.php` | High
37 | File | `/admin/students/view_details.php` | High
38 | File | `/admin/transactions/track_shipment.php` | High
39 | File | `/admin/user/manage_user.php` | High
40 | File | `/admin/users` | Medium
41 | File | `/admin_route/dec_service_credits.php` | High
42 | File | `/adplanet/PlanetCommentList` | High
43 | File | `/ajax.php?action=read_msg` | High
44 | File | `/ajax.php?action=save_company` | High
45 | File | `/ample/app/action/edit_product.php` | High
46 | File | `/api/stl/actions/search` | High
47 | File | `/app/api/controller/default/File.php` | High
48 | File | `/app/api/controller/default/Sqlite.php` | High
49 | File | `/app/index/controller/Common.php` | High
50 | File | `/boaform/device_reset.cgi` | High
51 | File | `/boafrm/formFilter` | High
52 | File | `/boafrm/formMapDelDevice` | High
53 | File | `/cgi-bin/cstecgi.cgi` | High
54 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
55 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
56 | ... | ... | ...

There are 487 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
