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
* [DE](https://vuldb.com/?country.de)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 1 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/aboutadd.php` | High
4 | File | `/aboutedit.php` | High
5 | File | `/account.php` | Medium
6 | File | `/account.php?q=quiz&step=2` | High
7 | File | `/activation.php` | High
8 | File | `/add-pig.php` | Medium
9 | File | `/add.php` | Medium
10 | File | `/addCatController.php` | High
11 | File | `/add_achievement_details.php` | High
12 | File | `/add_personal_details.php` | High
13 | File | `/add_user.php` | High
14 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
15 | File | `/admin/about-us.php` | High
16 | File | `/admin/aboutus.php` | High
17 | File | `/admin/add-customer-services.php` | High
18 | File | `/admin/add-customer.php` | High
19 | File | `/admin/add-property.php` | High
20 | File | `/admin/add-propertytype.php` | High
21 | File | `/admin/add-services.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/Admin/adminlogin.php` | High
24 | File | `/admin/admin_action.php` | High
25 | File | `/admin/ajax.php?action=login` | High
26 | File | `/admin/all_users.php` | High
27 | File | `/admin/article.php` | High
28 | File | `/admin/article.php?action=upload_cover` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
32 | File | `/admin/categories/update` | High
33 | File | `/admin/category.php` | High
34 | File | `/admin/chatroom.php` | High
35 | File | `/admin/check_admin_login.php` | High
36 | File | `/admin/cmsTagType/save` | High
37 | File | `/admin/complaint-search.php` | High
38 | File | `/admin/contactus.php` | High
39 | File | `/admin/content/book` | High
40 | File | `/admin/content/editor` | High
41 | File | `/admin/course_action.php` | High
42 | File | `/admin/create_product.php` | High
43 | File | `/Admin/detail.php` | High
44 | File | `/admin/edit-category.php` | High
45 | File | `/admin/edit-customer-detailed.php` | High
46 | File | `/admin/edit-propertytype.php` | High
47 | File | `/admin/edit-services.php` | High
48 | File | `/admin/edit-user.php` | High
49 | File | `/admin/editorder.php` | High
50 | File | `/admin/faculty_action.php` | High
51 | File | `/admin/index.php` | High
52 | File | `/admin/link.php` | High
53 | File | `/admin/login.php` | High
54 | File | `/admin/login_process.php` | High
55 | File | `/admin/msg.php` | High
56 | File | `/admin/network/ajax_getChannelList` | High
57 | File | `/admin/network/diag_iperf` | High
58 | File | `/admin/network/diag_nslookup` | High
59 | File | `/admin/network/diag_ping6` | High
60 | File | `/admin/network/diag_pinginterface` | High
61 | File | `/admin/network/diag_traceroute` | High
62 | File | `/admin/network/diag_traceroute6` | High
63 | File | `/admin/network/wifi_schedule` | High
64 | File | `/admin/newsletter.php` | High
65 | File | `/admin/plugin.php` | High
66 | File | `/admin/print.php` | High
67 | File | `/admin/profile.php` | High
68 | File | `/admin/property-details.php` | High
69 | File | `/Admin/Proses_Edit_Akun.php` | High
70 | File | `/admin/publishnews.php` | High
71 | File | `/admin/registration.php` | High
72 | File | `/admin/report.php` | High
73 | File | `/admin/room.php` | High
74 | File | `/admin/search-appointment.php` | High
75 | File | `/admin/search-invoices.php` | High
76 | File | `/admin/search-maid.php` | High
77 | File | `/admin/search-property.php` | High
78 | File | `/admin/services/view_service.php` | High
79 | File | `/admin/sn_package/sn_https` | High
80 | File | `/admin/state.php` | High
81 | File | `/admin/store.php` | High
82 | File | `/admin/student_action.php` | High
83 | File | `/admin/tag.php` | High
84 | File | `/admin/tag/save` | High
85 | ... | ... | ...

There are 749 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
