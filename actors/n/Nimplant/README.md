# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.17.181.161](https://vuldb.com/?ip.3.17.181.161) | ec2-3-17-181-161.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
4 | [3.239.44.147](https://vuldb.com/?ip.3.239.44.147) | ec2-3-239-44-147.compute-1.amazonaws.com | - | Medium
5 | [13.70.157.121](https://vuldb.com/?ip.13.70.157.121) | - | - | High
6 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
7 | [20.93.3.210](https://vuldb.com/?ip.20.93.3.210) | - | - | High
8 | [23.106.215.199](https://vuldb.com/?ip.23.106.215.199) | - | - | High
9 | [34.134.73.140](https://vuldb.com/?ip.34.134.73.140) | 140.73.134.34.bc.googleusercontent.com | - | Medium
10 | [34.251.151.38](https://vuldb.com/?ip.34.251.151.38) | ec2-34-251-151-38.eu-west-1.compute.amazonaws.com | - | Medium
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/%61dmin/api/logs` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/academic-calendar` | High
4 | File | `/Account/EditProfile` | High
5 | File | `/add-admin.php` | High
6 | File | `/add-apartment.php` | High
7 | File | `/add-category.php` | High
8 | File | `/add-course.php` | High
9 | File | `/add-subadmin.php` | High
10 | File | `/addclient1.php` | High
11 | File | `/addpayment.php` | High
12 | File | `/add_classes.php` | High
13 | File | `/add_company.php` | High
14 | File | `/admin-api/mp/material/upload-permanent` | High
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
28 | File | `/admin/admin-profile.php` | High
29 | File | `/admin/adminScoreUrl` | High
30 | File | `/admin/admin_addnew_product.php` | High
31 | File | `/admin/ajax.php?action=login` | High
32 | File | `/admin/all-applications.php` | High
33 | File | `/admin/app/asset_crud.php` | High
34 | File | `/admin/app/profile_crud.php` | High
35 | File | `/admin/app/role_crud.php` | High
36 | File | `/admin/app/web_crud.php` | High
37 | File | `/admin/applicants/index.php` | High
38 | File | `/admin/approve.php` | High
39 | File | `/admin/article/list` | High
40 | File | `/admin/booking-details.php` | High
41 | File | `/admin/case-status` | High
42 | File | `/admin/categories/save` | High
43 | File | `/admin/categories/update` | High
44 | File | `/Admin/Category.php` | High
45 | File | `/admin/category_save.php` | High
46 | File | `/admin/changeimage.php` | High
47 | File | `/Admin/changepassword.php` | High
48 | File | `/admin/conferences/list/` | High
49 | File | `/admin/config/uploadicon.php` | High
50 | File | `/admin/contact-us.php` | High
51 | File | `/Admin/createClass.php` | High
52 | File | `/admin/delete.php` | High
53 | File | `/admin/deleteBooking.php` | High
54 | File | `/admin/deleteuser.php` | High
55 | File | `/admin/delete_file.php` | High
56 | File | `/admin/department/add` | High
57 | File | `/admin/doctor-specilization.php` | High
58 | File | `/admin/doctors.php` | High
59 | File | `/admin/edit-art-product-detail.php?editid=2` | High
60 | File | `/admin/edit-artist-detail.php?editid=1` | High
61 | File | `/admin/edit-boat.php` | High
62 | File | `/admin/edit-category.php` | High
63 | File | `/admin/edit-directory.php` | High
64 | File | `/admin/edit-products.php` | High
65 | File | `/admin/edit-state.php` | High
66 | File | `/admin/edit-subadmin.php` | High
67 | File | `/admin/edit-subcategory.php` | High
68 | File | `/Admin/EditCategory` | High
69 | File | `/Admin/EditCity.php` | High
70 | File | `/admin/edit_action.php` | High
71 | File | `/admin/edit_area.php` | High
72 | File | `/Admin/edit_profile.php` | High
73 | File | `/admin/employee/index.php` | High
74 | File | `/admin/forget-password.php` | High
75 | File | `/admin/forgot-password.php` | High
76 | File | `/admin/get_balance.php` | High
77 | File | `/admin/goods/update` | High
78 | File | `/admin/group` | Medium
79 | File | `/admin/home/index.html` | High
80 | File | `/admin/indexConfigs/save` | High
81 | File | `/admin/inventory/manage_stock.php` | High
82 | File | `/admin/list_resource_icon.php?action=delete` | High
83 | File | `/admin/login.php` | High
84 | File | `/admin/manage-pages.php` | High
85 | File | `/admin/member_save.php` | High
86 | File | `/admin/member_update.php` | High
87 | File | `/admin/menus/view_menu.php` | High
88 | File | `/admin/menu_update.php` | High
89 | File | `/admin/modules/lesson/index.php` | High
90 | File | `/Admin/News.php` | High
91 | File | `/admin/newsletter1.php` | High
92 | File | `/admin/operations/expense_category.php` | High
93 | File | `/admin/pass-bwdates-reports-details.php` | High
94 | File | `/admin/pass-details.php` | High
95 | File | `/admin/post-avehical.php` | High
96 | File | `/admin/print_barcode.php` | High
97 | File | `/admin/profile.php` | High
98 | File | `/admin/redirect.php` | High
99 | File | `/admin/registration.php` | High
100 | File | `/admin/reports/index.php` | High
101 | File | `/admin/reservation_view.php` | High
102 | File | `/admin/search-booking-request.php` | High
103 | File | `/admin/search-pass.php` | High
104 | File | `/admin/search.php` | High
105 | File | `/admin/searchview.php` | High
106 | File | `/admin/service/stop/` | High
107 | File | `/admin/services/manage_service.php` | High
108 | File | `/admin/sign/out` | High
109 | File | `/admin/student.php` | High
110 | File | `/admin/students.php` | High
111 | File | `/admin/subcategory.php` | High
112 | File | `/admin/success_story.php` | High
113 | File | `/admin/sys/menu/list` | High
114 | File | `/admin/updateorder.php` | High
115 | File | `/admin/user/index.php` | High
116 | File | `/admin/user/manage_user.php` | High
117 | File | `/admin/user_save.php` | High
118 | File | `/admin/user_update.php` | High
119 | File | `/admin/view-enquiry.php` | High
120 | File | `/admin/view-foreigner-ticket.php` | High
121 | File | `/admin/visitor-details.php` | High
122 | File | `/adminPage/conf/saveCmd` | High
123 | File | `/ajax.php?action=delete_member` | High
124 | File | `/ajax.php?action=delete_plan` | High
125 | File | `/ajax/loadShopInfo.php` | High
126 | File | `/ajax_state.php` | High
127 | File | `/ample/app/ajax/member_data.php` | High
128 | File | `/api.php` | Medium
129 | File | `/api/admin/question/edit` | High
130 | ... | ... | ...

There are 1152 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/3.239.44.147
* https://search.censys.io/hosts/13.70.157.121
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/20.93.3.210
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/34.134.73.140
* https://search.censys.io/hosts/34.134.73.140+140.73.134.34.bc.googleusercontent.com
* https://search.censys.io/hosts/43.143.128.128
* https://search.censys.io/hosts/44.201.19.178
* https://search.censys.io/hosts/46.247.108.127
* https://search.censys.io/hosts/47.243.184.85
* https://search.censys.io/hosts/51.68.222.10
* https://search.censys.io/hosts/54.38.242.131
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/65.49.204.212
* https://search.censys.io/hosts/88.208.3.157
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/94.102.49.16
* https://search.censys.io/hosts/94.102.49.106
* https://search.censys.io/hosts/136.144.243.50
* https://search.censys.io/hosts/139.180.217.224
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/146.190.109.188
* https://search.censys.io/hosts/146.190.241.166
* https://search.censys.io/hosts/149.248.79.215
* https://search.censys.io/hosts/156.244.13.120
* https://search.censys.io/hosts/161.97.116.56
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://search.censys.io/hosts/185.196.10.245
* https://search.censys.io/hosts/207.154.192.30
* https://search.censys.io/hosts/207.180.253.60
* https://search.censys.io/hosts/210.2.169.231
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
