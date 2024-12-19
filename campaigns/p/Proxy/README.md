# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Proxy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Proxy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
6 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=reserve` | High
3 | File | `/?page=tickets` | High
4 | File | `/aboutadd.php` | High
5 | File | `/aboutedit.php` | High
6 | File | `/abs.php` | Medium
7 | File | `/activation.php` | High
8 | File | `/add.php` | Medium
9 | File | `/addcompany.php` | High
10 | File | `/add_new_invoice.php` | High
11 | File | `/add_new_purchase.php?action=is_supplier` | High
12 | File | `/add_new_supplier.php` | High
13 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
14 | File | `/admin/` | Low
15 | File | `/admin/?page=inventory/view_inventory&id=2` | High
16 | File | `/admin/?page=products/view_product` | High
17 | File | `/admin/?page=reports` | High
18 | File | `/admin/about-us.php` | High
19 | File | `/Admin/add-admin.php` | High
20 | File | `/admin/add-customer.php` | High
21 | File | `/admin/add-doctor.php` | High
22 | File | `/admin/add-services.php` | High
23 | File | `/admin/admin-profile.php` | High
24 | File | `/Admin/adminlogin.php` | High
25 | File | `/admin/apply.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
28 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
30 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
33 | File | `/admin/blood/update/B+.php` | High
34 | File | `/admin/blood/update/B-.php` | High
35 | File | `/admin/blood/update/o-.php` | High
36 | File | `/admin/book-details.php` | High
37 | File | `/admin/bwdates-report-details.php` | High
38 | File | `/admin/campsdetails.php` | High
39 | File | `/admin/categories/manage_category.php` | High
40 | File | `/admin/change-image.php` | High
41 | File | `/admin/check_admin_login.php` | High
42 | File | `/admin/cmsTagType/save` | High
43 | File | `/admin/create-package.php` | High
44 | File | `/Admin/detail.php` | High
45 | File | `/admin/edit-brand.php` | High
46 | File | `/admin/edit-card-detail.php` | High
47 | File | `/admin/edit-customer-detailed.php` | High
48 | File | `/admin/edit-services.php` | High
49 | File | `/admin/edit-subadmin.php` | High
50 | File | `/admin/edit_fuel.php` | High
51 | File | `/admin/edit_manufacturer.php` | High
52 | File | `/admin/File/fileUpload` | High
53 | File | `/admin/File/pictureUpload` | High
54 | File | `/admin/home.php` | High
55 | File | `/admin/index.php` | High
56 | File | `/admin/inquiries/view_details.php` | High
57 | File | `/admin/login.php` | High
58 | File | `/admin/login_process.php` | High
59 | File | `/admin/maintenance/manage_department.php` | High
60 | File | `/admin/massage.php` | High
61 | File | `/admin/network/ajax_getChannelList` | High
62 | File | `/admin/network/diag_nslookup` | High
63 | File | `/admin/network/diag_ping6` | High
64 | File | `/admin/network/diag_pinginterface` | High
65 | File | `/admin/network/diag_traceroute` | High
66 | File | `/admin/network/diag_traceroute6` | High
67 | File | `/admin/network/wifi_schedule` | High
68 | File | `/admin/overtime_add.php` | High
69 | File | `/admin/overtime_row.php` | High
70 | File | `/admin/password-recovery.php` | High
71 | File | `/admin/process_category_add.php` | High
72 | File | `/admin/profile.php` | High
73 | File | `/admin/robot.php` | High
74 | File | `/admin/room.php` | High
75 | File | `/admin/search-appointment.php` | High
76 | File | `/admin/search-medicalcard.php` | High
77 | File | `/admin/search-vehicle.php` | High
78 | File | `/admin/services/view_service.php` | High
79 | File | `/admin/sn_package/sn_https` | High
80 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
81 | File | `/admin/tag.php` | High
82 | File | `/admin/tag/save` | High
83 | File | `/admin/view-card-detail.php` | High
84 | File | `/admin/view-enquiry.php` | High
85 | File | `/admin?do=admin:user:editPost` | High
86 | File | `/ajax.php?action=signup` | High
87 | File | `/animalsadd.php` | High
88 | File | `/api/config/list` | High
89 | File | `/api/v2/schema` | High
90 | ... | ... | ...

There are 792 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/vishalyadav70/Proxy-Server/blob/main/proxy/blacklist.txt
* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
