# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [DE](https://vuldb.com/?country.de)
* ...

There are 7 more country items available. Please use our online service to access the data.

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
5 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

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
15 | File | `/admin/?page=user/list` | High
16 | File | `/admin/aboutus.php` | High
17 | File | `/admin/add-customer.php` | High
18 | File | `/admin/add-services.php` | High
19 | File | `/Admin/adminlogin.php` | High
20 | File | `/admin/ajax.php?action=save_settings` | High
21 | File | `/admin/ajax.php?action=save_student` | High
22 | File | `/admin/all_users.php` | High
23 | File | `/admin/article.php` | High
24 | File | `/admin/article.php?action=upload_cover` | High
25 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
28 | File | `/admin/blood/update/B+.php` | High
29 | File | `/admin/book-details.php` | High
30 | File | `/admin/bwdates-report-details.php` | High
31 | File | `/admin/campsdetails.php` | High
32 | File | `/admin/categories/manage_category.php` | High
33 | File | `/admin/chatroom.php` | High
34 | File | `/admin/complaint-search.php` | High
35 | File | `/admin/contactus.php` | High
36 | File | `/admin/content/book` | High
37 | File | `/admin/court-type` | High
38 | File | `/admin/create_product.php` | High
39 | File | `/admin/dialog/select_images_post.php` | High
40 | File | `/admin/edit-brand.php` | High
41 | File | `/admin/edit-card-detail.php` | High
42 | File | `/admin/edit-propertytype.php` | High
43 | File | `/admin/edit-subadmin.php` | High
44 | File | `/admin/edit_area.php` | High
45 | File | `/admin/edit_customer.php` | High
46 | File | `/admin/edit_manufacturer.php` | High
47 | File | `/admin/emp-profile-avatar.php` | High
48 | File | `/admin/employee/controller.php` | High
49 | File | `/admin/faculty_action.php` | High
50 | File | `/admin/foreigner-search.php` | High
51 | File | `/admin/home.php` | High
52 | File | `/admin/index.php` | High
53 | File | `/admin/index.php?page=categories` | High
54 | File | `/admin/inquiries/view_details.php` | High
55 | File | `/admin/login.php` | High
56 | File | `/admin/maintenance/manage_department.php` | High
57 | File | `/admin/manage_complaint.php` | High
58 | File | `/admin/manage_user.php` | High
59 | File | `/admin/modules/product/controller.php?action=add` | High
60 | File | `/admin/mod_room/controller.php?action=add` | High
61 | File | `/admin/msg.php` | High
62 | File | `/admin/network/ajax_getChannelList` | High
63 | File | `/admin/network/diag_iperf` | High
64 | File | `/admin/network/diag_nslookup` | High
65 | File | `/admin/network/diag_ping6` | High
66 | File | `/admin/network/diag_traceroute` | High
67 | File | `/admin/network/diag_traceroute6` | High
68 | File | `/admin/normal-bwdates-reports-details.php` | High
69 | File | `/admin/pass-bwdates-reports-details.php` | High
70 | File | `/admin/password-recovery.php` | High
71 | File | `/admin/print.php` | High
72 | File | `/admin/profile.php` | High
73 | File | `/admin/property-details.php` | High
74 | File | `/Admin/Proses_Edit_Akun.php` | High
75 | File | `/admin/report.php` | High
76 | File | `/admin/robot.php` | High
77 | File | `/admin/search-invoices.php` | High
78 | File | `/admin/search-medicalcard.php` | High
79 | File | `/admin/system.php` | High
80 | File | `/admin/tasks` | Medium
81 | File | `/admin/tax` | Medium
82 | File | `/admin/template` | High
83 | File | `/admin/update_room.php` | High
84 | File | `/admin/update_user.php` | High
85 | File | `/Admin/user-record.php` | High
86 | File | `/admin/user.php` | High
87 | File | `/admin/vendor` | High
88 | File | `/admin/view-appointment.php` | High
89 | File | `/admin/view-enquiry.php` | High
90 | File | `/adminPage/conf/saveCmd` | High
91 | File | `/adminPage/www/addOver` | High
92 | File | `/ajax.php?action=delete_block` | High
93 | File | `/ajax.php?action=delete_deductions` | High
94 | File | `/ajax.php?action=delete_tenant` | High
95 | File | `/ajax.php?action=save_category` | High
96 | File | `/animalsupdate.php` | High
97 | File | `/api/cron/settings/setJob/` | High
98 | File | `/api/v2/maps` | Medium
99 | File | `/api/v2/schema` | High
100 | File | `/app/admin/controller/file/File.php` | High
101 | File | `/apply/index.php` | High
102 | File | `/authMonitCallcenter` | High
103 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
104 | File | `/backend/admin/his_admin_register_patient.php` | High
105 | File | `/backend/register.php` | High
106 | File | `/billaction.php` | High
107 | File | `/book_car.php` | High
108 | File | `/catalog/all-products` | High
109 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
110 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
111 | File | `/cgi-bin/apkg_mgr.cgi` | High
112 | File | `/cgi-bin/cstecgi.cgi` | High
113 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
114 | File | `/cgi-bin/discovery.cgi` | High
115 | ... | ... | ...

There are 1021 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/120/pysa-ransomware-iocs/
* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
