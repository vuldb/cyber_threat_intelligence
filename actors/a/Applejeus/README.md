# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 7 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37, CWE-44, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/admin/?page=inventory/view_inventory&id=2` | High
10 | File | `/admin/?page=products/view_product` | High
11 | File | `/admin/?page=system_info/contact_info` | High
12 | File | `/admin/add-doctor.php` | High
13 | File | `/admin/add-property.php` | High
14 | File | `/admin/admin_editor.php` | High
15 | File | `/admin/admin_invt2.php` | High
16 | File | `/admin/admin_login.php` | High
17 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
18 | File | `/admin/ajax.php?action=login` | High
19 | File | `/admin/ajax_product.php` | High
20 | File | `/admin/blood/update/B+.php` | High
21 | File | `/admin/blood/update/B-.php` | High
22 | File | `/admin/bwdates-report-details.php` | High
23 | File | `/admin/campsdetails.php` | High
24 | File | `/admin/card-bwdates-reports-details.php` | High
25 | File | `/admin/change-image.php` | High
26 | File | `/admin/changeimage.php` | High
27 | File | `/Admin/consulting_detail.php` | High
28 | File | `/admin/create-package.php` | High
29 | File | `/admin/create_product.php` | High
30 | File | `/admin/DatabaseQuery` | High
31 | File | `/admin/edit-admin.php` | High
32 | File | `/admin/edit-subadmin.php` | High
33 | File | `/admin/edit_area.php` | High
34 | File | `/admin/edit_customer.php` | High
35 | File | `/admin/edit_fuel.php` | High
36 | File | `/admin/edit_manufacturer.php` | High
37 | File | `/admin/extensions/upload.php` | High
38 | File | `/admin/File/fileUpload` | High
39 | File | `/admin/file_manager/export` | High
40 | File | `/admin/file_manager/files` | High
41 | File | `/admin/home.php` | High
42 | File | `/admin/home.php?con=add` | High
43 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
44 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
45 | File | `/admin/inquiries/view_details.php` | High
46 | File | `/admin/invoice.php` | High
47 | File | `/admin/maintenance/manage_department.php` | High
48 | File | `/admin/massage.php` | High
49 | File | `/admin/mod_room/controller.php?action=add` | High
50 | File | `/admin/network/diag_pinginterface` | High
51 | File | `/admin/options-theme.php` | High
52 | File | `/admin/overtime_add.php` | High
53 | File | `/admin/overtime_row.php` | High
54 | File | `/admin/print.php` | High
55 | File | `/admin/robot.php` | High
56 | File | `/admin/salary_slip.php` | High
57 | File | `/admin/search-vehicle.php` | High
58 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
59 | File | `/admin/template/edit` | High
60 | File | `/admin/template/update` | High
61 | File | `/admin/user/user-move-run.php` | High
62 | File | `/adms/admin/?page=vehicles/view_transaction` | High
63 | File | `/ajax.php?action=delete_tenant` | High
64 | File | `/ajax/chpwd.php` | High
65 | File | `/ajax/getBasicInfo.php` | High
66 | File | `/animalsadd.php` | High
67 | File | `/api/` | Low
68 | File | `/api/client/editemedia.php` | High
69 | File | `/api/Common/uploadFile` | High
70 | File | `/api/config/list` | High
71 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
72 | File | `/app/admin/controller/file/File.php` | High
73 | File | `/apply/index.php` | High
74 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
75 | ... | ... | ...

There are 661 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
