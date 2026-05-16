# WannaCry - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [WannaCry](https://vuldb.com/actor/wannacry). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/wannacry](https://vuldb.com/actor/wannacry)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WannaCry:

* [US](https://vuldb.com/country/us)
* [SE](https://vuldb.com/country/se)
* [RU](https://vuldb.com/country/ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WannaCry.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.3.69.209](https://vuldb.com/ip/2.3.69.209) | lfbn-cle-1-223-209.w2-3.abo.wanadoo.fr | - | High
2 | [5.35.251.247](https://vuldb.com/ip/5.35.251.247) | rs209896.rs.hosteurope.de | - | High
3 | [23.254.167.231](https://vuldb.com/ip/23.254.167.231) | hwsrv-985873.hostwindsdns.com | - | High
4 | [38.229.72.16](https://vuldb.com/ip/38.229.72.16) | - | - | High
5 | [46.101.166.19](https://vuldb.com/ip/46.101.166.19) | - | - | High
6 | [50.7.161.218](https://vuldb.com/ip/50.7.161.218) | - | - | High
7 | [62.210.124.124](https://vuldb.com/ip/62.210.124.124) | leavenged.best | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WannaCry_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WannaCry. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/.env` | Low
3 | File | `/?page=reports` | High
4 | File | `/aboutadd.php` | High
5 | File | `/academic-calendar` | High
6 | File | `/ad-list` | Medium
7 | File | `/add-book.php` | High
8 | File | `/add_judge.php` | High
9 | File | `/add_student/` | High
10 | File | `/add_student_grade.php` | High
11 | File | `/adicionar-cliente.php` | High
12 | File | `/admin-profile.php` | High
13 | File | `/admin.php/addon/index` | High
14 | File | `/admin/` | Low
15 | File | `/admin/?page=inventory/view_inventory&id=2` | High
16 | File | `/admin/?page=products/view_product` | High
17 | File | `/admin/action/add_con.php` | High
18 | File | `/admin/action/delete-vaccine.php` | High
19 | File | `/admin/addgiving.php` | High
20 | File | `/admin/addTithes.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/admin/adminprofile.php` | High
23 | File | `/admin/admin_user.php` | High
24 | File | `/admin/all_users.php` | High
25 | File | `/admin/announcement/index.php?view=add` | High
26 | File | `/Admin/assets/backend/seller/add_seller.php` | High
27 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
28 | File | `/admin/attendance_row.php` | High
29 | File | `/admin/between-date-complaintreport.php` | High
30 | File | `/admin/blood/update/B+.php` | High
31 | File | `/admin/candidates_delete.php` | High
32 | File | `/admin/categories/manage_category.php` | High
33 | File | `/admin/categories/view_category.php` | High
34 | File | `/admin/category.php` | High
35 | File | `/admin/config_Anticrack.php` | High
36 | File | `/admin/courses/manage_course.php` | High
37 | File | `/admin/course_action.php` | High
38 | File | `/admin/delete_file.php` | High
39 | File | `/admin/department/add` | High
40 | File | `/admin/departments/manage_department.php` | High
41 | File | `/admin/display-teacher.php` | High
42 | File | `/admin/doctor-specilization.php` | High
43 | File | `/admin/edit-admin.php` | High
44 | File | `/admin/edit-ambulance.php` | High
45 | File | `/admin/edit-brand.php` | High
46 | File | `/admin/edit-course.php` | High
47 | File | `/admin/edit-guard-detail.php` | High
48 | File | `/admin/edit-nurse.php` | High
49 | File | `/admin/edit-services.php` | High
50 | File | `/admin/edit_subject.php` | High
51 | File | `/admin/emp-profile-avatar.php` | High
52 | File | `/admin/employee_row.php` | High
53 | File | `/admin/index.php` | High
54 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
55 | File | `/admin/maintenance/brand.php` | High
56 | File | `/admin/maintenance/view_designation.php` | High
57 | File | `/admin/manage-normal-ticket.php` | High
58 | File | `/admin/mechanics/manage_mechanic.php` | High
59 | File | `/admin/member_save.php` | High
60 | File | `/admin/network/diag_iperf` | High
61 | File | `/admin/new-requests.php` | High
62 | File | `/admin/normal-bwdates-reports-details.php` | High
63 | File | `/admin/Operations/Role.php` | High
64 | File | `/admin/plugin.php` | High
65 | File | `/admin/print.php` | High
66 | File | `/admin/redirect.php` | High
67 | File | `/admin/registration.php` | High
68 | File | `/admin/reportupload.aspx` | High
69 | File | `/admin/search-report-details.php` | High
70 | File | `/admin/service.php` | High
71 | File | `/admin/setup.cgi` | High
72 | File | `/admin/students/manage_academic.php` | High
73 | File | `/admin/subject/controller.php` | High
74 | File | `/admin/time-table.php` | High
75 | File | `/admin/transactions/track_shipment.php` | High
76 | File | `/admin/upload.php` | High
77 | File | `/admin/upload/upimage.html` | High
78 | File | `/admin/user-search.php` | High
79 | File | `/admin/useragentdelete.php` | High
80 | File | `/admin/v1/link/edit` | High
81 | File | `/admin_pic.php` | High
82 | File | `/admin_single_student_update.php` | High
83 | File | `/aim/storage/query.py` | High
84 | File | `/ajax.php?action=calculate_payroll` | High
85 | File | `/ajax.php?action=save_category` | High
86 | File | `/ajax.php?action=save_plan` | High
87 | File | `/ajax.php?action=update_account` | High
88 | File | `/api/admin/common/download/templates` | High
89 | File | `/api/controllers/merchant/shop/PosterController.php` | High
90 | File | `/api/log/killJob` | High
91 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
92 | File | `/api/system/user/getAvatar` | High
93 | File | `/Api/TinyMce/UploadAjax.ashx` | High
94 | File | `/api/user` | Medium
95 | File | `/api/v1/serve/awel/flow/import` | High
96 | File | `/api/wizard/getNetworkConf` | High
97 | File | `/api/wizard/getWifiNeighbour` | High
98 | File | `/api/wizard/networkSetup` | High
99 | File | `/app/controller/Setup.php` | High
100 | File | `/app/controller/Upload.php` | High
101 | File | `/App/Tpl/Admin/Default/Log/index.html` | High
102 | File | `/Archive/ErecordManage/uploadFile.html` | High
103 | File | `/auth/user/all.api` | High
104 | File | `/backend/app/api/v1/module_common/file/controller.py` | High
105 | File | `/bbms.php` | Medium
106 | File | `/blog` | Low
107 | File | `/blog/bContent/save` | High
108 | File | `/boaform/formLoopBack` | High
109 | File | `/boaform/formSamba` | High
110 | File | `/boafrm/formDateReboot` | High
111 | File | `/boafrm/formIpQoS` | High
112 | File | `/boafrm/formNtp` | High
113 | File | `/boafrm/formPortFw` | High
114 | File | `/boafrm/formUSSDSetup` | High
115 | File | `/boafrm/formWsc` | High
116 | File | `/book_list.php` | High
117 | File | `/c6/Jhsoft.Web.message/ToolBar/DelTemp.aspx` | High
118 | File | `/category.php` | High
119 | File | `/categoryvalue.php` | High
120 | ... | ... | ...

There are 1069 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/212/wannacry-ransomware-iocs/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
