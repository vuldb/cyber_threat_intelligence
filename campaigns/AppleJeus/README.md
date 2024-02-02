# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/admin/category/save` | High
10 | File | `/admin/category_row.php` | High
11 | File | `/admin/clientview.php` | High
12 | File | `/admin/course.php` | High
13 | File | `/admin/courses/manage_course.php` | High
14 | File | `/admin/courses/view_course.php` | High
15 | File | `/admin/departments/manage_department.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/ind_backstage.php` | High
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
29 | File | `/adplanet/PlanetCommentList` | High
30 | File | `/adplanet/PlanetUser` | High
31 | File | `/ample/app/action/edit_product.php` | High
32 | File | `/api.php` | Medium
33 | File | `/api/baskets/{name}` | High
34 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
35 | File | `/api/log/killJob` | High
36 | File | `/app/ajax/sell_return_data.php` | High
37 | File | `/app/api/controller/caiji.php` | High
38 | File | `/app/api/controller/collect.php` | High
39 | File | `/app/Http/Controllers/ImageController.php` | High
40 | File | `/application/pay/controller/Api.php` | High
41 | File | `/article/DelectArticleById/` | High
42 | File | `/assets/php/upload.php` | High
43 | File | `/auth/auth.php?user=1` | High
44 | File | `/b2b-supermarket/catalog/all-products` | High
45 | File | `/bin/boa` | Medium
46 | File | `/boaform/device_reset.cgi` | High
47 | File | `/boaform/wlan_basic_set.cgi` | High
48 | File | `/cgi-bin/cstecgi.cgi` | High
49 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
50 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
51 | File | `/cgi-bin/wlogin.cgi` | High
52 | File | `/cgi/cpaddons_report.pl` | High
53 | File | `/classes/Master.php` | High
54 | File | `/classes/Master.php? f=save_medicine` | High
55 | File | `/config-manager/save` | High
56 | File | `/dashboard/createblog` | High
57 | File | `/dashboard?controller=UserCollection::createUser` | High
58 | File | `/debug/pprof` | Medium
59 | File | `/devinfo` | Medium
60 | File | `/DXR.axd` | Medium
61 | File | `/endpoint/add-guest.php` | High
62 | File | `/file-manager/rename.php` | High
63 | File | `/forum/away.php` | High
64 | File | `/general/email/inbox/delete_webmail.php` | High
65 | ... | ... | ...

There are 568 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
