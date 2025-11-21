# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/?import` | Medium
4 | File | `/account.php` | Medium
5 | File | `/account.php?q=quiz&step=2` | High
6 | File | `/add-normal-ticket.php` | High
7 | File | `/add-pig.php` | Medium
8 | File | `/add-product.php` | High
9 | File | `/add.php` | Medium
10 | File | `/addCatController.php` | High
11 | File | `/addelidetails.php` | High
12 | File | `/adding-exec.php` | High
13 | File | `/addpayment.php` | High
14 | File | `/add_achievement_details.php` | High
15 | File | `/add_personal_details.php` | High
16 | File | `/add_user.php` | High
17 | File | `/admin#themes` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-customer-services.php` | High
20 | File | `/admin/add-property.php` | High
21 | File | `/admin/add-propertytype.php` | High
22 | File | `/admin/add-services.php` | High
23 | File | `/admin/add_student.php` | High
24 | File | `/admin/admin-profile.php` | High
25 | File | `/admin/admin_action.php` | High
26 | File | `/admin/ajax.php?action=login` | High
27 | File | `/admin/all_users.php` | High
28 | File | `/admin/app/profile_crud.php` | High
29 | File | `/admin/article.php?action=upload_cover` | High
30 | File | `/admin/auto-taxi-entry-detail.php` | High
31 | File | `/admin/ballot_down.php` | High
32 | File | `/admin/categories/update` | High
33 | File | `/admin/category.php` | High
34 | File | `/admin/category_save.php` | High
35 | File | `/admin/changeimage.php` | High
36 | File | `/admin/chatroom.php` | High
37 | File | `/admin/check_admin_login.php` | High
38 | File | `/admin/conferences/list/` | High
39 | File | `/admin/confirm.php` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/content/book` | High
42 | File | `/admin/content/editor` | High
43 | File | `/admin/core/new_user` | High
44 | File | `/admin/course_action.php` | High
45 | File | `/admin/deletedoctorclinic.php` | High
46 | File | `/admin/delete_file.php` | High
47 | File | `/admin/edit-category.php` | High
48 | File | `/admin/edit-customer-detailed.php` | High
49 | File | `/admin/edit-guard-detail.php` | High
50 | File | `/admin/edit-propertytype.php` | High
51 | File | `/admin/edit-subjects-detail.php` | High
52 | File | `/admin/edit-user.php` | High
53 | File | `/admin/edit.php` | High
54 | File | `/admin/editorder.php` | High
55 | File | `/admin/edit_members.php` | High
56 | File | `/admin/edit_student_query.php` | High
57 | File | `/admin/eligibility.php` | High
58 | File | `/admin/employee/index.php?view=edit` | High
59 | File | `/admin/faculty_action.php` | High
60 | File | `/admin/group/edit.do` | High
61 | File | `/admin/index.php` | High
62 | File | `/admin/index.php?language=en&nv=upload` | High
63 | File | `/admin/link.php` | High
64 | File | `/admin/login.php` | High
65 | File | `/admin/member_save.php` | High
66 | File | `/admin/menus/view_menu.php` | High
67 | File | `/admin/newsletter.php` | High
68 | File | `/admin/operations/expense.php` | High
69 | File | `/admin/Operations/Role.php` | High
70 | File | `/admin/pages_account.php` | High
71 | File | `/admin/payment_save.php` | High
72 | File | `/admin/plugin.php` | High
73 | File | `/admin/print.php` | High
74 | File | `/admin/print1.php` | High
75 | File | `/admin/profile.php` | High
76 | File | `/admin/property-details.php` | High
77 | File | `/admin/publishnews.php` | High
78 | File | `/admin/registration.php` | High
79 | File | `/admin/room.php` | High
80 | File | `/admin/rooms.php` | High
81 | File | `/admin/search-maid.php` | High
82 | File | `/admin/search-property.php` | High
83 | File | `/admin/state.php` | High
84 | File | `/admin/storage/delete` | High
85 | File | `/admin/store.php` | High
86 | File | `/admin/student_action.php` | High
87 | File | `/admin/system.php` | High
88 | File | `/admin/tag.php` | High
89 | File | `/admin/tag/save` | High
90 | File | `/admin/team_update.php` | High
91 | File | `/admin/updateorder.php` | High
92 | File | `/admin/updatestudent.php` | High
93 | File | `/admin/update_room.php` | High
94 | File | `/admin/update_user.php` | High
95 | File | `/admin/update_users.php` | High
96 | File | `/admin/user.php` | High
97 | File | `/admin/user/edit.do` | High
98 | File | `/admin/users.php` | High
99 | File | `/admin/vacancy/index.php` | High
100 | ... | ... | ...

There are 884 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
