# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/99/ImportSQLTable` | High
2 | File | `/Account/EditProfile` | High
3 | File | `/add-courier.php` | High
4 | File | `/add-customer.php` | High
5 | File | `/add-notes.php` | High
6 | File | `/addclient1.php` | High
7 | File | `/admin#themes` | High
8 | File | `/admin-api/upload_image` | High
9 | File | `/admin-cp/media` | High
10 | File | `/admin-cp/setting/system/general` | High
11 | File | `/admin.php?mod=brand&act=del` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=back_order/view_bo` | High
14 | File | `/admin/?page=categories/view_category` | High
15 | File | `/admin/?page=inventory/view_inventory&id=2` | High
16 | File | `/admin/aboutus.php` | High
17 | File | `/admin/add-directory.php` | High
18 | File | `/admin/add-subadmin.php` | High
19 | File | `/admin/add_city.php` | High
20 | File | `/admin/add_postlogin.php` | High
21 | File | `/admin/add_trainers.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/admin.php` | High
24 | File | `/Admin/adminlogin.php` | High
25 | File | `/admin/AdminLogin.php` | High
26 | File | `/admin/admin_login.php` | High
27 | File | `/admin/admin_user.php` | High
28 | File | `/admin/ajax.php?action=save_area` | High
29 | File | `/admin/all_users.php` | High
30 | File | `/admin/app/role_crud.php` | High
31 | File | `/admin/applicants/index.php` | High
32 | File | `/admin/apply.php` | High
33 | File | `/admin/appointment.php` | High
34 | File | `/admin/archives_add.php` | High
35 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
36 | File | `/admin/backup/backups.php` | High
37 | File | `/admin/ballot_down.php` | High
38 | File | `/admin/ballot_up.php` | High
39 | File | `/admin/candidates.php` | High
40 | File | `/admin/category_row.php` | High
41 | File | `/admin/client_user` | High
42 | File | `/admin/content/book` | High
43 | File | `/admin/delete_pending.php` | High
44 | File | `/admin/edit-post.php` | High
45 | File | `/admin/edit-services.php` | High
46 | File | `/admin/edit-state.php` | High
47 | File | `/admin/edit-subadmin.php` | High
48 | File | `/admin/edit-subcategory.php` | High
49 | File | `/admin/editempeducation.php` | High
50 | File | `/admin/edit_state.php` | High
51 | File | `/admin/execedituser.php` | High
52 | File | `/admin/fetch_product_details.php` | High
53 | File | `/admin/file_manager/export` | High
54 | File | `/admin/images/add` | High
55 | File | `/admin/index.php` | High
56 | File | `/admin/index.php/news/edit` | High
57 | File | `/admin/indexConfigs/save` | High
58 | File | `/admin/insert-product.php` | High
59 | File | `/admin/inv-print.php` | High
60 | File | `/admin/list_localuser.php` | High
61 | File | `/admin/login.php` | High
62 | File | `/Admin/login.php` | High
63 | File | `/admin/manage-category.php` | High
64 | File | `/admin/manage-notices.php` | High
65 | File | `/admin/manage-tickets.php` | High
66 | File | `/admin/menu_save.php` | High
67 | File | `/admin/mod_room/controller.php?action=add` | High
68 | File | `/admin/offenses/view_details.php` | High
69 | File | `/admin/operations/travellers.php` | High
70 | File | `/admin/plan/examExportPDF` | High
71 | File | `/admin/positions.php` | High
72 | File | `/admin/posts.php?source=add_post` | High
73 | File | `/admin/print-payment.php` | High
74 | File | `/admin/print.php` | High
75 | File | `/admin/products/manage_product.php` | High
76 | File | `/admin/reg-users.php` | High
77 | File | `/admin/registration.php` | High
78 | File | `/admin/reset-password.php` | High
79 | File | `/Admin/resultdetails.php` | High
80 | File | `/admin/return_add.php` | High
81 | File | `/admin/rooms.php` | High
82 | File | `/admin/sales/manage_sale.php` | High
83 | File | `/admin/save_student.php` | High
84 | File | `/admin/search-appointment.php` | High
85 | File | `/admin/search-directory.php` | High
86 | File | `/admin/search-maid.php` | High
87 | File | `/admin/search1.php` | High
88 | File | `/admin/services/manage.php` | High
89 | File | `/admin/services/manage_service.php` | High
90 | File | `/admin/subject.php` | High
91 | File | `/admin/suppliers/view_details.php` | High
92 | File | `/admin/sys/menu/list` | High
93 | File | `/admin/sys/user/list` | High
94 | File | `/admin/test_status.php` | High
95 | File | `/admin/user.php` | High
96 | File | `/admin/user/user-move-run.php` | High
97 | File | `/admin/users.php` | High
98 | File | `/adminLogin.php` | High
99 | File | `/adminprofile.php` | High
100 | File | `/admin_class.php` | High
101 | File | `/adv_dhcps.php` | High
102 | File | `/agent/profile/edit` | High
103 | File | `/ajax.php` | Medium
104 | File | `/ajax.php?action=delete_employee_attendance_single` | High
105 | File | `/ajax.php?action=save_product` | High
106 | File | `/ajax.php?action=save_student` | High
107 | File | `/ajax/action.php` | High
108 | File | `/alphaware/summary.php` | High
109 | File | `/Android/data/com.myairtelapp/files/` | High
110 | File | `/api/blade-system/menu/list?updatexml` | High
111 | File | `/api/blade-user/export-user` | High
112 | File | `/api/comment/add` | High
113 | File | `/api/config/list` | High
114 | File | `/api/deploy/upload` | High
115 | File | `/api/semantic/database/testConnect` | High
116 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
117 | File | `/api/v1/challenges//solves` | High
118 | File | `/api/v2/open/rowsInfo` | High
119 | File | `/app-api/v1/members/openid/` | High
120 | File | `/app/checkout/delete.php` | High
121 | File | `/applyleave.php` | High
122 | File | `/appointment.php` | High
123 | File | `/appy.cgi` | Medium
124 | File | `/assetsGroupReport/fixedAssetsList.j%73p` | High
125 | ... | ... | ...

There are 1112 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
