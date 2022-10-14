# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [FR](https://vuldb.com/?country.fr)
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

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.dbshell` | Medium
2 | File | `/addQuestion.php` | High
3 | File | `/admin/addemployee.php` | High
4 | File | `/admin/add_exercises.php` | High
5 | File | `/admin/add_trainers.php` | High
6 | File | `/admin/budget.php` | High
7 | File | `/admin/contact/list` | High
8 | File | `/admin/edit.php` | High
9 | File | `/admin/students/view_student.php` | High
10 | File | `/baseOpLog.do` | High
11 | File | `/bd_genie_create_account.cgi` | High
12 | File | `/bits/stl_vector.h` | High
13 | File | `/categories/view_category.php` | High
14 | File | `/claire_blake` | High
15 | File | `/classes/Master.php?f=delete_category` | High
16 | File | `/dashboard/add-blog.php` | High
17 | File | `/dashboard/add-portfolio.php` | High
18 | File | `/dashboard/add-service.php` | High
19 | File | `/dashboard/contact` | High
20 | File | `/dashboard/settings` | High
21 | File | `/dashboard/updatelogo.php` | High
22 | File | `/employees/manage_leave_type.php` | High
23 | File | `/etc/shadow.sample` | High
24 | File | `/fax/fax_send.php` | High
25 | File | `/framework/mod/db/DBMapper.xml` | High
26 | File | `/gasmark/assets/myimages/oneWord.php` | High
27 | File | `/goform/aspForm` | High
28 | File | `/goform/form2userconfig.cgi` | High
29 | File | `/goform/NatStaticSetting` | High
30 | File | `/goform/setAutoPing` | High
31 | File | `/goform/wifiSSIDget` | High
32 | File | `/goform/wifiSSIDset` | High
33 | File | `/guestmanagement/front.php` | High
34 | File | `/home/www/cgi-bin/diagnostics.cgi` | High
35 | File | `/htmldoc/htmldoc/html.cxx` | High
36 | File | `/index.php` | Medium
37 | File | `/items/manage_item.php` | High
38 | File | `/kfm/index.php` | High
39 | ... | ... | ...

There are 338 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
