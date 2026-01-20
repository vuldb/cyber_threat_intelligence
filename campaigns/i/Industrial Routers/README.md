# Industrial Routers - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Industrial Routers_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Industrial Routers:

* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Industrial Routers or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Chaya_005](https://vuldb.com/?actor.chaya_005) | High
2 | [Mozi](https://vuldb.com/?actor.mozi) | High
3 | [Mirai](https://vuldb.com/?actor.mirai) | High
4 | ... | ...

There are 2 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Industrial Routers.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.181.3.24](https://vuldb.com/?ip.5.181.3.24) | 55072.ip-ptr.tech | [Chaya_005](https://vuldb.com/?actor.chaya_005) | High
2 | [23.95.235.22](https://vuldb.com/?ip.23.95.235.22) | 23-95-235-22-host.colocrossing.com | [Chaya_005](https://vuldb.com/?actor.chaya_005) | High
3 | [26.249.145.103](https://vuldb.com/?ip.26.249.145.103) | - | [Mirai](https://vuldb.com/?actor.mirai) | High
4 | [31.57.243.170](https://vuldb.com/?ip.31.57.243.170) | - | [Chaya_005](https://vuldb.com/?actor.chaya_005) | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Industrial Routers. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Industrial Routers. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
3 | File | `/?r=email/api/mark&op=delFromSend` | High
4 | File | `/abstract_sql/abstract_sql_store.go` | High
5 | File | `/actuator` | Medium
6 | File | `/add-office.php` | High
7 | File | `/addCatController.php` | High
8 | File | `/addcategory.php` | High
9 | File | `/addcompany.php` | High
10 | File | `/addelivery.php` | High
11 | File | `/addproduct.php` | High
12 | File | `/addrecord.php` | High
13 | File | `/add_dealerrequest.php` | High
14 | File | `/add_student_grade.php` | High
15 | File | `/admin-profile.php` | High
16 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
17 | File | `/admin/?page=borrow/view_borrow` | High
18 | File | `/admin/?page=products/view_product` | High
19 | File | `/admin/aboutus.php` | High
20 | File | `/admin/add-customer.php` | High
21 | File | `/admin/add-foreigner-ticket.php` | High
22 | File | `/admin/addmanagerclinic.php` | High
23 | File | `/admin/admin-profile.php` | High
24 | File | `/admin/admin.php` | High
25 | File | `/admin/admin_action.php` | High
26 | File | `/admin/admin_feature.php` | High
27 | File | `/admin/admin_running.php` | High
28 | File | `/admin/allemployees.php` | High
29 | File | `/admin/approve_user.php` | High
30 | File | `/admin/assign/assign.php` | High
31 | File | `/admin/backup/backups.php` | High
32 | File | `/admin/book-details.php` | High
33 | File | `/admin/booking-details.php` | High
34 | File | `/admin/borrow_add.php` | High
35 | File | `/admin/bwdates-reports-details.php` | High
36 | File | `/admin/check_admin.php` | High
37 | File | `/admin/content/editor` | High
38 | File | `/admin/create_product.php` | High
39 | File | `/Admin/CustomerReport.php` | High
40 | File | `/admin/delete.php` | High
41 | File | `/admin/deleteuser.php` | High
42 | File | `/admin/doctor-specilization.php` | High
43 | File | `/admin/edit-category.php` | High
44 | File | `/admin/edit-customer-detailed.php` | High
45 | File | `/admin/edit-pass-detail.php` | High
46 | File | `/admin/edit-propertytype.php` | High
47 | File | `/admin/edit-services.php` | High
48 | File | `/admin/employee/controller.php` | High
49 | File | `/admin/execeditroom.php` | High
50 | File | `/admin/index.php` | High
51 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
52 | File | `/admin/manage-normal-ticket.php` | High
53 | File | `/admin/member_update.php` | High
54 | File | `/admin/model/addOrUpdate` | High
55 | File | `/admin/modules/course/index.php` | High
56 | File | `/admin/modules/subject/edit.php` | High
57 | File | `/admin/network/diag_nslookup` | High
58 | File | `/admin/network/diag_pinginterface` | High
59 | File | `/admin/network/diag_traceroute6` | High
60 | File | `/admin/network/wifi_schedule` | High
61 | File | `/admin/operations/travellers.php` | High
62 | File | `/admin/order.php` | High
63 | File | `/admin/product.php` | High
64 | File | `/admin/profile.php` | High
65 | File | `/admin/project/update/2` | High
66 | File | `/Admin/registration.php` | High
67 | File | `/admin/rules.php` | High
68 | File | `/admin/sales/view_details.php` | High
69 | File | `/admin/save_airlines.php` | High
70 | File | `/admin/save_student.php` | High
71 | File | `/admin/school_year.php` | High
72 | File | `/admin/search-directory.php` | High
73 | File | `/admin/search.php` | High
74 | File | `/admin/serverinfo` | High
75 | File | `/admin/tag/list` | High
76 | File | `/admin/template/update` | High
77 | File | `/admin/update-progress.php` | High
78 | File | `/admin/updateabout.php` | High
79 | File | `/admin/user/manage_user.php` | High
80 | File | `/admin/user_update.php` | High
81 | File | `/admin/view-patient.php` | High
82 | File | `/admin/view_all_posts.php` | High
83 | File | `/adminapi/export/product_list` | High
84 | File | `/adminFile/upload` | High
85 | File | `/admin_class.php` | High
86 | File | `/adposition/queryAll` | High
87 | File | `/ajax.php` | Medium
88 | File | `/ajax.php?action=delete_payment` | High
89 | File | `/ajax.php?action=delete_sales` | High
90 | File | `/ajax.php?action=save_category` | High
91 | File | `/api/process.php` | High
92 | File | `/api/upload` | Medium
93 | File | `/api/user` | Medium
94 | File | `/api/wechat/app_auth` | High
95 | File | `/api/wizard/getNetworkConf` | High
96 | File | `/app/ajax/sell_return_data.php` | High
97 | File | `/app/platform/controllers/ResetpwdController.php` | High
98 | File | `/backend/api/buscarTipoDenuncia.php` | High
99 | File | `/backend/register.php` | High
100 | File | `/bank/statements.php` | High
101 | File | `/bishe/register` | High
102 | File | `/blog/comment` | High
103 | File | `/boafrm/formOneKeyAccessButton` | High
104 | File | `/boafrm/formParentControl` | High
105 | File | `/boafrm/formStaticDHCP` | High
106 | File | `/boafrm/formWlanMultipleAP` | High
107 | File | `/book_car.php` | High
108 | ... | ... | ...

There are 955 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.forescout.com/blog/ot-network-security-threats-industrial-routers-under-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
