# GoatRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GoatRAT](https://vuldb.com/?actor.goatrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.goatrat](https://vuldb.com/?actor.goatrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GoatRAT:

* [US](https://vuldb.com/?country.us)
* [AT](https://vuldb.com/?country.at)
* [IT](https://vuldb.com/?country.it)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GoatRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.133.1.108](https://vuldb.com/?ip.31.133.1.108) | unused-31-133-1-108.hosteam.pl | - | High
2 | [51.81.56.136](https://vuldb.com/?ip.51.81.56.136) | ns1001063.ip-51-81-56.us | - | High
3 | [51.81.93.37](https://vuldb.com/?ip.51.81.93.37) | ns1003996.ip-51-81-93.us | - | High
4 | [51.148.150.203](https://vuldb.com/?ip.51.148.150.203) | 51-148-150-203.dsl.in-addr.zen.co.uk | - | High
5 | [80.241.214.102](https://vuldb.com/?ip.80.241.214.102) | tor.kroell.net | - | High
6 | [81.7.16.177](https://vuldb.com/?ip.81.7.16.177) | tor.blue.kundencontroller.de | - | High
7 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GoatRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GoatRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `../mtd/Config/Sha1Account1` | High
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/;/admin/role/edit` | High
5 | File | `/?page=reserve` | High
6 | File | `/?page=tickets` | High
7 | File | `/aboutadd.php` | High
8 | File | `/Account/login.php` | High
9 | File | `/add-product.php` | High
10 | File | `/add-subadmin.php` | High
11 | File | `/addcompany.php` | High
12 | File | `/addProduct.php` | High
13 | File | `/add_achievement_details.php` | High
14 | File | `/add_new_purchase.php?action=is_supplier` | High
15 | File | `/add_new_supplier.php` | High
16 | File | `/add_personal_details.php` | High
17 | File | `/add_sales_print.php` | High
18 | File | `/admin#themes` | High
19 | File | `/admin-cp/menus` | High
20 | File | `/admin-cp/permalinks` | High
21 | File | `/admin-dashboard` | High
22 | File | `/admin.php/addon/index` | High
23 | File | `/admin/` | Low
24 | File | `/admin/?page=back_order/view_bo` | High
25 | File | `/admin/?page=inventory/view_inventory&id=2` | High
26 | File | `/admin/?page=system_info/contact_info` | High
27 | File | `/admin/aboutus.php` | High
28 | File | `/admin/accepted-appointment.php` | High
29 | File | `/Admin/add-admin.php` | High
30 | File | `/admin/add-propertytype.php` | High
31 | File | `/admin/add-services.php` | High
32 | File | `/admin/add-table.php` | High
33 | File | `/admin/addroom.php` | High
34 | File | `/admin/admin-profile.php` | High
35 | File | `/admin/ad_list.php?action=pass` | High
36 | File | `/admin/ajax.php?action=login` | High
37 | File | `/Admin/akun_edit.php` | High
38 | File | `/admin/app/role_crud.php` | High
39 | File | `/admin/article.php` | High
40 | File | `/Admin/assets/backend/seller/add_seller.php` | High
41 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
42 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
43 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
44 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
45 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
46 | File | `/admin/attendance_action.php` | High
47 | File | `/admin/book-details.php` | High
48 | File | `/admin/bwdates-report-details.php` | High
49 | File | `/admin/bwdates-report-result.php` | High
50 | File | `/admin/bwdates-reports-details.php` | High
51 | File | `/admin/campsdetails.php` | High
52 | File | `/admin/card-bwdates-reports-details.php` | High
53 | File | `/admin/changeimage.php` | High
54 | File | `/admin/checkout_query.php` | High
55 | File | `/admin/check_availability.php` | High
56 | File | `/admin/contactus.php` | High
57 | File | `/admin/content/book` | High
58 | File | `/Admin/Controller/CustomController.class.php` | High
59 | File | `/admin/create-package.php` | High
60 | File | `/admin/delete_pending.php` | High
61 | File | `/admin/doctor-specilization.php` | High
62 | File | `/admin/edit-admin.php` | High
63 | File | `/admin/edit-boat.php` | High
64 | File | `/admin/edit-brand.php` | High
65 | File | `/admin/edit-subadmin.php` | High
66 | File | `/admin/edit-team.php` | High
67 | File | `/admin/edit-user.php` | High
68 | File | `/admin/editorder.php` | High
69 | File | `/admin/edit_customer.php` | High
70 | File | `/admin/edit_expenses.php` | High
71 | File | `/admin/edit_product.php` | High
72 | File | `/admin/eligibility.php` | High
73 | File | `/admin/File/fileUpload` | High
74 | File | `/admin/finished.php` | High
75 | File | `/admin/forget-password.php` | High
76 | File | `/admin/index.php` | High
77 | File | `/admin/inquiries/view_details.php` | High
78 | File | `/admin/lastthirtyays-reg-users.php` | High
79 | File | `/admin/login.php` | High
80 | File | `/admin/login_process.php` | High
81 | File | `/admin/maintenance/manage_department.php` | High
82 | File | `/admin/manage-art-medium.php` | High
83 | File | `/admin/manage-foreigners-ticket.php` | High
84 | File | `/admin/manage-users.php` | High
85 | File | `/admin/massage.php` | High
86 | File | `/Admin/match.php` | High
87 | File | `/admin/modules/lesson/index.php` | High
88 | File | `/admin/network/diag_ping6` | High
89 | File | `/admin/network/diag_pinginterface` | High
90 | File | `/admin/network/diag_traceroute` | High
91 | File | `/admin/new-autoortaxi-entry-form.php` | High
92 | File | `/admin/positions_edit.php` | High
93 | File | `/admin/print.php` | High
94 | File | `/admin/profile.php` | High
95 | File | `/admin/publishnews.php` | High
96 | File | `/admin/registration.php` | High
97 | File | `/admin/search-appointment.php` | High
98 | File | `/admin/search-property.php` | High
99 | File | `/admin/search1.php` | High
100 | File | `/admin/sn_package/sn_https` | High
101 | File | `/admin/store.php` | High
102 | File | `/Admin/student.php` | High
103 | File | `/admin/students.php` | High
104 | File | `/admin/subcategory.php` | High
105 | File | `/admin/sys/menu/list` | High
106 | File | `/admin/tag.php` | High
107 | File | `/admin/template/edit` | High
108 | File | `/admin/template/update` | High
109 | File | `/admin/theme/Upload.html` | High
110 | File | `/admin/topic/list` | High
111 | File | `/admin/update_room.php` | High
112 | File | `/admin/update_s1.php` | High
113 | File | `/admin/update_user.php` | High
114 | File | `/admin/update_users.php` | High
115 | File | `/admin/user-search.php` | High
116 | File | `/admin/user.php` | High
117 | File | `/admin/user/edit.do` | High
118 | File | `/admin/usersetting.php` | High
119 | File | `/admin/view-enquiry.php` | High
120 | File | `/admin/view-user-queries.php` | High
121 | File | `/admin/view_sendlist.php` | High
122 | File | `/admin/view_vacancy.php` | High
123 | File | `/admin/voters_row.php` | High
124 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
125 | File | `/adminPage/conf/check` | High
126 | File | `/admin_class.php` | High
127 | File | `/admin_single_student_update.php` | High
128 | File | `/adv_mac_filter.php` | High
129 | File | `/AGE0000700/GetImageMedico?fooId=1` | High
130 | File | `/ajax.php?action=delete_plan` | High
131 | File | `/ajax.php?action=signup` | High
132 | File | `/api/admin/common/download/templates` | High
133 | File | `/api/admin/sys-message/` | High
134 | File | `/api/article/del` | High
135 | File | `/api/blade-user/submit` | High
136 | File | `/api/config/list` | High
137 | File | `/api/esps` | Medium
138 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
139 | File | `/api/system/user/getAvatar` | High
140 | File | `/api/undo/` | Medium
141 | File | `/api/users/updateAvatar` | High
142 | File | `/api/v1/serve/awel/flow/import` | High
143 | File | `/api/v2/serve/awel/flow/import` | High
144 | File | `/api/wizard/getsyncpppoecfg` | High
145 | ... | ... | ...

There are 1286 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ddanchev.blogspot.com/2024/01/whos-behind-goatrat.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
