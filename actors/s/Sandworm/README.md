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
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandworm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/a/sys/user/save` | High
3 | File | `/Account/EditProfile` | High
4 | File | `/addcatexec.php` | High
5 | File | `/addstock.php` | High
6 | File | `/add_employee.php` | High
7 | File | `/add_patient.php` | High
8 | File | `/admin` | Low
9 | File | `/admin-cp/plugin/editor` | High
10 | File | `/admin-cp/setting/system/general` | High
11 | File | `/admin-page.php` | High
12 | File | `/admin/?page=user/manage` | High
13 | File | `/admin/about-us.php` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/about_edit.php?action=modify` | High
16 | File | `/admin/action/new-feed.php` | High
17 | File | `/admin/add-art-product.php` | High
18 | File | `/admin/add-services.php` | High
19 | File | `/admin/add-subadmin.php` | High
20 | File | `/admin/addroom.php` | High
21 | File | `/admin/add_ikev2.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/AdminLogin.php` | High
24 | File | `/admin/admin_invt2.php` | High
25 | File | `/admin/ajax.php?action=delete_application` | High
26 | File | `/admin/ajax.php?action=login` | High
27 | File | `/admin/allemployees.php` | High
28 | File | `/admin/approve.php` | High
29 | File | `/admin/article/add/do` | High
30 | File | `/admin/article/article-edit-run.php` | High
31 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
32 | File | `/admin/ballot_down.php` | High
33 | File | `/admin/ballot_up.php` | High
34 | File | `/admin/bwdates-passreports-details.php` | High
35 | File | `/admin/bwdates-reports-details.php` | High
36 | File | `/admin/candidates_row.php` | High
37 | File | `/admin/categories/view_category.php` | High
38 | File | `/admin/category/cate-edit-run.php` | High
39 | File | `/admin/changeimage.php` | High
40 | File | `/admin/changepassword.php` | High
41 | File | `/admin/chatroom.php` | High
42 | File | `/admin/class.php?dowhat=modifyclass` | High
43 | File | `/admin/contactus.php` | High
44 | File | `/admin/delete_file.php` | High
45 | File | `/admin/department.php` | High
46 | File | `/admin/doctor-specilization.php` | High
47 | File | `/admin/edit-admin.php` | High
48 | File | `/admin/edit-course.php` | High
49 | File | `/admin/edit-directory.php` | High
50 | File | `/admin/edit-guard-detail.php` | High
51 | File | `/admin/edit-pass-detail.php` | High
52 | File | `/admin/edit-state.php` | High
53 | File | `/admin/edit-subadmin.php` | High
54 | File | `/admin/editempexp.php` | High
55 | File | `/admin/edit_action.php` | High
56 | File | `/admin/edit_manufacturer.php` | High
57 | File | `/admin/edit_subject.php` | High
58 | File | `/admin/forgot-password.php` | High
59 | File | `/admin/index.php` | High
60 | File | `/Admin/InsertCity.php` | High
61 | File | `/admin/leancloud.php` | High
62 | File | `/admin/login.php` | High
63 | File | `/Admin/login.php` | High
64 | File | `/admin/maintenance/brand.php` | High
65 | File | `/admin/manage-directory.php` | High
66 | File | `/admin/manage-students.php` | High
67 | File | `/admin/manage-subadmins.php` | High
68 | File | `/admin/manage-teams.php` | High
69 | File | `/admin/manage_model.php` | High
70 | File | `/admin/menu.php` | High
71 | File | `/admin/modal_add_product.php` | High
72 | File | `/admin/msg.php` | High
73 | File | `/admin/offenses/view_details.php` | High
74 | File | `/admin/pass-details.php` | High
75 | File | `/admin/plan/examExportPDF` | High
76 | File | `/admin/positions_delete.php` | High
77 | File | `/admin/process_login.php` | High
78 | File | `/admin/registered-users.php` | High
79 | File | `/admin/reminders/manage_reminder.php` | High
80 | File | `/admin/search-directory.php` | High
81 | File | `/admin/search.php` | High
82 | File | `/admin/services/manage.php` | High
83 | File | `/admin/services/view_service.php` | High
84 | File | `/admin/settings/` | High
85 | File | `/admin/sign/out` | High
86 | File | `/admin/student.php` | High
87 | File | `/admin/sys/log/list` | High
88 | File | `/admin/sys/role/list` | High
89 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
90 | File | `/admin/template/edit` | High
91 | File | `/admin/updatecomplaint.php` | High
92 | File | `/admin/update_user.php` | High
93 | File | `/admin/user/index.php` | High
94 | File | `/admin/user/manage_user.php` | High
95 | File | `/admin/users.php` | High
96 | File | `/admin/users_photo.php` | High
97 | File | `/admin/user_save.php` | High
98 | File | `/admin/vacancy/index.php` | High
99 | File | `/admin/view-incomingvehicle-detail.php` | High
100 | File | `/admin/view-pass-detail.php` | High
101 | File | `/admin/viewpackage.php` | High
102 | File | `/admin/view_all_posts.php` | High
103 | File | `/admin/view_reserved.php` | High
104 | File | `/admin/visitor-details.php` | High
105 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
106 | File | `/ajax.php?action=calculate_payroll` | High
107 | File | `/ajax.php?action=end_membership` | High
108 | File | `/ajax.php?action=login` | High
109 | File | `/ajax.php?action=save_package` | High
110 | File | `/ajax.php?action=save_payroll` | High
111 | File | `/ajax.php?action=save_quiz` | High
112 | File | `/ajax.php?action=save_schedule` | High
113 | File | `/ample/app/ajax/member_data.php` | High
114 | File | `/api/article/del` | High
115 | File | `/api/authentication/login` | High
116 | File | `/api/dept/build` | High
117 | File | `/api/front/search/books` | High
118 | File | `/api/process.php` | High
119 | File | `/api/public/signup` | High
120 | File | `/api/sys/set_passwd` | High
121 | File | `/api/v1/bait/set` | High
122 | File | `/app/admin/controller/file/File.php` | High
123 | File | `/app/admin/controller/Upload.php` | High
124 | File | `/app/middleware/TokenVerify.php` | High
125 | File | `/app/sys1.php` | High
126 | ... | ... | ...

There are 1116 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
