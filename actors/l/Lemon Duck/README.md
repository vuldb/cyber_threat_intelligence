# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lemon Duck.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.202.15.246](https://vuldb.com/?ip.1.202.15.246) | 246.15.202.1.static.bjtelecom.net | - | High
2 | [27.195.157.70](https://vuldb.com/?ip.27.195.157.70) | - | - | High
3 | [36.48.94.254](https://vuldb.com/?ip.36.48.94.254) | - | - | High
4 | [36.110.1.222](https://vuldb.com/?ip.36.110.1.222) | 222.1.110.36.static.bjtelecom.net | - | High
5 | [40.68.42.171](https://vuldb.com/?ip.40.68.42.171) | - | - | High
6 | [42.7.4.88](https://vuldb.com/?ip.42.7.4.88) | - | - | High
7 | [42.7.31.243](https://vuldb.com/?ip.42.7.31.243) | - | - | High
8 | [42.176.133.183](https://vuldb.com/?ip.42.176.133.183) | - | - | High
9 | [49.71.208.124](https://vuldb.com/?ip.49.71.208.124) | - | - | High
10 | [49.147.72.67](https://vuldb.com/?ip.49.147.72.67) | dsl.49.148.72.67.pldt.net | - | High
11 | [51.36.170.221](https://vuldb.com/?ip.51.36.170.221) | - | - | High
12 | [58.56.135.198](https://vuldb.com/?ip.58.56.135.198) | - | - | High
13 | [58.62.125.245](https://vuldb.com/?ip.58.62.125.245) | - | - | High
14 | [58.221.24.178](https://vuldb.com/?ip.58.221.24.178) | - | - | High
15 | [58.251.2.115](https://vuldb.com/?ip.58.251.2.115) | reverse.gdsz.cncnet.net | - | High
16 | [59.111.181.116](https://vuldb.com/?ip.59.111.181.116) | - | - | High
17 | [59.175.154.97](https://vuldb.com/?ip.59.175.154.97) | - | - | High
18 | [60.10.56.169](https://vuldb.com/?ip.60.10.56.169) | hebei.10.60.in-addr.arpa | - | High
19 | [60.10.134.93](https://vuldb.com/?ip.60.10.134.93) | hebei.10.60.in-addr.arpa | - | High
20 | [60.19.236.50](https://vuldb.com/?ip.60.19.236.50) | - | - | High
21 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lemon Duck_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/%61dmin/api/logs` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/academic-calendar` | High
4 | File | `/Account/EditProfile` | High
5 | File | `/add-admin.php` | High
6 | File | `/add-category.php` | High
7 | File | `/add-course.php` | High
8 | File | `/add-subadmin.php` | High
9 | File | `/addclient1.php` | High
10 | File | `/addpayment.php` | High
11 | File | `/add_classes.php` | High
12 | File | `/add_company.php` | High
13 | File | `/admin-api/mp/material/upload-permanent` | High
14 | File | `/admin-cp/media` | High
15 | File | `/admin-dashboard` | High
16 | File | `/admin-profile.php` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?page=back_order/view_bo` | High
19 | File | `/admin/?page=system_info` | High
20 | File | `/admin/about-us.php` | High
21 | File | `/admin/action/delete-vaccine.php` | High
22 | File | `/admin/add-art-type.php` | High
23 | File | `/admin/add-category.php` | High
24 | File | `/admin/add-customer-services.php` | High
25 | File | `/admin/add-services.php` | High
26 | File | `/admin/addroom.php` | High
27 | File | `/admin/add_city.php` | High
28 | File | `/admin/add_student.php` | High
29 | File | `/admin/admin-profile.php` | High
30 | File | `/admin/adminScoreUrl` | High
31 | File | `/admin/admin_addnew_product.php` | High
32 | File | `/admin/ajax.php?action=login` | High
33 | File | `/admin/all-applications.php` | High
34 | File | `/admin/app/asset_crud.php` | High
35 | File | `/admin/app/profile_crud.php` | High
36 | File | `/admin/app/role_crud.php` | High
37 | File | `/admin/app/web_crud.php` | High
38 | File | `/admin/applicants/index.php` | High
39 | File | `/admin/approve.php` | High
40 | File | `/admin/article/list` | High
41 | File | `/admin/booking-details.php` | High
42 | File | `/admin/book_add.php` | High
43 | File | `/admin/case-status` | High
44 | File | `/admin/categories/save` | High
45 | File | `/admin/categories/update` | High
46 | File | `/Admin/Category.php` | High
47 | File | `/admin/changeimage.php` | High
48 | File | `/Admin/changepassword.php` | High
49 | File | `/admin/conferences/list/` | High
50 | File | `/admin/config/uploadicon.php` | High
51 | File | `/admin/contact-us.php` | High
52 | File | `/Admin/createClass.php` | High
53 | File | `/admin/delete.php` | High
54 | File | `/admin/deleteBooking.php` | High
55 | File | `/admin/deleteuser.php` | High
56 | File | `/admin/delete_file.php` | High
57 | File | `/admin/department/add` | High
58 | File | `/admin/doctor-specilization.php` | High
59 | File | `/admin/doctors.php` | High
60 | File | `/admin/edit-art-product-detail.php?editid=2` | High
61 | File | `/admin/edit-artist-detail.php?editid=1` | High
62 | File | `/admin/edit-boat.php` | High
63 | File | `/admin/edit-category.php` | High
64 | File | `/admin/edit-directory.php` | High
65 | File | `/admin/edit-products.php` | High
66 | File | `/admin/edit-state.php` | High
67 | File | `/admin/edit-subadmin.php` | High
68 | File | `/admin/edit-subcategory.php` | High
69 | File | `/Admin/EditCategory` | High
70 | File | `/Admin/EditCity.php` | High
71 | File | `/admin/edit_action.php` | High
72 | File | `/admin/edit_area.php` | High
73 | File | `/Admin/edit_profile.php` | High
74 | File | `/admin/employee/index.php` | High
75 | File | `/admin/forget-password.php` | High
76 | File | `/admin/forgot-password.php` | High
77 | File | `/admin/get_balance.php` | High
78 | File | `/admin/goods/update` | High
79 | File | `/admin/group` | Medium
80 | File | `/admin/home/index.html` | High
81 | File | `/admin/index.php` | High
82 | File | `/admin/indexConfigs/save` | High
83 | File | `/admin/inventory/manage_stock.php` | High
84 | File | `/admin/list_resource_icon.php?action=delete` | High
85 | File | `/admin/login.php` | High
86 | File | `/admin/manage-pages.php` | High
87 | File | `/admin/member_save.php` | High
88 | File | `/admin/member_update.php` | High
89 | File | `/admin/menus/view_menu.php` | High
90 | File | `/admin/menu_update.php` | High
91 | File | `/admin/modules/lesson/index.php` | High
92 | File | `/Admin/News.php` | High
93 | File | `/admin/newsletter1.php` | High
94 | File | `/admin/operations/expense_category.php` | High
95 | File | `/admin/pass-bwdates-reports-details.php` | High
96 | File | `/admin/pass-details.php` | High
97 | File | `/admin/post-avehical.php` | High
98 | File | `/admin/print_barcode.php` | High
99 | File | `/admin/profile.php` | High
100 | File | `/admin/redirect.php` | High
101 | File | `/admin/registration.php` | High
102 | File | `/admin/reports/index.php` | High
103 | File | `/admin/reservation_view.php` | High
104 | File | `/admin/search-booking-request.php` | High
105 | File | `/admin/search-pass.php` | High
106 | File | `/admin/search.php` | High
107 | File | `/admin/searchview.php` | High
108 | File | `/admin/service/stop/` | High
109 | File | `/admin/services/manage_service.php` | High
110 | File | `/admin/sign/out` | High
111 | File | `/admin/student.php` | High
112 | File | `/admin/students.php` | High
113 | File | `/admin/subcategory.php` | High
114 | File | `/admin/success_story.php` | High
115 | File | `/admin/sys/menu/list` | High
116 | File | `/admin/updateorder.php` | High
117 | File | `/admin/user/index.php` | High
118 | File | `/admin/user/manage_user.php` | High
119 | File | `/admin/user_save.php` | High
120 | File | `/admin/user_update.php` | High
121 | File | `/admin/view-enquiry.php` | High
122 | File | `/admin/view-foreigner-ticket.php` | High
123 | File | `/adminPage/conf/saveCmd` | High
124 | File | `/ajax.php?action=delete_member` | High
125 | File | `/ajax.php?action=delete_plan` | High
126 | File | `/ajax/loadShopInfo.php` | High
127 | File | `/ajax_state.php` | High
128 | File | `/ample/app/ajax/member_data.php` | High
129 | ... | ... | ...

There are 1143 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/10/lemon-duck-brings-cryptocurrency-miners.html
* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
