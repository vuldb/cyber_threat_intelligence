# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Naikon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [47.241.127.190](https://vuldb.com/?ip.47.241.127.190) | - | - | High
2 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | Camerashy | High
3 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | Camerashy | High
4 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | Camerashy | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Naikon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-35, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\TSplus\UserDesktop\themes.` | High
2 | File | `/?mobile=1` | Medium
3 | File | `/?p=products` | Medium
4 | File | `/?r=recruit/resume/edit&op=status` | High
5 | File | `/?r=report/api/getlist` | High
6 | File | `/academy/home/courses` | High
7 | File | `/account/delivery` | High
8 | File | `/ad-list` | Medium
9 | File | `/admin` | Low
10 | File | `/admin.php/appcenter/local.html?type=addon` | High
11 | File | `/admin/?page=maintenance/brand` | High
12 | File | `/admin/?page=product/manage_product&id=2` | High
13 | File | `/admin/?page=system_info` | High
14 | File | `/admin/?page=user` | High
15 | File | `/admin/?page=user/list` | High
16 | File | `/admin/?page=user/manage_user&id=3` | High
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/add-category.php` | High
19 | File | `/admin/add-services.php` | High
20 | File | `/admin/add_user_modal.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/admin/admin.php` | High
23 | File | `/admin/ajax.php` | High
24 | File | `/admin/article/article-add.php` | High
25 | File | `/admin/assign/assign.php` | High
26 | File | `/admin/ballot_down.php` | High
27 | File | `/admin/ballot_up.php` | High
28 | File | `/admin/bookings/manage_booking.php` | High
29 | File | `/admin/casedetails.php` | High
30 | File | `/admin/categories/manage_category.php` | High
31 | File | `/admin/categories/view_category.php` | High
32 | File | `/admin/configurations/userInfo` | High
33 | File | `/admin/config_save.php` | High
34 | File | `/admin/deduction_edit.php` | High
35 | File | `/admin/del_category.php` | High
36 | File | `/admin/del_feedback.php` | High
37 | File | `/admin/del_service.php` | High
38 | File | `/admin/departments/view_department.php` | High
39 | File | `/admin/edit-accepted-appointment.php` | High
40 | File | `/admin/edit-services.php` | High
41 | File | `/admin/edit_category.php` | High
42 | File | `/admin/edit_product.php` | High
43 | File | `/admin/forgot-password.php` | High
44 | File | `/admin/getallarticleinfo` | High
45 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
46 | File | `/admin/index3.php` | High
47 | File | `/admin/info_deal.php` | High
48 | File | `/admin/invoice.php` | High
49 | File | `/admin/login.php` | High
50 | File | `/admin/maintenance/brand.php` | High
51 | File | `/admin/maintenance/manage_category.php` | High
52 | File | `/admin/modal_add_product.php` | High
53 | File | `/admin/offenses/view_details.php` | High
54 | File | `/admin/positions_add.php` | High
55 | File | `/admin/positions_row.php` | High
56 | File | `/admin/read.php?mudi=announContent` | High
57 | File | `/admin/report/index.php` | High
58 | File | `/admin/reports/index.php` | High
59 | File | `/admin/reportupload.aspx` | High
60 | File | `/admin/robot/approval/list` | High
61 | File | `/admin/sales/index.php` | High
62 | File | `/admin/sales/manage_sale.php` | High
63 | File | `/admin/search-appointment.php` | High
64 | File | `/admin/services/manage_service.php` | High
65 | File | `/admin/students/view_details.php` | High
66 | File | `/admin/suppliers/view_details.php` | High
67 | File | `/admin/sys_sql_query.php` | High
68 | File | `/admin/test_status.php` | High
69 | File | `/admin/transactions/track_shipment.php` | High
70 | File | `/admin/upload` | High
71 | File | `/admin/upload.php` | High
72 | File | `/admin/user/manage_user.php` | High
73 | File | `/admin/vote_edit.php` | High
74 | File | `/admin_system/api.php` | High
75 | File | `/ajax.php?action=read_msg` | High
76 | File | `/ajax.php?action=save_company` | High
77 | File | `/analysisProject/pagingQueryData` | High
78 | File | `/api/admin/store/product/list` | High
79 | File | `/api/admin/store/product/save` | High
80 | File | `/api/sys/set_passwd` | High
81 | File | `/api/v1/terminal/sessions/?limit=1` | High
82 | File | `/App_Resource/UEditor/server/upload.aspx` | High
83 | File | `/author/list?limit=10&offset=0&order=desc` | High
84 | File | `/author_posts.php` | High
85 | File | `/blog-single.php` | High
86 | File | `/booking/show_bookings/` | High
87 | File | `/bsenordering/index.php` | High
88 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
89 | File | `/cas/logout` | Medium
90 | File | `/category/list?limit=10&offset=0&order=desc` | High
91 | File | `/cgi-bin/adm.cgi` | High
92 | File | `/cgi-bin/luci/api/auth` | High
93 | File | `/changeimage.php` | High
94 | File | `/classes/Login.php` | High
95 | File | `/classes/Master.php` | High
96 | ... | ... | ...

There are 851 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf
* https://1275.ru/ioc/164/lotus-panda-apt-iocs/
* https://research.checkpoint.com/2020/naikon-apt-cyber-espionage-reloaded/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.04.23(1)/NAIKON.pdf
* https://www.threatminer.org/report.php?q=TheNaikonAPT-MsnMM1.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
