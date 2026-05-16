# Campaign 1 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 1_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 1:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)

## Actors

These _actors_ are associated with Campaign 1 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign 1.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [10.16.91.131](https://vuldb.com/?ip.10.16.91.131) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [11.24.8.54](https://vuldb.com/?ip.11.24.8.54) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [11.25.41.114](https://vuldb.com/?ip.11.25.41.114) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [13.33.26.95](https://vuldb.com/?ip.13.33.26.95) | server-13-33-26-95.phx50.r.cloudfront.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [13.56.107.66](https://vuldb.com/?ip.13.56.107.66) | ec2-13-56-107-66.us-west-1.compute.amazonaws.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | Medium
6 | [14.40.57.104](https://vuldb.com/?ip.14.40.57.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [15.85.30.84](https://vuldb.com/?ip.15.85.30.84) | atp467w084.sgp.hp.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [19.140.139.6](https://vuldb.com/?ip.19.140.139.6) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [20.143.69.60](https://vuldb.com/?ip.20.143.69.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [23.26.60.60](https://vuldb.com/?ip.23.26.60.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | [23.92.211.10](https://vuldb.com/?ip.23.92.211.10) | gramwide.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
12 | [25.108.63.68](https://vuldb.com/?ip.25.108.63.68) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
13 | [26.50.108.98](https://vuldb.com/?ip.26.50.108.98) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
14 | [27.22.41.133](https://vuldb.com/?ip.27.22.41.133) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
15 | [29.136.101.40](https://vuldb.com/?ip.29.136.101.40) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
16 | [30.101.13.14](https://vuldb.com/?ip.30.101.13.14) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
17 | [33.9.140.76](https://vuldb.com/?ip.33.9.140.76) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
18 | [36.75.63.47](https://vuldb.com/?ip.36.75.63.47) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
3 | File | `/?r=email/api/mark&op=delFromSend` | High
4 | File | `/?r=recruit/resume/edit&op=status` | High
5 | File | `/abstract_sql/abstract_sql_store.go` | High
6 | File | `/addCatController.php` | High
7 | File | `/addcategory.php` | High
8 | File | `/addcompany.php` | High
9 | File | `/addelivery.php` | High
10 | File | `/addproduct.php` | High
11 | File | `/addrecord.php` | High
12 | File | `/add_dealerrequest.php` | High
13 | File | `/add_student_grade.php` | High
14 | File | `/admin-profile.php` | High
15 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
16 | File | `/admin/?page=borrow/view_borrow` | High
17 | File | `/admin/?page=products/view_product` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-subadmin.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/admin.php` | High
22 | File | `/admin/admin_action.php` | High
23 | File | `/admin/admin_feature.php` | High
24 | File | `/admin/admin_running.php` | High
25 | File | `/admin/allemployees.php` | High
26 | File | `/admin/approve_user.php` | High
27 | File | `/admin/article.php` | High
28 | File | `/admin/assign/assign.php` | High
29 | File | `/admin/backup/backups.php` | High
30 | File | `/admin/book-details.php` | High
31 | File | `/admin/borrow_add.php` | High
32 | File | `/admin/bwdates-reports-details.php` | High
33 | File | `/admin/check_admin.php` | High
34 | File | `/admin/comment/list` | High
35 | File | `/admin/contactus.php` | High
36 | File | `/admin/content/editor` | High
37 | File | `/admin/create_product.php` | High
38 | File | `/Admin/CustomerReport.php` | High
39 | File | `/admin/delete.php` | High
40 | File | `/admin/deleteuser.php` | High
41 | File | `/admin/edit-category.php` | High
42 | File | `/admin/edit-customer-detailed.php` | High
43 | File | `/admin/edit-pass-detail.php` | High
44 | File | `/admin/edit-propertytype.php` | High
45 | File | `/admin/edit-services.php` | High
46 | File | `/admin/edit-user-profile.php` | High
47 | File | `/admin/edit_class.php` | High
48 | File | `/admin/edit_customer.php` | High
49 | File | `/admin/edit_product.php` | High
50 | File | `/admin/employee/controller.php` | High
51 | File | `/admin/goods/update` | High
52 | File | `/admin/index.php` | High
53 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
54 | File | `/admin/manage-normal-ticket.php` | High
55 | File | `/admin/member_update.php` | High
56 | File | `/admin/model/addOrUpdate` | High
57 | File | `/admin/modules/course/index.php` | High
58 | File | `/admin/modules/subject/edit.php` | High
59 | File | `/admin/network/diag_nslookup` | High
60 | File | `/admin/network/diag_traceroute6` | High
61 | File | `/admin/network/wifi_schedule` | High
62 | File | `/admin/operations/travellers.php` | High
63 | File | `/admin/order.php` | High
64 | File | `/admin/product.php` | High
65 | File | `/admin/profile.php` | High
66 | File | `/admin/project/update/2` | High
67 | File | `/admin/rules.php` | High
68 | File | `/admin/sales/view_details.php` | High
69 | File | `/admin/save_airlines.php` | High
70 | File | `/admin/save_student.php` | High
71 | File | `/admin/school_year.php` | High
72 | File | `/admin/search-directory.php` | High
73 | File | `/admin/search.php` | High
74 | File | `/admin/serverinfo` | High
75 | File | `/admin/sms_setting.php` | High
76 | File | `/admin/sys/admin.html` | High
77 | File | `/admin/tag/list` | High
78 | File | `/admin/template/update` | High
79 | File | `/admin/twitter.php` | High
80 | File | `/admin/update-progress.php` | High
81 | File | `/admin/updateabout.php` | High
82 | File | `/admin/user/manage_user.php` | High
83 | File | `/admin/view-patient.php` | High
84 | File | `/admin/view_all_posts.php` | High
85 | File | `/adminapi/export/product_list` | High
86 | File | `/admin_class.php` | High
87 | File | `/adposition/queryAll` | High
88 | File | `/ajax.php` | Medium
89 | File | `/ajax.php?action=delete_sales` | High
90 | File | `/api/admin/system/store/order/list` | High
91 | File | `/api/upload` | Medium
92 | File | `/api/user` | Medium
93 | File | `/api/wizard/getNetworkConf` | High
94 | File | `/app/ajax/sell_return_data.php` | High
95 | File | `/applyleave.php` | High
96 | File | `/backend/api/buscarTipoDenuncia.php` | High
97 | File | `/backend/register.php` | High
98 | File | `/bank/statements.php` | High
99 | File | `/bin/ntfs-3g` | Medium
100 | File | `/bishe/register` | High
101 | File | `/blog/comment` | High
102 | File | `/bmp-account-detail/` | High
103 | File | `/boafrm/formOneKeyAccessButton` | High
104 | File | `/boafrm/formParentControl` | High
105 | File | `/boafrm/formWlanMultipleAP` | High
106 | ... | ... | ...

There are 938 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_1_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
