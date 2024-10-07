# Poison Ivy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Poison Ivy](https://vuldb.com/?actor.poison_ivy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.poison_ivy](https://vuldb.com/?actor.poison_ivy)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Poison Ivy:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [EG](https://vuldb.com/?country.eg)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Poison Ivy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.153.123.11](https://vuldb.com/?ip.5.153.123.11) | 11-123-153-5.dyn.cable.fcom.ch | - | High
2 | [45.32.8.137](https://vuldb.com/?ip.45.32.8.137) | 45.32.8.137.vultr.com | - | Medium
3 | [45.76.125.176](https://vuldb.com/?ip.45.76.125.176) | 45.76.125.176.vultr.com | - | Medium
4 | [45.76.228.61](https://vuldb.com/?ip.45.76.228.61) | 45.76.228.61.vultr.com | - | Medium
5 | [94.49.168.110](https://vuldb.com/?ip.94.49.168.110) | - | - | High
6 | [94.49.176.147](https://vuldb.com/?ip.94.49.176.147) | - | - | High
7 | [94.49.178.155](https://vuldb.com/?ip.94.49.178.155) | - | - | High
8 | ... | ... | ... | ...

There are 28 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Poison Ivy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79 | Cross Site Scripting | High
4 | T1068 | CWE-284 | Execution with Unnecessary Privileges | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Poison Ivy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/` | Low
3 | File | `/admin/action/add_con.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/action/edit_chicken.php` | High
6 | File | `/admin/action/new-father.php` | High
7 | File | `/admin/action/new-feed.php` | High
8 | File | `/admin/action/update-deworm.php` | High
9 | File | `/admin/admin_login_process.php` | High
10 | File | `/admin/admin_user.php` | High
11 | File | `/admin/book_add.php` | High
12 | File | `/admin/book_row.php` | High
13 | File | `/admin/borrow_add.php` | High
14 | File | `/admin/category_row.php` | High
15 | File | `/admin/clientview.php` | High
16 | File | `/admin/edit_teacher.php` | High
17 | File | `/admin/index.php?act=reset_admin_psw` | High
18 | File | `/Admin/login.php` | High
19 | File | `/admin/makehtml_freelist_action.php` | High
20 | File | `/Admin/News.php` | High
21 | File | `/admin/pages/edit_chicken.php` | High
22 | File | `/admin/pages/student-print.php` | High
23 | File | `/admin/pages/update_go.php` | High
24 | File | `/admin/regester.php` | High
25 | File | `/admin/request-received-bydonar.php` | High
26 | File | `/admin/return_add.php` | High
27 | File | `/admin/update-clients.php` | High
28 | File | `/admin/uploads/` | High
29 | File | `/admin_ping.htm` | High
30 | File | `/admin_route/dec_service_credits.php` | High
31 | File | `/admin_route/inc_service_credits.php` | High
32 | File | `/ample/app/action/edit_product.php` | High
33 | File | `/api.php` | Medium
34 | File | `/api/controllers/admin/app/AppController.php` | High
35 | File | `/api/controllers/admin/app/ComboController.php` | High
36 | File | `/api/controllers/common/UploadsController.php` | High
37 | File | `/api/controllers/merchant/app/ComboController.php` | High
38 | File | `/app/ajax/sell_return_data.php` | High
39 | File | `/app/api/controller/caiji.php` | High
40 | File | `/app/api/controller/collect.php` | High
41 | File | `/app/api/controller/default/File.php` | High
42 | File | `/app/api/controller/default/Sqlite.php` | High
43 | File | `/application/index/common.php` | High
44 | File | `/application/index/controller/Databasesource.php` | High
45 | File | `/application/index/controller/Datament.php` | High
46 | File | `/application/index/controller/File.php` | High
47 | File | `/application/index/controller/Icon.php` | High
48 | File | `/application/index/controller/Pay.php` | High
49 | File | `/application/index/controller/Screen.php` | High
50 | File | `/application/index/controller/Service.php` | High
51 | File | `/application/index/controller/Unity.php` | High
52 | File | `/application/pay/controller/Api.php` | High
53 | File | `/application/plugins/controller/Upload.php` | High
54 | File | `/application/websocket/controller/Setting.php` | High
55 | File | `/apply/index.php` | High
56 | File | `/apps/login_auth.php` | High
57 | File | `/apps/reg_go.php` | High
58 | File | `/assets/php/upload.php` | High
59 | File | `/att_add.php` | Medium
60 | File | `/auth/user/all.api` | High
61 | File | `/bin/boa` | Medium
62 | File | `/boaform/device_reset.cgi` | High
63 | File | `/boafrm/formMapDelDevice` | High
64 | File | `/cgi-bin/cstecgi.cgi` | High
65 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
66 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
67 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
68 | File | `/classes/Users.php?f=save` | High
69 | File | `/core/config-revisions` | High
70 | File | `/devinfo` | Medium
71 | ... | ... | ...

There are 625 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://www.threatminer.org/report.php?q=PoisonIvyGroupandtheCyberespionageCampaignAgainstChineseMilitaryandGoverment-360CoreSecurity.pdf&y=2018

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
