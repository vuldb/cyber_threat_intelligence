# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.254.54](https://vuldb.com/?ip.2.56.254.54) | - | - | High
2 | [5.188.159.44](https://vuldb.com/?ip.5.188.159.44) | - | - | High
3 | [14.241.58.222](https://vuldb.com/?ip.14.241.58.222) | static.vnpt.vn | - | High
4 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
5 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
6 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
7 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
8 | [23.133.4.2](https://vuldb.com/?ip.23.133.4.2) | indoctum.weadesign.com | - | High
9 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
10 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
11 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
12 | [37.113.171.12](https://vuldb.com/?ip.37.113.171.12) | dynamicip-37-113-171-12.pppoe.chel.ertelecom.ru | - | High
13 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
14 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
15 | [37.139.129.243](https://vuldb.com/?ip.37.139.129.243) | - | - | High
16 | [42.157.128.69](https://vuldb.com/?ip.42.157.128.69) | - | - | High
17 | [43.248.98.121](https://vuldb.com/?ip.43.248.98.121) | - | - | High
18 | [43.248.129.34](https://vuldb.com/?ip.43.248.129.34) | - | - | High
19 | [43.248.129.49](https://vuldb.com/?ip.43.248.129.49) | - | - | High
20 | [43.248.130.253](https://vuldb.com/?ip.43.248.130.253) | - | - | High
21 | [43.249.193.230](https://vuldb.com/?ip.43.249.193.230) | - | - | High
22 | [45.14.165.18](https://vuldb.com/?ip.45.14.165.18) | - | - | High
23 | ... | ... | ... | ...

There are 86 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/account/forgotpassword` | High
3 | File | `/action.php` | Medium
4 | File | `/adduser-exec.php` | High
5 | File | `/add_librarian.php` | High
6 | File | `/add_overtime.php` | High
7 | File | `/add_student_grade.php` | High
8 | File | `/adm/ajax.php` | High
9 | File | `/admin-cp/imports` | High
10 | File | `/admin.php?id=inbox` | High
11 | File | `/admin/?page=maintenance/brand` | High
12 | File | `/admin/aboutPost.php` | High
13 | File | `/admin/aboutus.php` | High
14 | File | `/Admin/add-admin.php` | High
15 | File | `/admin/add-animals.php` | High
16 | File | `/admin/add-art-type.php` | High
17 | File | `/admin/add-customer-services.php` | High
18 | File | `/admin/add-student.php` | High
19 | File | `/admin/adddoctorclinic.php` | High
20 | File | `/admin/addroom.php` | High
21 | File | `/admin/add_room.php` | High
22 | File | `/admin/admin/save` | High
23 | File | `/admin/admin_running.php` | High
24 | File | `/admin/ajax.php?action=delete_user` | High
25 | File | `/admin/ajax.php?action=delete_vacancy` | High
26 | File | `/admin/all-appointment.php` | High
27 | File | `/admin/announcement/index.php?view=add` | High
28 | File | `/admin/api/theme-edit/` | High
29 | File | `/admin/api/workspace/default/tool/debug` | High
30 | File | `/admin/application-bwdates-reports-details.php` | High
31 | File | `/admin/archives_add.php` | High
32 | File | `/Admin/assets/backend/seller/add_seller.php` | High
33 | File | `/admin/assigned-requests.php` | High
34 | File | `/admin/backup/backups.php` | High
35 | File | `/admin/ballot_up.php` | High
36 | File | `/admin/blood/update/o-.php` | High
37 | File | `/admin/booking-bwdates-reports-details.php` | High
38 | File | `/admin/bookings/view_details.php` | High
39 | File | `/admin/bwdates-reports-details.php` | High
40 | File | `/Admin/Category.php` | High
41 | File | `/admin/category/controller.php` | High
42 | File | `/admin/changeimage.php` | High
43 | File | `/admin/checklogin.php` | High
44 | File | `/admin/cms/material/add` | High
45 | File | `/admin/company/index.php` | High
46 | File | `/admin/configurations/userInfo` | High
47 | File | `/Admin/consulting_detail.php` | High
48 | File | `/admin/content` | High
49 | File | `/admin/customer-list.php` | High
50 | File | `/admin/edit-category.php` | High
51 | File | `/admin/edit-class.php?cid=1` | High
52 | File | `/admin/edit-customer-detailed.php` | High
53 | File | `/admin/edit-user.php` | High
54 | File | `/admin/edit.php` | High
55 | File | `/admin/editsite.php` | High
56 | File | `/admin/edit_category.php` | High
57 | File | `/admin/file/delete.do` | High
58 | File | `/admin/file/rename.do` | High
59 | File | `/admin/finished.php` | High
60 | File | `/admin/forget-password.php` | High
61 | File | `/admin/getallarticleinfo` | High
62 | File | `/admin/index.php` | High
63 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
64 | File | `/admin/inv-print.php` | High
65 | File | `/admin/inventory/manage_stock.php` | High
66 | File | `/admin/invoices.php` | High
67 | File | `/admin/login.php` | High
68 | File | `/admin/manage-scdetails.php` | High
69 | File | `/admin/manage-users.php` | High
70 | File | `/admin/member_save.php` | High
71 | File | `/admin/network/diag_traceroute` | High
72 | File | `/admin/new-content` | High
73 | File | `/admin/newsletter.php` | High
74 | File | `/admin/offenses/view_details.php` | High
75 | File | `/admin/options-theme.php` | High
76 | File | `/admin/php/crud.php` | High
77 | File | `/admin/positions_add.php` | High
78 | File | `/admin/print_inv.php` | High
79 | File | `/admin/profile.php` | High
80 | File | `/admin/roombook.php` | High
81 | File | `/admin/roomdel.php` | High
82 | File | `/admin/sales-reports-detail.php` | High
83 | File | `/admin/settings.php` | High
84 | File | `/admin/settings/users/edit/` | High
85 | File | `/admin/show.php` | High
86 | File | `/admin/sms_setting.php` | High
87 | File | `/admin/spec_add.php` | High
88 | File | `/admin/template/edit` | High
89 | File | `/admin/transactions/track_shipment.php` | High
90 | File | `/admin/update-image.php` | High
91 | File | `/admin/update-rooms.php` | High
92 | File | `/admin/update-users.php` | High
93 | File | `/admin/update_user.php` | High
94 | File | `/admin/user/controller.php?action=photos` | High
95 | File | `/admin/user/manage_user.php` | High
96 | File | `/admin/userdelete.php` | High
97 | File | `/admin/users-applications.php` | High
98 | File | `/admin/view-appointment.php` | High
99 | File | `/admin/view-progress-report.php` | High
100 | File | `/admin/voters_add.php` | High
101 | File | `/adminac.php` | Medium
102 | File | `/adminapi/product/product` | High
103 | File | `/adminPage/conf/check` | High
104 | File | `/admin_class.php` | High
105 | File | `/admin_topic.php?action=delall` | High
106 | File | `/adpweb/a/ica/api/service/rfa/testService` | High
107 | File | `/aim/storage/query.py` | High
108 | File | `/ajax.php?action=delete_block` | High
109 | File | `/ajax.php?action=end_membership` | High
110 | File | `/ajax.php?action=login` | High
111 | File | `/ajax.php?action=save_customer` | High
112 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
113 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
114 | File | `/ample/app/action/edit_product.php` | High
115 | File | `/api/admin/question/edit` | High
116 | File | `/api/article/del` | High
117 | File | `/api/dept` | Medium
118 | File | `/api/file/upload` | High
119 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
120 | File | `/api/GylOperator/UpdatePasswordBatch` | High
121 | File | `/api/upload` | Medium
122 | File | `/api/users/updateAvatar` | High
123 | File | `/api/users/updateEmail/` | High
124 | File | `/api/v2/categories` | High
125 | File | `/api/v2/open/rowsInfo` | High
126 | File | `/app-api/v1/orders/` | High
127 | File | `/app/admin/view/web_user.html` | High
128 | ... | ... | ...

There are 1140 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3602383/
* https://urlhaus.abuse.ch/url/3607222/
* https://urlhaus.abuse.ch/url/3607417/
* https://www.threat.rip/file/963128c607f8fed1d3a1b4c7872afed7d34e8a0ddfdac9d1a631d5294aacf5e9/config

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
