# Sandworm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sandworm](https://vuldb.com/?actor.sandworm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sandworm](https://vuldb.com/?actor.sandworm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sandworm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sandworm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.164.52](https://vuldb.com/?ip.2.56.164.52) | exit.node | - | High
2 | [2.58.56.101](https://vuldb.com/?ip.2.58.56.101) | 2.58.56.101.powered.by.rdp.sh | - | High
3 | [5.45.73.243](https://vuldb.com/?ip.5.45.73.243) | - | - | High
4 | [5.181.80.132](https://vuldb.com/?ip.5.181.80.132) | local.charge.manufacturingservices.de | - | High
5 | [5.252.118.19](https://vuldb.com/?ip.5.252.118.19) | blocked.aeza.net | - | High
6 | [5.255.99.205](https://vuldb.com/?ip.5.255.99.205) | - | - | High
7 | [23.129.64.133](https://vuldb.com/?ip.23.129.64.133) | - | - | High
8 | [27.19.56.44](https://vuldb.com/?ip.27.19.56.44) | - | - | High
9 | [45.89.106.147](https://vuldb.com/?ip.45.89.106.147) | - | - | High
10 | [45.128.232.108](https://vuldb.com/?ip.45.128.232.108) | - | - | High
11 | [45.128.232.143](https://vuldb.com/?ip.45.128.232.143) | 143.232.128.45.pfcloud.io | - | High
12 | [45.139.122.241](https://vuldb.com/?ip.45.139.122.241) | - | - | High
13 | [45.141.215.111](https://vuldb.com/?ip.45.141.215.111) | - | - | High
14 | [45.154.98.225](https://vuldb.com/?ip.45.154.98.225) | - | - | High
15 | [46.8.198.196](https://vuldb.com/?ip.46.8.198.196) | - | - | High
16 | [46.182.21.248](https://vuldb.com/?ip.46.182.21.248) | tor-exit-relay.anonymizing-proxy.digitalcourage.de | - | High
17 | [51.89.153.112](https://vuldb.com/?ip.51.89.153.112) | ns3145504.ip-51-89-153.eu | - | High
18 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | - | High
19 | [62.182.84.146](https://vuldb.com/?ip.62.182.84.146) | ml148.spryraven.com | - | High
20 | [63.79.171.112](https://vuldb.com/?ip.63.79.171.112) | - | - | High
21 | [64.112.74.166](https://vuldb.com/?ip.64.112.74.166) | - | - | High
22 | [70.62.153.174](https://vuldb.com/?ip.70.62.153.174) | syn-070-062-153-174.biz.spectrum.com | - | High
23 | [77.48.28.204](https://vuldb.com/?ip.77.48.28.204) | 204.28.48.77.finalhosting.cz | - | High
24 | [77.48.28.236](https://vuldb.com/?ip.77.48.28.236) | missun.intervocalically.com | - | High
25 | [77.64.229.43](https://vuldb.com/?ip.77.64.229.43) | 77.64.229.43.dyn.pyur.net | - | High
26 | [77.91.123.136](https://vuldb.com/?ip.77.91.123.136) | vm1756241.stark-industries.solutions | - | High
27 | [79.137.194.146](https://vuldb.com/?ip.79.137.194.146) | karlx1da.pwh | - | High
28 | [80.67.167.81](https://vuldb.com/?ip.80.67.167.81) | nosoignons.cust.milkywan.net | - | High
29 | [82.180.150.197](https://vuldb.com/?ip.82.180.150.197) | - | - | High
30 | ... | ... | ... | ...

There are 115 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sandworm_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandworm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/a/sys/user/save` | High
2 | File | `/accounts_con/register_account` | High
3 | File | `/activity/newActivityedit.php?DontCheckLogin=1&id=null&ret=mod1` | High
4 | File | `/addstock.php` | High
5 | File | `/admin` | Low
6 | File | `/admin/` | Low
7 | File | `/admin/?page=bike` | High
8 | File | `/admin/?page=user/list` | High
9 | File | `/admin/about-us.php` | High
10 | File | `/admin/add-services.php` | High
11 | File | `/admin/add-teacher.php` | High
12 | File | `/admin/adddoctor.php` | High
13 | File | `/admin/addmanagerclinic.php` | High
14 | File | `/admin/admin-profile.php` | High
15 | File | `/admin/admin.php` | High
16 | File | `/admin/admin_content_tag.php?action=save_content` | High
17 | File | `/admin/api/admin/v2_products` | High
18 | File | `/admin/appointment.php` | High
19 | File | `/admin/approve.php` | High
20 | File | `/admin/article/article-edit-run.php` | High
21 | File | `/admin/bwdates-report-details.php` | High
22 | File | `/admin/bwdates-reports-details.php` | High
23 | File | `/admin/category/cate-edit-run.php` | High
24 | File | `/admin/category_save.php` | High
25 | File | `/admin/changeimage.php` | High
26 | File | `/admin/changepassword.php` | High
27 | File | `/admin/change_pass.php` | High
28 | File | `/admin/chatroom.php` | High
29 | File | `/admin/clients/manage.php` | High
30 | File | `/admin/clientview.php` | High
31 | File | `/admin/confirm_reserve.php` | High
32 | File | `/admin/contact-us.php` | High
33 | File | `/admin/course.php` | High
34 | File | `/admin/courses/manage_course.php` | High
35 | File | `/admin/deleteuser.php` | High
36 | File | `/admin/del_category.php` | High
37 | File | `/admin/departments/manage_department.php` | High
38 | File | `/admin/edit-accepted-appointment.php` | High
39 | File | `/admin/edit-category.php` | High
40 | File | `/admin/edit-subadmin.php` | High
41 | File | `/admin/edit-subcategory.php` | High
42 | File | `/admin/edit-subjects-detail.php` | High
43 | File | `/admin/editcar-washpoint.php` | High
44 | File | `/admin/editempprofile.php` | High
45 | File | `/admin/edit_action.php` | High
46 | File | `/admin/edit_product.php` | High
47 | File | `/admin/employee_edit.php` | High
48 | File | `/admin/execedituser.php` | High
49 | File | `/admin/forgot-password.php` | High
50 | File | `/admin/index.php` | High
51 | File | `/admin/invoice.php` | High
52 | File | `/admin/leancloud.php` | High
53 | File | `/admin/list_ipAddressPolicy.php` | High
54 | File | `/admin/login.php` | High
55 | File | `/admin/manage-normal-ticket.php` | High
56 | File | `/admin/manage-users.php` | High
57 | File | `/admin/manage_academic.php` | High
58 | File | `/admin/mechanics/manage_mechanic.php` | High
59 | File | `/admin/member_update.php` | High
60 | File | `/admin/menu/toEdit` | High
61 | File | `/admin/menu_save.php` | High
62 | File | `/admin/positions_row.php` | High
63 | File | `/admin/print.php` | High
64 | File | `/admin/profile.php` | High
65 | File | `/admin/read.php?mudi=getSignal` | High
66 | File | `/admin/regester.php` | High
67 | File | `/admin/return_add.php` | High
68 | File | `/admin/sales/view_details.php` | High
69 | File | `/admin/search-appointment.php` | High
70 | File | `/admin/search-medicalcard.php` | High
71 | File | `/admin/search-property.php` | High
72 | File | `/admin/search-report-details.php` | High
73 | File | `/admin/store.php` | High
74 | File | `/admin/student.php` | High
75 | File | `/admin/sys/menu/list` | High
76 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
77 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
78 | File | `/admin/sys_sql_query.php` | High
79 | File | `/admin/test_status.php` | High
80 | File | `/admin/update_room.php` | High
81 | File | `/admin/update_user.php` | High
82 | File | `/admin/upload.php` | High
83 | File | `/admin/user/manage_user.php` | High
84 | File | `/admin/users_photo.php` | High
85 | File | `/admin/view-foreigner-ticket.php` | High
86 | File | `/adminapi/system/crud` | High
87 | File | `/administrator` | High
88 | File | `/adminPage/www/addOver` | High
89 | File | `/admin_paylog.php` | High
90 | File | `/api/DataDictionary/GetItemList` | High
91 | File | `/api/front/search/books` | High
92 | File | `/api/log/killJob` | High
93 | File | `/api/role` | Medium
94 | File | `/Api/TinyMce/UploadAjax.ashx` | High
95 | File | `/api/v2/open/tablesInfo` | High
96 | File | `/app/admin/controller/Upload.php` | High
97 | File | `/app/sys1.php` | High
98 | File | `/application/index/controller/File.php` | High
99 | File | `/App_Resource/UEditor/server/upload.aspx` | High
100 | File | `/artist-display.php` | High
101 | File | `/att_add.php` | Medium
102 | File | `/backup.pl` | Medium
103 | File | `/bbs/scrap_popin_update/qa/` | High
104 | File | `/bin/gpio` | Medium
105 | File | `/birthing.php` | High
106 | File | `/blog` | Low
107 | File | `/boaform/device_reset.cgi` | High
108 | File | `/boafrm/formFilter` | High
109 | File | `/boafrm/formIpQoS` | High
110 | File | `/boafrm/formVlan` | High
111 | File | `/boafrm/formWdsEncrypt` | High
112 | File | `/boafrm/formWlanMultipleAP` | High
113 | File | `/boat-details.php` | High
114 | File | `/booking/show_bookings/` | High
115 | ... | ... | ...

There are 1015 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/3718487
* https://cert.gov.ua/article/6123309
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/Clearing%20the%20Fog%20of%20War%20A%20Critical%20Analysis%20of%20Recent%20Energy%20Sector%20Attacks%20in%20Denmark%20and%20Ukraine.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/NCSC-MAR-Infamous-Chisel.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/SBU%20exposes%20russian%20intelligence%20attempts%20to%20penetrate%20Armed%20Forces'%20planning%20operations%20system.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/sektorcert-angrebet-mod-dansk-kritisk-infrastruktur-tlp-clear-en.pdf
* https://www.mandiant.com/resources/blog/sandworm-disrupts-power-ukraine-operational-technology

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
