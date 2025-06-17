# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Camerashy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Naikon](https://vuldb.com/?actor.naikon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Camerashy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
2 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
3 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | [Naikon](https://vuldb.com/?actor.naikon) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-268, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add-company.php` | High
2 | File | `/addschedule.htm` | High
3 | File | `/adm/ajax.php` | High
4 | File | `/adm/index.php` | High
5 | File | `/admin-cp/log-viewer` | High
6 | File | `/admin-cp/logs/email` | High
7 | File | `/admin-cp/plugin/editor` | High
8 | File | `/admin-cp/plugin/install` | High
9 | File | `/admin-cp/theme/editor/default` | High
10 | File | `/admin/` | Low
11 | File | `/admin/about-us.php` | High
12 | File | `/admin/aboutus.php` | High
13 | File | `/admin/adminprofile.php` | High
14 | File | `/admin/all-applications.php` | High
15 | File | `/admin/article.php` | High
16 | File | `/admin/between-dates-application-report.php` | High
17 | File | `/admin/betweendates-detailsreports.php` | High
18 | File | `/admin/campsdetails.php` | High
19 | File | `/admin/change-password.php` | High
20 | File | `/admin/check_availability.php` | High
21 | File | `/admin/doctor-specilization.php` | High
22 | File | `/admin/edit-category.php` | High
23 | File | `/admin/edit-course.php` | High
24 | File | `/admin/edit-subcategory.php` | High
25 | File | `/admin/edit-subjects-detail.php` | High
26 | File | `/Admin/EditCity.php` | High
27 | File | `/admin/editempexp.php` | High
28 | File | `/admin/home/index.html` | High
29 | File | `/Admin/InsertCategory.php` | High
30 | File | `/Admin/InsertState.php` | High
31 | File | `/admin/new-ccapplication.php` | High
32 | File | `/Admin/NewsReport.php` | High
33 | File | `/admin/post-avehical.php` | High
34 | File | `/admin/posts.php?source=add_post` | High
35 | File | `/admin/readenq.php` | High
36 | File | `/admin/registration.php` | High
37 | File | `/admin/setup.cgi` | High
38 | File | `/admin/update_expense.php` | High
39 | File | `/admin/up_booking.php` | High
40 | File | `/admin/users-applications.php` | High
41 | File | `/admin/util/Field.php` | High
42 | File | `/admin/view-pass-detail.php` | High
43 | File | `/api/asset/upload` | High
44 | File | `/api/export/exportResources` | High
45 | File | `/api/user/password/sent-reset-email` | High
46 | File | `/api/user/users` | High
47 | File | `/api/v4/teams/` | High
48 | File | `/app/ConfirmSmsCode` | High
49 | File | `/appointment-history.php` | High
50 | File | `/appointment.php` | High
51 | File | `/auth/soup-auth-digest.c` | High
52 | File | `/barangay_management/admin/?page=view_clearance` | High
53 | File | `/bin/boa` | Medium
54 | File | `/bin/main` | Medium
55 | File | `/birthing_record.php` | High
56 | File | `/boafrm/formDiskCreateGroup` | High
57 | File | `/boafrm/formDiskCreateShare` | High
58 | ... | ... | ...

There are 507 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
