# GoatRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GoatRAT](https://vuldb.com/?actor.goatrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.goatrat](https://vuldb.com/?actor.goatrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GoatRAT:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 8 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GoatRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/account/delivery` | High
3 | File | `/Actions.php?a=login` | High
4 | File | `/addclient1.php` | High
5 | File | `/add_classes.php` | High
6 | File | `/admin-manage-user.php` | High
7 | File | `/admin.php?p=/Area/index#tab=t2` | High
8 | File | `/admin/?page=musics/manage_music` | High
9 | File | `/admin/?page=user/list` | High
10 | File | `/admin/about_edit.php?action=modify` | High
11 | File | `/Admin/add-admin.php` | High
12 | File | `/admin/admin-profile.php` | High
13 | File | `/admin/admin-update-employee.php` | High
14 | File | `/admin/admin.php` | High
15 | File | `/admin/app/login_crud.php` | High
16 | File | `/admin/book_row.php` | High
17 | File | `/admin/budget/manage_budget.php` | High
18 | File | `/admin/bwdates-report-details.php` | High
19 | File | `/admin/case-status` | High
20 | File | `/admin/case-type` | High
21 | File | `/admin/check_admin.php` | High
22 | File | `/admin/class.php?dowhat=modifyclass` | High
23 | File | `/admin/company/index.php` | High
24 | File | `/admin/config_Anticrack.php` | High
25 | File | `/admin/config_ISCGroupNoCache.php` | High
26 | File | `/admin/contacts/organizations/edit/2` | High
27 | File | `/admin/curriculum/view_curriculum.php` | High
28 | File | `/admin/dialog/select_images_post.php` | High
29 | File | `/admin/edit_categories.php` | High
30 | File | `/admin/educloud/videobind.html` | High
31 | File | `/admin/emp-profile-avatar.php` | High
32 | File | `/admin/foreigner-bwdates-reports-details.php` | High
33 | File | `/admin/forgot-password.php` | High
34 | File | `/admin/index3.php` | High
35 | File | `/admin/ind_backstage.php` | High
36 | File | `/admin/list_addr_fwresource_ip.php` | High
37 | File | `/admin/login.php` | High
38 | File | `/admin/maintenance/manage_brand.php` | High
39 | File | `/admin/modal_add_product.php` | High
40 | File | `/admin/modules/product/controller.php?action=add` | High
41 | File | `/admin/mod_room/controller.php?action=add` | High
42 | File | `/admin/normal-search.php` | High
43 | File | `/admin/notes/create` | High
44 | File | `/admin/order.php` | High
45 | File | `/admin/pages/list` | High
46 | File | `/admin/pages/student-print.php` | High
47 | File | `/admin/reg.php` | High
48 | File | `/admin/reportupload.aspx` | High
49 | File | `/admin/rooms.php` | High
50 | File | `/admin/search-directory.php.` | High
51 | File | `/admin/singlelogin.php` | High
52 | File | `/admin/singlelogin.php?submit=1` | High
53 | File | `/admin/students/manage_academic.php` | High
54 | File | `/admin/sys_sql_query.php` | High
55 | File | `/admin/tasks` | Medium
56 | File | `/admin/template` | High
57 | File | `/admin/template/edit` | High
58 | File | `/admin/template/update` | High
59 | File | `/admin/test_status.php` | High
60 | File | `/admin/twitter.php` | High
61 | File | `/admin/upload.php` | High
62 | File | `/admin/user/index.php` | High
63 | File | `/admin/user/manage_user.php` | High
64 | File | `/admin/vendor` | High
65 | File | `/admin/vote_edit.php` | High
66 | File | `/adminPage/main/upload` | High
67 | File | `/admin_class.php` | High
68 | File | `/admin_route/inc_service_credits.php` | High
69 | File | `/adplanet/PlanetUser` | High
70 | File | `/ajax.php` | Medium
71 | File | `/ajax.php?action=load_answered` | High
72 | File | `/ajax.php?action=save_establishment` | High
73 | File | `/ajax.php?action=save_user` | High
74 | File | `/ajax/getBasicInfo.php` | High
75 | File | `/ajax/get_patient_history.php` | High
76 | File | `/ample/app/action/edit_product.php` | High
77 | File | `/ample/app/ajax/member_data.php` | High
78 | File | `/api/controllers/common/UploadsController.php` | High
79 | File | `/api/dept` | Medium
80 | File | `/api/ping` | Medium
81 | File | `/api/sys/login` | High
82 | File | `/api/user` | Medium
83 | File | `/api/v2/maps` | Medium
84 | File | `/api/wechat/app_auth` | High
85 | File | `/app/api/controller/collect.php` | High
86 | File | `/application/index/controller/Databasesource.php` | High
87 | File | `/application/index/controller/Datament.php` | High
88 | File | `/application/index/controller/Screen.php` | High
89 | File | `/application/index/controller/Unity.php` | High
90 | File | `/apps/system/router/upload.go` | High
91 | File | `/assets/php/upload.php` | High
92 | File | `/attendancelist.php` | High
93 | File | `/author_posts.php` | High
94 | File | `/b2b-supermarket/shopping-cart` | High
95 | File | `/billing/bill/edit/` | High
96 | File | `/blog` | Low
97 | File | `/bolt/editcontent/showcases` | High
98 | File | `/catalog/all-products` | High
99 | File | `/category.php` | High
100 | File | `/cgi-bin/cstecgi.cgi` | High
101 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
102 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
103 | File | `/cgi-bin/hd_config.cgi` | High
104 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
105 | File | `/cgi-bin/myMusic.cgi` | High
106 | File | `/cgi-bin/nas_sharing.cgi` | High
107 | File | `/cgi-bin/p1_ftpserver.php` | High
108 | File | `/cgi-bin/photocenter_mgr.cgi` | High
109 | File | `/cgi-bin/s3.cgi` | High
110 | File | `/cgi-bin/webfile_mgr.cgi` | High
111 | File | `/cgi-bin/widget_api.cgi` | High
112 | File | `/classes/Master.php` | High
113 | File | `/classes/Master.php?f=delete_category` | High
114 | File | `/classes/Master.php?f=delete_inquiry` | High
115 | File | `/classes/Master.php?f=delete_service` | High
116 | File | `/classes/Master.php?f=save_category` | High
117 | File | `/classes/Master.php?f=save_item` | High
118 | File | `/classes/Master.php?f=save_package` | High
119 | File | `/classes/Users.php?f=delete` | High
120 | File | `/classes/Users.php?f=save` | High
121 | File | `/classes/Users.php?f=save_client` | High
122 | ... | ... | ...

There are 1081 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ddanchev.blogspot.com/2024/01/whos-behind-goatrat.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
