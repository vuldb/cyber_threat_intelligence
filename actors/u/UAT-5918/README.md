# UAT-5918 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAT-5918](https://vuldb.com/?actor.uat-5918). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uat-5918](https://vuldb.com/?actor.uat-5918)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAT-5918:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAT-5918.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAT-5918_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-272, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAT-5918. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/admin-cp/plugin/install` | High
3 | File | `/admin/?/login/forgot` | High
4 | File | `/admin/?page=user/list` | High
5 | File | `/admin/aboutPost.php` | High
6 | File | `/admin/add-brand.php` | High
7 | File | `/admin/admin.php` | High
8 | File | `/admin/allemployees.php` | High
9 | File | `/admin/applicants/controller.php` | High
10 | File | `/admin/ballot_down.php` | High
11 | File | `/admin/change-image.php` | High
12 | File | `/admin/change-password.php` | High
13 | File | `/admin/check_admin.php` | High
14 | File | `/admin/courses/manage_course.php` | High
15 | File | `/Admin/createClass.php` | High
16 | File | `/admin/departments/manage_department.php` | High
17 | File | `/admin/edit-category.php` | High
18 | File | `/admin/edit.php` | High
19 | File | `/admin/edit_area.php` | High
20 | File | `/admin/group` | Medium
21 | File | `/admin/home.php?con=add` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/indexConfigs/update` | High
24 | File | `/admin/judge` | Medium
25 | File | `/admin/newsletter1.php` | High
26 | File | `/admin/orders/view_order.php` | High
27 | File | `/admin/product/manage.php` | High
28 | File | `/admin/profile.php` | High
29 | File | `/admin/save_teacher.php` | High
30 | File | `/admin/uesrs.php&action=display&value=Hide` | High
31 | File | `/admin/updatestudent.php` | High
32 | File | `/admin/user/manage_user.php` | High
33 | File | `/admin/view_all_posts.php` | High
34 | File | `/admin/view_reserved.php` | High
35 | File | `/api/controllers/merchant/shop/PosterController.php` | High
36 | File | `/api/docs/index.php` | High
37 | File | `/api/trackedEntityInstances` | High
38 | File | `/appinfo/save` | High
39 | File | `/application/index/controller/Databasesource.php` | High
40 | File | `/binutils/debug.c` | High
41 | File | `/blotter/blotter.php` | High
42 | File | `/boafrm/formFilter` | High
43 | File | `/boafrm/formIpQoS` | High
44 | File | `/boafrm/formWsc` | High
45 | File | `/bsenordering/index.php` | High
46 | File | `/cgi-bin/discovery.cgi` | High
47 | File | `/cgi-bin/koha/catalogue/search.pl` | High
48 | File | `/cgi-bin/sessions/get-temp-file` | High
49 | File | `/cgi-bin/touchlist_sync.cgi` | High
50 | File | `/chart` | Low
51 | File | `/classes/Master.php?f=save_brand` | High
52 | File | `/contract` | Medium
53 | File | `/dashboard/getData.php` | High
54 | File | `/doorgets/app/requests/user/configurationRequest.php` | High
55 | File | `/endpoint/delete-bookmark.php?bookmark=1` | High
56 | File | `/endpoint/delete-user.php` | High
57 | File | `/extensions/realestate/index.php/properties/list/list-with-sidebar/realties` | High
58 | File | `/farm/store.php` | High
59 | File | `/fhconf/umconfig.txt` | High
60 | File | `/fileman/php/deletefile.php` | High
61 | ... | ... | ...

There are 536 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/uat-5918-targets-critical-infra-in-taiwan/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
