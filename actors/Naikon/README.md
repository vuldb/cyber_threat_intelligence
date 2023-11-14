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
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-28, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/?r=report/api/getlist` | High
4 | File | `/academy/home/courses` | High
5 | File | `/academy/tutor/filter` | High
6 | File | `/ad-list` | Medium
7 | File | `/admin.php/appcenter/local.html?type=addon` | High
8 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
9 | File | `/admin/?page=bike` | High
10 | File | `/admin/?page=maintenance/brand` | High
11 | File | `/admin/?page=product/manage_product&id=2` | High
12 | File | `/admin/?page=reminders/view_reminder` | High
13 | File | `/admin/?page=system_info` | High
14 | File | `/admin/?page=user` | High
15 | File | `/admin/?page=user/list` | High
16 | File | `/admin/admin-profile.php` | High
17 | File | `/admin/admin.php` | High
18 | File | `/admin/admin_content_tag.php?action=save_content` | High
19 | File | `/admin/ajax.php` | High
20 | File | `/admin/ajax.php?action=confirm_order` | High
21 | File | `/admin/article/article-add.php` | High
22 | File | `/admin/assign/assign.php` | High
23 | File | `/admin/attendance_row.php` | High
24 | File | `/admin/ballot_down.php` | High
25 | File | `/admin/ballot_up.php` | High
26 | File | `/admin/bookings/manage_booking.php` | High
27 | File | `/admin/bookings/view_booking.php` | High
28 | File | `/admin/bookings/view_details.php` | High
29 | File | `/admin/budget/manage_budget.php` | High
30 | File | `/admin/casedetails.php` | High
31 | File | `/admin/cashadvance_row.php` | High
32 | File | `/admin/categories/manage_category.php` | High
33 | File | `/admin/categories/view_category.php` | High
34 | File | `/admin/cms_admin.php` | High
35 | File | `/admin/cms_content.php` | High
36 | File | `/admin/config/uploadicon.php` | High
37 | File | `/admin/configurations/userInfo` | High
38 | File | `/admin/config_save.php` | High
39 | File | `/admin/contacts/organizations/edit/2` | High
40 | File | `/admin/deduction_edit.php` | High
41 | File | `/admin/deduction_row.php` | High
42 | File | `/admin/del_category.php` | High
43 | File | `/admin/del_feedback.php` | High
44 | File | `/admin/del_service.php` | High
45 | File | `/admin/departments/view_department.php` | High
46 | File | `/admin/edit-accepted-appointment.php` | High
47 | File | `/admin/edit-doc.php` | High
48 | File | `/admin/edit-services.php` | High
49 | File | `/admin/edit_category.php` | High
50 | File | `/admin/edit_product.php` | High
51 | File | `/admin/edit_subject.php` | High
52 | File | `/admin/employee_add.php` | High
53 | File | `/admin/employee_edit.php` | High
54 | File | `/admin/employee_row.php` | High
55 | File | `/admin/forgot-password.php` | High
56 | File | `/admin/getallarticleinfo` | High
57 | File | `/admin/index.php` | High
58 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
59 | File | `/admin/index3.php` | High
60 | File | `/admin/info_deal.php` | High
61 | File | `/admin/inquiries/view_inquiry.php` | High
62 | File | `/admin/label/delete` | High
63 | File | `/admin/leancloud.php` | High
64 | File | `/admin/list_addr_fwresource_ip.php` | High
65 | File | `/admin/login.php` | High
66 | File | `/admin/maintenance/brand.php` | High
67 | File | `/admin/maintenance/manage_category.php` | High
68 | File | `/admin/maintenance/view_designation.php` | High
69 | File | `/admin/manage_academic.php` | High
70 | File | `/admin/modal_add_product.php` | High
71 | File | `/admin/order.php` | High
72 | File | `/admin/positions_row.php` | High
73 | File | `/admin/product/manage.php` | High
74 | File | `/admin/products/view_product.php` | High
75 | File | `/admin/project/update/2` | High
76 | File | `/admin/read.php?mudi=getSignal` | High
77 | File | `/admin/reminders/manage_reminder.php` | High
78 | File | `/admin/report/index.php` | High
79 | File | `/admin/reportupload.aspx` | High
80 | File | `/admin/robot/approval/list` | High
81 | File | `/admin/sales/index.php` | High
82 | File | `/admin/sales/manage_sale.php` | High
83 | File | `/admin/sales/view_details.php` | High
84 | File | `/admin/save.php` | High
85 | File | `/admin/search-appointment.php` | High
86 | File | `/admin/services/manage_service.php` | High
87 | File | `/admin/suppliers/view_details.php` | High
88 | File | `/admin/sys_sql_query.php` | High
89 | File | `/admin/test_status.php` | High
90 | File | `/admin/transactions/track_shipment.php` | High
91 | File | `/admin/upload` | High
92 | File | `/admin/upload.php` | High
93 | File | `/admin/user/manage_user.php` | High
94 | File | `/admin/userprofile.php` | High
95 | File | `/admin/voters_row.php` | High
96 | File | `/admin/vote_edit.php` | High
97 | File | `/admin_system/api.php` | High
98 | File | `/ajax.php?action=save_company` | High
99 | File | `/analysisProject/pagingQueryData` | High
100 | File | `/api/` | Low
101 | File | `/api/admin/store/product/list` | High
102 | File | `/api/admin/store/product/save` | High
103 | File | `/api/es/admin/v3/security/user/1` | High
104 | File | `/api/ping` | Medium
105 | File | `/api/sys/login` | High
106 | File | `/api/sys/set_passwd` | High
107 | File | `/api/v1/company/upload-logo` | High
108 | File | `/api/v4/users/ids` | High
109 | File | `/app/sys1.php` | High
110 | File | `/autheditpwd.php` | High
111 | File | `/author_posts.php` | High
112 | File | `/blog` | Low
113 | File | `/blog-single.php` | High
114 | File | `/boafrm/formFilter` | High
115 | File | `/book-services.php` | High
116 | File | `/booking/show_bookings/` | High
117 | File | `/bsenordering/index.php` | High
118 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
119 | File | `/cas/logout` | Medium
120 | File | `/category.php` | High
121 | File | `/category/list?limit=10&offset=0&order=desc` | High
122 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
123 | ... | ... | ...

There are 1091 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
