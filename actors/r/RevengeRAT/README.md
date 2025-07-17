# RevengeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RevengeRAT](https://vuldb.com/?actor.revengerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revengerat](https://vuldb.com/?actor.revengerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RevengeRAT:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RevengeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
2 | [10.0.2.15](https://vuldb.com/?ip.10.0.2.15) | - | - | High
3 | [38.132.101.45](https://vuldb.com/?ip.38.132.101.45) | - | - | High
4 | [45.147.230.231](https://vuldb.com/?ip.45.147.230.231) | - | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RevengeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RevengeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/account/delivery` | High
3 | File | `/adama/adama/downloadService` | High
4 | File | `/admin/?/layout/edit/1` | High
5 | File | `/admin/?/page/delete/10` | High
6 | File | `/admin/?/snippet/delete/3` | High
7 | File | `/admin/?page=products/view_product` | High
8 | File | `/admin/?page=user/list` | High
9 | File | `/admin/aboutPost.php` | High
10 | File | `/admin/add-art-type.php` | High
11 | File | `/admin/add-brand.php` | High
12 | File | `/admin/add-customer.php` | High
13 | File | `/admin/admin.php` | High
14 | File | `/admin/allemployees.php` | High
15 | File | `/admin/article.php?action=upload_cover` | High
16 | File | `/admin/ballot_down.php` | High
17 | File | `/admin/core/update_student.php` | High
18 | File | `/admin/courses/manage_course.php` | High
19 | File | `/admin/deleteBooking.php` | High
20 | File | `/admin/departments/manage_department.php` | High
21 | File | `/admin/edit-category.php` | High
22 | File | `/admin/edit-subadmin.php` | High
23 | File | `/admin/edit.php` | High
24 | File | `/Admin/EditCity.php` | High
25 | File | `/admin/edit_user.php` | High
26 | File | `/admin/forms/option_lists/edit.php` | High
27 | File | `/admin/home.php?con=add` | High
28 | File | `/admin/index.php` | High
29 | File | `/admin/judge` | Medium
30 | File | `/admin/login.php` | High
31 | File | `/admin/manage_model.php` | High
32 | File | `/admin/orders/view_order.php` | High
33 | File | `/admin/profile.php` | High
34 | File | `/admin/save.php` | High
35 | File | `/admin/save_teacher.php` | High
36 | File | `/admin/uesrs.php&action=display&value=Hide` | High
37 | File | `/admin/users.php` | High
38 | File | `/admin/view_all_posts.php` | High
39 | File | `/admin/view_reserved.php` | High
40 | File | `/admin/view_sendlist.php` | High
41 | File | `/ajax.php?action=read_msg` | High
42 | File | `/ajax.php?action=save_quiz` | High
43 | File | `/api/client/article/list` | High
44 | File | `/api/controllers/merchant/shop/PosterController.php` | High
45 | File | `/api/docs/index.php` | High
46 | File | `/api/trackedEntityInstances` | High
47 | File | `/api/user` | Medium
48 | File | `/appinfo/save` | High
49 | File | `/application/index/controller/Databasesource.php` | High
50 | File | `/binutils/debug.c` | High
51 | File | `/blotter/blotter.php` | High
52 | File | `/boafrm/formDosCfg` | High
53 | File | `/boafrm/formMultiAP` | High
54 | File | `/boafrm/formWsc` | High
55 | File | `/catalog/all-products` | High
56 | File | `/cgi-bin/cstecgi.cgi` | High
57 | File | `/cgi-bin/discovery.cgi` | High
58 | File | `/ci_spms/admin/category` | High
59 | File | `/classes/Users.php?f=delete` | High
60 | File | `/com/esafenet/servlet/netSec/NetSecConfigService.java` | High
61 | File | `/company/store` | High
62 | File | `/config,admin.jsp` | High
63 | File | `/course/edit/` | High
64 | File | `/directRouter.rfc` | High
65 | File | `/doneDetail.jsp` | High
66 | ... | ... | ...

There are 575 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/149/revengerat-iocs/
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/08/rat-ratatouille-revrat-orcus.html
* https://blog.talosintelligence.com/threat-roundup-0616-0623-2/
* https://www.fortinet.com/blog/threat-research/malware-analysis-revenge-rat-sample.html
* https://www.proofpoint.com/us/blog/threat-insight/reservations-requested-ta558-targets-hospitality-and-travel

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
