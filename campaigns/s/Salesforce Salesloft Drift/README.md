# Salesforce Salesloft Drift - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Salesforce Salesloft Drift_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Salesforce Salesloft Drift:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [DE](https://vuldb.com/?country.de)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Salesforce Salesloft Drift or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [UNC6395](https://vuldb.com/?actor.unc6395) | High
2 | [GRUB1](https://vuldb.com/?actor.grub1) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Salesforce Salesloft Drift.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [44.215.108.109](https://vuldb.com/?ip.44.215.108.109) | ec2-44-215-108-109.compute-1.amazonaws.com | [UNC6395](https://vuldb.com/?actor.unc6395) | Medium
2 | [154.41.95.2](https://vuldb.com/?ip.154.41.95.2) | - | [UNC6395](https://vuldb.com/?actor.unc6395) | High
3 | [176.65.149.100](https://vuldb.com/?ip.176.65.149.100) | hosted-by.pfcloud.io | [UNC6395](https://vuldb.com/?actor.unc6395) | High
4 | [179.43.159.198](https://vuldb.com/?ip.179.43.159.198) | hostedby.privatelayer.com | [UNC6395](https://vuldb.com/?actor.unc6395) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Salesforce Salesloft Drift. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Salesforce Salesloft Drift. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/add-pig.php` | Medium
4 | File | `/add-product.php` | High
5 | File | `/add-subadmin.php` | High
6 | File | `/addelidetails.php` | High
7 | File | `/adding-exec.php` | High
8 | File | `/add_achievement_details.php` | High
9 | File | `/add_user.php` | High
10 | File | `/admin.php?mod=brand&act=del` | High
11 | File | `/admin/aboutus.php` | High
12 | File | `/admin/add-customer-services.php` | High
13 | File | `/admin/add-property.php` | High
14 | File | `/admin/add-propertytype.php` | High
15 | File | `/admin/add-table.php` | High
16 | File | `/admin/addclinic.php` | High
17 | File | `/admin/add_student.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/admin_running.php` | High
20 | File | `/admin/ajax.php?action=login` | High
21 | File | `/admin/all_users.php` | High
22 | File | `/admin/app/asset_crud.php` | High
23 | File | `/admin/app/profile_crud.php` | High
24 | File | `/admin/article.php` | High
25 | File | `/admin/article.php?action=upload_cover` | High
26 | File | `/admin/attendance_action.php` | High
27 | File | `/admin/auto-taxi-entry-detail.php` | High
28 | File | `/admin/ballot_down.php` | High
29 | File | `/admin/bwdates-reports-details.php` | High
30 | File | `/admin/categories/update` | High
31 | File | `/admin/category.php` | High
32 | File | `/admin/changeimage.php` | High
33 | File | `/admin/chatroom.php` | High
34 | File | `/admin/confirm.php` | High
35 | File | `/admin/contactus.php` | High
36 | File | `/admin/content/book` | High
37 | File | `/admin/content/editor` | High
38 | File | `/admin/delete-session.php` | High
39 | File | `/admin/deleteBooking.php` | High
40 | File | `/admin/deletedoctorclinic.php` | High
41 | File | `/admin/delete_file.php` | High
42 | File | `/admin/delete_s6.php` | High
43 | File | `/admin/delete_user.php` | High
44 | File | `/admin/edit-category.php` | High
45 | File | `/admin/edit-propertytype.php` | High
46 | File | `/admin/edit-subcategory.php` | High
47 | File | `/admin/edit-subjects-detail.php` | High
48 | File | `/admin/edit-user.php` | High
49 | File | `/admin/edit.php` | High
50 | File | `/admin/edit_members.php` | High
51 | File | `/admin/edit_student_query.php` | High
52 | File | `/admin/employee/index.php?view=edit` | High
53 | File | `/admin/group/edit.do` | High
54 | File | `/admin/ImgUpdaPost.php` | High
55 | File | `/admin/index.php` | High
56 | File | `/admin/login.php` | High
57 | File | `/Admin/login.php` | High
58 | File | `/admin/manage_movie.php` | High
59 | File | `/admin/mechanics/manage_mechanic.php` | High
60 | File | `/admin/menus/view_menu.php` | High
61 | File | `/admin/modules/room/index.php` | High
62 | File | `/admin/newsletter.php` | High
63 | File | `/admin/operations/expense.php` | High
64 | File | `/admin/Operations/Role.php` | High
65 | File | `/admin/print.php` | High
66 | File | `/admin/print1.php` | High
67 | File | `/admin/profile.php` | High
68 | File | `/admin/profit_report.php` | High
69 | File | `/admin/property-details.php` | High
70 | File | `/admin/publishnews.php` | High
71 | File | `/admin/quote-details.php` | High
72 | File | `/admin/registration.php` | High
73 | File | `/admin/report.php` | High
74 | File | `/admin/rooms.php` | High
75 | File | `/admin/search-booking-request.php` | High
76 | File | `/admin/search-maid.php` | High
77 | File | `/admin/search-property.php` | High
78 | File | `/admin/state.php` | High
79 | File | `/admin/storage/delete` | High
80 | File | `/admin/tags/save` | High
81 | File | `/admin/twitter.php` | High
82 | File | `/admin/updateorder.php` | High
83 | File | `/admin/updatestudent.php` | High
84 | ... | ... | ...

There are 737 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.cloudflare.com/response-to-salesloft-drift-incident/
* https://cloud.google.com/blog/topics/threat-intelligence/data-theft-salesforce-instances-via-salesloft-drift/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
