# Shade - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shade](https://vuldb.com/?actor.shade). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shade](https://vuldb.com/?actor.shade)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shade:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shade.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.66](https://vuldb.com/?ip.5.9.116.66) | static.66.116.9.5.clients.your-server.de | - | High
2 | [5.9.158.75](https://vuldb.com/?ip.5.9.158.75) | static.75.158.9.5.clients.your-server.de | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.6.22.189](https://vuldb.com/?ip.23.6.22.189) | a23-6-22-189.deploy.static.akamaitechnologies.com | - | High
5 | [37.157.254.113](https://vuldb.com/?ip.37.157.254.113) | rs004106.root.server-hosting.expert | - | High
6 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | - | High
7 | [46.166.182.20](https://vuldb.com/?ip.46.166.182.20) | - | - | High
8 | [47.101.49.13](https://vuldb.com/?ip.47.101.49.13) | - | - | High
9 | [51.68.204.139](https://vuldb.com/?ip.51.68.204.139) | ns3127231.ip-51-68-204.eu | - | High
10 | [51.68.206.28](https://vuldb.com/?ip.51.68.206.28) | ns3128207.ip-51-68-206.eu | - | High
11 | [62.151.180.62](https://vuldb.com/?ip.62.151.180.62) | mx18062.brandengager.info | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shade_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shade. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?g=net_pro_keyword_import_save` | High
3 | File | `/?page=tickets` | High
4 | File | `/?page=tracks` | High
5 | File | `/abs.php` | Medium
6 | File | `/actuator/heapdump` | High
7 | File | `/add_new_purchase.php?action=is_supplier` | High
8 | File | `/add_new_supplier.php` | High
9 | File | `/admin` | Low
10 | File | `/admin-dashboard` | High
11 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=categories/view_category` | High
14 | File | `/admin/?page=inventory/view_inventory&id=2` | High
15 | File | `/admin/?page=products/view_product` | High
16 | File | `/admin/?page=system_info/contact_info` | High
17 | File | `/Admin/add-admin.php` | High
18 | File | `/admin/add-doctor.php` | High
19 | File | `/admin/addgiving.php` | High
20 | File | `/admin/addTithes.php` | High
21 | File | `/admin/add_ikev2.php` | High
22 | File | `/admin/add_postlogin.php` | High
23 | File | `/admin/add_sundaysch.php` | High
24 | File | `/admin/admin_cl.php?mudi=revPwd` | High
25 | File | `/admin/admin_invt2.php` | High
26 | File | `/admin/admin_user.php` | High
27 | File | `/admin/ajax_product.php` | High
28 | File | `/admin/blood/update/B+.php` | High
29 | File | `/admin/bwdates-report-details.php` | High
30 | File | `/admin/campsdetails.php` | High
31 | File | `/admin/card-bwdates-reports-details.php` | High
32 | File | `/admin/change-image.php` | High
33 | File | `/admin/changeimage.php` | High
34 | File | `/admin/config_Anticrack.php` | High
35 | File | `/admin/config_ISCGroupNoCache.php` | High
36 | File | `/admin/config_MT.php?action=delete` | High
37 | File | `/admin/create-package.php` | High
38 | File | `/admin/delete_log.php` | High
39 | File | `/admin/edit-brand.php` | High
40 | File | `/Admin/edit-photo.php` | High
41 | File | `/admin/edit-post.php` | High
42 | File | `/admin/edit-subadmin.php` | High
43 | File | `/admin/edit_area.php` | High
44 | File | `/admin/edit_customer.php` | High
45 | File | `/admin/edit_fuel.php` | High
46 | File | `/admin/edit_manufacturer.php` | High
47 | File | `/Admin/edit_profile.php` | High
48 | File | `/admin/emp-profile-avatar.php` | High
49 | File | `/admin/File/fileUpload` | High
50 | File | `/admin/file_manager/export` | High
51 | File | `/admin/file_manager/files` | High
52 | File | `/admin/general-setting` | High
53 | File | `/admin/home.php` | High
54 | File | `/admin/home.php?con=add` | High
55 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
56 | File | `/admin/index.php` | High
57 | File | `/admin/inquiries/view_details.php` | High
58 | File | `/admin/invoice.php` | High
59 | File | `/admin/login.php` | High
60 | File | `/admin/maintenance/manage_brand.php` | High
61 | File | `/admin/maintenance/manage_department.php` | High
62 | File | `/admin/massage.php` | High
63 | File | `/admin/media_folders` | High
64 | File | `/admin/member_save.php` | High
65 | File | `/admin/mod_room/controller.php?action=add` | High
66 | File | `/admin/normal-bwdates-reports-details.php` | High
67 | File | `/admin/overtime_add.php` | High
68 | File | `/admin/overtime_row.php` | High
69 | File | `/admin/pages/` | High
70 | File | `/admin/print.php` | High
71 | File | `/admin/robot.php` | High
72 | File | `/admin/search-vehicle.php` | High
73 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
74 | File | `/admin/system.html` | High
75 | File | `/admin/template/edit` | High
76 | File | `/admin/template/update` | High
77 | File | `/admin/user/user-move-run.php` | High
78 | File | `/adminPage/conf/reload` | High
79 | File | `/adminPage/main/upload` | High
80 | File | `/adminPage/www/addOver` | High
81 | File | `/adminpanel/admin/query/addCourseExe.php` | High
82 | File | `/admin_class.php` | High
83 | File | `/ad_js.php` | Medium
84 | File | `/ajax.php?action=delete_tenant` | High
85 | File | `/ajax.php?action=save_category` | High
86 | File | `/ajax/chpwd.php` | High
87 | File | `/ajax/getBasicInfo.php` | High
88 | File | `/animalsadd.php` | High
89 | File | `/api/file/downloadfile` | High
90 | File | `/api/process.php` | High
91 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
92 | File | `/api/user` | Medium
93 | File | `/app/admin/controller/file/File.php` | High
94 | File | `/appConfig/userDB.json` | High
95 | File | `/application/controller/Pelanggan.php` | High
96 | File | `/application/controller/Pengeluaran.php` | High
97 | File | `/application/controller/Transaki.php` | High
98 | File | `/authMonitCallcenter` | High
99 | File | `/backend/register.php` | High
100 | File | `/branch_viewmore.php` | High
101 | File | `/buscar_integrada.php` | High
102 | File | `/cart.php` | Medium
103 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
104 | File | `/cgi-bin/cstecgi.cgi` | High
105 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
106 | ... | ... | ...

There are 936 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0906-0913.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0920-0927.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1025-1101.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
