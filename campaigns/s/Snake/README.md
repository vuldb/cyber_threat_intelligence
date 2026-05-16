# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Snake_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Snake or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Snake](https://vuldb.com/?actor.snake) | High
2 | [Snake Keylogger](https://vuldb.com/?actor.snake_keylogger) | High
3 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | [Snake](https://vuldb.com/?actor.snake) | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | [Snake](https://vuldb.com/?actor.snake) | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | [Snake](https://vuldb.com/?actor.snake) | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | [Snake](https://vuldb.com/?actor.snake) | High
5 | [31.170.164.249](https://vuldb.com/?ip.31.170.164.249) | ns4.hostinger.com | [Snake](https://vuldb.com/?actor.snake) | High
6 | [34.122.197.93](https://vuldb.com/?ip.34.122.197.93) | 93.197.122.34.bc.googleusercontent.com | [Snake](https://vuldb.com/?actor.snake) | Medium
7 | [37.75.10.148](https://vuldb.com/?ip.37.75.10.148) | mail.datamerkezi.com | [Snake](https://vuldb.com/?actor.snake) | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
4 | File | `/academic-calendar` | High
5 | File | `/add-normal-ticket.php` | High
6 | File | `/add-pig.php` | Medium
7 | File | `/add-product.php` | High
8 | File | `/addelidetails.php` | High
9 | File | `/adding-exec.php` | High
10 | File | `/add_user.php` | High
11 | File | `/adm/index.php` | High
12 | File | `/admin.php/addon/index` | High
13 | File | `/admin.php?mod=brand&act=del` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/add-ambulance.php` | High
16 | File | `/admin/add-art-product.php` | High
17 | File | `/admin/add-artist.php` | High
18 | File | `/admin/add-customer-services.php` | High
19 | File | `/admin/add-property.php` | High
20 | File | `/admin/add-propertytype.php` | High
21 | File | `/admin/addroom.php` | High
22 | File | `/admin/add_student.php` | High
23 | File | `/admin/admin-profile.php` | High
24 | File | `/admin/admin_football.php` | High
25 | File | `/admin/ajax.php?action=login` | High
26 | File | `/admin/all_users.php` | High
27 | File | `/admin/app/profile_crud.php` | High
28 | File | `/admin/article.php?action=upload_cover` | High
29 | File | `/admin/assign_save.php` | High
30 | File | `/admin/attachment/download` | High
31 | File | `/admin/attendance_row.php` | High
32 | File | `/admin/auto-taxi-entry-detail.php` | High
33 | File | `/admin/ballot_down.php` | High
34 | File | `/admin/blog/comment/create` | High
35 | File | `/admin/bookdate.php` | High
36 | File | `/admin/booktime.php` | High
37 | File | `/admin/candidates_add.php` | High
38 | File | `/admin/candidates_delete.php` | High
39 | File | `/admin/categories/update` | High
40 | File | `/admin/changeimage.php` | High
41 | File | `/Admin/changepassword.php` | High
42 | File | `/admin/chatroom.php` | High
43 | File | `/admin/complaint-search.php` | High
44 | File | `/admin/confirm.php` | High
45 | File | `/admin/contactus.php` | High
46 | File | `/admin/content/book` | High
47 | File | `/admin/content/editor` | High
48 | File | `/admin/course.php` | High
49 | File | `/admin/deletedoctorclinic.php` | High
50 | File | `/admin/deleteitem.php` | High
51 | File | `/admin/delete_file.php` | High
52 | File | `/admin/doctor-specilization.php` | High
53 | File | `/admin/edit-admin.php` | High
54 | File | `/admin/edit-category.php` | High
55 | File | `/admin/edit-guard-detail.php` | High
56 | File | `/admin/edit-propertytype.php` | High
57 | File | `/admin/edit-subjects-detail.php` | High
58 | File | `/admin/edit.php` | High
59 | File | `/admin/edit_activity.php` | High
60 | File | `/admin/edit_admin_details.php?id=admin` | High
61 | File | `/admin/edit_admin_query.php` | High
62 | File | `/admin/edit_expenses_query.php` | High
63 | File | `/admin/edit_members.php` | High
64 | File | `/admin/edit_product.php` | High
65 | File | `/admin/edit_student_query.php` | High
66 | File | `/admin/employee/index.php?view=edit` | High
67 | File | `/admin/file/rename.do` | High
68 | File | `/admin/forget-password.php` | High
69 | File | `/admin/getmanagerregion.php` | High
70 | File | `/admin/group/edit.do` | High
71 | File | `/admin/images/add` | High
72 | File | `/admin/ImgUpdaPost.php` | High
73 | File | `/admin/index.php` | High
74 | File | `/admin/lab.php` | High
75 | File | `/admin/login-back.php` | High
76 | File | `/admin/login.php` | High
77 | File | `/admin/manage-notices.php` | High
78 | File | `/admin/manage-tickets.php` | High
79 | File | `/admin/manage_user.php` | High
80 | File | `/admin/member_save.php` | High
81 | File | `/admin/menus/view_menu.php` | High
82 | File | `/admin/new-autoortaxi-entry-form.php` | High
83 | File | `/admin/operation/user.php` | High
84 | File | `/admin/operations/expense.php` | High
85 | File | `/admin/Operations/Role.php` | High
86 | File | `/admin/payment_save.php` | High
87 | File | `/admin/print.php` | High
88 | File | `/admin/print1.php` | High
89 | File | `/admin/property-details.php` | High
90 | File | `/admin/publishnews.php` | High
91 | File | `/admin/redirect.php` | High
92 | File | `/admin/registration.php` | High
93 | File | `/admin/rooms.php` | High
94 | File | `/admin/search-directory.php` | High
95 | File | `/admin/search-invoices.php` | High
96 | File | `/admin/search-maid.php` | High
97 | File | `/admin/search-property.php` | High
98 | File | `/admin/storage/delete` | High
99 | File | `/admin/subject/controller.php` | High
100 | File | `/admin/suppliercontroller.php` | High
101 | File | `/admin/updateorder.php` | High
102 | File | `/admin/updatestudent.php` | High
103 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
104 | File | `/admin/update_room.php` | High
105 | File | `/admin/update_user.php` | High
106 | File | `/admin/update_users.php` | High
107 | File | `/admin/user.php` | High
108 | File | `/admin/user/edit.do` | High
109 | File | `/admin/users.php` | High
110 | File | `/admin/v1/blog/edit` | High
111 | File | `/admin/view-user-queries.php` | High
112 | File | `/admin/view_payorder.php` | High
113 | File | `/admin/voters_row.php` | High
114 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
115 | File | `/Administrator/PHP/AdminAddCategory.php` | High
116 | File | `/Administrator/PHP/AdminEditCategory.php` | High
117 | File | `/Administrator/PHP/AdminReply.php` | High
118 | File | `/administrator/weweee.php` | High
119 | ... | ... | ...

There are 1057 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://urlhaus.abuse.ch/url/3543270/
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.fortinet.com/blog/threat-research/deep-analysis-of-snake-keylogger-new-variant
* https://www.fortinet.com/blog/threat-research/fortisandbox-detects-evolving-snake-keylogger-variant
* https://www.malware-traffic-analysis.net/2024/09/16/index.html
* https://www.malware-traffic-analysis.net/2024/09/17/index.html
* https://www.seqrite.com/blog/snakekeylogger-a-multistage-info-stealer-malware-campaign/
* https://www.threat.rip/file/7efba5bdd57a190663d38a52ff71b525874b832cce859895adf688e9d5c41d7e/config
* https://www.threat.rip/file/8e0e366fbbec26e52239f27a9ca7ffa95b9edebc97f464484698a34b65b0930d/config
* https://www.threat.rip/file/26c564ff055b44c33b8392099102e63ea285e7b92c45c6205d5780b2033f34e4/config
* https://www.threat.rip/file/63e7fe8945be18dcd296c456a4a314d336c3c5c798d5c70066c02e7627861870/config
* https://www.threat.rip/file/167f1c3cdca7d2542e5e8dca0e24787aad4c8dd2ea3bee530d56075c278a3ed0/config
* https://www.threat.rip/file/b59169914f10a914d135c2617eaf75bf9a9eb3816b3d5eadc3f192d817f2698c/config
* https://www.threat.rip/file/c02c29e0bcd5b9f4110d716846c22e6797083be601b4c4af629b3804ce556d38/config
* https://www.threat.rip/file/d3a2900c5043cd6b59e01ddb534ce51b172738527b60430501845b1a42c9308f/config
* https://www.threat.rip/file/deb7046f73f0a4e2d1481e6dbc127af59f6ebdbaa003b852508dc6c612bf7f5f/config
* https://www.threat.rip/file/fda48b0a6caeff0d71c738ce394f6156d5394d02c0c4d45f54acd9ef57060728/config
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
