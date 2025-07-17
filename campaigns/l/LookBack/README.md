# LookBack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LookBack_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LookBack:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)

## Actors

These _actors_ are associated with LookBack or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lookback](https://vuldb.com/?actor.lookback) | High
2 | [Witchetty](https://vuldb.com/?actor.witchetty) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LookBack.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.176.3](https://vuldb.com/?ip.5.252.176.3) | no-rdns.mivocloud.com | [Witchetty](https://vuldb.com/?actor.witchetty) | High
2 | [79.141.168.137](https://vuldb.com/?ip.79.141.168.137) | nceess.com | [Lookback](https://vuldb.com/?actor.lookback) | High
3 | [103.253.41.45](https://vuldb.com/?ip.103.253.41.45) | mail.e-cigs-mart.com | [Lookback](https://vuldb.com/?actor.lookback) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/account/delivery` | High
3 | File | `/admin/?/layout/edit/1` | High
4 | File | `/admin/?/snippet/delete/3` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/aboutPost.php` | High
7 | File | `/admin/add-brand.php` | High
8 | File | `/admin/admin.php` | High
9 | File | `/admin/allemployees.php` | High
10 | File | `/admin/applicants/controller.php` | High
11 | File | `/admin/article.php?action=upload_cover` | High
12 | File | `/admin/ballot_down.php` | High
13 | File | `/admin/change-image.php` | High
14 | File | `/admin/core/update_student.php` | High
15 | File | `/admin/courses/manage_course.php` | High
16 | File | `/admin/departments/manage_department.php` | High
17 | File | `/admin/edit-category.php` | High
18 | File | `/admin/edit-subadmin.php` | High
19 | File | `/admin/edit.php` | High
20 | File | `/Admin/EditCity.php` | High
21 | File | `/admin/edit_area.php` | High
22 | File | `/admin/forms/option_lists/edit.php` | High
23 | File | `/admin/home.php?con=add` | High
24 | File | `/admin/index.php` | High
25 | File | `/admin/judge` | Medium
26 | File | `/admin/newsletter1.php` | High
27 | File | `/admin/orders/view_order.php` | High
28 | File | `/admin/product/manage.php` | High
29 | File | `/admin/profile.php` | High
30 | File | `/admin/save.php` | High
31 | File | `/admin/save_teacher.php` | High
32 | File | `/admin/uesrs.php&action=display&value=Hide` | High
33 | File | `/admin/view_all_posts.php` | High
34 | File | `/admin/view_reserved.php` | High
35 | File | `/ajax.php?action=read_msg` | High
36 | File | `/ajax.php?action=save_quiz` | High
37 | File | `/api/client/article/list` | High
38 | File | `/api/controllers/merchant/shop/PosterController.php` | High
39 | File | `/api/docs/index.php` | High
40 | File | `/api/trackedEntityInstances` | High
41 | File | `/api/user` | Medium
42 | File | `/appinfo/save` | High
43 | File | `/application/index/controller/Databasesource.php` | High
44 | File | `/binutils/debug.c` | High
45 | File | `/blotter/blotter.php` | High
46 | File | `/boafrm/formWsc` | High
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/discovery.cgi` | High
49 | File | `/cgi-bin/koha/catalogue/search.pl` | High
50 | File | `/chart` | Low
51 | File | `/classes/Master.php?f=save_brand` | High
52 | File | `/course/edit/` | High
53 | File | `/directRouter.rfc` | High
54 | File | `/doneDetail.jsp` | High
55 | File | `/doorgets/app/requests/user/configurationRequest.php` | High
56 | File | `/edit-product.php` | High
57 | File | `/editor/index.php` | High
58 | File | `/Employer/ManageWalkin.php` | High
59 | ... | ... | ...

There are 513 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/witchetty-steganography-espionage
* https://www.proofpoint.com/us/threat-insight/post/lookback-malware-targets-united-states-utilities-sector-phishing-attacks

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
