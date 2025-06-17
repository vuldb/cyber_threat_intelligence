# GoatRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GoatRAT](https://vuldb.com/?actor.goatrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.goatrat](https://vuldb.com/?actor.goatrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GoatRAT:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [DE](https://vuldb.com/?country.de)
* ...

There are 10 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-25, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GoatRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/;/admin/role/edit` | High
4 | File | `/?page=reserve` | High
5 | File | `/?page=tickets` | High
6 | File | `/?page=tracks` | High
7 | File | `/aboutadd.php` | High
8 | File | `/Account/login.php` | High
9 | File | `/Actions.php?a=login` | High
10 | File | `/addclient1.php` | High
11 | File | `/addcompany.php` | High
12 | File | `/add_achievement_details.php` | High
13 | File | `/add_classes.php` | High
14 | File | `/add_new_purchase.php?action=is_supplier` | High
15 | File | `/add_new_supplier.php` | High
16 | File | `/add_personal_details.php` | High
17 | File | `/admin-dashboard` | High
18 | File | `/admin-manage-user.php` | High
19 | File | `/admin.php?p=/Area/index#tab=t2` | High
20 | File | `/admin/` | Low
21 | File | `/admin/?page=inventory/view_inventory&id=2` | High
22 | File | `/admin/?page=musics/manage_music` | High
23 | File | `/admin/?page=system_info/contact_info` | High
24 | File | `/admin/?page=user/list` | High
25 | File | `/admin/aboutus.php` | High
26 | File | `/admin/about_edit.php?action=modify` | High
27 | File | `/Admin/add-admin.php` | High
28 | File | `/admin/add-propertytype.php` | High
29 | File | `/admin/add-services.php` | High
30 | File | `/admin/admin-profile.php` | High
31 | File | `/admin/admin-update-employee.php` | High
32 | File | `/admin/admin.php` | High
33 | File | `/admin/ad_list.php?action=pass` | High
34 | File | `/admin/ajax.php?action=login` | High
35 | File | `/Admin/akun_edit.php` | High
36 | File | `/admin/app/login_crud.php` | High
37 | File | `/admin/article.php` | High
38 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
39 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
40 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
41 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
42 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
43 | File | `/admin/attendance_action.php` | High
44 | File | `/admin/book-details.php` | High
45 | File | `/admin/bwdates-report-details.php` | High
46 | File | `/admin/campsdetails.php` | High
47 | File | `/admin/card-bwdates-reports-details.php` | High
48 | File | `/admin/case-status` | High
49 | File | `/admin/case-type` | High
50 | File | `/admin/changeimage.php` | High
51 | File | `/admin/check_admin.php` | High
52 | File | `/admin/class.php?dowhat=modifyclass` | High
53 | File | `/admin/company/index.php` | High
54 | File | `/admin/config_Anticrack.php` | High
55 | File | `/admin/config_ISCGroupNoCache.php` | High
56 | File | `/admin/contactus.php` | High
57 | File | `/admin/content/book` | High
58 | File | `/admin/create-package.php` | High
59 | File | `/admin/dialog/select_images_post.php` | High
60 | File | `/admin/edit-boat.php` | High
61 | File | `/admin/edit-brand.php` | High
62 | File | `/admin/edit-subadmin.php` | High
63 | File | `/admin/edit-user.php` | High
64 | File | `/admin/editorder.php` | High
65 | File | `/admin/edit_categories.php` | High
66 | File | `/admin/edit_customer.php` | High
67 | File | `/admin/educloud/videobind.html` | High
68 | File | `/admin/emp-profile-avatar.php` | High
69 | File | `/admin/File/fileUpload` | High
70 | File | `/admin/foreigner-bwdates-reports-details.php` | High
71 | File | `/admin/forgot-password.php` | High
72 | File | `/admin/index.php` | High
73 | File | `/admin/inquiries/view_details.php` | High
74 | File | `/admin/login.php` | High
75 | File | `/admin/login_process.php` | High
76 | File | `/admin/maintenance/manage_brand.php` | High
77 | File | `/admin/maintenance/manage_department.php` | High
78 | File | `/admin/massage.php` | High
79 | File | `/admin/modules/product/controller.php?action=add` | High
80 | File | `/admin/mod_room/controller.php?action=add` | High
81 | File | `/admin/network/diag_ping6` | High
82 | File | `/admin/network/diag_pinginterface` | High
83 | File | `/admin/network/diag_traceroute` | High
84 | File | `/admin/normal-search.php` | High
85 | File | `/admin/notes/create` | High
86 | File | `/admin/pages/list` | High
87 | File | `/admin/print.php` | High
88 | File | `/admin/profile.php` | High
89 | File | `/admin/publishnews.php` | High
90 | File | `/admin/registration.php` | High
91 | File | `/admin/rooms.php` | High
92 | File | `/admin/search-appointment.php` | High
93 | File | `/admin/search-directory.php.` | High
94 | File | `/admin/search-property.php` | High
95 | File | `/admin/singlelogin.php` | High
96 | File | `/admin/sn_package/sn_https` | High
97 | File | `/admin/store.php` | High
98 | File | `/admin/subcategory.php` | High
99 | File | `/admin/sys/menu/list` | High
100 | File | `/admin/tag.php` | High
101 | File | `/admin/tasks` | Medium
102 | File | `/admin/template` | High
103 | File | `/admin/template/edit` | High
104 | File | `/admin/template/update` | High
105 | File | `/admin/twitter.php` | High
106 | File | `/admin/update_room.php` | High
107 | File | `/admin/update_user.php` | High
108 | File | `/admin/update_users.php` | High
109 | File | `/admin/user-search.php` | High
110 | File | `/admin/user.php` | High
111 | File | `/admin/user/index.php` | High
112 | File | `/admin/vendor` | High
113 | File | `/admin/view-enquiry.php` | High
114 | File | `/adminPage/main/upload` | High
115 | File | `/admin_class.php` | High
116 | File | `/ajax.php` | Medium
117 | File | `/ajax.php?action=load_answered` | High
118 | File | `/ajax.php?action=save_establishment` | High
119 | File | `/ajax.php?action=save_user` | High
120 | File | `/ajax.php?action=signup` | High
121 | File | `/ajax/getBasicInfo.php` | High
122 | File | `/ajax/get_patient_history.php` | High
123 | File | `/api/config/list` | High
124 | File | `/api/controllers/common/UploadsController.php` | High
125 | File | `/api/dept` | Medium
126 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
127 | File | `/api/user` | Medium
128 | File | `/api/v2/maps` | Medium
129 | File | `/app/action/add_staff.php` | High
130 | File | `/app/api/controller/Site.php` | High
131 | File | `/application/index/controller/Databasesource.php` | High
132 | File | `/application/index/controller/Datament.php` | High
133 | File | `/application/index/controller/Screen.php` | High
134 | File | `/application/index/controller/Unity.php` | High
135 | File | `/apps/system/router/upload.go` | High
136 | File | `/assets/php/upload.php` | High
137 | File | `/attendancelist.php` | High
138 | File | `/billing/bill/edit/` | High
139 | ... | ... | ...

There are 1238 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ddanchev.blogspot.com/2024/01/whos-behind-goatrat.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
