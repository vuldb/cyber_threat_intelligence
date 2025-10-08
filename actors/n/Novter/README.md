# Novter - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Novter](https://vuldb.com/?actor.novter). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.novter](https://vuldb.com/?actor.novter)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Novter:

* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Novter.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.88.24.27](https://vuldb.com/?ip.1.88.24.27) | - | - | High
2 | [2.58.80.150](https://vuldb.com/?ip.2.58.80.150) | - | - | High
3 | [2.196.217.25](https://vuldb.com/?ip.2.196.217.25) | - | - | High
4 | [3.128.83.132](https://vuldb.com/?ip.3.128.83.132) | ec2-3-128-83-132.us-east-2.compute.amazonaws.com | - | Medium
5 | [5.61.40.95](https://vuldb.com/?ip.5.61.40.95) | - | - | High
6 | [5.61.42.103](https://vuldb.com/?ip.5.61.42.103) | - | - | High
7 | [5.61.42.111](https://vuldb.com/?ip.5.61.42.111) | box.invfx.eu | - | High
8 | [5.61.42.116](https://vuldb.com/?ip.5.61.42.116) | - | - | High
9 | [5.61.48.155](https://vuldb.com/?ip.5.61.48.155) | - | - | High
10 | [5.61.48.156](https://vuldb.com/?ip.5.61.48.156) | 192.64.119.156 | - | High
11 | [6.217.158.104](https://vuldb.com/?ip.6.217.158.104) | - | - | High
12 | [7.130.244.4](https://vuldb.com/?ip.7.130.244.4) | - | - | High
13 | [13.158.242.227](https://vuldb.com/?ip.13.158.242.227) | - | - | High
14 | [20.56.162.154](https://vuldb.com/?ip.20.56.162.154) | - | - | High
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Novter_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Novter. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?import` | Medium
3 | File | `/?p=products` | Medium
4 | File | `/?page=tracks` | High
5 | File | `/?r=email/api/mark&op=delFromSend` | High
6 | File | `/aboutadd.php` | High
7 | File | `/academy/tutor/filter` | High
8 | File | `/account/forgotpassword` | High
9 | File | `/accounts_con/register_account` | High
10 | File | `/ad-list` | Medium
11 | File | `/addclient1.php` | High
12 | File | `/addproduct.php` | High
13 | File | `/add_new_invoice.php` | High
14 | File | `/admin` | Low
15 | File | `/admin#permissions` | High
16 | File | `/admin-cp/theme/editor/default` | High
17 | File | `/admin-manage-user.php` | High
18 | File | `/admin/` | Low
19 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
20 | File | `/admin/?page=bike` | High
21 | File | `/admin/about-us.php` | High
22 | File | `/admin/action/new-father.php` | High
23 | File | `/Admin/add-admin.php` | High
24 | File | `/admin/add-services.php` | High
25 | File | `/admin/addproduct.php` | High
26 | File | `/admin/admin-profile.php` | High
27 | File | `/admin/admin.php` | High
28 | File | `/admin/adminHome.php` | High
29 | File | `/Admin/adminlogin.php` | High
30 | File | `/admin/ajax_product.php` | High
31 | File | `/admin/api/theme-edit/` | High
32 | File | `/admin/app/service_crud.php` | High
33 | File | `/admin/application-bwdates-reports-details.php` | High
34 | File | `/admin/apply.php` | High
35 | File | `/admin/article/article-edit-run.php` | High
36 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
37 | File | `/admin/attendance_row.php` | High
38 | File | `/admin/blood/update/o-.php` | High
39 | File | `/admin/booking-search.php` | High
40 | File | `/admin/bwdates-report-details.php` | High
41 | File | `/admin/card-bwdates-reports-details.php` | High
42 | File | `/admin/case-status` | High
43 | File | `/admin/category_row.php` | High
44 | File | `/admin/changeimage.php` | High
45 | File | `/admin/class.php?dowhat=modifyclass` | High
46 | File | `/admin/clientview.php` | High
47 | File | `/admin/cms_content.php` | High
48 | File | `/admin/conferences/list/` | High
49 | File | `/admin/config_ISCGroupNoCache.php` | High
50 | File | `/admin/contacts/organizations/edit/2` | High
51 | File | `/admin/court` | Medium
52 | File | `/admin/deduction_row.php` | High
53 | File | `/admin/deleteBooking.php` | High
54 | File | `/admin/del_service.php` | High
55 | File | `/admin/edit-card-detail.php` | High
56 | File | `/admin/edit_supplier.php` | High
57 | File | `/admin/edit_teacher.php` | High
58 | File | `/admin/extended` | High
59 | File | `/admin/fields/manage_field.php` | High
60 | File | `/admin/file_manager/export` | High
61 | File | `/admin/foreigner-search.php` | High
62 | File | `/admin/forgot-password.php` | High
63 | File | `/admin/forms/option_lists/edit.php` | High
64 | File | `/admin/general-setting` | High
65 | File | `/admin/get_price.php` | High
66 | File | `/admin/group` | Medium
67 | File | `/admin/home.php` | High
68 | File | `/admin/home.php?con=add` | High
69 | File | `/admin/index.php` | High
70 | File | `/admin/index.php?page=categories` | High
71 | File | `/admin/index.php?page=manage_lot` | High
72 | File | `/admin/list_addr_fwresource_ip.php` | High
73 | File | `/admin/login.php` | High
74 | File | `/Admin/login.php` | High
75 | File | `/admin/maintenance/manage_category.php` | High
76 | File | `/admin/makehtml_freelist_action.php` | High
77 | File | `/admin/manage-ambulance.php` | High
78 | File | `/admin/manage-users.php` | High
79 | File | `/admin/manage_user.php` | High
80 | File | `/admin/modal_add_product.php` | High
81 | File | `/admin/network/ajax_getChannelList` | High
82 | File | `/admin/network/diag_iperf` | High
83 | File | `/admin/network/diag_ping6` | High
84 | File | `/admin/network/wifi_schedule` | High
85 | File | `/admin/orders/view_order.php` | High
86 | File | `/admin/pages/subjects.php` | High
87 | File | `/admin/payment.php` | High
88 | File | `/admin/plugin.php` | High
89 | File | `/admin/positions_add.php` | High
90 | File | `/admin/print.php` | High
91 | File | `/admin/products/index.php` | High
92 | File | `/admin/profile.php` | High
93 | File | `/Admin/Proses_Edit_Akun.php` | High
94 | File | `/Admin/registration.php` | High
95 | File | `/admin/reset-password.php` | High
96 | File | `/admin/role` | Medium
97 | File | `/admin/rooms.php` | High
98 | File | `/admin/search-invoices.php` | High
99 | File | `/admin/service` | High
100 | File | `/admin/settings/` | High
101 | File | `/admin/sn_package/sn_https` | High
102 | File | `/admin/store.php` | High
103 | File | `/admin/students/manage.php` | High
104 | File | `/admin/subject.php` | High
105 | File | `/admin/sys_sql_query.php` | High
106 | File | `/admin/tag.php` | High
107 | File | `/admin/tag/save` | High
108 | File | `/admin/template/edit` | High
109 | File | `/admin/user-search.php` | High
110 | File | `/admin/user.php` | High
111 | File | `/admin/user/manage_user.php` | High
112 | File | `/admin/userprofile.php` | High
113 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
114 | File | `/adminpanel/admin/query/loginExe.php` | High
115 | File | `/admin_route/inc_service_credits.php` | High
116 | File | `/admin_system/api.php` | High
117 | File | `/ajax.php?action=delete_block` | High
118 | File | `/ajax.php?action=save_establishment` | High
119 | File | `/ajax/getBasicInfo.php` | High
120 | File | `/api.php` | Medium
121 | File | `/api/` | Low
122 | File | `/api/admin/store/product/save` | High
123 | File | `/api/controllers/admin/app/AppController.php` | High
124 | File | `/api/dept` | Medium
125 | File | `/api/file/multiDownload` | High
126 | File | `/api/process.php` | High
127 | File | `/api/role` | Medium
128 | File | `/api/sys/login` | High
129 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
130 | File | `/api/system/user?deptId=1&page=1&size=10` | High
131 | File | `/api/upload` | Medium
132 | File | `/api/user` | Medium
133 | File | `/api/v2/open/rowsInfo` | High
134 | File | `/api/v2/open/tablesInfo` | High
135 | File | `/app/admin/controller/Upload.php` | High
136 | File | `/app/admin/view/web_user.html` | High
137 | File | `/app/api/controller/collect.php` | High
138 | File | `/application/controller/Pelanggan.php` | High
139 | File | `/application/pay/controller/Api.php` | High
140 | File | `/apps/api/views/deploy_api.py` | High
141 | File | `/apps/system/api/user.go` | High
142 | File | `/article/DelectArticleById/` | High
143 | File | `/assoc_table.php` | High
144 | File | `/authenticate.php` | High
145 | File | `/b2b-supermarket/shopping-cart` | High
146 | File | `/backend/admin/his_admin_add_vendor.php` | High
147 | File | `/backup.pl` | Medium
148 | File | `/bilal final/edit_stud.php` | High
149 | File | `/billaction.php` | High
150 | File | `/boaform/wlan_basic_set.cgi` | High
151 | File | `/book_car.php` | High
152 | File | `/branch_viewmore.php` | High
153 | File | `/bsms_ci/index.php` | High
154 | ... | ... | ...

There are 1370 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/hvs-consulting/ioc_signatures/blob/main/Novter/HvS_Novter_2021-02_IOCs.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
