# Poison Ivy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Poison Ivy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Poison Ivy:

* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Poison Ivy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [menuPass](https://vuldb.com/?actor.menupass) | High
2 | [Tropic Trooper](https://vuldb.com/?actor.tropic_trooper) | High
3 | [Poison Ivy](https://vuldb.com/?actor.poison_ivy) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Poison Ivy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.153.123.11](https://vuldb.com/?ip.5.153.123.11) | 11-123-153-5.dyn.cable.fcom.ch | [Poison Ivy](https://vuldb.com/?actor.poison_ivy) | High
2 | [23.27.112.216](https://vuldb.com/?ip.23.27.112.216) | - | [Tropic Trooper](https://vuldb.com/?actor.tropic_trooper) | High
3 | [45.32.8.137](https://vuldb.com/?ip.45.32.8.137) | 45.32.8.137.vultr.com | [Poison Ivy](https://vuldb.com/?actor.poison_ivy) | Medium
4 | [45.76.125.176](https://vuldb.com/?ip.45.76.125.176) | 45.76.125.176.vultr.com | [Poison Ivy](https://vuldb.com/?actor.poison_ivy) | Medium
5 | [45.76.228.61](https://vuldb.com/?ip.45.76.228.61) | 45.76.228.61.vultr.com | [Poison Ivy](https://vuldb.com/?actor.poison_ivy) | Medium
6 | [49.254.211.75](https://vuldb.com/?ip.49.254.211.75) | - | [Tropic Trooper](https://vuldb.com/?actor.tropic_trooper) | High
7 | [50.117.38.164](https://vuldb.com/?ip.50.117.38.164) | - | [Tropic Trooper](https://vuldb.com/?actor.tropic_trooper) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Poison Ivy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Poison Ivy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/addbill.php` | Medium
2 | File | `/admin` | Low
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/action/add_con.php` | High
6 | File | `/admin/action/delete-vaccine.php` | High
7 | File | `/admin/action/edit_chicken.php` | High
8 | File | `/admin/action/new-father.php` | High
9 | File | `/admin/action/new-feed.php` | High
10 | File | `/admin/action/update-deworm.php` | High
11 | File | `/admin/admin_login_process.php` | High
12 | File | `/admin/admin_user.php` | High
13 | File | `/admin/book_add.php` | High
14 | File | `/admin/book_row.php` | High
15 | File | `/admin/borrow_add.php` | High
16 | File | `/admin/bwdates-report-details.php` | High
17 | File | `/admin/category_row.php` | High
18 | File | `/admin/clientview.php` | High
19 | File | `/admin/edit_teacher.php` | High
20 | File | `/admin/index.php?act=reset_admin_psw` | High
21 | File | `/Admin/login.php` | High
22 | File | `/admin/makehtml_freelist_action.php` | High
23 | File | `/Admin/News.php` | High
24 | File | `/admin/pages/edit_chicken.php` | High
25 | File | `/admin/pages/student-print.php` | High
26 | File | `/admin/pages/subjects.php` | High
27 | File | `/admin/pages/update_go.php` | High
28 | File | `/admin/pages/yearlevel.php` | High
29 | File | `/admin/php/crud.php` | High
30 | File | `/admin/regester.php` | High
31 | File | `/admin/request-received-bydonar.php` | High
32 | File | `/admin/return_add.php` | High
33 | File | `/admin/update-clients.php` | High
34 | File | `/admin/uploads/` | High
35 | File | `/admin_ping.htm` | High
36 | File | `/admin_route/dec_service_credits.php` | High
37 | File | `/admin_route/inc_service_credits.php` | High
38 | File | `/ample/app/action/edit_product.php` | High
39 | File | `/api.php` | Medium
40 | File | `/api/log/killJob` | High
41 | File | `/app/ajax/sell_return_data.php` | High
42 | File | `/app/api/controller/caiji.php` | High
43 | File | `/app/api/controller/collect.php` | High
44 | File | `/app/api/controller/default/File.php` | High
45 | File | `/app/api/controller/default/Sqlite.php` | High
46 | File | `/application/index/common.php` | High
47 | File | `/application/index/controller/Databasesource.php` | High
48 | File | `/application/index/controller/Datament.php` | High
49 | File | `/application/index/controller/File.php` | High
50 | File | `/application/index/controller/Icon.php` | High
51 | File | `/application/index/controller/Screen.php` | High
52 | File | `/application/index/controller/Service.php` | High
53 | File | `/application/pay/controller/Api.php` | High
54 | File | `/apply/index.php` | High
55 | File | `/apps/login_auth.php` | High
56 | File | `/apps/reg_go.php` | High
57 | File | `/assets/php/upload.php` | High
58 | File | `/auth/user/all.api` | High
59 | File | `/bin/boa` | Medium
60 | File | `/boaform/device_reset.cgi` | High
61 | File | `/boaform/wlan_basic_set.cgi` | High
62 | File | `/boafrm/formMapDelDevice` | High
63 | File | `/cgi-bin/cstecgi.cgi` | High
64 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
65 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
66 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
67 | File | `/classes/Master.php? f=save_medicine` | High
68 | File | `/classes/Users.php?f=save` | High
69 | File | `/config,admin.jsp` | High
70 | File | `/core/config-revisions` | High
71 | File | `/dashboard?controller=UserCollection::createUser` | High
72 | File | `/devinfo` | Medium
73 | File | `/download.php?file=author.png` | High
74 | File | `/file-manager/delete.php` | High
75 | ... | ... | ...

There are 663 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://threatfox.abuse.ch
* https://unit42.paloaltonetworks.com/unit42-tropic-trooper-targets-taiwanese-government-and-fossil-fuel-provider-with-poison-ivy/
* https://www.fireeye.com/content/dam/fireeye-www/global/en/current-threats/pdfs/rpt-poison-ivy.pdf
* https://www.threatminer.org/report.php?q=PoisonIvyGroupandtheCyberespionageCampaignAgainstChineseMilitaryandGoverment-360CoreSecurity.pdf&y=2018

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
