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
1 | T1006 | CWE-21, CWE-22, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/addQuestion.php` | High
2 | File | `/admin/addemployee.php` | High
3 | File | `/admin/add_exercises.php` | High
4 | File | `/admin/add_trainers.php` | High
5 | File | `/admin/edit.php` | High
6 | File | `/admin/lab.php` | High
7 | File | `/admin/students/view_student.php` | High
8 | File | `/api/` | Low
9 | File | `/bd_genie_create_account.cgi` | High
10 | File | `/categories/view_category.php` | High
11 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
12 | File | `/cgi-bin/nightled.cgi` | High
13 | File | `/cgi-bin/touchlist_sync.cgi` | High
14 | File | `/ci_hms/massage_room/edit/1` | High
15 | File | `/ci_hms/search` | High
16 | File | `/ci_spms/admin/category` | High
17 | File | `/ci_spms/admin/search/searching/` | High
18 | File | `/ci_ssms/index.php/orders/create` | High
19 | File | `/claire_blake` | High
20 | File | `/classes/Master.php?f=delete_category` | High
21 | File | `/dashboard/add-blog.php` | High
22 | File | `/dashboard/add-portfolio.php` | High
23 | File | `/dashboard/add-service.php` | High
24 | File | `/dashboard/contact` | High
25 | File | `/dashboard/settings` | High
26 | File | `/dashboard/updatelogo.php` | High
27 | File | `/editbrand.php` | High
28 | File | `/edituser.php` | High
29 | File | `/etc/shadow.sample` | High
30 | File | `/fax/fax_send.php` | High
31 | File | `/framework/mod/db/DBMapper.xml` | High
32 | File | `/gasmark/assets/myimages/oneWord.php` | High
33 | File | `/goform/aspForm` | High
34 | File | `/goform/form2userconfig.cgi` | High
35 | File | `/goform/setAutoPing` | High
36 | File | `/guestmanagement/front.php` | High
37 | File | `/home/www/cgi-bin/diagnostics.cgi` | High
38 | File | `/htmldoc/htmldoc/html.cxx` | High
39 | File | `/include/menu_v.inc.php` | High
40 | File | `/includes/utils.php` | High
41 | File | `/index.php` | Medium
42 | File | `/index.php?route=extension/module/so_filter_shop_by/filter_data` | High
43 | File | `/items/manage_item.php` | High
44 | File | `/login.php` | Medium
45 | File | `/loginVaLidation.php` | High
46 | File | `/manage-apartment.php` | High
47 | File | `/management/api/rcx_management/global_config_query` | High
48 | File | `/mdiy/page/verify` | High
49 | File | `/mkshop/Men/profile.php` | High
50 | File | `/mkshope/login.php` | High
51 | ... | ... | ...

There are 446 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
