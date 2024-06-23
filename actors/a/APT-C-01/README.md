# APT-C-01 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT-C-01](https://vuldb.com/?actor.apt-c-01). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt-c-01](https://vuldb.com/?actor.apt-c-01)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT-C-01:

* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT-C-01.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.32.8.137](https://vuldb.com/?ip.45.32.8.137) | 45.32.8.137.vultr.com | - | Medium
2 | [45.76.125.176](https://vuldb.com/?ip.45.76.125.176) | 45.76.125.176.vultr.com | - | Medium
3 | [45.76.228.61](https://vuldb.com/?ip.45.76.228.61) | 45.76.228.61.vultr.com | - | Medium
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT-C-01_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 12 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT-C-01. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/` | Low
4 | File | `/admin/action/add_con.php` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/admin/action/edit_chicken.php` | High
7 | File | `/admin/action/new-father.php` | High
8 | File | `/admin/action/new-feed.php` | High
9 | File | `/admin/action/update-deworm.php` | High
10 | File | `/admin/admin_login_process.php` | High
11 | File | `/admin/admin_user.php` | High
12 | File | `/admin/book_add.php` | High
13 | File | `/admin/book_row.php` | High
14 | File | `/admin/borrow_add.php` | High
15 | File | `/admin/category_row.php` | High
16 | File | `/admin/clientview.php` | High
17 | File | `/admin/edit_teacher.php` | High
18 | File | `/admin/index.php?act=reset_admin_psw` | High
19 | File | `/Admin/login.php` | High
20 | File | `/admin/makehtml_freelist_action.php` | High
21 | File | `/Admin/News.php` | High
22 | File | `/admin/pages/edit_chicken.php` | High
23 | File | `/admin/pages/student-print.php` | High
24 | File | `/admin/pages/subjects.php` | High
25 | File | `/admin/pages/update_go.php` | High
26 | File | `/admin/pages/yearlevel.php` | High
27 | File | `/admin/regester.php` | High
28 | File | `/admin/request-received-bydonar.php` | High
29 | File | `/admin/return_add.php` | High
30 | File | `/admin/update-clients.php` | High
31 | File | `/admin/uploads/` | High
32 | File | `/admin_ping.htm` | High
33 | File | `/admin_route/dec_service_credits.php` | High
34 | File | `/admin_route/inc_service_credits.php` | High
35 | File | `/ample/app/action/edit_product.php` | High
36 | File | `/api.php` | Medium
37 | File | `/api/controllers/admin/app/AppController.php` | High
38 | File | `/api/controllers/admin/app/ComboController.php` | High
39 | File | `/api/controllers/common/UploadsController.php` | High
40 | File | `/api/controllers/merchant/app/ComboController.php` | High
41 | File | `/api/log/killJob` | High
42 | File | `/app/ajax/sell_return_data.php` | High
43 | File | `/app/api/controller/caiji.php` | High
44 | File | `/app/api/controller/collect.php` | High
45 | File | `/app/api/controller/default/File.php` | High
46 | File | `/app/api/controller/default/Sqlite.php` | High
47 | File | `/application/index/common.php` | High
48 | File | `/application/index/controller/Databasesource.php` | High
49 | File | `/application/index/controller/Datament.php` | High
50 | File | `/application/index/controller/File.php` | High
51 | File | `/application/index/controller/Icon.php` | High
52 | File | `/application/index/controller/Pay.php` | High
53 | File | `/application/index/controller/Screen.php` | High
54 | File | `/application/index/controller/Service.php` | High
55 | File | `/application/index/controller/Unity.php` | High
56 | File | `/application/pay/controller/Api.php` | High
57 | File | `/application/plugins/controller/Upload.php` | High
58 | File | `/application/websocket/controller/Setting.php` | High
59 | File | `/apply/index.php` | High
60 | File | `/apps/login_auth.php` | High
61 | File | `/apps/reg_go.php` | High
62 | File | `/assets/php/upload.php` | High
63 | File | `/att_add.php` | Medium
64 | File | `/auth/user/all.api` | High
65 | File | `/bin/boa` | Medium
66 | File | `/boaform/device_reset.cgi` | High
67 | File | `/boaform/wlan_basic_set.cgi` | High
68 | File | `/boafrm/formMapDelDevice` | High
69 | File | `/cgi-bin/cstecgi.cgi` | High
70 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
71 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
72 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
73 | File | `/classes/Master.php? f=save_medicine` | High
74 | File | `/classes/Users.php?f=save` | High
75 | ... | ... | ...

There are 657 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=APT-C-01-360.pdf&y=2018

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
