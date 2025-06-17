# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Snake_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 1 more country items available. Please use our online service to access the data.

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
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/?page=reports` | High
4 | File | `/aboutadd.php` | High
5 | File | `/aboutedit.php` | High
6 | File | `/abs.php` | Medium
7 | File | `/account.php` | Medium
8 | File | `/account.php?q=quiz&step=2` | High
9 | File | `/activation.php` | High
10 | File | `/add-pig.php` | Medium
11 | File | `/add.php` | Medium
12 | File | `/addCatController.php` | High
13 | File | `/addcustcom.php` | High
14 | File | `/add_achievement_details.php` | High
15 | File | `/add_new_purchase.php?action=is_supplier` | High
16 | File | `/add_personal_details.php` | High
17 | File | `/add_user.php` | High
18 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
19 | File | `/admin/about-us.php` | High
20 | File | `/admin/aboutus.php` | High
21 | File | `/admin/add-customer-services.php` | High
22 | File | `/admin/add-customer.php` | High
23 | File | `/admin/add-doctor.php` | High
24 | File | `/admin/add-property.php` | High
25 | File | `/admin/add-propertytype.php` | High
26 | File | `/admin/add-services.php` | High
27 | File | `/admin/admin-profile.php` | High
28 | File | `/Admin/adminlogin.php` | High
29 | File | `/admin/admin_action.php` | High
30 | File | `/admin/ajax.php?action=login` | High
31 | File | `/admin/all_users.php` | High
32 | File | `/admin/article.php?action=upload_cover` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
34 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
35 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
36 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
37 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
38 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
39 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
40 | File | `/admin/blood/update/B-.php` | High
41 | File | `/admin/book-details.php` | High
42 | File | `/admin/bwdates-report-details.php` | High
43 | File | `/admin/categories/update` | High
44 | File | `/admin/category.php` | High
45 | File | `/admin/chatroom.php` | High
46 | File | `/admin/check_admin_login.php` | High
47 | File | `/admin/cmsTagType/save` | High
48 | File | `/admin/contactus.php` | High
49 | File | `/admin/content/book` | High
50 | File | `/admin/content/editor` | High
51 | File | `/admin/course_action.php` | High
52 | File | `/Admin/detail.php` | High
53 | File | `/admin/edit-brand.php` | High
54 | File | `/admin/edit-card-detail.php` | High
55 | File | `/admin/edit-category.php` | High
56 | File | `/admin/edit-customer-detailed.php` | High
57 | File | `/admin/edit-propertytype.php` | High
58 | File | `/admin/edit-services.php` | High
59 | File | `/admin/edit-user.php` | High
60 | File | `/admin/editorder.php` | High
61 | File | `/admin/edit_fuel.php` | High
62 | File | `/admin/faculty_action.php` | High
63 | File | `/admin/home.php` | High
64 | File | `/admin/index.php` | High
65 | File | `/admin/link.php` | High
66 | File | `/admin/login.php` | High
67 | File | `/admin/login_process.php` | High
68 | File | `/admin/massage.php` | High
69 | File | `/admin/network/ajax_getChannelList` | High
70 | File | `/admin/network/diag_nslookup` | High
71 | File | `/admin/network/diag_ping6` | High
72 | File | `/admin/network/diag_pinginterface` | High
73 | File | `/admin/network/diag_traceroute` | High
74 | File | `/admin/network/diag_traceroute6` | High
75 | File | `/admin/network/wifi_schedule` | High
76 | File | `/admin/newsletter.php` | High
77 | File | `/admin/overtime_add.php` | High
78 | File | `/admin/overtime_row.php` | High
79 | File | `/admin/plugin.php` | High
80 | File | `/admin/print.php` | High
81 | File | `/admin/profile.php` | High
82 | File | `/admin/property-details.php` | High
83 | File | `/admin/publishnews.php` | High
84 | File | `/admin/registration.php` | High
85 | File | `/admin/room.php` | High
86 | File | `/admin/search-appointment.php` | High
87 | File | `/admin/search-maid.php` | High
88 | File | `/admin/search-medicalcard.php` | High
89 | File | `/admin/search-property.php` | High
90 | File | `/admin/search-vehicle.php` | High
91 | File | `/admin/services/view_service.php` | High
92 | File | `/admin/sn_package/sn_https` | High
93 | File | `/admin/state.php` | High
94 | File | `/admin/store.php` | High
95 | File | `/admin/student_action.php` | High
96 | File | `/admin/tag.php` | High
97 | File | `/admin/tag/save` | High
98 | File | `/admin/update_room.php` | High
99 | ... | ... | ...

There are 878 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
