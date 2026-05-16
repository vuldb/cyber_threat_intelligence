# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [VN](https://vuldb.com/?country.vn)
* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Proxy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [SystemBC](https://vuldb.com/?actor.systembc) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Proxy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
6 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
7 | [85.206.167.134](https://vuldb.com/?ip.85.206.167.134) | localhost | [SystemBC](https://vuldb.com/?actor.systembc) | High
8 | [85.206.167.139](https://vuldb.com/?ip.85.206.167.139) | localhost | [SystemBC](https://vuldb.com/?actor.systembc) | High
9 | [85.206.167.143](https://vuldb.com/?ip.85.206.167.143) | localhost | [SystemBC](https://vuldb.com/?actor.systembc) | High
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-29, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `/99/ImportSQLTable` | High
3 | File | `/aa` | Low
4 | File | `/activity/newActivityedit.php?DontCheckLogin=1&id=null&ret=mod1` | High
5 | File | `/add-book.php` | High
6 | File | `/add-notes.php` | High
7 | File | `/addCandidate.php` | High
8 | File | `/addelidetails.php` | High
9 | File | `/adduser-exec.php` | High
10 | File | `/add_classes.php` | High
11 | File | `/add_command_action` | High
12 | File | `/add_employee.php` | High
13 | File | `/add_reserve.php` | High
14 | File | `/adm/ajax.php` | High
15 | File | `/admin` | Low
16 | File | `/admin-api/mp/material/upload-temporary` | High
17 | File | `/admin.php?id=inbox` | High
18 | File | `/admin/?page=back_order/view_bo` | High
19 | File | `/admin/?page=maintenance/brand` | High
20 | File | `/admin/add-art-type.php` | High
21 | File | `/admin/add-category.php` | High
22 | File | `/admin/add-doctor.php` | High
23 | File | `/admin/add_candidate_modal.php.` | High
24 | File | `/admin/admin-profile.php` | High
25 | File | `/admin/admin/save` | High
26 | File | `/admin/admin_content_tag.php?action=save_content` | High
27 | File | `/admin/admin_product.ph` | High
28 | File | `/admin/all-applications.php` | High
29 | File | `/admin/api/theme-edit/` | High
30 | File | `/admin/app/slider_crud.php` | High
31 | File | `/Admin/assets/backend/seller/add_seller.php` | High
32 | File | `/admin/auto-taxi-entry-detail.php` | High
33 | File | `/admin/blood/update/B+.php` | High
34 | File | `/admin/category/add.do` | High
35 | File | `/admin/category_save.php` | High
36 | File | `/admin/changeimage.php` | High
37 | File | `/admin/changeimage4.php` | High
38 | File | `/admin/checkout_query.php` | High
39 | File | `/admin/check_studid.php` | High
40 | File | `/admin/class.php?dowhat=modifyclass` | High
41 | File | `/admin/complaint-search.php` | High
42 | File | `/admin/contactus.php` | High
43 | File | `/admin/content/editor` | High
44 | File | `/admin/core/new_user` | High
45 | File | `/Admin/CustomerReport.php` | High
46 | File | `/admin/deleteitem.php` | High
47 | File | `/admin/deleteroom.php` | High
48 | File | `/admin/department/add` | High
49 | File | `/admin/display-teacher.php` | High
50 | File | `/admin/edit-category.php` | High
51 | File | `/admin/edit-nurse.php` | High
52 | File | `/admin/edit-services.php` | High
53 | File | `/admin/edit-subadmin.php` | High
54 | File | `/admin/edit-subjects-detail.php` | High
55 | File | `/Admin/facilitator.php` | High
56 | File | `/admin/file.php` | High
57 | File | `/admin/forgot-password.php` | High
58 | File | `/admin/freelist_main.php` | High
59 | File | `/admin/gallery.php` | High
60 | File | `/admin/goods/update` | High
61 | File | `/admin/home/index.html` | High
62 | File | `/admin/index.php` | High
63 | File | `/admin/index.php/news/edit` | High
64 | File | `/admin/lab.php` | High
65 | File | `/admin/login` | Medium
66 | File | `/admin/login.php` | High
67 | File | `/admin/manage-art-medium.php` | High
68 | File | `/admin/manage-users.php` | High
69 | File | `/admin/manage_seat.php` | High
70 | File | `/admin/manage_user.php` | High
71 | File | `/admin/member_save.php` | High
72 | File | `/admin/menu_update.php` | High
73 | File | `/admin/message/search.php` | High
74 | File | `/admin/new-autoortaxi-entry-form.php` | High
75 | File | `/admin/offenses/view_details.php` | High
76 | File | `/admin/Operations/Role.php` | High
77 | File | `/admin/pass-bwdates-reports-details.php` | High
78 | File | `/admin/product/edit/` | High
79 | File | `/admin/registration.php` | High
80 | File | `/admin/request-received-bydonar.php` | High
81 | File | `/admin/save_teacher.php` | High
82 | File | `/admin/search-appointment.php` | High
83 | File | `/admin/search.php` | High
84 | File | `/admin/semester.php` | High
85 | File | `/admin/show.php` | High
86 | File | `/admin/subject/controller.php` | High
87 | File | `/admin/subscriber-csv.php` | High
88 | File | `/admin/SysModule/edit.html` | High
89 | File | `/admin/teacher-salary.php` | High
90 | File | `/admin/theme/Upload.html` | High
91 | File | `/admin/update_s2.php` | High
92 | File | `/admin/update_s8.php` | High
93 | File | `/admin/update_user.php` | High
94 | File | `/admin/users-applications.php` | High
95 | File | `/admin/user_update.php` | High
96 | File | `/admin/view-normal-ticket.php` | High
97 | File | `/admin/view_vacancy.php` | High
98 | File | `/admin/voters_add.php` | High
99 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
100 | File | `/Administrator/PHP/AdminEditCategory.php` | High
101 | File | `/admin_class.php` | High
102 | File | `/admin_single_student.php` | High
103 | File | `/aim/storage/query.py` | High
104 | File | `/airag/knowledge/doc/edit` | High
105 | File | `/ajax.php` | Medium
106 | File | `/ajax.php?action=delete_member` | High
107 | File | `/ajax.php?action=delete_package` | High
108 | File | `/ajax.php?action=delete_payroll` | High
109 | File | `/all_student.php` | High
110 | File | `/api/admin/sys-user/reset/password/` | High
111 | File | `/api/article/del` | High
112 | File | `/api/backend/core/web-file-upload/upload` | High
113 | File | `/api/backend/ext/import-data/import-channel` | High
114 | File | `/api/CONFIG/restore` | High
115 | File | `/api/File/downloadFile` | High
116 | File | `/api/file/multiDownload` | High
117 | File | `/api/GylOperator/LoadData` | High
118 | File | `/api/role` | Medium
119 | ... | ... | ...

There are 1052 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.lumen.com/systembc-bringing-the-noise/
* https://github.com/vishalyadav70/Proxy-Server/blob/main/proxy/blacklist.txt
* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
