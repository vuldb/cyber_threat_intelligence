# UNC6395 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UNC6395](https://vuldb.com/?actor.unc6395). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.unc6395](https://vuldb.com/?actor.unc6395)

## Campaigns

The following _campaigns_ are known and can be associated with UNC6395:

* Salesforce Salesloft Drift

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNC6395:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [IT](https://vuldb.com/?country.it)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNC6395.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [44.215.108.109](https://vuldb.com/?ip.44.215.108.109) | ec2-44-215-108-109.compute-1.amazonaws.com | Salesforce Salesloft Drift | Medium
2 | [154.41.95.2](https://vuldb.com/?ip.154.41.95.2) | - | Salesforce Salesloft Drift | High
3 | [176.65.149.100](https://vuldb.com/?ip.176.65.149.100) | hosted-by.pfcloud.io | Salesforce Salesloft Drift | High
4 | [179.43.159.198](https://vuldb.com/?ip.179.43.159.198) | hostedby.privatelayer.com | Salesforce Salesloft Drift | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UNC6395_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UNC6395. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/account.php` | Medium
4 | File | `/account.php?q=quiz&step=2` | High
5 | File | `/add-pig.php` | Medium
6 | File | `/add-product.php` | High
7 | File | `/add-subadmin.php` | High
8 | File | `/addCatController.php` | High
9 | File | `/addelidetails.php` | High
10 | File | `/add_achievement_details.php` | High
11 | File | `/add_personal_details.php` | High
12 | File | `/add_user.php` | High
13 | File | `/admin.php?mod=brand&act=del` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/add-customer-services.php` | High
16 | File | `/admin/add-property.php` | High
17 | File | `/admin/add-propertytype.php` | High
18 | File | `/admin/addclinic.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/admin_action.php` | High
21 | File | `/admin/admin_login.php` | High
22 | File | `/admin/admin_running.php` | High
23 | File | `/admin/ajax.php?action=login` | High
24 | File | `/admin/all_users.php` | High
25 | File | `/admin/app/asset_crud.php` | High
26 | File | `/admin/article.php` | High
27 | File | `/admin/article.php?action=upload_cover` | High
28 | File | `/admin/attendance_action.php` | High
29 | File | `/admin/auto-taxi-entry-detail.php` | High
30 | File | `/admin/ballot_down.php` | High
31 | File | `/admin/bwdates-reports-details.php` | High
32 | File | `/admin/categories/update` | High
33 | File | `/admin/category.php` | High
34 | File | `/admin/chatroom.php` | High
35 | File | `/admin/confirm.php` | High
36 | File | `/admin/contactus.php` | High
37 | File | `/admin/content/book` | High
38 | File | `/admin/content/editor` | High
39 | File | `/admin/course_action.php` | High
40 | File | `/admin/delete-session.php` | High
41 | File | `/admin/deleteBooking.php` | High
42 | File | `/admin/deletedoctorclinic.php` | High
43 | File | `/admin/delete_s6.php` | High
44 | File | `/admin/delete_user.php` | High
45 | File | `/admin/edit-category.php` | High
46 | File | `/admin/edit-propertytype.php` | High
47 | File | `/admin/edit-subcategory.php` | High
48 | File | `/admin/edit-subjects-detail.php` | High
49 | File | `/admin/edit-user.php` | High
50 | File | `/admin/edit_student_query.php` | High
51 | File | `/admin/faculty_action.php` | High
52 | File | `/admin/group/edit.do` | High
53 | File | `/admin/ImgUpdaPost.php` | High
54 | File | `/admin/index.php` | High
55 | File | `/admin/login.php` | High
56 | File | `/admin/manage_movie.php` | High
57 | File | `/admin/menus/view_menu.php` | High
58 | File | `/admin/newsletter.php` | High
59 | File | `/admin/plugin.php` | High
60 | File | `/admin/print.php` | High
61 | File | `/admin/profile.php` | High
62 | File | `/admin/property-details.php` | High
63 | File | `/admin/publishnews.php` | High
64 | File | `/admin/quote-details.php` | High
65 | File | `/admin/registration.php` | High
66 | File | `/admin/report.php` | High
67 | File | `/admin/search-booking-request.php` | High
68 | File | `/admin/search-maid.php` | High
69 | File | `/admin/search-property.php` | High
70 | File | `/admin/state.php` | High
71 | File | `/admin/store.php` | High
72 | File | `/admin/student_action.php` | High
73 | ... | ... | ...

There are 643 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloud.google.com/blog/topics/threat-intelligence/data-theft-salesforce-instances-via-salesloft-drift/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
