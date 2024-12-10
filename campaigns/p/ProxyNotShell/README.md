# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/?page=tracks` | High
4 | File | `/abcd/opac/php/otros_sitios.php` | High
5 | File | `/abs.php` | Medium
6 | File | `/Actions.php?a=login` | High
7 | File | `/addcompany.php` | High
8 | File | `/add_new_invoice.php` | High
9 | File | `/add_new_purchase.php?action=is_supplier` | High
10 | File | `/add_new_supplier.php` | High
11 | File | `/admin` | Low
12 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
13 | File | `/admin/` | Low
14 | File | `/admin/?page=inventory/view_inventory&id=2` | High
15 | File | `/admin/?page=products/view_product` | High
16 | File | `/admin/?page=reports` | High
17 | File | `/Admin/add-admin.php` | High
18 | File | `/admin/add-doctor.php` | High
19 | File | `/Admin/adminlogin.php` | High
20 | File | `/admin/apply.php` | High
21 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
22 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
23 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
24 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
25 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
28 | File | `/admin/blood/update/B+.php` | High
29 | File | `/admin/blood/update/B-.php` | High
30 | File | `/admin/blood/update/o-.php` | High
31 | File | `/admin/book-details.php` | High
32 | File | `/admin/bwdates-report-details.php` | High
33 | File | `/admin/campsdetails.php` | High
34 | File | `/admin/categories/manage_category.php` | High
35 | File | `/admin/change-image.php` | High
36 | File | `/admin/create-package.php` | High
37 | File | `/admin/edit-brand.php` | High
38 | File | `/admin/edit-card-detail.php` | High
39 | File | `/admin/edit-subadmin.php` | High
40 | File | `/admin/edit_area.php` | High
41 | File | `/admin/edit_fuel.php` | High
42 | File | `/admin/edit_manufacturer.php` | High
43 | File | `/admin/educloud/videobind.html` | High
44 | File | `/admin/File/fileUpload` | High
45 | File | `/admin/File/pictureUpload` | High
46 | File | `/admin/home.php` | High
47 | File | `/admin/index.php` | High
48 | File | `/admin/inquiries/view_details.php` | High
49 | File | `/admin/login.php` | High
50 | File | `/admin/maintenance/manage_department.php` | High
51 | File | `/admin/massage.php` | High
52 | File | `/admin/overtime_add.php` | High
53 | File | `/admin/overtime_row.php` | High
54 | File | `/admin/password-recovery.php` | High
55 | File | `/admin/profile.php` | High
56 | File | `/admin/robot.php` | High
57 | File | `/admin/search-medicalcard.php` | High
58 | File | `/admin/search-vehicle.php` | High
59 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
60 | File | `/admin/tag.php` | High
61 | File | `/admin/template/edit` | High
62 | File | `/admin/template/update` | High
63 | File | `/admin/user/user-move-run.php` | High
64 | File | `/admin/view-card-detail.php` | High
65 | File | `/admin/view-enquiry.php` | High
66 | File | `/ajax.php?action=delete_deductions` | High
67 | File | `/ajax.php?action=save_category` | High
68 | File | `/ajax.php?action=signup` | High
69 | File | `/ajax.php?action=update_account` | High
70 | File | `/animalsadd.php` | High
71 | File | `/api/config/list` | High
72 | File | `/api/files/recipepictures/` | High
73 | File | `/app/action/add_staff.php` | High
74 | File | `/app/admin/controller/api/Plugs.php` | High
75 | File | `/app/admin/controller/file/File.php` | High
76 | File | `/apply/index.php` | High
77 | File | `/bloodrequest.php` | High
78 | File | `/buscar_integrada.php` | High
79 | ... | ... | ...

There are 697 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
