# Powload - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Powload](https://vuldb.com/?actor.powload). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powload](https://vuldb.com/?actor.powload)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Powload.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.29.155](https://vuldb.com/?ip.5.61.29.155) | 5-61-29-155.nrp.co | - | High
2 | [31.14.103.164](https://vuldb.com/?ip.31.14.103.164) | dns103164.phdns19.es | - | High
3 | [37.211.38.50](https://vuldb.com/?ip.37.211.38.50) | - | - | High
4 | [42.114.73.81](https://vuldb.com/?ip.42.114.73.81) | - | - | High
5 | [45.40.251.243](https://vuldb.com/?ip.45.40.251.243) | - | - | High
6 | [47.99.85.122](https://vuldb.com/?ip.47.99.85.122) | - | - | High
7 | [50.99.132.7](https://vuldb.com/?ip.50.99.132.7) | s50-99-132-7.ab.hsia.telus.net | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Powload_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Powload. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?p=products` | Medium
3 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
4 | File | `/Account/login.php` | High
5 | File | `/actuator/heapdump` | High
6 | File | `/add_members.php` | High
7 | File | `/admin-api/upload_image` | High
8 | File | `/admin-manage-user.php` | High
9 | File | `/admin/?page=borrow/view_borrow` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/Admin/add-admin.php` | High
12 | File | `/admin/add-ambulance.php` | High
13 | File | `/admin/addgiving.php` | High
14 | File | `/admin/addTithes.php` | High
15 | File | `/admin/add_ikev2.php` | High
16 | File | `/admin/add_postlogin.php` | High
17 | File | `/admin/add_sundaysch.php` | High
18 | File | `/admin/add_visitor.php` | High
19 | File | `/admin/admin-profile.php` | High
20 | File | `/admin/admin.php` | High
21 | File | `/admin/adminHome.php` | High
22 | File | `/admin/admin_cl.php?mudi=revPwd` | High
23 | File | `/admin/admin_user.php` | High
24 | File | `/admin/app/profile_crud.php` | High
25 | File | `/admin/applicants/controller.php` | High
26 | File | `/admin/applicants/index.php` | High
27 | File | `/admin/application-bwdates-reports-details.php` | High
28 | File | `/admin/bookdate.php` | High
29 | File | `/admin/booking-bwdates-reports-details.php` | High
30 | File | `/admin/booking-search.php` | High
31 | File | `/admin/booktime.php` | High
32 | File | `/admin/category/controller.php` | High
33 | File | `/admin/category/index.php` | High
34 | File | `/admin/category/view_category.php` | High
35 | File | `/admin/company/controller.php` | High
36 | File | `/admin/company/index.php` | High
37 | File | `/admin/config_Anticrack.php` | High
38 | File | `/admin/config_ISCGroupNoCache.php` | High
39 | File | `/admin/contact-us.php` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/delete_log.php` | High
42 | File | `/admin/div_data/delete?divId=9` | High
43 | File | `/Admin/edit-photo.php` | High
44 | File | `/admin/edit-post.php` | High
45 | File | `/admin/edit-services.php` | High
46 | File | `/Admin/edit_profile.php` | High
47 | File | `/admin/employee/controller.php` | High
48 | File | `/admin/employee/index.php` | High
49 | File | `/admin/forgot-password.php` | High
50 | File | `/admin/index.php` | High
51 | File | `/admin/list_crl_conf` | High
52 | File | `/admin/list_resource_icon.php?action=delete` | High
53 | File | `/admin/login.php` | High
54 | File | `/Admin/login.php` | High
55 | File | `/admin/maintenance/manage_category.php` | High
56 | File | `/admin/manage-ambulance.php` | High
57 | File | `/admin/manage-students.php` | High
58 | File | `/admin/menu/toEdit` | High
59 | File | `/admin/operations/expense_category.php` | High
60 | File | `/admin/orders/view_order.php` | High
61 | File | `/admin/product/manage_product.php` | High
62 | File | `/admin/receipt.php` | High
63 | File | `/admin/rooms.php` | High
64 | File | `/admin/search.php` | High
65 | File | `/admin/singlelogin.php` | High
66 | File | `/admin/tag.php` | High
67 | File | `/admin/twitter.php` | High
68 | File | `/admin/update-rooms.php` | High
69 | File | `/admin/update-users.php` | High
70 | File | `/admin/user-search.php` | High
71 | File | `/admin/user/controller.php` | High
72 | File | `/admin/user/index.php` | High
73 | File | `/admin/users.php` | High
74 | File | `/admin/users_photo.php` | High
75 | File | `/admin/vacancy/controller.php` | High
76 | File | `/admin/vacancy/index.php` | High
77 | File | `/adminPage/conf/reload` | High
78 | File | `/adminPage/conf/saveCmd` | High
79 | File | `/adminPage/main/upload` | High
80 | File | `/adminPage/www/addOver` | High
81 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
82 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
83 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
84 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
85 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
86 | File | `/adminpanel/admin/query/loginExe.php` | High
87 | File | `/api/blade-user/export-user` | High
88 | File | `/api/client/editemedia.php` | High
89 | File | `/api/process.php` | High
90 | File | `/api/v1/toolbox/device/update/swap` | High
91 | File | `/app/admin/controller/Upload.php` | High
92 | File | `/application/controller/Pelanggan.php` | High
93 | File | `/application/controller/Pengeluaran.php` | High
94 | File | `/application/controller/Transaki.php` | High
95 | File | `/apps/system/api/user.go` | High
96 | File | `/apps/system/router/upload.go` | High
97 | File | `/apps/system/services/role_menu.go` | High
98 | File | `/backend/register.php` | High
99 | File | `/billing/bill/edit/` | High
100 | File | `/bishe/register` | High
101 | File | `/cart.php` | Medium
102 | File | `/cgi-bin/cstecgi.cgi` | High
103 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
104 | File | `/change-password.php` | High
105 | File | `/check_availability.php` | High
106 | ... | ... | ...

There are 940 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0921-0928.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1207-1214.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0419-to-0426.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0503-0510.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
