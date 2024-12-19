# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [GB](https://vuldb.com/?country.gb)
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
1 | File | `/?page=reserve` | High
2 | File | `/aboutedit.php` | High
3 | File | `/abs.php` | Medium
4 | File | `/addcustind.php` | High
5 | File | `/addstock.php` | High
6 | File | `/add_new_purchase.php?action=is_supplier` | High
7 | File | `/add_new_supplier.php` | High
8 | File | `/admin-manage-user.php` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=inventory/view_inventory&id=2` | High
11 | File | `/admin/?page=musics/manage_music` | High
12 | File | `/admin/?page=user/list` | High
13 | File | `/admin/add-customer.php` | High
14 | File | `/admin/add-services.php` | High
15 | File | `/Admin/adminlogin.php` | High
16 | File | `/admin/ajax.php?action=save_settings` | High
17 | File | `/admin/ajax.php?action=save_student` | High
18 | File | `/admin/applicants/controller.php` | High
19 | File | `/admin/applicants/index.php` | High
20 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
21 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
22 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
23 | File | `/admin/blood/update/B+.php` | High
24 | File | `/admin/book-details.php` | High
25 | File | `/admin/booking-bwdates-reports-details.php` | High
26 | File | `/admin/bwdates-report-details.php` | High
27 | File | `/admin/campsdetails.php` | High
28 | File | `/admin/categories/manage_category.php` | High
29 | File | `/admin/complaint-search.php` | High
30 | File | `/admin/court-type` | High
31 | File | `/admin/dialog/select_images_post.php` | High
32 | File | `/admin/edit-brand.php` | High
33 | File | `/admin/edit-card-detail.php` | High
34 | File | `/admin/edit-subadmin.php` | High
35 | File | `/admin/edit_area.php` | High
36 | File | `/admin/edit_customer.php` | High
37 | File | `/admin/edit_manufacturer.php` | High
38 | File | `/admin/emp-profile-avatar.php` | High
39 | File | `/admin/employee/controller.php` | High
40 | File | `/admin/foreigner-search.php` | High
41 | File | `/admin/home.php` | High
42 | File | `/admin/index.php` | High
43 | File | `/admin/index.php?page=categories` | High
44 | File | `/admin/inquiries/view_details.php` | High
45 | File | `/admin/login.php` | High
46 | File | `/admin/maintenance/manage_category.php` | High
47 | File | `/admin/maintenance/manage_department.php` | High
48 | File | `/admin/manage_complaint.php` | High
49 | File | `/admin/manage_user.php` | High
50 | File | `/admin/modules/product/controller.php?action=add` | High
51 | File | `/admin/mod_room/controller.php?action=add` | High
52 | File | `/admin/msg.php` | High
53 | File | `/admin/network/ajax_getChannelList` | High
54 | File | `/admin/network/diag_iperf` | High
55 | File | `/admin/network/diag_nslookup` | High
56 | File | `/admin/network/diag_ping6` | High
57 | File | `/admin/network/diag_traceroute` | High
58 | File | `/admin/network/diag_traceroute6` | High
59 | File | `/admin/normal-bwdates-reports-details.php` | High
60 | File | `/admin/pass-bwdates-reports-details.php` | High
61 | File | `/admin/password-recovery.php` | High
62 | File | `/Admin/Proses_Edit_Akun.php` | High
63 | File | `/admin/robot.php` | High
64 | File | `/admin/search-invoices.php` | High
65 | File | `/admin/search-medicalcard.php` | High
66 | File | `/admin/system.php` | High
67 | File | `/admin/tasks` | Medium
68 | File | `/admin/tax` | Medium
69 | File | `/admin/template` | High
70 | File | `/Admin/user-record.php` | High
71 | File | `/admin/user/controller.php` | High
72 | File | `/admin/vendor` | High
73 | File | `/admin/view-appointment.php` | High
74 | File | `/admin/view-enquiry.php` | High
75 | File | `/adminPage/conf/saveCmd` | High
76 | File | `/adminPage/www/addOver` | High
77 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
78 | File | `/ajax.php?action=delete_block` | High
79 | File | `/ajax.php?action=delete_deductions` | High
80 | File | `/ajax.php?action=delete_tenant` | High
81 | File | `/ajax.php?action=save_category` | High
82 | File | `/animalsupdate.php` | High
83 | File | `/api/client/editemedia.php` | High
84 | File | `/api/cron/settings/setJob/` | High
85 | File | `/api/v1/policies/validation/condition/` | High
86 | File | `/api/v2/maps` | Medium
87 | File | `/api/v2/schema` | High
88 | File | `/app/admin/controller/file/File.php` | High
89 | File | `/apply/index.php` | High
90 | File | `/apps/system/router/upload.go` | High
91 | File | `/authMonitCallcenter` | High
92 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
93 | File | `/backend/admin/his_admin_register_patient.php` | High
94 | File | `/backend/register.php` | High
95 | File | `/book_car.php` | High
96 | File | `/catalog/all-products` | High
97 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
98 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
99 | File | `/cgi-bin/apkg_mgr.cgi` | High
100 | File | `/cgi-bin/cstecgi.cgi` | High
101 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
102 | File | `/cgi-bin/discovery.cgi` | High
103 | File | `/cgi-bin/glc` | Medium
104 | File | `/cgi-bin/hd_config.cgi` | High
105 | File | `/cgi-bin/nas_sharing.cgi` | High
106 | File | `/cgi-bin/photocenter_mgr.cgi` | High
107 | File | `/cgi-bin/s3.cgi` | High
108 | File | `/cgi-bin/tosei_kikai.php` | High
109 | File | `/cgi-bin/webfile_mgr.cgi` | High
110 | ... | ... | ...

There are 977 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/120/pysa-ransomware-iocs/
* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
