# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [IT](https://vuldb.com/?country.it)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PYSA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.129.64.190](https://vuldb.com/?ip.23.129.64.190) | - | - | High
2 | [45.147.231.210](https://vuldb.com/?ip.45.147.231.210) | - | - | High
3 | [185.220.100.240](https://vuldb.com/?ip.185.220.100.240) | tor-exit-13.zbau.f3netze.de | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PYSA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PYSA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?page=reserve` | High
3 | File | `/aboutedit.php` | High
4 | File | `/abs.php` | Medium
5 | File | `/account.php` | Medium
6 | File | `/account.php?q=quiz&step=2` | High
7 | File | `/addcustind.php` | High
8 | File | `/addstock.php` | High
9 | File | `/add_achievement_details.php` | High
10 | File | `/add_new_purchase.php?action=is_supplier` | High
11 | File | `/add_new_supplier.php` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=inventory/view_inventory&id=2` | High
14 | File | `/admin/?page=musics/manage_music` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/add-customer.php` | High
17 | File | `/admin/add-services.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/Admin/adminlogin.php` | High
20 | File | `/admin/admin_football.php` | High
21 | File | `/admin/ajax.php?action=save_settings` | High
22 | File | `/admin/ajax.php?action=save_student` | High
23 | File | `/admin/all_users.php` | High
24 | File | `/admin/article.php` | High
25 | File | `/admin/article.php?action=upload_cover` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
28 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
29 | File | `/admin/blood/update/B+.php` | High
30 | File | `/admin/book-details.php` | High
31 | File | `/admin/bwdates-report-details.php` | High
32 | File | `/admin/campsdetails.php` | High
33 | File | `/admin/categories/manage_category.php` | High
34 | File | `/admin/category.php` | High
35 | File | `/admin/chatroom.php` | High
36 | File | `/admin/complaint-search.php` | High
37 | File | `/admin/confirm.php` | High
38 | File | `/admin/contactus.php` | High
39 | File | `/admin/content/book` | High
40 | File | `/admin/create_product.php` | High
41 | File | `/admin/delete-session.php` | High
42 | File | `/admin/dialog/select_images_post.php` | High
43 | File | `/admin/edit-brand.php` | High
44 | File | `/admin/edit-card-detail.php` | High
45 | File | `/admin/edit-course.php` | High
46 | File | `/admin/edit-propertytype.php` | High
47 | File | `/admin/edit-subadmin.php` | High
48 | File | `/admin/edit-subcategory.php` | High
49 | File | `/admin/edit_admin.php` | High
50 | File | `/admin/edit_area.php` | High
51 | File | `/admin/edit_customer.php` | High
52 | File | `/admin/edit_manufacturer.php` | High
53 | File | `/admin/emp-profile-avatar.php` | High
54 | File | `/admin/faculty_action.php` | High
55 | File | `/admin/home.php` | High
56 | File | `/admin/index.php` | High
57 | File | `/admin/inquiries/view_details.php` | High
58 | File | `/admin/login.php` | High
59 | File | `/admin/maintenance/manage_department.php` | High
60 | File | `/admin/manage_complaint.php` | High
61 | File | `/admin/manage_user.php` | High
62 | File | `/admin/mod_room/controller.php?action=add` | High
63 | File | `/admin/msg.php` | High
64 | File | `/admin/network/ajax_getChannelList` | High
65 | File | `/admin/network/diag_iperf` | High
66 | File | `/admin/network/diag_nslookup` | High
67 | File | `/admin/network/diag_ping6` | High
68 | File | `/admin/network/diag_traceroute` | High
69 | File | `/admin/network/diag_traceroute6` | High
70 | File | `/admin/pagerole.php&action=edit` | High
71 | File | `/admin/pass-bwdates-reports-details.php` | High
72 | File | `/admin/password-recovery.php` | High
73 | File | `/admin/print.php` | High
74 | File | `/admin/profile.php` | High
75 | File | `/admin/property-details.php` | High
76 | File | `/Admin/Proses_Edit_Akun.php` | High
77 | File | `/admin/report.php` | High
78 | File | `/admin/robot.php` | High
79 | File | `/admin/search-invoices.php` | High
80 | File | `/admin/search-medicalcard.php` | High
81 | File | `/admin/system.php` | High
82 | File | `/admin/update_room.php` | High
83 | File | `/admin/update_user.php` | High
84 | File | `/admin/user.php` | High
85 | File | `/admin/users.php` | High
86 | File | `/admin/view-appointment.php` | High
87 | File | `/admin/view-enquiry.php` | High
88 | File | `/admin/view-outgoingvehicle-detail.php` | High
89 | File | `/admin/voters_add.php` | High
90 | File | `/admin/voters_delete.php` | High
91 | File | `/Administrator/PHP/AdminEditCategory.php` | High
92 | File | `/ajax.php?action=delete_block` | High
93 | File | `/ajax.php?action=delete_deductions` | High
94 | File | `/ajax.php?action=delete_tenant` | High
95 | File | `/ajax.php?action=save_category` | High
96 | File | `/ajax.php?action=save_student` | High
97 | File | `/animalsupdate.php` | High
98 | File | `/api/system/dept/update` | High
99 | File | `/api/v2/maps` | Medium
100 | File | `/api/v2/schema` | High
101 | File | `/api/wizard/getsyncpppoecfg` | High
102 | File | `/app/admin/controller/file/File.php` | High
103 | File | `/app/controller/Upload.php` | High
104 | File | `/appDetail.jsp` | High
105 | File | `/application/admin/logic/FilemanagerLogic.php` | High
106 | File | `/apply/index.php` | High
107 | File | `/authMonitCallcenter` | High
108 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
109 | File | `/backend/admin/his_admin_register_patient.php` | High
110 | File | `/billaction.php` | High
111 | File | `/birthing_record.php` | High
112 | File | `/boafrm/formDosCfg` | High
113 | File | `/boafrm/formNtp` | High
114 | File | `/boafrm/formPortFw` | High
115 | File | `/book_car.php` | High
116 | ... | ... | ...

There are 1033 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/120/pysa-ransomware-iocs/
* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
