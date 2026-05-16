# Cactus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cactus](https://vuldb.com/?actor.cactus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cactus](https://vuldb.com/?actor.cactus)

## Campaigns

The following _campaigns_ are known and can be associated with Cactus:

* CVE-2023-38035
* CVE-2023-41266 / CVE-2023-41265 / CVE-2023-48365
* CVE-2023–38035

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cactus:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [AT](https://vuldb.com/?country.at)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cactus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.227.203.210](https://vuldb.com/?ip.23.227.203.210) | 23-227-203-210.static.hvvc.us | - | High
2 | [45.61.136.79](https://vuldb.com/?ip.45.61.136.79) | - | CVE-2023-38035 | High
3 | [45.61.136.127](https://vuldb.com/?ip.45.61.136.127) | - | CVE-2023-38035 | High
4 | [45.61.137.65](https://vuldb.com/?ip.45.61.137.65) | - | - | High
5 | [45.61.138.99](https://vuldb.com/?ip.45.61.138.99) | - | CVE-2023-38035 | High
6 | [45.61.147.176](https://vuldb.com/?ip.45.61.147.176) | - | - | High
7 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cactus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cactus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `/aa` | Low
3 | File | `/accomodation.php` | High
4 | File | `/add-customer.php` | High
5 | File | `/add_drive.php` | High
6 | File | `/add_sales_print.php` | High
7 | File | `/add_stock.php` | High
8 | File | `/admin-api/mp/material/upload-permanent` | High
9 | File | `/admin/?page=back_order/view_bo` | High
10 | File | `/admin/?page=maintenance/brand` | High
11 | File | `/admin/accepted-appointment.php` | High
12 | File | `/admin/add-table.php` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/admin/admin/save` | High
15 | File | `/admin/all-applications.php` | High
16 | File | `/admin/app/slider_crud.php` | High
17 | File | `/Admin/assets/backend/seller/add_seller.php` | High
18 | File | `/admin/auto-taxi-entry-detail.php` | High
19 | File | `/admin/blogger.php?action=update_avatar` | High
20 | File | `/admin/booking-search.php` | High
21 | File | `/admin/bwdates-report-result.php` | High
22 | File | `/admin/campsdetails.php` | High
23 | File | `/admin/category_save.php` | High
24 | File | `/admin/checkout_query.php` | High
25 | File | `/admin/check_studid.php` | High
26 | File | `/admin/contact-list.php` | High
27 | File | `/admin/contactus.php` | High
28 | File | `/admin/core/import_users.php` | High
29 | File | `/admin/deleteuser.php` | High
30 | File | `/admin/department/add` | High
31 | File | `/admin/display-teacher.php` | High
32 | File | `/admin/doctor-specilization.php` | High
33 | File | `/admin/edit-admin.php` | High
34 | File | `/admin/edit-category.php` | High
35 | File | `/admin/edit-nurse.php` | High
36 | File | `/admin/edit-services.php` | High
37 | File | `/admin/editempexp.php` | High
38 | File | `/admin/edit_product.php` | High
39 | File | `/Admin/facilitator.php` | High
40 | File | `/admin/file.php` | High
41 | File | `/admin/filemanager/view` | High
42 | File | `/admin/forget-password.php` | High
43 | File | `/admin/forgot-password.php` | High
44 | File | `/admin/gallery.php` | High
45 | File | `/admin/index.php` | High
46 | File | `/admin/index.php/news/edit` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/manage-art-medium.php` | High
49 | File | `/admin/manage-users.php` | High
50 | File | `/admin/manage_booking.php` | High
51 | File | `/admin/manage_register.php` | High
52 | File | `/admin/manage_seat.php` | High
53 | File | `/Admin/match.php` | High
54 | File | `/admin/member_save.php` | High
55 | File | `/admin/product/edit/` | High
56 | File | `/admin/registration.php` | High
57 | File | `/admin/request-received-bydonar.php` | High
58 | File | `/admin/save_settings.php` | High
59 | File | `/admin/semester.php` | High
60 | File | `/admin/subject/controller.php` | High
61 | File | `/admin/subscriber-csv.php` | High
62 | File | `/admin/SysModule/edit.html` | High
63 | File | `/admin/teacher-salary.php` | High
64 | File | `/admin/topic/list` | High
65 | File | `/admin/update_s2.php` | High
66 | File | `/admin/update_s8.php` | High
67 | File | `/admin/users-applications.php` | High
68 | File | `/admin/user_update.php` | High
69 | File | `/admin/view-normal-ticket.php` | High
70 | File | `/admin/view-patient.php` | High
71 | File | `/admin/view_sendlist.php` | High
72 | File | `/admin/view_vacancy.php` | High
73 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
74 | File | `/Administrator/PHP/AdminEditCategory.php` | High
75 | File | `/adminPage/conf/check` | High
76 | File | `/Adminupdate.php` | High
77 | File | `/admin_single_student.php` | High
78 | File | `/admin_single_student_update.php` | High
79 | File | `/ajax.php?action=delete_member` | High
80 | File | `/ajax.php?action=delete_package` | High
81 | File | `/ajax.php?action=delete_payroll` | High
82 | File | `/ajax.php?action=delete_plan` | High
83 | File | `/api/admin/common/download/templates` | High
84 | File | `/api/admin/sys-message/` | High
85 | File | `/api/admin/sys-user/reset/password/` | High
86 | File | `/api/article/del` | High
87 | File | `/api/backend/ext/import-data/import-channel` | High
88 | File | `/api/blade-user/submit` | High
89 | File | `/api/deploy/upload` | High
90 | File | `/api/File/downloadFile` | High
91 | File | `/api/GylOperator/LoadData` | High
92 | File | `/api/Security/` | High
93 | File | `/api/semantic/database/testConnect` | High
94 | File | `/api/system/dashboard/getCount` | High
95 | File | `/api/system/user/getAvatar` | High
96 | File | `/api/users/updateAvatar` | High
97 | File | `/api/v1/mail/send` | High
98 | File | `/api/v1/serve/awel/flow/import` | High
99 | File | `/app/api/v1/openvpn.py` | High
100 | File | `/Archive/ErecordManage/uploadFile.html` | High
101 | File | `/att_single_view.php` | High
102 | File | `/auth/list_projects` | High
103 | File | `/backend/app/api/v1/module_common/file/controller.py` | High
104 | File | `/backend/app/api/v1/module_system/params/controller.py` | High
105 | File | `/backend/app/api/v1/module_system/user/controller.py` | High
106 | File | `/backend/app/plugin/init_app.py` | High
107 | File | `/billaction.php` | High
108 | File | `/Blood/A+.php` | High
109 | File | `/boaform/formgponConf` | High
110 | File | `/boaform/formLoopBack` | High
111 | ... | ... | ...

There are 981 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/introducing-toymaker-an-initial-access-broker/
* https://northwave-cybersecurity.com/whitepapers-articles/pricksense-how-cactus-exploits-qlik-sense
* https://www.arcticwolf.com/resources/blog/qlik-sense-exploited-in-cactus-ransomware-campaign/
* https://www.bitdefender.com/blog/businessinsights/cactus-analyzing-a-coordinated-ransomware-attack-on-corporate-networks/
* https://www.trellix.com/blogs/research/cactus-ransomware-new-strain-in-the-market/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
