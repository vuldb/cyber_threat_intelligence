# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | - | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | - | High
3 | [24.88.87.29](https://vuldb.com/?ip.24.88.87.29) | syn-024-088-087-029.res.spectrum.com | - | High
4 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | - | High
5 | [32.143.50.222](https://vuldb.com/?ip.32.143.50.222) | - | - | High
6 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | - | High
7 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | - | High
8 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | - | High
9 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | - | High
10 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | - | High
11 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | - | High
12 | [68.76.150.97](https://vuldb.com/?ip.68.76.150.97) | 68-76-150-97.lightspeed.hstntx.sbcglobal.net | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pawn Storm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/%61dmin/api/logs` | High
2 | File | `/?s=doudou&c=file&a=list` | High
3 | File | `/aa` | Low
4 | File | `/aboutus.php` | Medium
5 | File | `/AcceptZip.ashx` | High
6 | File | `/Account/EditProfile` | High
7 | File | `/add-category.php` | High
8 | File | `/add-normal-ticket.php` | High
9 | File | `/add_classes.php` | High
10 | File | `/add_employee.php` | High
11 | File | `/admin#themes` | High
12 | File | `/admin-api/mp/material/upload-permanent` | High
13 | File | `/admin-api/upload_image` | High
14 | File | `/admin-cp/logs/email` | High
15 | File | `/admin-cp/media` | High
16 | File | `/admin-cp/plugin/editor` | High
17 | File | `/admin-page.php` | High
18 | File | `/admin-profile.php` | High
19 | File | `/admin/` | Low
20 | File | `/admin/?page=system_info` | High
21 | File | `/admin/about-us.php` | High
22 | File | `/admin/action/delete-vaccine.php` | High
23 | File | `/admin/add-doctor.php` | High
24 | File | `/admin/add-services.php` | High
25 | File | `/admin/add_student.php` | High
26 | File | `/admin/add_teacher.php` | High
27 | File | `/admin/admin-profile.php` | High
28 | File | `/admin/AdminLogin.php` | High
29 | File | `/admin/admin_addnew_product.php` | High
30 | File | `/admin/ajax.php?action=add_to_cart` | High
31 | File | `/admin/ajax.php?action=login` | High
32 | File | `/admin/all-applications.php` | High
33 | File | `/admin/api/theme-edit/` | High
34 | File | `/admin/app/asset_crud.php` | High
35 | File | `/admin/app/profile_crud.php` | High
36 | File | `/admin/app/soulwinning_crud.php` | High
37 | File | `/admin/app/web_crud.php` | High
38 | File | `/admin/approve.php` | High
39 | File | `/admin/article/add/do` | High
40 | File | `/admin/article/list` | High
41 | File | `/admin/auth/roles` | High
42 | File | `/admin/booking-bwdates-reports-details.php` | High
43 | File | `/admin/book_add.php` | High
44 | File | `/admin/bwdates-report-details.php` | High
45 | File | `/admin/carousels/save` | High
46 | File | `/Admin/Category.php` | High
47 | File | `/admin/category.php` | High
48 | File | `/admin/category_update.php` | High
49 | File | `/admin/changeimage.php` | High
50 | File | `/admin/conferences/list/` | High
51 | File | `/admin/contact-us.php` | High
52 | File | `/admin/delete_file.php` | High
53 | File | `/admin/edit-boat.php` | High
54 | File | `/admin/edit-category.php` | High
55 | File | `/admin/edit-guard-detail.php` | High
56 | File | `/admin/edit-pass-detail.php` | High
57 | File | `/admin/edit-subcategory.php` | High
58 | File | `/admin/edit_action.php` | High
59 | File | `/Admin/edit_profile.php` | High
60 | File | `/admin/employee/index.php` | High
61 | File | `/admin/file/delete.do` | High
62 | File | `/admin/file/rename.do` | High
63 | File | `/admin/file/upload.do` | High
64 | File | `/admin/forgot-password.php` | High
65 | File | `/admin/googleads.php` | High
66 | File | `/admin/group` | Medium
67 | File | `/admin/group/list/` | High
68 | File | `/admin/home/index.html` | High
69 | File | `/admin/index.php` | High
70 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
71 | File | `/Admin/InsertCategory.php` | High
72 | File | `/admin/leancloud.php` | High
73 | File | `/admin/level.php` | High
74 | File | `/admin/manage-pages.php` | High
75 | File | `/admin/manage-users.php` | High
76 | File | `/admin/manage_user.php` | High
77 | File | `/admin/member_update.php` | High
78 | File | `/admin/menus/view_menu.php` | High
79 | File | `/admin/model/addOrUpdate` | High
80 | File | `/admin/modules/lesson/index.php` | High
81 | File | `/admin/order.php` | High
82 | File | `/admin/pass-details.php` | High
83 | File | `/admin/payment.php` | High
84 | File | `/admin/post-avehical.php` | High
85 | File | `/admin/print.php` | High
86 | File | `/admin/print_barcode.php` | High
87 | File | `/admin/profile.php` | High
88 | File | `/admin/publishnews.php` | High
89 | File | `/admin/registration.php` | High
90 | File | `/admin/reports/index.php` | High
91 | File | `/admin/reportupload.aspx` | High
92 | File | `/admin/save_teacher.php` | High
93 | File | `/admin/search-booking-request.php` | High
94 | File | `/admin/search-medicalcard.php` | High
95 | File | `/admin/search-pass.php` | High
96 | File | `/admin/search.php` | High
97 | File | `/admin/service/stop/` | High
98 | File | `/admin/settings/` | High
99 | File | `/admin/sign/out` | High
100 | File | `/admin/student.php` | High
101 | File | `/admin/subscriber-csv.php` | High
102 | File | `/admin/sys/role/list` | High
103 | File | `/admin/theme/Upload.html` | High
104 | File | `/admin/update_room.php` | High
105 | File | `/admin/upload/upimage.html` | High
106 | File | `/admin/vacancy/controller.php` | High
107 | File | `/admin/view-enquiry.php` | High
108 | File | `/admin/view-foreigner-ticket.php` | High
109 | File | `/admin_paylog.php` | High
110 | File | `/admin_user.php` | High
111 | File | `/aim/storage/query.py` | High
112 | File | `/ajax.php?action=delete_member` | High
113 | File | `/ajax.php?action=delete_trainer` | High
114 | File | `/ajax.php?action=login` | High
115 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
116 | File | `/ample/app/ajax/member_data.php` | High
117 | File | `/api.php` | Medium
118 | File | `/api/admin/question/edit` | High
119 | File | `/api/deploy/upload` | High
120 | File | `/Api/FileUploadApi.ashx` | High
121 | File | `/api/front/search/books` | High
122 | File | `/api/GylOperator/LoadData` | High
123 | File | `/api/login/auth` | High
124 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
125 | File | `/api/studentPWD` | High
126 | File | `/Api/TinyMce/UploadAjax.ashx` | High
127 | File | `/app/controller/Upload.php` | High
128 | File | `/app/Http/Controllers/ImageController.php` | High
129 | ... | ... | ...

There are 1142 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
