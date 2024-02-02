# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | - | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | - | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | Snake | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snake_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-29, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/accounts_con/register_account` | High
3 | File | `/admin/` | Low
4 | File | `/admin/action/add_con.php` | High
5 | File | `/admin/action/new-father.php` | High
6 | File | `/admin/action/new-feed.php` | High
7 | File | `/admin/ajax.php` | High
8 | File | `/admin/book_add.php` | High
9 | File | `/admin/book_row.php` | High
10 | File | `/admin/borrow_add.php` | High
11 | File | `/admin/bwdates-report-details.php` | High
12 | File | `/admin/category/updateStatus` | High
13 | File | `/admin/category_row.php` | High
14 | File | `/admin/course.php` | High
15 | File | `/admin/div/update` | High
16 | File | `/admin/edit.php` | High
17 | File | `/admin/edit_teacher.php` | High
18 | File | `/admin/friend_link/update` | High
19 | File | `/Admin/login.php` | High
20 | File | `/admin/makehtml_freelist_action.php` | High
21 | File | `/admin/manage-pages.php` | High
22 | File | `/admin/manage-users.php` | High
23 | File | `/Admin/News.php` | High
24 | File | `/admin/pages/edit_chicken.php` | High
25 | File | `/admin/pages/update_go.php` | High
26 | File | `/admin/pages/yearlevel.php` | High
27 | File | `/admin/php/crud.php` | High
28 | File | `/admin/slide/update` | High
29 | File | `/admin/subject.php` | High
30 | File | `/admin_route/dec_service_credits.php` | High
31 | File | `/adplanet/PlanetUser` | High
32 | File | `/ample/app/action/edit_product.php` | High
33 | File | `/ample/app/ajax/member_data.php` | High
34 | File | `/api.php` | Medium
35 | File | `/api/dashboard/activity` | High
36 | File | `/app/api/controller/default/File.php` | High
37 | File | `/application/index/controller/Datament.php` | High
38 | File | `/application/pay/controller/Api.php` | High
39 | File | `/apply/index.php` | High
40 | File | `/apps/reg_go.php` | High
41 | File | `/article/DelectArticleById/` | High
42 | File | `/Attachment/fromImageUrl` | High
43 | File | `/auth/user/all.api` | High
44 | File | `/b2b-supermarket/catalog/all-products` | High
45 | File | `/bin/boa` | Medium
46 | File | `/boaform/device_reset.cgi` | High
47 | File | `/boaform/wlan_basic_set.cgi` | High
48 | File | `/boafrm/formMapDelDevice` | High
49 | File | `/category.php` | High
50 | File | `/cgi-bin/cstecgi.cgi` | High
51 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
52 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
53 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
54 | File | `/classes/Users.php?f=save` | High
55 | File | `/clinic/medical_records_view.php` | High
56 | File | `/common/down/file` | High
57 | File | `/config,admin.jsp` | High
58 | File | `/download.php?file=author.png` | High
59 | ... | ... | ...

There are 519 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
