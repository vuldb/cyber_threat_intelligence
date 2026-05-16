# Rocke - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rocke](https://vuldb.com/?actor.rocke). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rocke](https://vuldb.com/?actor.rocke)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rocke:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rocke.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.4.151](https://vuldb.com/?ip.23.234.4.151) | - | - | High
2 | [23.234.4.153](https://vuldb.com/?ip.23.234.4.153) | - | - | High
3 | [27.193.180.224](https://vuldb.com/?ip.27.193.180.224) | - | - | High
4 | [27.210.170.197](https://vuldb.com/?ip.27.210.170.197) | - | - | High
5 | [27.221.28.231](https://vuldb.com/?ip.27.221.28.231) | - | - | High
6 | [27.221.54.252](https://vuldb.com/?ip.27.221.54.252) | - | - | High
7 | [36.103.236.221](https://vuldb.com/?ip.36.103.236.221) | - | - | High
8 | [36.103.247.121](https://vuldb.com/?ip.36.103.247.121) | - | - | High
9 | [36.248.26.205](https://vuldb.com/?ip.36.248.26.205) | - | - | High
10 | [42.56.76.104](https://vuldb.com/?ip.42.56.76.104) | - | - | High
11 | [42.202.141.230](https://vuldb.com/?ip.42.202.141.230) | - | - | High
12 | [42.236.125.84](https://vuldb.com/?ip.42.236.125.84) | hn.kd.ny.adsl | - | High
13 | [43.224.225.220](https://vuldb.com/?ip.43.224.225.220) | - | - | High
14 | [43.242.166.88](https://vuldb.com/?ip.43.242.166.88) | - | - | High
15 | [52.167.219.168](https://vuldb.com/?ip.52.167.219.168) | - | - | High
16 | [58.215.145.137](https://vuldb.com/?ip.58.215.145.137) | - | - | High
17 | [58.216.107.77](https://vuldb.com/?ip.58.216.107.77) | - | - | High
18 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rocke_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rocke. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
3 | File | `/?r=email/api/mark&op=delFromSend` | High
4 | File | `/?r=recruit/resume/edit&op=status` | High
5 | File | `/abstract_sql/abstract_sql_store.go` | High
6 | File | `/addCatController.php` | High
7 | File | `/addcompany.php` | High
8 | File | `/addelivery.php` | High
9 | File | `/addproduct.php` | High
10 | File | `/addrecord.php` | High
11 | File | `/add_dealerrequest.php` | High
12 | File | `/add_student_grade.php` | High
13 | File | `/admin-profile.php` | High
14 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
15 | File | `/admin/` | Low
16 | File | `/admin/?page=borrow/view_borrow` | High
17 | File | `/admin/?page=products/view_product` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-subadmin.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/admin.php` | High
22 | File | `/admin/admin_action.php` | High
23 | File | `/admin/admin_running.php` | High
24 | File | `/admin/allemployees.php` | High
25 | File | `/admin/approve_user.php` | High
26 | File | `/admin/article.php` | High
27 | File | `/admin/assign/assign.php` | High
28 | File | `/admin/backup/backups.php` | High
29 | File | `/admin/book-details.php` | High
30 | File | `/admin/borrow_add.php` | High
31 | File | `/admin/bwdates-reports-details.php` | High
32 | File | `/admin/check_admin.php` | High
33 | File | `/admin/comment/list` | High
34 | File | `/admin/contactus.php` | High
35 | File | `/Admin/CustomerReport.php` | High
36 | File | `/admin/delete.php` | High
37 | File | `/admin/deleteuser.php` | High
38 | File | `/admin/edit-category.php` | High
39 | File | `/admin/edit-customer-detailed.php` | High
40 | File | `/admin/edit-pass-detail.php` | High
41 | File | `/admin/edit-propertytype.php` | High
42 | File | `/admin/edit-services.php` | High
43 | File | `/admin/edit-user-profile.php` | High
44 | File | `/admin/edit_class.php` | High
45 | File | `/admin/edit_customer.php` | High
46 | File | `/admin/edit_product.php` | High
47 | File | `/admin/employee/controller.php` | High
48 | File | `/admin/faculty_action.php` | High
49 | File | `/admin/goods/update` | High
50 | File | `/admin/index.php` | High
51 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
52 | File | `/admin/manage-normal-ticket.php` | High
53 | File | `/admin/member_update.php` | High
54 | File | `/admin/model/addOrUpdate` | High
55 | File | `/admin/modules/course/index.php` | High
56 | File | `/admin/modules/subject/edit.php` | High
57 | File | `/admin/network/diag_nslookup` | High
58 | File | `/admin/network/diag_traceroute6` | High
59 | File | `/admin/network/wifi_schedule` | High
60 | File | `/admin/operations/travellers.php` | High
61 | File | `/admin/order.php` | High
62 | File | `/admin/product.php` | High
63 | File | `/admin/profile.php` | High
64 | File | `/admin/project/update/2` | High
65 | File | `/admin/rules.php` | High
66 | File | `/admin/sales/view_details.php` | High
67 | File | `/admin/save_airlines.php` | High
68 | File | `/admin/save_student.php` | High
69 | File | `/admin/search-directory.php` | High
70 | File | `/admin/search.php` | High
71 | File | `/admin/serverinfo` | High
72 | File | `/admin/sms_setting.php` | High
73 | File | `/admin/sys/admin.html` | High
74 | File | `/admin/tag/list` | High
75 | File | `/admin/template/update` | High
76 | File | `/admin/twitter.php` | High
77 | File | `/admin/update-progress.php` | High
78 | File | `/admin/updateabout.php` | High
79 | File | `/admin/user/manage_user.php` | High
80 | File | `/admin/view-patient.php` | High
81 | File | `/admin/view_all_posts.php` | High
82 | File | `/adminapi/export/product_list` | High
83 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
84 | File | `/admin_class.php` | High
85 | File | `/adposition/queryAll` | High
86 | File | `/ajax.php` | Medium
87 | File | `/ajax.php?action=delete_sales` | High
88 | File | `/api/admin/system/store/order/list` | High
89 | File | `/api/upload` | Medium
90 | File | `/api/wizard/getNetworkConf` | High
91 | File | `/applyleave.php` | High
92 | File | `/backend/api/buscarTipoDenuncia.php` | High
93 | File | `/backend/register.php` | High
94 | File | `/bank/statements.php` | High
95 | File | `/bidnow.php` | Medium
96 | File | `/bishe/register` | High
97 | File | `/blog/comment` | High
98 | File | `/bmp-account-detail/` | High
99 | File | `/boafrm/formOneKeyAccessButton` | High
100 | File | `/boafrm/formParentControl` | High
101 | File | `/boafrm/formWlanMultipleAP` | High
102 | File | `/book_car.php` | High
103 | File | `/c6/Jhsoft.Web.module/ToolBar/GetWordFileName.aspx/?text=GetUrl&style=add` | High
104 | File | `/catalog/all-products` | High
105 | File | `/cfgFile/fileContent` | High
106 | File | `/cgi-bin/adm.cgi` | High
107 | ... | ... | ...

There are 944 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/rocke-champion-of-monero-miners.html
* https://blog.talosintelligence.com/2018/12/cryptomining-campaigns-2018.html
* https://unit42.paloaltonetworks.com/malware-used-by-rocke-group-evolves-to-evade-detection-by-cloud-security-products/
* https://unit42.paloaltonetworks.com/rockein-the-netflow/
* https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
