# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Applejeus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | - | High
2 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | - | High
3 | [95.213.232.170](https://vuldb.com/?ip.95.213.232.170) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Applejeus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?page=tickets` | High
3 | File | `/?page=tracks` | High
4 | File | `/abs.php` | Medium
5 | File | `/add_new_purchase.php?action=is_supplier` | High
6 | File | `/add_new_supplier.php` | High
7 | File | `/admin` | Low
8 | File | `/admin-dashboard` | High
9 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
10 | File | `/admin/` | Low
11 | File | `/admin/?page=categories/view_category` | High
12 | File | `/admin/?page=inventory/view_inventory&id=2` | High
13 | File | `/admin/?page=products/view_product` | High
14 | File | `/admin/?page=system_info/contact_info` | High
15 | File | `/admin/add-doctor.php` | High
16 | File | `/admin/admin-add-employee.php` | High
17 | File | `/admin/admin_invt2.php` | High
18 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
19 | File | `/admin/ajax.php?action=login` | High
20 | File | `/admin/ajax.php?action=save_settings` | High
21 | File | `/admin/ajax_product.php` | High
22 | File | `/admin/blood/update/B+.php` | High
23 | File | `/admin/bwdates-report-details.php` | High
24 | File | `/admin/campsdetails.php` | High
25 | File | `/admin/card-bwdates-reports-details.php` | High
26 | File | `/admin/case-type` | High
27 | File | `/admin/change-image.php` | High
28 | File | `/admin/changeimage.php` | High
29 | File | `/admin/config_MT.php?action=delete` | High
30 | File | `/admin/create-package.php` | High
31 | File | `/admin/edit-subadmin.php` | High
32 | File | `/admin/edit_area.php` | High
33 | File | `/admin/edit_customer.php` | High
34 | File | `/admin/edit_fuel.php` | High
35 | File | `/admin/edit_manufacturer.php` | High
36 | File | `/admin/File/fileUpload` | High
37 | File | `/admin/file_manager/export` | High
38 | File | `/admin/file_manager/files` | High
39 | File | `/admin/forgot-password.php` | High
40 | File | `/admin/general-setting` | High
41 | File | `/admin/home.php` | High
42 | File | `/admin/home.php?con=add` | High
43 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
44 | File | `/admin/index.php` | High
45 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
46 | File | `/admin/index2.html` | High
47 | File | `/admin/inquiries/view_details.php` | High
48 | File | `/admin/invoice.php` | High
49 | File | `/admin/login.php` | High
50 | File | `/admin/maintenance/manage_brand.php` | High
51 | File | `/admin/maintenance/manage_department.php` | High
52 | File | `/admin/massage.php` | High
53 | File | `/admin/media_folders` | High
54 | File | `/admin/mod_room/controller.php?action=add` | High
55 | File | `/admin/overtime_add.php` | High
56 | File | `/admin/overtime_row.php` | High
57 | File | `/admin/pages/` | High
58 | File | `/admin/print.php` | High
59 | File | `/admin/robot.php` | High
60 | File | `/admin/search-vehicle.php` | High
61 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
62 | File | `/admin/system.html` | High
63 | File | `/admin/template/edit` | High
64 | File | `/admin/template/update` | High
65 | File | `/admin/user/user-move-run.php` | High
66 | File | `/adminPage/conf/reload` | High
67 | File | `/adminpanel/admin/query/addCourseExe.php` | High
68 | File | `/admin_class.php` | High
69 | File | `/ajax.php?action=delete_tenant` | High
70 | File | `/ajax/chpwd.php` | High
71 | File | `/ajax/getBasicInfo.php` | High
72 | File | `/animalsadd.php` | High
73 | File | `/api/file/downloadfile` | High
74 | File | `/api/runscript` | High
75 | File | `/api/snapshots/` | High
76 | File | `/api/v1/snapshots` | High
77 | File | `/api/v2/maps` | Medium
78 | File | `/app/admin/controller/file/File.php` | High
79 | File | `/apply/index.php` | High
80 | File | `/authMonitCallcenter` | High
81 | File | `/branch_viewmore.php` | High
82 | File | `/buscar_integrada.php` | High
83 | File | `/candidate/index.php` | High
84 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
85 | File | `/cgi-bin/cstecgi.cgi` | High
86 | File | `/cgi-bin/discovery.cgi` | High
87 | File | `/cgi-bin/p1_ftpserver.php` | High
88 | File | `/cgi-bin/settings-firewall.cgi` | High
89 | File | `/cgi-bin/tosei_kikai.php` | High
90 | File | `/cgi-bin/widget_api.cgi` | High
91 | File | `/classes/Master.php?f=delete_category` | High
92 | File | `/classes/Master.php?f=delete_product` | High
93 | ... | ... | ...

There are 825 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
