# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)

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
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/admin/` | Low
3 | File | `/admin/action/add_con.php` | High
4 | File | `/admin/app/product.php` | High
5 | File | `/admin/app/service_crud.php` | High
6 | File | `/admin/book_add.php` | High
7 | File | `/admin/category_row.php` | High
8 | File | `/admin/content/data` | High
9 | File | `/admin/edit-admin.php` | High
10 | File | `/admin/edit.php` | High
11 | File | `/admin/edit_supplier.php` | High
12 | File | `/admin/edit_teacher.php` | High
13 | File | `/admin/file/edit.do` | High
14 | File | `/Admin/login.php` | High
15 | File | `/admin/orders/view_order.php` | High
16 | File | `/admin/pages/student-print.php` | High
17 | File | `/admin/pages/update_go.php` | High
18 | File | `/admin/product/manage_product.php` | High
19 | File | `/adminapi/system/crud` | High
20 | File | `/adminapi/system/file/openfile` | High
21 | File | `/alsdemo/ss/mediam.cgi` | High
22 | File | `/ample/app/action/edit_product.php` | High
23 | File | `/api/controllers/admin/app/AppController.php` | High
24 | File | `/api/controllers/admin/app/ComboController.php` | High
25 | File | `/api/controllers/common/UploadsController.php` | High
26 | File | `/api/controllers/merchant/shop/PosterController.php` | High
27 | File | `/api/dashboard/activity` | High
28 | File | `/api/system/sessions` | High
29 | File | `/app/api/controller/default/File.php` | High
30 | File | `/app/Http/Controllers/ImageController.php` | High
31 | File | `/application/index/controller/Datament.php` | High
32 | File | `/application/index/controller/Pay.php` | High
33 | File | `/application/index/controller/Screen.php` | High
34 | File | `/application/pay/controller/Api.php` | High
35 | File | `/apply/index.php` | High
36 | File | `/att_add.php` | Medium
37 | File | `/auth/user/all.api` | High
38 | File | `/boafrm/formMapDelDevice` | High
39 | File | `/cgi-bin/cstecgi.cgi` | High
40 | File | `/cgi-bin/reader` | High
41 | File | `/common/user_profile.php` | High
42 | File | `/cupseasylive/currencycreate.php` | High
43 | File | `/cupseasylive/currencymodify.php` | High
44 | File | `/cupseasylive/itemlist.php` | High
45 | File | `/cupseasylive/locationcreate.php` | High
46 | File | `/currentsetting.htm` | High
47 | File | `/dashboard/Cinvoice/manage_invoice` | High
48 | ... | ... | ...

There are 416 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
