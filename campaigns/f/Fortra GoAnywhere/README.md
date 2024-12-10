# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/?actor.clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/?actor.clop) | Medium
2 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/?actor.clop) | High
3 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/?actor.clop) | High
4 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | [Clop](https://vuldb.com/?actor.clop) | High
5 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/?actor.clop) | High
6 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/?actor.clop) | High
7 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/?actor.clop) | High
8 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | [Clop](https://vuldb.com/?actor.clop) | High
9 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/?actor.clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/aboutedit.php` | High
4 | File | `/abs.php` | Medium
5 | File | `/Actions.php?a=login` | High
6 | File | `/addcompany.php` | High
7 | File | `/addcustcom.php` | High
8 | File | `/addcustind.php` | High
9 | File | `/add_new_invoice.php` | High
10 | File | `/add_new_purchase.php?action=is_supplier` | High
11 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=categories/view_category` | High
14 | File | `/admin/?page=inventory/view_inventory&id=2` | High
15 | File | `/admin/?page=musics/manage_music` | High
16 | File | `/Admin/add-admin.php` | High
17 | File | `/admin/add-doctor.php` | High
18 | File | `/Admin/adminlogin.php` | High
19 | File | `/admin/admin_invt2.php` | High
20 | File | `/admin/ad_list.php?action=pass` | High
21 | File | `/admin/ajax_product.php` | High
22 | File | `/Admin/akun_edit.php` | High
23 | File | `/admin/apply.php` | High
24 | File | `/admin/assets/` | High
25 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
28 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
34 | File | `/admin/blood/update/B+.php` | High
35 | File | `/admin/blood/update/B-.php` | High
36 | File | `/admin/blood/update/o-.php` | High
37 | File | `/admin/book-details.php` | High
38 | File | `/admin/bwdates-report-details.php` | High
39 | File | `/admin/campsdetails.php` | High
40 | File | `/admin/card-bwdates-reports-details.php` | High
41 | File | `/admin/categories/manage_category.php` | High
42 | File | `/admin/cmsTagType/save` | High
43 | File | `/Admin/consulting_detail.php` | High
44 | File | `/Admin/detail.php` | High
45 | File | `/admin/dialog/select_images_post.php` | High
46 | File | `/admin/edit-card-detail.php` | High
47 | File | `/admin/edit-subadmin.php` | High
48 | File | `/admin/edit_area.php` | High
49 | File | `/admin/edit_customer.php` | High
50 | File | `/admin/edit_fuel.php` | High
51 | File | `/admin/edit_manufacturer.php` | High
52 | File | `/admin/edit_role.php` | High
53 | File | `/admin/emp-profile-avatar.php` | High
54 | File | `/admin/File/fileUpload` | High
55 | File | `/admin/File/pictureUpload` | High
56 | File | `/admin/index.php` | High
57 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
58 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
59 | File | `/admin/index.php?r=user%2Fcreate` | High
60 | File | `/admin/login.php` | High
61 | File | `/admin/login_process.php` | High
62 | File | `/admin/maintenance/manage_department.php` | High
63 | File | `/admin/massage.php` | High
64 | File | `/admin/mod_room/controller.php?action=add` | High
65 | File | `/admin/msg.php` | High
66 | File | `/admin/overtime_add.php` | High
67 | File | `/admin/overtime_row.php` | High
68 | File | `/admin/print.php` | High
69 | File | `/admin/process_category_add.php` | High
70 | File | `/admin/process_category_edit.php` | High
71 | File | `/admin/profile.php` | High
72 | File | `/Admin/Proses_Edit_Akun.php` | High
73 | File | `/Admin/registration.php` | High
74 | File | `/admin/robot.php` | High
75 | File | `/admin/search-invoices.php` | High
76 | File | `/admin/search-medicalcard.php` | High
77 | File | `/admin/services/view_service.php` | High
78 | File | `/admin/sou.php` | High
79 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
80 | File | `/admin/system.html` | High
81 | File | `/admin/system.php` | High
82 | File | `/admin/tag.php` | High
83 | File | `/admin/template/edit` | High
84 | File | `/admin/user/user-move-run.php` | High
85 | File | `/admin/view-card-detail.php` | High
86 | File | `/admin_class.php` | High
87 | File | `/ajax.php?action=delete_deductions` | High
88 | File | `/ajax.php?action=save_category` | High
89 | File | `/ajax.php?action=signup` | High
90 | File | `/ajax.php?action=update_account` | High
91 | File | `/api/blade-system/menu/list?updatexml` | High
92 | File | `/api/config/list` | High
93 | File | `/api/files/recipepictures/` | High
94 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
95 | ... | ... | ...

There are 844 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
