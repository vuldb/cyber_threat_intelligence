# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | - | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | - | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | Snake | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snake_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 12 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/aboutadd.php` | High
4 | File | `/aboutedit.php` | High
5 | File | `/abs.php` | Medium
6 | File | `/account.php` | Medium
7 | File | `/account.php?q=quiz&step=2` | High
8 | File | `/activation.php` | High
9 | File | `/add-pig.php` | Medium
10 | File | `/add.php` | Medium
11 | File | `/addCatController.php` | High
12 | File | `/add_achievement_details.php` | High
13 | File | `/add_new_purchase.php?action=is_supplier` | High
14 | File | `/add_personal_details.php` | High
15 | File | `/add_user.php` | High
16 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-customer-services.php` | High
20 | File | `/admin/add-customer.php` | High
21 | File | `/admin/add-doctor.php` | High
22 | File | `/admin/add-property.php` | High
23 | File | `/admin/add-propertytype.php` | High
24 | File | `/admin/add-services.php` | High
25 | File | `/admin/admin-profile.php` | High
26 | File | `/Admin/adminlogin.php` | High
27 | File | `/admin/admin_action.php` | High
28 | File | `/admin/ajax.php?action=login` | High
29 | File | `/admin/all_users.php` | High
30 | File | `/admin/article.php?action=upload_cover` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
34 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
35 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
36 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
37 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
38 | File | `/admin/blood/update/B-.php` | High
39 | File | `/admin/book-details.php` | High
40 | File | `/admin/bwdates-report-details.php` | High
41 | File | `/admin/categories/update` | High
42 | File | `/admin/category.php` | High
43 | File | `/admin/chatroom.php` | High
44 | File | `/admin/check_admin_login.php` | High
45 | File | `/admin/cmsTagType/save` | High
46 | File | `/admin/contactus.php` | High
47 | File | `/admin/content/book` | High
48 | File | `/admin/content/editor` | High
49 | File | `/admin/course_action.php` | High
50 | File | `/Admin/detail.php` | High
51 | File | `/admin/edit-brand.php` | High
52 | File | `/admin/edit-card-detail.php` | High
53 | File | `/admin/edit-category.php` | High
54 | File | `/admin/edit-customer-detailed.php` | High
55 | File | `/admin/edit-propertytype.php` | High
56 | File | `/admin/edit-services.php` | High
57 | File | `/admin/edit-user.php` | High
58 | File | `/admin/editorder.php` | High
59 | File | `/admin/edit_fuel.php` | High
60 | File | `/admin/faculty_action.php` | High
61 | File | `/admin/home.php` | High
62 | File | `/admin/index.php` | High
63 | File | `/admin/link.php` | High
64 | File | `/admin/login.php` | High
65 | File | `/admin/login_process.php` | High
66 | File | `/admin/massage.php` | High
67 | File | `/admin/network/ajax_getChannelList` | High
68 | File | `/admin/network/diag_nslookup` | High
69 | File | `/admin/network/diag_ping6` | High
70 | File | `/admin/network/diag_pinginterface` | High
71 | File | `/admin/network/diag_traceroute` | High
72 | File | `/admin/network/diag_traceroute6` | High
73 | File | `/admin/network/wifi_schedule` | High
74 | File | `/admin/newsletter.php` | High
75 | File | `/admin/overtime_add.php` | High
76 | File | `/admin/overtime_row.php` | High
77 | File | `/admin/plugin.php` | High
78 | File | `/admin/print.php` | High
79 | File | `/admin/profile.php` | High
80 | File | `/admin/property-details.php` | High
81 | File | `/admin/publishnews.php` | High
82 | File | `/admin/registration.php` | High
83 | File | `/admin/room.php` | High
84 | File | `/admin/search-appointment.php` | High
85 | File | `/admin/search-maid.php` | High
86 | File | `/admin/search-medicalcard.php` | High
87 | File | `/admin/search-property.php` | High
88 | File | `/admin/search-vehicle.php` | High
89 | File | `/admin/services/view_service.php` | High
90 | File | `/admin/sn_package/sn_https` | High
91 | File | `/admin/state.php` | High
92 | File | `/admin/store.php` | High
93 | File | `/admin/student_action.php` | High
94 | File | `/admin/tag.php` | High
95 | File | `/admin/tag/save` | High
96 | File | `/admin/update_room.php` | High
97 | File | `/admin/update_user.php` | High
98 | File | `/admin/update_users.php` | High
99 | ... | ... | ...

There are 876 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://urlhaus.abuse.ch/url/3543270/
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
