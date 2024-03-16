# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Applejeus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | - | High
2 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | - | High
3 | [95.213.232.170](https://vuldb.com/?ip.95.213.232.170) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Applejeus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accounts_con/register_account` | High
2 | File | `/admin` | Low
3 | File | `/admin/` | Low
4 | File | `/admin/admin_login_process.php` | High
5 | File | `/admin/admin_user.php` | High
6 | File | `/admin/book_add.php` | High
7 | File | `/admin/book_row.php` | High
8 | File | `/admin/borrow_add.php` | High
9 | File | `/admin/category_row.php` | High
10 | File | `/admin/clientview.php` | High
11 | File | `/admin/course.php` | High
12 | File | `/admin/courses/manage_course.php` | High
13 | File | `/admin/courses/view_course.php` | High
14 | File | `/admin/departments/manage_department.php` | High
15 | File | `/admin/index.php` | High
16 | File | `/admin/ind_backstage.php` | High
17 | File | `/admin/list_ipAddressPolicy.php` | High
18 | File | `/admin/makehtml_freelist_action.php` | High
19 | File | `/admin/manage-users.php` | High
20 | File | `/admin/options-theme.php` | High
21 | File | `/admin/pages/subjects.php` | High
22 | File | `/admin/pages/yearlevel.php` | High
23 | File | `/admin/regester.php` | High
24 | File | `/admin/return_add.php` | High
25 | File | `/admin/students/manage_academic.php` | High
26 | File | `/admin/students/update_status.php` | High
27 | File | `/admin/subject.php` | High
28 | File | `/admin/update-clients.php` | High
29 | File | `/admin/view_sendlist.php` | High
30 | File | `/adplanet/PlanetCommentList` | High
31 | File | `/adplanet/PlanetUser` | High
32 | File | `/ample/app/action/edit_product.php` | High
33 | File | `/api.php` | Medium
34 | File | `/api/baskets/{name}` | High
35 | File | `/api/controllers/admin/app/AppController.php` | High
36 | File | `/api/controllers/admin/app/ComboController.php` | High
37 | File | `/api/controllers/common/UploadsController.php` | High
38 | File | `/api/controllers/merchant/app/ComboController.php` | High
39 | File | `/api/controllers/merchant/design/MaterialController.php` | High
40 | File | `/api/controllers/merchant/shop/PosterController.php` | High
41 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
42 | File | `/api/log/killJob` | High
43 | File | `/app/ajax/sell_return_data.php` | High
44 | File | `/app/api/controller/caiji.php` | High
45 | File | `/app/api/controller/collect.php` | High
46 | File | `/app/Http/Controllers/ImageController.php` | High
47 | File | `/application/index/controller/Datament.php` | High
48 | File | `/application/pay/controller/Api.php` | High
49 | File | `/article/DelectArticleById/` | High
50 | File | `/assets/php/upload.php` | High
51 | File | `/auth/auth.php?user=1` | High
52 | File | `/b2b-supermarket/catalog/all-products` | High
53 | File | `/bin/boa` | Medium
54 | File | `/boaform/device_reset.cgi` | High
55 | File | `/boaform/wlan_basic_set.cgi` | High
56 | File | `/cgi-bin/cstecgi.cgi` | High
57 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
58 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
59 | File | `/cgi-bin/wlogin.cgi` | High
60 | File | `/cgi/cpaddons_report.pl` | High
61 | File | `/classes/Master.php` | High
62 | File | `/classes/Master.php? f=save_medicine` | High
63 | File | `/common/dict/list` | High
64 | File | `/config-manager/save` | High
65 | File | `/core/config-revisions` | High
66 | File | `/currentsetting.htm` | High
67 | File | `/dashboard/createblog` | High
68 | File | `/dashboard?controller=UserCollection::createUser` | High
69 | File | `/debug/pprof` | Medium
70 | ... | ... | ...

There are 619 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
