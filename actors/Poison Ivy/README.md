# Poison Ivy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Poison Ivy](https://vuldb.com/?actor.poison_ivy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.poison_ivy](https://vuldb.com/?actor.poison_ivy)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Poison Ivy:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Poison Ivy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.153.123.11](https://vuldb.com/?ip.5.153.123.11) | 11-123-153-5.dyn.cable.fcom.ch | - | High
2 | [45.32.8.137](https://vuldb.com/?ip.45.32.8.137) | 45.32.8.137.vultr.com | - | Medium
3 | [45.76.125.176](https://vuldb.com/?ip.45.76.125.176) | 45.76.125.176.vultr.com | - | Medium
4 | [45.76.228.61](https://vuldb.com/?ip.45.76.228.61) | 45.76.228.61.vultr.com | - | Medium
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Poison Ivy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Poison Ivy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accounts_con/register_account` | High
2 | File | `/addbill.php` | Medium
3 | File | `/admin` | Low
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
19 | File | `/admin/course.php` | High
20 | File | `/admin/edit_teacher.php` | High
21 | File | `/admin/index.php?act=reset_admin_psw` | High
22 | File | `/admin/ind_backstage.php` | High
23 | File | `/admin/makehtml_freelist_action.php` | High
24 | File | `/admin/manage-pages.php` | High
25 | File | `/admin/manage-users.php` | High
26 | File | `/Admin/News.php` | High
27 | File | `/admin/options-theme.php` | High
28 | File | `/admin/pages/edit_chicken.php` | High
29 | File | `/admin/pages/student-print.php` | High
30 | File | `/admin/pages/subjects.php` | High
31 | File | `/admin/pages/update_go.php` | High
32 | File | `/admin/pages/yearlevel.php` | High
33 | File | `/admin/php/crud.php` | High
34 | File | `/admin/regester.php` | High
35 | File | `/admin/request-received-bydonar.php` | High
36 | File | `/admin/return_add.php` | High
37 | File | `/admin/singlelogin.php?submit=1` | High
38 | File | `/admin/subject.php` | High
39 | File | `/admin/update-clients.php` | High
40 | File | `/admin/upload/img` | High
41 | File | `/admin/uploads/` | High
42 | File | `/admin_route/dec_service_credits.php` | High
43 | File | `/admin_route/inc_service_credits.php` | High
44 | File | `/adplanet/PlanetCommentList` | High
45 | File | `/adplanet/PlanetUser` | High
46 | File | `/ample/app/action/edit_product.php` | High
47 | File | `/api.php` | Medium
48 | File | `/api/log/killJob` | High
49 | File | `/app/ajax/sell_return_data.php` | High
50 | File | `/app/api/controller/caiji.php` | High
51 | File | `/app/api/controller/collect.php` | High
52 | File | `/app/api/controller/default/File.php` | High
53 | File | `/app/api/controller/default/Sqlite.php` | High
54 | File | `/application/pay/controller/Api.php` | High
55 | File | `/apps/login_auth.php` | High
56 | File | `/apps/reg_go.php` | High
57 | File | `/article/DelectArticleById/` | High
58 | File | `/assets/php/upload.php` | High
59 | File | `/auth/auth.php?user=1` | High
60 | File | `/auth/user/all.api` | High
61 | File | `/b2b-supermarket/catalog/all-products` | High
62 | File | `/bin/boa` | Medium
63 | File | `/boaform/device_reset.cgi` | High
64 | File | `/boaform/wlan_basic_set.cgi` | High
65 | File | `/boafrm/formMapDelDevice` | High
66 | File | `/cgi-bin/cstecgi.cgi` | High
67 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
68 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
69 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
70 | File | `/classes/Master.php? f=save_medicine` | High
71 | File | `/classes/Users.php?f=save` | High
72 | File | `/config,admin.jsp` | High
73 | File | `/dashboard?controller=UserCollection::createUser` | High
74 | ... | ... | ...

There are 646 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
