# Tsunami - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Tsunami_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tsunami:

* [VN](https://vuldb.com/?country.vn)

## Actors

These _actors_ are associated with Tsunami or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
2 | [Tsunami](https://vuldb.com/?actor.tsunami) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tsunami.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.101.118.127](https://vuldb.com/?ip.5.101.118.127) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
2 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
3 | [5.181.25.210](https://vuldb.com/?ip.5.181.25.210) | vpn1255rm.com | [Tsunami](https://vuldb.com/?actor.tsunami) | High
4 | [5.181.80.119](https://vuldb.com/?ip.5.181.80.119) | rate-lead.cheapjerseysbrewers.com | [Tsunami](https://vuldb.com/?actor.tsunami) | High
5 | [5.231.70.214](https://vuldb.com/?ip.5.231.70.214) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
6 | [20.151.71.228](https://vuldb.com/?ip.20.151.71.228) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
7 | [23.95.226.157](https://vuldb.com/?ip.23.95.226.157) | 157-226-scilla.manykril.sbs | [Tsunami](https://vuldb.com/?actor.tsunami) | High
8 | [31.131.16.127](https://vuldb.com/?ip.31.131.16.127) | moy-dom.biz | [Tsunami](https://vuldb.com/?actor.tsunami) | High
9 | [37.44.244.106](https://vuldb.com/?ip.37.44.244.106) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
10 | [37.44.244.124](https://vuldb.com/?ip.37.44.244.124) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
11 | [45.9.148.44](https://vuldb.com/?ip.45.9.148.44) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
12 | [45.9.148.182](https://vuldb.com/?ip.45.9.148.182) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
13 | [45.95.55.24](https://vuldb.com/?ip.45.95.55.24) | flyhosting.de | [Tsunami](https://vuldb.com/?actor.tsunami) | High
14 | [47.105.158.116](https://vuldb.com/?ip.47.105.158.116) | - | [Tsunami](https://vuldb.com/?actor.tsunami) | High
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Tsunami. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Tsunami. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/activation.php` | High
2 | File | `/activity/newActivityedit.php?DontCheckLogin=1&id=null&ret=mod1` | High
3 | File | `/add-lockertype.php` | High
4 | File | `/add-users.php` | High
5 | File | `/addclient1.php` | High
6 | File | `/addcustcom.php` | High
7 | File | `/addstock.php` | High
8 | File | `/admin` | Low
9 | File | `/admin-api/bpm/model/deploy` | High
10 | File | `/admin-api/infra/file/upload` | High
11 | File | `/admin-cp/imports` | High
12 | File | `/admin-cp/menus` | High
13 | File | `/admin-cp/plugin/install` | High
14 | File | `/admin-page.php` | High
15 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
16 | File | `/admin.php?id=inbox` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?page=categories/view_category` | High
19 | File | `/admin/?page=return/view_return` | High
20 | File | `/admin/?page=user` | High
21 | File | `/admin/?page=user/manage_user&id=3` | High
22 | File | `/admin/about-us.php` | High
23 | File | `/admin/add-category.php` | High
24 | File | `/admin/add-pass.php` | High
25 | File | `/admin/add-scdetails.php` | High
26 | File | `/admin/addadvertisement.php` | High
27 | File | `/Admin/additems.php` | High
28 | File | `/admin/add_category.php` | High
29 | File | `/admin/add_teacher.php` | High
30 | File | `/admin/admin-profile.php` | High
31 | File | `/admin/admin.php` | High
32 | File | `/admin/adminprofile.php` | High
33 | File | `/admin/admin_forum/search_result.php` | High
34 | File | `/admin/admin_index.php` | High
35 | File | `/admin/admin_user.php` | High
36 | File | `/admin/ajax.php?action=delete_recruitment_status` | High
37 | File | `/admin/ajax.php?action=save_student` | High
38 | File | `/admin/app/service_crud.php` | High
39 | File | `/admin/archives_add.php` | High
40 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
41 | File | `/admin/bill.php` | High
42 | File | `/admin/book-details.php` | High
43 | File | `/admin/bwdates-passreports-details.php` | High
44 | File | `/admin/calendar_of_events.php` | High
45 | File | `/admin/categories/manage_category.php` | High
46 | File | `/admin/category_update.php` | High
47 | File | `/admin/change-emailid.php` | High
48 | File | `/admin/changeimage.php` | High
49 | File | `/Admin/changepassword.php` | High
50 | File | `/admin/clients/` | High
51 | File | `/admin/clientview.php` | High
52 | File | `/admin/complaint-search.php` | High
53 | File | `/admin/config_save.php` | High
54 | File | `/admin/edit-admin.php` | High
55 | File | `/admin/edit-category-detail.php` | High
56 | File | `/admin/edit-category.php` | High
57 | File | `/admin/edit-class.php` | High
58 | File | `/admin/edit-class.php?cid=1` | High
59 | File | `/admin/edit-products.php` | High
60 | File | `/admin/edit-services.php` | High
61 | File | `/admin/edit-subcategory.php` | High
62 | File | `/admin/edit-teacher-info.php` | High
63 | File | `/admin/edit-user.php` | High
64 | File | `/admin/edit_customer.php` | High
65 | File | `/admin/edit_room.php` | High
66 | File | `/admin/edit_teacher.php` | High
67 | File | `/admin/fetch_product_details.php` | High
68 | File | `/admin/finished.php` | High
69 | File | `/admin/forgot-password.php` | High
70 | File | `/admin/freelist_main.php` | High
71 | File | `/admin/home.php?con=add` | High
72 | File | `/admin/includes/edit_post.php` | High
73 | File | `/admin/index.php` | High
74 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
75 | File | `/admin/insert-product.php` | High
76 | File | `/admin/invoiceprint.php` | High
77 | File | `/admin/list_addr_fwresource_ip.php` | High
78 | File | `/admin/login.php` | High
79 | File | `/admin/login_process.php` | High
80 | File | `/admin/model/addOrUpdate` | High
81 | File | `/admin/newsletterdel.php` | High
82 | File | `/admin/password-recovery.php` | High
83 | File | `/admin/payment_save.php` | High
84 | File | `/admin/print1.php` | High
85 | File | `/admin/profile.php` | High
86 | File | `/admin/receipt.php` | High
87 | File | `/Admin/registration.php` | High
88 | File | `/admin/registration.php` | High
89 | File | `/admin/reservation.php` | High
90 | File | `/admin/roomdel.php` | High
91 | File | `/admin/save_student.php` | High
92 | File | `/admin/search-appointment.php` | High
93 | File | `/admin/search-autoortaxi.php` | High
94 | File | `/admin/search-maid.php` | High
95 | File | `/admin/search.php` | High
96 | File | `/admin/semester.php` | High
97 | File | `/admin/spec_add.php` | High
98 | File | `/admin/students/manage_academic.php` | High
99 | File | `/admin/suppliercontroller.php` | High
100 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
101 | File | `/admin/templets_one_edit.php` | High
102 | File | `/admin/test_status.php` | High
103 | File | `/admin/transactions/track_shipment.php` | High
104 | File | `/admin/update_user.php` | High
105 | File | `/admin/uploads/` | High
106 | File | `/admin/user/manage_user.php` | High
107 | File | `/admin/users.php` | High
108 | File | `/admin/user_update.php` | High
109 | File | `/admin/view-member-report.php` | High
110 | File | `/admin/view-outgoingvehicle-detail.php` | High
111 | File | `/admin/view-progress-report.php` | High
112 | File | `/adminFile/upload` | High
113 | File | `/adminPage/conf/reload` | High
114 | File | `/admin_class.php` | High
115 | File | `/admin_type.php` | High
116 | File | `/admin_user.php` | High
117 | File | `/adposition/queryAll` | High
118 | File | `/agent/profile/edit` | High
119 | File | `/ajax.php?action=delete_employee_attendance_single` | High
120 | File | `/ajax.php?action=delete_package` | High
121 | File | `/ajax.php?action=delete_sales` | High
122 | File | `/ajax.php?action=delete_user` | High
123 | File | `/ajax.php?action=login` | High
124 | File | `/ajax.php?action=save_customer` | High
125 | File | `/ajax_city.php` | High
126 | File | `/alunos/search_autocomplete` | High
127 | File | `/api/admin/template/config` | High
128 | File | `/api/backend/core/web-file-upload/upload` | High
129 | File | `/api/controllers/merchant/design/MaterialController.php` | High
130 | File | `/api/dept/build` | High
131 | ... | ... | ...

There are 1159 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/54647/
* https://bazaar.abuse.ch/sample/02acdc11b6e22b8fa19ebafb10190ac28a7f0e5ee569a058c2df825337e4447a/
* https://bazaar.abuse.ch/sample/1b40a289556934d67a35d6422f66b3b062e616d0b7e00d23f543d25183ebe8d6/
* https://bazaar.abuse.ch/sample/2f1854f309c913068700c0c3efec3a84ea48e62393df38bab9c8233053e2b19b/
* https://bazaar.abuse.ch/sample/6c6888a75d6a62dc7414dd22d0b6a70456a108a14889b8406f7aeb8b61b34633/
* https://bazaar.abuse.ch/sample/7c4e9e95a27147623ec5b3be81c76c131a0871d75f50b148b93e88ef6ee0b468/
* https://bazaar.abuse.ch/sample/8a04585157033b86cb2c104f441d236bc3255b46127355f8342b75ab40eb3e35/
* https://bazaar.abuse.ch/sample/8d411d1ec4327e5a10b8ffddaacdac17a0a6acab43db81202119604b35c7317b/
* https://bazaar.abuse.ch/sample/15c7fe5a56b80a43544c3227a8589045bf67d0a65c2ebba2506102250f6da963/
* https://bazaar.abuse.ch/sample/15e7942ebf88a51346d3a5975bb1c2d87996799e6255db9e92aed798d279b36b/
* https://bazaar.abuse.ch/sample/31bb97ce0b8274599f47a8630b58a303d2f3dde966df511cd3dc3f993780ceec/
* https://bazaar.abuse.ch/sample/47ae4040d1a421d43309e11b9e2fcd687f34f085e203ef170913708ca3c35e3c/
* https://bazaar.abuse.ch/sample/85cbeced4d53526b94815b894e09199f8f5f7d4c889643ad1cb23aeaf2f7619f/
* https://bazaar.abuse.ch/sample/210c65c6af61d62146925dbe5821f90e8eb9282775fb48921bb573facc478c52/
* https://bazaar.abuse.ch/sample/601a9a769138a444dd359058dee0b4d797f8aef42d7c22dfb469bbaf55695ed6/
* https://bazaar.abuse.ch/sample/800c90c7b4eaf5562a0bcd6b640fd0a29a34aef48522fe579583d3866ca038f4/
* https://bazaar.abuse.ch/sample/938cd2020a8551d57ed522c81a4fca9df0cb22db221381ea0e19f0149ee8100e/
* https://bazaar.abuse.ch/sample/1917aa3e5bfd1c6a958ca61875c4f58edcbf68d5b954707523b3088fbb096363/
* https://bazaar.abuse.ch/sample/76420e2f4edda9c5b643b1d2d1ff895b02373a746a8d004e87f71e2b15122669/
* https://bazaar.abuse.ch/sample/355807fc92869c656200c3c8a7f41cd204c92a5abf3437324e4a0a6a8a68ed78/
* https://bazaar.abuse.ch/sample/656639f032e8e10efc8c581cf03bd2a75c89cdb71cf25e857f2bca1d8b983c42/
* https://bazaar.abuse.ch/sample/a64ddaa1e3747b10863af3b60e79bbef1295a71ffdf3dd15a390d5926a6c3c13/
* https://bazaar.abuse.ch/sample/aaa03b1810498597909ddb7756779921fd187df1baea91faafeee0e00ffdaccc/
* https://bazaar.abuse.ch/sample/b30702b6432c4a5ca65ebc060b72f28ba71f60b20bb38b6f858af5e6aa61896f/
* https://bazaar.abuse.ch/sample/d335c83c0dd5bc9a078e796016f9a9f845ff89ee434c63c7a2e7b360e8be3e95/
* https://bazaar.abuse.ch/sample/db31b258371a7e643cb35cb84798090a00c6c02cd9879f02187cdbba60be1ce3/
* https://bazaar.abuse.ch/sample/e21ba3f25330cf22713367d510a50510ec807e73240f4f9ad3e37987754de534/
* https://bazaar.abuse.ch/sample/fe3c5c4f94b90619f7385606dfb86b6211b030efe19b49c12ead507c8156507a/
* https://blog.netlab.360.com/threat-alert-log4j-vulnerability-has-been-adopted-by-two-linux-botnets/
* https://exchange.xforce.ibmcloud.com/threats/guid:94e798f76e8cfd2feab41ea2d028135a
* https://threatfox.abuse.ch
* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/
* https://urlhaus.abuse.ch/host/202.110.187.205/
* https://urlhaus.abuse.ch/url/3518097/
* https://urlhaus.abuse.ch/url/3518102/
* https://urlhaus.abuse.ch/url/3548307/
* https://urlhaus.abuse.ch/url/3568976/
* https://urlhaus.abuse.ch/url/3571562/
* https://urlhaus.abuse.ch/url/3700479/
* https://urlhaus.abuse.ch/url/3713105/
* https://www.virustotal.com/gui/file/6c0dbbd757cac412e4f80a761d0084c4dcee7d0ec46d1a0bf769474f8ed153b3

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
