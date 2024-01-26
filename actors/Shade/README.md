# Shade - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shade](https://vuldb.com/?actor.shade). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shade](https://vuldb.com/?actor.shade)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shade:

* [US](https://vuldb.com/?country.us)
* [LT](https://vuldb.com/?country.lt)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shade.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.66](https://vuldb.com/?ip.5.9.116.66) | static.66.116.9.5.clients.your-server.de | - | High
2 | [5.9.158.75](https://vuldb.com/?ip.5.9.158.75) | static.75.158.9.5.clients.your-server.de | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.6.22.189](https://vuldb.com/?ip.23.6.22.189) | a23-6-22-189.deploy.static.akamaitechnologies.com | - | High
5 | [37.157.254.113](https://vuldb.com/?ip.37.157.254.113) | rs004106.root.server-hosting.expert | - | High
6 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | - | High
7 | [46.166.182.20](https://vuldb.com/?ip.46.166.182.20) | - | - | High
8 | [47.101.49.13](https://vuldb.com/?ip.47.101.49.13) | - | - | High
9 | [51.68.204.139](https://vuldb.com/?ip.51.68.204.139) | ns3127231.ip-51-68-204.eu | - | High
10 | [51.68.206.28](https://vuldb.com/?ip.51.68.206.28) | ns3128207.ip-51-68-206.eu | - | High
11 | [62.151.180.62](https://vuldb.com/?ip.62.151.180.62) | mx18062.brandengager.info | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shade_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shade. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/account/delivery` | High
2 | File | `/accounts_con/register_account` | High
3 | File | `/admin` | Low
4 | File | `/admin/` | Low
5 | File | `/admin/admin_login_process.php` | High
6 | File | `/admin/ajax.php?action=confirm_order` | High
7 | File | `/admin/book_add.php` | High
8 | File | `/admin/book_row.php` | High
9 | File | `/admin/borrow_add.php` | High
10 | File | `/admin/category_row.php` | High
11 | File | `/admin/clientview.php` | High
12 | File | `/admin/cms_admin.php` | High
13 | File | `/admin/cms_content.php` | High
14 | File | `/admin/config/uploadicon.php` | High
15 | File | `/admin/course.php` | High
16 | File | `/admin/courses/manage_course.php` | High
17 | File | `/admin/courses/view_course.php` | High
18 | File | `/admin/departments/manage_department.php` | High
19 | File | `/admin/employee_edit.php` | High
20 | File | `/admin/index.php` | High
21 | File | `/admin/ind_backstage.php` | High
22 | File | `/admin/leancloud.php` | High
23 | File | `/admin/list_addr_fwresource_ip.php` | High
24 | File | `/admin/manage-pages.php` | High
25 | File | `/admin/manage-users.php` | High
26 | File | `/admin/options-theme.php` | High
27 | File | `/admin/order.php` | High
28 | File | `/admin/pages/subjects.php` | High
29 | File | `/admin/pages/yearlevel.php` | High
30 | File | `/admin/regester.php` | High
31 | File | `/admin/return_add.php` | High
32 | File | `/admin/save.php` | High
33 | File | `/admin/singlelogin.php?submit=1` | High
34 | File | `/admin/students/manage_academic.php` | High
35 | File | `/admin/students/update_status.php` | High
36 | File | `/admin/subject.php` | High
37 | File | `/admin/update-clients.php` | High
38 | File | `/admin/upload/img` | High
39 | File | `/adplanet/PlanetCommentList` | High
40 | File | `/adplanet/PlanetUser` | High
41 | File | `/ample/app/action/edit_product.php` | High
42 | File | `/api/` | Low
43 | File | `/api/log/killJob` | High
44 | File | `/api/V2/internal/TaskPermissions/CheckTaskAccess` | High
45 | File | `/app/ajax/sell_return_data.php` | High
46 | File | `/app/api/controller/caiji.php` | High
47 | File | `/app/api/controller/collect.php` | High
48 | File | `/application/pay/controller/Api.php` | High
49 | File | `/article/DelectArticleById/` | High
50 | File | `/auth/auth.php?user=1` | High
51 | File | `/b2b-supermarket/catalog/all-products` | High
52 | File | `/bin/boa` | Medium
53 | File | `/boaform/device_reset.cgi` | High
54 | File | `/boaform/wlan_basic_set.cgi` | High
55 | File | `/book-services.php` | High
56 | File | `/cgi-bin/cstecgi.cgi` | High
57 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
58 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
59 | File | `/cgi-bin/vitogate.cgi` | High
60 | File | `/claire_blake` | High
61 | File | `/classes/Master.php` | High
62 | File | `/classes/Master.php?f=delete_payment` | High
63 | File | `/classes/Master.php? f=save_medicine` | High
64 | File | `/com.biepie/shared_prefs/com.bitpie_preferences.xml` | High
65 | File | `/config,admin.jsp` | High
66 | File | `/config-manager/save` | High
67 | File | `/course/filterRecords/` | High
68 | File | `/dashboard/createblog` | High
69 | File | `/dashboard?controller=UserCollection::createUser` | High
70 | File | `/download.php?file=author.png` | High
71 | File | `/drivers/infiniband/core/cm.c` | High
72 | File | `/endpoint/add-guest.php` | High
73 | ... | ... | ...

There are 645 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0906-0913.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0920-0927.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1025-1101.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
