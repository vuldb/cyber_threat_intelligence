# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [Applejeus](https://vuldb.com/?actor.applejeus) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tickets` | High
2 | File | `/?page=tracks` | High
3 | File | `/abs.php` | Medium
4 | File | `/add_new_purchase.php?action=is_supplier` | High
5 | File | `/add_new_supplier.php` | High
6 | File | `/admin-dashboard` | High
7 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
8 | File | `/admin/` | Low
9 | File | `/admin/?page=categories/view_category` | High
10 | File | `/admin/?page=inventory/view_inventory&id=2` | High
11 | File | `/admin/?page=products/view_product` | High
12 | File | `/admin/?page=system_info/contact_info` | High
13 | File | `/admin/add-doctor.php` | High
14 | File | `/admin/admin-add-employee.php` | High
15 | File | `/admin/admin_invt2.php` | High
16 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
17 | File | `/admin/ajax.php?action=login` | High
18 | File | `/admin/ajax.php?action=save_settings` | High
19 | File | `/admin/ajax_product.php` | High
20 | File | `/admin/blood/update/B+.php` | High
21 | File | `/admin/blood/update/B-.php` | High
22 | File | `/admin/bwdates-report-details.php` | High
23 | File | `/admin/campsdetails.php` | High
24 | File | `/admin/card-bwdates-reports-details.php` | High
25 | File | `/admin/change-image.php` | High
26 | File | `/admin/changeimage.php` | High
27 | File | `/admin/config_MT.php?action=delete` | High
28 | File | `/Admin/consulting_detail.php` | High
29 | File | `/admin/create-package.php` | High
30 | File | `/admin/edit-subadmin.php` | High
31 | File | `/admin/edit_area.php` | High
32 | File | `/admin/edit_customer.php` | High
33 | File | `/admin/edit_fuel.php` | High
34 | File | `/admin/edit_manufacturer.php` | High
35 | File | `/admin/File/fileUpload` | High
36 | File | `/admin/file_manager/export` | High
37 | File | `/admin/file_manager/files` | High
38 | File | `/admin/forgot-password.php` | High
39 | File | `/admin/home.php` | High
40 | File | `/admin/home.php?con=add` | High
41 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
42 | File | `/admin/index.php` | High
43 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
44 | File | `/admin/index2.html` | High
45 | File | `/admin/inquiries/view_details.php` | High
46 | File | `/admin/invoice.php` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/maintenance/manage_department.php` | High
49 | File | `/admin/massage.php` | High
50 | File | `/admin/media_folders` | High
51 | File | `/admin/mod_room/controller.php?action=add` | High
52 | File | `/admin/network/diag_pinginterface` | High
53 | File | `/admin/options-theme.php` | High
54 | File | `/admin/overtime_add.php` | High
55 | File | `/admin/overtime_row.php` | High
56 | File | `/admin/pages/` | High
57 | File | `/admin/print.php` | High
58 | File | `/admin/robot.php` | High
59 | File | `/admin/search-vehicle.php` | High
60 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
61 | File | `/admin/system.html` | High
62 | File | `/admin/template/edit` | High
63 | File | `/admin/template/update` | High
64 | File | `/admin/user/user-move-run.php` | High
65 | File | `/adminPage/conf/reload` | High
66 | File | `/ajax.php?action=delete_tenant` | High
67 | File | `/ajax/chpwd.php` | High
68 | File | `/ajax/getBasicInfo.php` | High
69 | File | `/animalsadd.php` | High
70 | File | `/api/config/list` | High
71 | File | `/api/file/downloadfile` | High
72 | File | `/api/snapshots/` | High
73 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
74 | File | `/api/v2/maps` | Medium
75 | File | `/app/admin/controller/file/File.php` | High
76 | File | `/apply/index.php` | High
77 | File | `/authMonitCallcenter` | High
78 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
79 | File | `/branch_viewmore.php` | High
80 | File | `/buscar_integrada.php` | High
81 | File | `/candidate/index.php` | High
82 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
83 | File | `/cgi-bin/adm.cgi` | High
84 | File | `/cgi-bin/cstecgi.cgi` | High
85 | File | `/cgi-bin/discovery.cgi` | High
86 | File | `/cgi-bin/p1_ftpserver.php` | High
87 | File | `/cgi-bin/settings-firewall.cgi` | High
88 | File | `/cgi-bin/tosei_kikai.php` | High
89 | File | `/cgi-bin/widget_api.cgi` | High
90 | File | `/classes/Master.php?f=delete_category` | High
91 | File | `/classes/Master.php?f=delete_product` | High
92 | ... | ... | ...

There are 809 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
