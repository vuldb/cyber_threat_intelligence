# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [DE](https://vuldb.com/?country.de)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/academic-calendar` | High
4 | File | `/account.php` | Medium
5 | File | `/account.php?q=quiz&step=2` | High
6 | File | `/add-pig.php` | Medium
7 | File | `/add-product.php` | High
8 | File | `/addCandidate.php` | High
9 | File | `/addCatController.php` | High
10 | File | `/addelidetails.php` | High
11 | File | `/adding-exec.php` | High
12 | File | `/add_achievement_details.php` | High
13 | File | `/add_personal_details.php` | High
14 | File | `/add_user.php` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/add-customer-services.php` | High
17 | File | `/admin/add-property.php` | High
18 | File | `/admin/add-propertytype.php` | High
19 | File | `/admin/add_student.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/admin_action.php` | High
22 | File | `/admin/admin_football.php` | High
23 | File | `/admin/ajax.php?action=login` | High
24 | File | `/admin/all_users.php` | High
25 | File | `/admin/app/profile_crud.php` | High
26 | File | `/admin/article.php` | High
27 | File | `/admin/article.php?action=upload_cover` | High
28 | File | `/admin/auto-taxi-entry-detail.php` | High
29 | File | `/admin/ballot_down.php` | High
30 | File | `/admin/bookdate.php` | High
31 | File | `/admin/booktime.php` | High
32 | File | `/admin/categories/update` | High
33 | File | `/admin/category.php` | High
34 | File | `/admin/changeimage.php` | High
35 | File | `/Admin/changepassword.php` | High
36 | File | `/admin/chatroom.php` | High
37 | File | `/admin/confirm.php` | High
38 | File | `/admin/contactus.php` | High
39 | File | `/admin/content/book` | High
40 | File | `/admin/content/editor` | High
41 | File | `/admin/course_action.php` | High
42 | File | `/admin/create_product.php` | High
43 | File | `/admin/deletedoctorclinic.php` | High
44 | File | `/admin/deleteitem.php` | High
45 | File | `/admin/delete_file.php` | High
46 | File | `/admin/edit-category.php` | High
47 | File | `/admin/edit-course.php` | High
48 | File | `/admin/edit-propertytype.php` | High
49 | File | `/admin/edit-subcategory.php` | High
50 | File | `/admin/edit-subjects-detail.php` | High
51 | File | `/admin/edit-user.php` | High
52 | File | `/admin/edit.php` | High
53 | File | `/admin/editorder.php` | High
54 | File | `/admin/edit_admin_query.php` | High
55 | File | `/admin/edit_members.php` | High
56 | File | `/admin/edit_student_query.php` | High
57 | File | `/admin/employee/index.php?view=edit` | High
58 | File | `/admin/faculty_action.php` | High
59 | File | `/admin/group/edit.do` | High
60 | File | `/admin/images/add` | High
61 | File | `/admin/index.php` | High
62 | File | `/admin/link.php` | High
63 | File | `/admin/login.php` | High
64 | File | `/admin/menus/view_menu.php` | High
65 | File | `/admin/newsletter.php` | High
66 | File | `/admin/operation/user.php` | High
67 | File | `/admin/operations/expense.php` | High
68 | File | `/admin/Operations/Role.php` | High
69 | File | `/admin/pagerole.php&action=edit` | High
70 | File | `/admin/plugin.php` | High
71 | File | `/admin/print.php` | High
72 | File | `/admin/print1.php` | High
73 | File | `/admin/profile.php` | High
74 | File | `/admin/property-details.php` | High
75 | File | `/admin/publishnews.php` | High
76 | File | `/admin/registration.php` | High
77 | File | `/admin/report.php` | High
78 | File | `/admin/rooms.php` | High
79 | File | `/admin/search-maid.php` | High
80 | File | `/admin/search-property.php` | High
81 | File | `/admin/state.php` | High
82 | File | `/admin/storage/delete` | High
83 | File | `/admin/store.php` | High
84 | File | `/admin/student_action.php` | High
85 | File | `/admin/tag.php` | High
86 | File | `/admin/updateorder.php` | High
87 | File | `/admin/updatestudent.php` | High
88 | File | `/admin/update_room.php` | High
89 | File | `/admin/update_user.php` | High
90 | ... | ... | ...

There are 796 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
