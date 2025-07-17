# MoonPeak - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MoonPeak](https://vuldb.com/?actor.moonpeak). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.moonpeak](https://vuldb.com/?actor.moonpeak)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MoonPeak:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MoonPeak.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.255.80.162](https://vuldb.com/?ip.27.255.80.162) | - | - | High
2 | [27.255.81.118](https://vuldb.com/?ip.27.255.81.118) | - | - | High
3 | [45.87.153.79](https://vuldb.com/?ip.45.87.153.79) | vm1856550.stark-industries.solutions | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MoonPeak_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-272, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MoonPeak. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/admin/?/snippet/delete/3` | High
3 | File | `/admin/?page=user/list` | High
4 | File | `/admin/aboutPost.php` | High
5 | File | `/admin/add-brand.php` | High
6 | File | `/admin/admin.php` | High
7 | File | `/admin/allemployees.php` | High
8 | File | `/admin/applicants/controller.php` | High
9 | File | `/admin/article.php?action=upload_cover` | High
10 | File | `/admin/ballot_down.php` | High
11 | File | `/admin/change-image.php` | High
12 | File | `/admin/core/update_student.php` | High
13 | File | `/admin/courses/manage_course.php` | High
14 | File | `/admin/departments/manage_department.php` | High
15 | File | `/admin/edit-category.php` | High
16 | File | `/admin/edit-subadmin.php` | High
17 | File | `/admin/edit.php` | High
18 | File | `/admin/edit_area.php` | High
19 | File | `/admin/forms/option_lists/edit.php` | High
20 | File | `/admin/home.php?con=add` | High
21 | File | `/admin/index.php` | High
22 | File | `/admin/judge` | Medium
23 | File | `/admin/newsletter1.php` | High
24 | File | `/admin/orders/view_order.php` | High
25 | File | `/admin/product/manage.php` | High
26 | File | `/admin/profile.php` | High
27 | File | `/admin/save.php` | High
28 | File | `/admin/save_teacher.php` | High
29 | File | `/admin/uesrs.php&action=display&value=Hide` | High
30 | File | `/admin/view_all_posts.php` | High
31 | File | `/admin/view_reserved.php` | High
32 | File | `/ajax.php?action=save_quiz` | High
33 | File | `/api/client/article/list` | High
34 | File | `/api/controllers/merchant/shop/PosterController.php` | High
35 | File | `/api/docs/index.php` | High
36 | File | `/api/trackedEntityInstances` | High
37 | File | `/api/user` | Medium
38 | File | `/appinfo/save` | High
39 | File | `/application/index/controller/Databasesource.php` | High
40 | File | `/binutils/debug.c` | High
41 | File | `/blotter/blotter.php` | High
42 | File | `/boafrm/formWsc` | High
43 | File | `/cgi-bin/cstecgi.cgi` | High
44 | File | `/cgi-bin/discovery.cgi` | High
45 | File | `/cgi-bin/koha/catalogue/search.pl` | High
46 | File | `/chart` | Low
47 | File | `/classes/Master.php?f=save_brand` | High
48 | File | `/course/edit/` | High
49 | File | `/directRouter.rfc` | High
50 | File | `/doorgets/app/requests/user/configurationRequest.php` | High
51 | File | `/edit-product.php` | High
52 | File | `/editor/index.php` | High
53 | File | `/Employer/ManageWalkin.php` | High
54 | File | `/endpoint/delete-bookmark.php?bookmark=1` | High
55 | File | `/endpoint/delete-user.php` | High
56 | File | `/farm/store.php` | High
57 | ... | ... | ...

There are 494 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/moonpeak-malware-infrastructure-north-korea/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
