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
* [RU](https://vuldb.com/?country.ru)
* [IT](https://vuldb.com/?country.it)
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

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cactus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cactus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/aboutadd.php` | High
4 | File | `/aboutedit.php` | High
5 | File | `/abs.php` | Medium
6 | File | `/activation.php` | High
7 | File | `/addcompany.php` | High
8 | File | `/addcustind.php` | High
9 | File | `/addstock.php` | High
10 | File | `/add_new_purchase.php?action=is_supplier` | High
11 | File | `/add_new_supplier.php` | High
12 | File | `/admin-dashboard` | High
13 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
14 | File | `/admin/` | Low
15 | File | `/admin/?page=inventory/view_inventory&id=2` | High
16 | File | `/admin/?page=products/view_product` | High
17 | File | `/admin/?page=reports` | High
18 | File | `/admin/?page=system_info/contact_info` | High
19 | File | `/Admin/add-admin.php` | High
20 | File | `/admin/add-doctor.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/Admin/adminlogin.php` | High
23 | File | `/admin/ad_list.php?action=pass` | High
24 | File | `/Admin/akun_edit.php` | High
25 | File | `/admin/apply.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
28 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
34 | File | `/admin/blood/update/B+.php` | High
35 | File | `/admin/blood/update/B-.php` | High
36 | File | `/admin/book-details.php` | High
37 | File | `/admin/bwdates-report-details.php` | High
38 | File | `/admin/campsdetails.php` | High
39 | File | `/admin/card-bwdates-reports-details.php` | High
40 | File | `/admin/categories/manage_category.php` | High
41 | File | `/admin/change-image.php` | High
42 | File | `/admin/changeimage.php` | High
43 | File | `/admin/cmsTagType/save` | High
44 | File | `/admin/create-package.php` | High
45 | File | `/Admin/detail.php` | High
46 | File | `/admin/edit-brand.php` | High
47 | File | `/admin/edit-card-detail.php` | High
48 | File | `/admin/edit-subadmin.php` | High
49 | File | `/admin/edit_customer.php` | High
50 | File | `/admin/edit_fuel.php` | High
51 | File | `/admin/edit_manufacturer.php` | High
52 | File | `/admin/File/fileUpload` | High
53 | File | `/admin/File/pictureUpload` | High
54 | File | `/admin/home.php` | High
55 | File | `/admin/index.php` | High
56 | File | `/admin/inquiries/view_details.php` | High
57 | File | `/admin/login_process.php` | High
58 | File | `/admin/maintenance/manage_department.php` | High
59 | File | `/admin/massage.php` | High
60 | File | `/admin/msg.php` | High
61 | File | `/admin/overtime_add.php` | High
62 | File | `/admin/overtime_row.php` | High
63 | File | `/admin/password-recovery.php` | High
64 | File | `/admin/profile.php` | High
65 | File | `/Admin/Proses_Edit_Akun.php` | High
66 | File | `/admin/robot.php` | High
67 | File | `/admin/search-invoices.php` | High
68 | File | `/admin/search-medicalcard.php` | High
69 | File | `/admin/search-vehicle.php` | High
70 | File | `/admin/services/view_service.php` | High
71 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
72 | File | `/admin/tag.php` | High
73 | File | `/admin/view-card-detail.php` | High
74 | File | `/admin/view-enquiry.php` | High
75 | File | `/ajax.php?action=delete_tenant` | High
76 | File | `/ajax.php?action=save_category` | High
77 | File | `/ajax.php?action=signup` | High
78 | ... | ... | ...

There are 687 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://northwave-cybersecurity.com/whitepapers-articles/pricksense-how-cactus-exploits-qlik-sense
* https://www.arcticwolf.com/resources/blog/qlik-sense-exploited-in-cactus-ransomware-campaign/
* https://www.bitdefender.com/blog/businessinsights/cactus-analyzing-a-coordinated-ransomware-attack-on-corporate-networks/
* https://www.trellix.com/blogs/research/cactus-ransomware-new-strain-in-the-market/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
