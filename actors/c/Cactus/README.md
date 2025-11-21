# Cactus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cactus](https://vuldb.com/?actor.cactus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cactus](https://vuldb.com/?actor.cactus)

## Campaigns

The following _campaigns_ are known and can be associated with Cactus:

* CVE-2023-38035
* CVE-2023-41266 / CVE-2023-41265 / CVE-2023-48365
* CVE-2023–38035

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cactus:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cactus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.227.203.210](https://vuldb.com/?ip.23.227.203.210) | 23-227-203-210.static.hvvc.us | - | High
2 | [45.61.136.79](https://vuldb.com/?ip.45.61.136.79) | - | CVE-2023-38035 | High
3 | [45.61.136.127](https://vuldb.com/?ip.45.61.136.127) | - | CVE-2023-38035 | High
4 | [45.61.137.65](https://vuldb.com/?ip.45.61.137.65) | - | - | High
5 | [45.61.138.99](https://vuldb.com/?ip.45.61.138.99) | - | CVE-2023-38035 | High
6 | [45.61.147.176](https://vuldb.com/?ip.45.61.147.176) | - | - | High
7 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cactus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cactus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/account.php` | Medium
4 | File | `/account.php?q=quiz&step=2` | High
5 | File | `/add-pig.php` | Medium
6 | File | `/add-product.php` | High
7 | File | `/addCatController.php` | High
8 | File | `/addelidetails.php` | High
9 | File | `/adding-exec.php` | High
10 | File | `/add_achievement_details.php` | High
11 | File | `/add_personal_details.php` | High
12 | File | `/add_user.php` | High
13 | File | `/admin-cp/theme/editor/default` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/add-customer-services.php` | High
16 | File | `/admin/add-property.php` | High
17 | File | `/admin/add-propertytype.php` | High
18 | File | `/admin/add_student.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/admin_action.php` | High
21 | File | `/admin/ajax.php?action=login` | High
22 | File | `/admin/all_users.php` | High
23 | File | `/admin/app/profile_crud.php` | High
24 | File | `/admin/article.php` | High
25 | File | `/admin/article.php?action=upload_cover` | High
26 | File | `/admin/attendance_action.php` | High
27 | File | `/admin/auto-taxi-entry-detail.php` | High
28 | File | `/admin/ballot_down.php` | High
29 | File | `/admin/categories/update` | High
30 | File | `/admin/category.php` | High
31 | File | `/admin/changeimage.php` | High
32 | File | `/admin/chatroom.php` | High
33 | File | `/admin/check_admin_login.php` | High
34 | File | `/admin/conferences/list/` | High
35 | File | `/admin/confirm.php` | High
36 | File | `/admin/contactus.php` | High
37 | File | `/admin/content/book` | High
38 | File | `/admin/content/editor` | High
39 | File | `/admin/course_action.php` | High
40 | File | `/admin/create_product.php` | High
41 | File | `/admin/deletedoctorclinic.php` | High
42 | File | `/admin/delete_file.php` | High
43 | File | `/admin/edit-category.php` | High
44 | File | `/admin/edit-propertytype.php` | High
45 | File | `/admin/edit-subjects-detail.php` | High
46 | File | `/admin/edit-user.php` | High
47 | File | `/admin/edit.php` | High
48 | File | `/admin/editorder.php` | High
49 | File | `/admin/edit_members.php` | High
50 | File | `/admin/edit_student_query.php` | High
51 | File | `/admin/employee/index.php?view=edit` | High
52 | File | `/admin/faculty_action.php` | High
53 | File | `/admin/group/edit.do` | High
54 | File | `/admin/index.php` | High
55 | File | `/admin/link.php` | High
56 | File | `/admin/login.php` | High
57 | File | `/admin/menus/view_menu.php` | High
58 | File | `/admin/newsletter.php` | High
59 | File | `/admin/operations/expense.php` | High
60 | File | `/admin/Operations/Role.php` | High
61 | File | `/admin/plugin.php` | High
62 | File | `/admin/print.php` | High
63 | File | `/admin/print1.php` | High
64 | File | `/admin/profile.php` | High
65 | File | `/admin/property-details.php` | High
66 | File | `/admin/publishnews.php` | High
67 | File | `/admin/registration.php` | High
68 | File | `/admin/report.php` | High
69 | File | `/admin/rooms.php` | High
70 | File | `/admin/search-maid.php` | High
71 | File | `/admin/search-property.php` | High
72 | File | `/admin/state.php` | High
73 | File | `/admin/storage/delete` | High
74 | File | `/admin/store.php` | High
75 | File | `/admin/student_action.php` | High
76 | File | `/admin/tag.php` | High
77 | File | `/admin/tag/save` | High
78 | File | `/admin/updateorder.php` | High
79 | File | `/admin/updatestudent.php` | High
80 | File | `/admin/update_room.php` | High
81 | ... | ... | ...

There are 710 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/introducing-toymaker-an-initial-access-broker/
* https://northwave-cybersecurity.com/whitepapers-articles/pricksense-how-cactus-exploits-qlik-sense
* https://www.arcticwolf.com/resources/blog/qlik-sense-exploited-in-cactus-ransomware-campaign/
* https://www.bitdefender.com/blog/businessinsights/cactus-analyzing-a-coordinated-ransomware-attack-on-corporate-networks/
* https://www.trellix.com/blogs/research/cactus-ransomware-new-strain-in-the-market/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
