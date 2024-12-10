# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [ES](https://vuldb.com/?country.es)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/aboutadd.php` | High
4 | File | `/aboutedit.php` | High
5 | File | `/abs.php` | Medium
6 | File | `/activation.php` | High
7 | File | `/addcustind.php` | High
8 | File | `/addstock.php` | High
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
19 | File | `/admin/admin-profile.php` | High
20 | File | `/Admin/adminlogin.php` | High
21 | File | `/admin/apply.php` | High
22 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
23 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
24 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
25 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
28 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
29 | File | `/admin/blood/update/B+.php` | High
30 | File | `/admin/blood/update/B-.php` | High
31 | File | `/admin/blood/update/o-.php` | High
32 | File | `/admin/book-details.php` | High
33 | File | `/admin/bwdates-report-details.php` | High
34 | File | `/admin/campsdetails.php` | High
35 | File | `/admin/categories/manage_category.php` | High
36 | File | `/admin/change-image.php` | High
37 | File | `/admin/cmsTagType/save` | High
38 | File | `/admin/create-package.php` | High
39 | File | `/Admin/detail.php` | High
40 | File | `/admin/edit-brand.php` | High
41 | File | `/admin/edit-card-detail.php` | High
42 | File | `/admin/edit-subadmin.php` | High
43 | File | `/admin/edit_customer.php` | High
44 | File | `/admin/edit_fuel.php` | High
45 | File | `/admin/edit_manufacturer.php` | High
46 | File | `/admin/File/fileUpload` | High
47 | File | `/admin/File/pictureUpload` | High
48 | File | `/admin/home.php` | High
49 | File | `/admin/index.php` | High
50 | File | `/admin/inquiries/view_details.php` | High
51 | File | `/admin/login.php` | High
52 | File | `/admin/login_process.php` | High
53 | File | `/admin/maintenance/manage_department.php` | High
54 | File | `/admin/massage.php` | High
55 | File | `/admin/msg.php` | High
56 | File | `/admin/overtime_add.php` | High
57 | File | `/admin/overtime_row.php` | High
58 | File | `/admin/password-recovery.php` | High
59 | File | `/admin/profile.php` | High
60 | File | `/Admin/Proses_Edit_Akun.php` | High
61 | File | `/admin/robot.php` | High
62 | File | `/admin/search-invoices.php` | High
63 | File | `/admin/search-medicalcard.php` | High
64 | File | `/admin/search-vehicle.php` | High
65 | File | `/admin/services/view_service.php` | High
66 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
67 | File | `/admin/tag.php` | High
68 | File | `/admin/view-card-detail.php` | High
69 | File | `/admin/view-enquiry.php` | High
70 | File | `/ajax.php?action=delete_tenant` | High
71 | File | `/ajax.php?action=save_category` | High
72 | File | `/ajax.php?action=signup` | High
73 | File | `/ajax.php?action=update_account` | High
74 | File | `/animalsadd.php` | High
75 | File | `/animalsupdate.php` | High
76 | File | `/api/config/list` | High
77 | File | `/api/v2/schema` | High
78 | File | `/app/action/add_staff.php` | High
79 | File | `/app/admin/controller/file/File.php` | High
80 | File | `/auth_files/photo/` | High
81 | File | `/bloodrequest.php` | High
82 | File | `/book_list.php` | High
83 | ... | ... | ...

There are 729 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
