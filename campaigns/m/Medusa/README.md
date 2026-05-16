# Medusa - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Medusa_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Medusa:

* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* [FR](https://vuldb.com/country/fr)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Medusa or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Medusa](https://vuldb.com/actor/medusa) | High
2 | [MedusaHTTP](https://vuldb.com/actor/medusahttp) | High
3 | [MedusaLocker](https://vuldb.com/actor/medusalocker) | High
4 | ... | ...

There are 2 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Medusa.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.29.17.1](https://vuldb.com/ip/3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | [Medusalocker](https://vuldb.com/actor/medusalocker) | Medium
2 | [5.42.78.61](https://vuldb.com/ip/5.42.78.61) | - | [Medusa](https://vuldb.com/actor/medusa) | High
3 | [5.61.49.177](https://vuldb.com/ip/5.61.49.177) | - | [Medusa](https://vuldb.com/actor/medusa) | High
4 | [5.182.87.27](https://vuldb.com/ip/5.182.87.27) | - | [Medusa](https://vuldb.com/actor/medusa) | High
5 | [8.217.23.144](https://vuldb.com/ip/8.217.23.144) | - | [Medusa](https://vuldb.com/actor/medusa) | High
6 | [20.0.25.177](https://vuldb.com/ip/20.0.25.177) | - | [Medusa](https://vuldb.com/actor/medusa) | High
7 | [23.27.124.228](https://vuldb.com/ip/23.27.124.228) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
8 | [23.27.140.49](https://vuldb.com/ip/23.27.140.49) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
9 | [23.27.140.135](https://vuldb.com/ip/23.27.140.135) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
10 | [23.27.140.228](https://vuldb.com/ip/23.27.140.228) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
11 | [31.220.45.120](https://vuldb.com/ip/31.220.45.120) | rhel9-satellite.vincenzomele.it | [Medusa](https://vuldb.com/actor/medusa) | High
12 | [40.92.90.105](https://vuldb.com/ip/40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | [MedusaLocker](https://vuldb.com/actor/medusalocker) | High
13 | [45.15.157.16](https://vuldb.com/ip/45.15.157.16) | scientific-group.aeza.network | [Medusa](https://vuldb.com/actor/medusa) | High
14 | [45.61.185.34](https://vuldb.com/ip/45.61.185.34) | - | [Medusa](https://vuldb.com/actor/medusa) | High
15 | [45.145.167.117](https://vuldb.com/ip/45.145.167.117) | hms16304.hostmyservers.me | [Medusa](https://vuldb.com/actor/medusa) | High
16 | [45.146.164.141](https://vuldb.com/ip/45.146.164.141) | - | [MedusaLocker](https://vuldb.com/actor/medusalocker) | High
17 | [45.150.65.121](https://vuldb.com/ip/45.150.65.121) | vm1757649.stark-industries.solutions | [Medusa](https://vuldb.com/actor/medusa) | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Medusa. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Medusa. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `.github/workflows/comment.yml` | High
3 | File | `/accomodation.php` | High
4 | File | `/account/orders/create` | High
5 | File | `/add-book.php` | High
6 | File | `/add-customer.php` | High
7 | File | `/add-product.php` | High
8 | File | `/add_drive.php` | High
9 | File | `/add_sales_print.php` | High
10 | File | `/add_stock.php` | High
11 | File | `/admin-api/system/mail-log/page` | High
12 | File | `/admin.php` | Medium
13 | File | `/admin/add-category.php` | High
14 | File | `/admin/add-subcategory.php` | High
15 | File | `/admin/admin-profile.php` | High
16 | File | `/admin/adminHome.php` | High
17 | File | `/admin/admin_edit_supplier.php` | High
18 | File | `/admin/admin_football.php` | High
19 | File | `/admin/ajax.php?action=login` | High
20 | File | `/admin/ajax.php?action=login2` | High
21 | File | `/admin/blogger.php?action=update_avatar` | High
22 | File | `/admin/campsdetails.php` | High
23 | File | `/admin/check_studid.php` | High
24 | File | `/admin/config/list.html` | High
25 | File | `/admin/core/import_users.php` | High
26 | File | `/admin/delete-appointment.php` | High
27 | File | `/admin/deleteuser.php` | High
28 | File | `/admin/display-teacher.php` | High
29 | File | `/admin/edit-art-medium-detail.php` | High
30 | File | `/admin/edit-doctor.php` | High
31 | File | `/admin/edit-teacher-info.php` | High
32 | File | `/admin/editempexp.php` | High
33 | File | `/admin/edit_product.php` | High
34 | File | `/admin/extend/list.html` | High
35 | File | `/admin/filemanager/view` | High
36 | File | `/admin/index.php` | High
37 | File | `/admin/jobs-admins/delete-jobs.php` | High
38 | File | `/admin/login.php` | High
39 | File | `/admin/manage-normal-ticket.php` | High
40 | File | `/admin/manage-notices.php` | High
41 | File | `/admin/manage_booking.php` | High
42 | File | `/admin/manage_register.php` | High
43 | File | `/admin/Member/index.html` | High
44 | File | `/admin/mod_room/index.php?view=edit` | High
45 | File | `/admin/product.php` | High
46 | File | `/admin/registration.php` | High
47 | File | `/admin/save_settings.php` | High
48 | File | `/Admin/sports.php` | High
49 | File | `/admin/student-fee.php` | High
50 | File | `/admin/subjects.php` | High
51 | File | `/admin/teacher-attendance.php` | High
52 | File | `/admin/time-table.php` | High
53 | File | `/admin/tools.php` | High
54 | File | `/admin/update-image2.php` | High
55 | File | `/admin/update-image3.php` | High
56 | File | `/admin/update-rooms.php` | High
57 | File | `/admin/update_s1.php` | High
58 | File | `/admin/update_s3.php` | High
59 | File | `/admin/update_s4.php` | High
60 | File | `/admin/users.php` | High
61 | File | `/admin/view-foreigner-ticket.php` | High
62 | File | `/admin/view-patient.php` | High
63 | File | `/admin/view_sendlist.php` | High
64 | File | `/admin/View_user.php` | High
65 | File | `/adminPage/conf/reload` | High
66 | File | `/adminPage/main/upload` | High
67 | File | `/Adminupdate.php` | High
68 | File | `/admin_panel/settings.php` | High
69 | File | `/admin_single_student.php` | High
70 | File | `/ajax.php?action=delete_user` | High
71 | File | `/ajax.php?action=save_plan` | High
72 | File | `/all-tickets.php` | High
73 | File | `/allocate_room.php` | High
74 | File | `/api` | Low
75 | File | `/api/admin/common/download/templates` | High
76 | File | `/api/admin/plugins/install/actions/download` | High
77 | File | `/api/admin/sys-user/reset/password/` | High
78 | File | `/api/backend/ext/import-data/import-channel` | High
79 | File | `/api/deploy/upload` | High
80 | File | `/api/endpoint` | High
81 | File | `/api/file/download` | High
82 | File | `/api/file/upload` | High
83 | File | `/api/health/detailed` | High
84 | File | `/api/job/add/` | High
85 | File | `/api/login/auth` | High
86 | File | `/api/monitor-api/alarm/previewData` | High
87 | File | `/api/System.php` | High
88 | File | `/api/system/dashboard/getCount` | High
89 | File | `/api/v1/editor/` | High
90 | File | `/api/v1/mail/send` | High
91 | File | `/api/v1/serve/awel/flow/import` | High
92 | File | `/api/wizard/getBasicInfo` | High
93 | File | `/api/wizard/getCapability` | High
94 | File | `/api/wizard/getCapabilityWeb` | High
95 | File | `/api/wizard/getDualbandSync` | High
96 | File | `/api/wizard/getWifiNeighbour` | High
97 | File | `/api/wizard/networkSetup` | High
98 | File | `/api/wizard/setsyncpppoecfg` | High
99 | File | `/app/ConfirmSmsCode` | High
100 | File | `/app/controller/share.class.php` | High
101 | File | `/application/websocket/controller/Setting.php` | High
102 | File | `/Archive/ErecordManage/uploadFile.html` | High
103 | File | `/assoc_table.php` | High
104 | File | `/att_single_view.php` | High
105 | File | `/auth/list_projects` | High
106 | File | `/backend/app/api/v1/module_common/file/controller.py` | High
107 | File | `/bank/transfer.php` | High
108 | File | `/bin/httpd` | Medium
109 | File | `/bin/netis.cgi` | High
110 | File | `/birthing.php` | High
111 | File | `/boaform/formPing` | High
112 | File | `/boaform/formSamba` | High
113 | File | `/boaform/formWlanSetup` | High
114 | File | `/boafrm/formDateReboot` | High
115 | File | `/boafrm/formDdns` | High
116 | File | `/boafrm/formDMZ` | High
117 | File | `/boafrm/formIpQoS` | High
118 | File | `/boafrm/formMultiAP` | High
119 | File | `/boafrm/formNtp` | High
120 | File | `/boafrm/formOpMode` | High
121 | File | `/boafrm/formVpnConfigSetup` | High
122 | File | `/boafrm/formWlAc` | High
123 | File | `/boafrm/formWlanSetup` | High
124 | File | `/boafrm/formWsc` | High
125 | File | `/booknow.php` | Medium
126 | File | `/book_car.php` | High
127 | File | `/borrowedequip.php` | High
128 | File | `/borrowed_equip_report.php` | High
129 | File | `/borrowed_tool.php` | High
130 | File | `/BranchManagement/ServiceAndSalesReport.php` | High
131 | File | `/bwdates-reports-details.php` | High
132 | File | `/c6/Jhsoft.Web.message/ToolBar/DelTemp.aspx` | High
133 | File | `/C6/Jhsoft.Web.officesupply/OfficeSupplyTypeRight.aspx` | High
134 | File | `/category.php` | High
135 | ... | ... | ...

There are 1196 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/talos-ir-ransomware-engagements-and-the-significance-of-timeliness-in-incident-response/
* https://cyble.com/blog/new-medusa-botnet-emerging-via-mirai-botnet-targeting-linux-users/
* https://isc.sans.edu/forums/diary/Recent+example+of+MedusaHTTP+malware/25234/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=5.42.78.61
* https://tracker.viriback.com/index.php?q=5.61.49.177
* https://tracker.viriback.com/index.php?q=45.15.157.16
* https://tracker.viriback.com/index.php?q=64.52.80.13
* https://tracker.viriback.com/index.php?q=77.105.146.254
* https://tracker.viriback.com/index.php?q=77.105.147.1
* https://tracker.viriback.com/index.php?q=77.105.147.136
* https://tracker.viriback.com/index.php?q=79.137.199.199
* https://tracker.viriback.com/index.php?q=79.137.202.24
* https://tracker.viriback.com/index.php?q=79.137.207.226
* https://tracker.viriback.com/index.php?q=85.192.63.65
* https://tracker.viriback.com/index.php?q=89.185.85.34
* https://tracker.viriback.com/index.php?q=89.185.85.132
* https://tracker.viriback.com/index.php?q=89.208.103.72
* https://tracker.viriback.com/index.php?q=89.208.107.158
* https://tracker.viriback.com/index.php?q=95.181.173.8
* https://tracker.viriback.com/index.php?q=95.181.173.233
* https://tracker.viriback.com/index.php?q=95.181.173.235
* https://tracker.viriback.com/index.php?q=146.70.161.13
* https://tracker.viriback.com/index.php?q=162.33.179.114
* https://tracker.viriback.com/index.php?q=185.46.46.133
* https://tracker.viriback.com/index.php?q=185.106.94.31
* https://tracker.viriback.com/index.php?q=185.112.83.36
* https://tracker.viriback.com/index.php?q=193.233.133.81
* https://tracker.viriback.com/index.php?q=193.233.133.97
* https://tracker.viriback.com/index.php?q=193.233.133.153
* https://tracker.viriback.com/index.php?q=193.233.133.198
* https://tracker.viriback.com/index.php?q=193.233.133.243
* https://tracker.viriback.com/index.php?q=212.113.116.56
* https://twitter.com/Jane_0sint/status/1670048531665518592
* https://www.bitdefender.com/blog/businessinsights/medusa-ransomware-a-growing-threat-with-a-bold-online-presence/
* https://www.bleepingcomputer.com/news/security/medusalocker-ransomware-wants-its-share-of-your-money/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a
* https://www.darktrace.com/blog/under-medusas-gaze-how-darktrace-uncovers-rmm-abuse-in-ransomware-campaigns
* https://www.security.com/threat-intelligence/lazarus-medusa-ransomware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
