# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [IT](https://vuldb.com/?country.it)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
2 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
3 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
4 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
5 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
4 | File | `/academic-calendar` | High
5 | File | `/account.php` | Medium
6 | File | `/add-normal-ticket.php` | High
7 | File | `/add-pig.php` | Medium
8 | File | `/add-product.php` | High
9 | File | `/addCatController.php` | High
10 | File | `/addelidetails.php` | High
11 | File | `/adding-exec.php` | High
12 | File | `/add_achievement_details.php` | High
13 | File | `/add_personal_details.php` | High
14 | File | `/add_user.php` | High
15 | File | `/adm/index.php` | High
16 | File | `/admin.php?mod=brand&act=del` | High
17 | File | `/admin/aboutus.php` | High
18 | File | `/admin/add-ambulance.php` | High
19 | File | `/admin/add-art-product.php` | High
20 | File | `/admin/add-artist.php` | High
21 | File | `/admin/add-customer-services.php` | High
22 | File | `/admin/add-property.php` | High
23 | File | `/admin/add-propertytype.php` | High
24 | File | `/admin/add_student.php` | High
25 | File | `/admin/admin-profile.php` | High
26 | File | `/admin/admin_action.php` | High
27 | File | `/admin/admin_football.php` | High
28 | File | `/admin/ajax.php?action=login` | High
29 | File | `/admin/all_users.php` | High
30 | File | `/admin/app/profile_crud.php` | High
31 | File | `/admin/article.php` | High
32 | File | `/admin/article.php?action=upload_cover` | High
33 | File | `/admin/auto-taxi-entry-detail.php` | High
34 | File | `/admin/ballot_down.php` | High
35 | File | `/admin/bookdate.php` | High
36 | File | `/admin/booktime.php` | High
37 | File | `/admin/candidates_add.php` | High
38 | File | `/admin/categories/update` | High
39 | File | `/admin/category.php` | High
40 | File | `/admin/changeimage.php` | High
41 | File | `/Admin/changepassword.php` | High
42 | File | `/admin/chatroom.php` | High
43 | File | `/admin/confirm.php` | High
44 | File | `/admin/contactus.php` | High
45 | File | `/admin/content/book` | High
46 | File | `/admin/content/editor` | High
47 | File | `/admin/course.php` | High
48 | File | `/admin/create_product.php` | High
49 | File | `/admin/delete-session.php` | High
50 | File | `/admin/deletedoctorclinic.php` | High
51 | File | `/admin/deleteitem.php` | High
52 | File | `/admin/delete_file.php` | High
53 | File | `/admin/doctor-specilization.php` | High
54 | File | `/admin/edit-admin.php` | High
55 | File | `/admin/edit-category.php` | High
56 | File | `/admin/edit-guard-detail.php` | High
57 | File | `/admin/edit-propertytype.php` | High
58 | File | `/admin/edit-subjects-detail.php` | High
59 | File | `/admin/edit-user.php` | High
60 | File | `/admin/edit.php` | High
61 | File | `/admin/edit_admin_details.php?id=admin` | High
62 | File | `/admin/edit_admin_query.php` | High
63 | File | `/admin/edit_expenses_query.php` | High
64 | File | `/admin/edit_members.php` | High
65 | File | `/admin/edit_student_query.php` | High
66 | File | `/admin/employee/index.php?view=edit` | High
67 | File | `/admin/forget-password.php` | High
68 | File | `/admin/group/edit.do` | High
69 | File | `/admin/images/add` | High
70 | File | `/admin/ImgUpdaPost.php` | High
71 | File | `/admin/index.php` | High
72 | File | `/admin/lab.php` | High
73 | File | `/admin/login-back.php` | High
74 | File | `/admin/login.php` | High
75 | File | `/admin/manage-notices.php` | High
76 | File | `/admin/manage-tickets.php` | High
77 | File | `/admin/member_save.php` | High
78 | File | `/admin/menus/view_menu.php` | High
79 | File | `/admin/newsletter.php` | High
80 | File | `/admin/operation/user.php` | High
81 | File | `/admin/operations/expense.php` | High
82 | File | `/admin/Operations/Role.php` | High
83 | File | `/admin/print.php` | High
84 | File | `/admin/print1.php` | High
85 | File | `/admin/profile.php` | High
86 | File | `/admin/property-details.php` | High
87 | File | `/admin/publishnews.php` | High
88 | File | `/admin/registration.php` | High
89 | File | `/admin/report.php` | High
90 | File | `/admin/rooms.php` | High
91 | File | `/admin/search-directory.php` | High
92 | File | `/admin/search-invoices.php` | High
93 | File | `/admin/search-maid.php` | High
94 | File | `/admin/search-property.php` | High
95 | File | `/admin/state.php` | High
96 | File | `/admin/storage/delete` | High
97 | File | `/admin/student_action.php` | High
98 | File | `/admin/suppliercontroller.php` | High
99 | File | `/admin/updateorder.php` | High
100 | File | `/admin/updatestudent.php` | High
101 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
102 | File | `/admin/update_room.php` | High
103 | File | `/admin/update_user.php` | High
104 | File | `/admin/update_users.php` | High
105 | File | `/admin/user.php` | High
106 | File | `/admin/user/edit.do` | High
107 | File | `/admin/users.php` | High
108 | File | `/admin/v1/blog/edit` | High
109 | ... | ... | ...

There are 967 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.bleepingcomputer.com/news/security/medusalocker-ransomware-wants-its-share-of-your-money/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
