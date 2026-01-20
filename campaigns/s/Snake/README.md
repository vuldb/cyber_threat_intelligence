# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Snake_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 11 more country items available. Please use our online service to access the data.

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
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/aboutadd.php` | High
4 | File | `/aboutedit.php` | High
5 | File | `/academic-calendar` | High
6 | File | `/account.php` | Medium
7 | File | `/account.php?q=quiz&step=2` | High
8 | File | `/activation.php` | High
9 | File | `/add-pig.php` | Medium
10 | File | `/add-product.php` | High
11 | File | `/add.php` | Medium
12 | File | `/addCatController.php` | High
13 | File | `/addelidetails.php` | High
14 | File | `/adding-exec.php` | High
15 | File | `/add_achievement_details.php` | High
16 | File | `/add_personal_details.php` | High
17 | File | `/add_user.php` | High
18 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
19 | File | `/admin/about-us.php` | High
20 | File | `/admin/aboutus.php` | High
21 | File | `/admin/add-customer-services.php` | High
22 | File | `/admin/add-customer.php` | High
23 | File | `/admin/add-property.php` | High
24 | File | `/admin/add-propertytype.php` | High
25 | File | `/admin/add-services.php` | High
26 | File | `/admin/add_student.php` | High
27 | File | `/admin/admin-profile.php` | High
28 | File | `/admin/admin_action.php` | High
29 | File | `/admin/ajax.php?action=login` | High
30 | File | `/admin/all_users.php` | High
31 | File | `/admin/app/profile_crud.php` | High
32 | File | `/admin/article.php?action=upload_cover` | High
33 | File | `/admin/auto-taxi-entry-detail.php` | High
34 | File | `/admin/ballot_down.php` | High
35 | File | `/admin/blog/comment/create` | High
36 | File | `/admin/bookdate.php` | High
37 | File | `/admin/booktime.php` | High
38 | File | `/admin/categories/update` | High
39 | File | `/admin/category.php` | High
40 | File | `/admin/changeimage.php` | High
41 | File | `/Admin/changepassword.php` | High
42 | File | `/admin/chatroom.php` | High
43 | File | `/admin/check_admin_login.php` | High
44 | File | `/admin/cmsTagType/save` | High
45 | File | `/admin/confirm.php` | High
46 | File | `/admin/contactus.php` | High
47 | File | `/admin/content/book` | High
48 | File | `/admin/content/editor` | High
49 | File | `/admin/course_action.php` | High
50 | File | `/admin/deletedoctorclinic.php` | High
51 | File | `/admin/deleteitem.php` | High
52 | File | `/admin/delete_file.php` | High
53 | File | `/Admin/detail.php` | High
54 | File | `/admin/edit-category.php` | High
55 | File | `/admin/edit-customer-detailed.php` | High
56 | File | `/admin/edit-propertytype.php` | High
57 | File | `/admin/edit-services.php` | High
58 | File | `/admin/edit-subjects-detail.php` | High
59 | File | `/admin/edit-user.php` | High
60 | File | `/admin/edit.php` | High
61 | File | `/admin/editorder.php` | High
62 | File | `/admin/edit_admin_query.php` | High
63 | File | `/admin/edit_members.php` | High
64 | File | `/admin/edit_student_query.php` | High
65 | File | `/admin/employee/index.php?view=edit` | High
66 | File | `/admin/faculty_action.php` | High
67 | File | `/admin/group/edit.do` | High
68 | File | `/admin/home.php` | High
69 | File | `/admin/images/add` | High
70 | File | `/admin/index.php` | High
71 | File | `/admin/link.php` | High
72 | File | `/admin/login.php` | High
73 | File | `/admin/login_process.php` | High
74 | File | `/admin/menus/view_menu.php` | High
75 | File | `/admin/network/ajax_getChannelList` | High
76 | File | `/admin/network/diag_nslookup` | High
77 | File | `/admin/network/diag_ping6` | High
78 | File | `/admin/network/diag_pinginterface` | High
79 | File | `/admin/network/diag_traceroute` | High
80 | File | `/admin/network/diag_traceroute6` | High
81 | File | `/admin/network/wifi_schedule` | High
82 | File | `/admin/newsletter.php` | High
83 | File | `/admin/operation/user.php` | High
84 | File | `/admin/operations/expense.php` | High
85 | File | `/admin/Operations/Role.php` | High
86 | File | `/admin/plugin.php` | High
87 | File | `/admin/print.php` | High
88 | File | `/admin/print1.php` | High
89 | File | `/admin/profile.php` | High
90 | File | `/admin/property-details.php` | High
91 | File | `/admin/publishnews.php` | High
92 | File | `/admin/registration.php` | High
93 | File | `/admin/room.php` | High
94 | File | `/admin/rooms.php` | High
95 | File | `/admin/search-appointment.php` | High
96 | File | `/admin/search-maid.php` | High
97 | File | `/admin/search-property.php` | High
98 | File | `/admin/services/view_service.php` | High
99 | File | `/admin/sn_package/sn_https` | High
100 | ... | ... | ...

There are 885 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
