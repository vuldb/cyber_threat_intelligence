# Cuba Ransomware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cuba Ransomware](https://vuldb.com/?actor.cuba_ransomware). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cuba_ransomware](https://vuldb.com/?actor.cuba_ransomware)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cuba Ransomware:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cuba Ransomware.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.13.102.1](https://vuldb.com/?ip.10.13.102.1) | - | - | High
2 | [10.13.102.58](https://vuldb.com/?ip.10.13.102.58) | - | - | High
3 | [10.14.100.20](https://vuldb.com/?ip.10.14.100.20) | - | - | High
4 | [10.133.78.41](https://vuldb.com/?ip.10.133.78.41) | - | - | High
5 | [23.160.193.145](https://vuldb.com/?ip.23.160.193.145) | server1.wlook.com | - | High
6 | [23.227.198.246](https://vuldb.com/?ip.23.227.198.246) | 23-227-198-246.static.hvvc.us | - | High
7 | [31.44.184.84](https://vuldb.com/?ip.31.44.184.84) | - | - | High
8 | [31.44.184.100](https://vuldb.com/?ip.31.44.184.100) | - | - | High
9 | [31.184.192.44](https://vuldb.com/?ip.31.184.192.44) | - | - | High
10 | [31.184.194.42](https://vuldb.com/?ip.31.184.194.42) | - | - | High
11 | [31.184.198.74](https://vuldb.com/?ip.31.184.198.74) | - | - | High
12 | [31.184.198.80](https://vuldb.com/?ip.31.184.198.80) | directingme.com | - | High
13 | [31.184.198.82](https://vuldb.com/?ip.31.184.198.82) | harms.directingme.com | - | High
14 | [31.184.198.83](https://vuldb.com/?ip.31.184.198.83) | - | - | High
15 | [31.184.198.84](https://vuldb.com/?ip.31.184.198.84) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cuba Ransomware_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-268, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cuba Ransomware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutus.php` | Medium
2 | File | `/academic-calendar` | High
3 | File | `/add-pig.php` | Medium
4 | File | `/add-subject.php` | High
5 | File | `/add.php` | Medium
6 | File | `/addpayment.php` | High
7 | File | `/addQuestion.php` | High
8 | File | `/admin#themes` | High
9 | File | `/admin-cp/menus` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/admin/add-art-type.php` | High
12 | File | `/admin/add-customer-services.php` | High
13 | File | `/admin/add-team.php` | High
14 | File | `/admin/add_cars.php` | High
15 | File | `/admin/add_vehicles.php` | High
16 | File | `/admin/admin-profile.php` | High
17 | File | `/admin/admin_user.php` | High
18 | File | `/admin/ajax.php?action=save_settings` | High
19 | File | `/admin/ajax_product.php` | High
20 | File | `/admin/all-appointment.php` | High
21 | File | `/admin/app/asset_crud.php` | High
22 | File | `/admin/applicants/index.php` | High
23 | File | `/admin/article/list` | High
24 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
25 | File | `/admin/assign_save.php` | High
26 | File | `/admin/booking_report.php` | High
27 | File | `/admin/cashadvance_row.php` | High
28 | File | `/admin/categories/save` | High
29 | File | `/admin/category/controller.php` | High
30 | File | `/admin/checklogin.php` | High
31 | File | `/admin/check_availability.php` | High
32 | File | `/admin/clients/manage.php` | High
33 | File | `/admin/company/index.php` | High
34 | File | `/admin/contactus.php` | High
35 | File | `/admin/controller/student_controller.php` | High
36 | File | `/admin/course.php` | High
37 | File | `/admin/create_product.php` | High
38 | File | `/admin/curriculum/view_curriculum.php` | High
39 | File | `/admin/departments/view_department.php` | High
40 | File | `/admin/disapprove_user.php` | High
41 | File | `/admin/doctor-specilization.php` | High
42 | File | `/admin/edit-accepted-appointment.php` | High
43 | File | `/admin/edit-admin.php` | High
44 | File | `/admin/edit-category.php` | High
45 | File | `/admin/edit-customer-detailed.php` | High
46 | File | `/admin/edit-doctor-specialization.php` | High
47 | File | `/admin/edit-services.php` | High
48 | File | `/admin/edit_member.php` | High
49 | File | `/admin/edit_role.php` | High
50 | File | `/admin/edit_user.php` | High
51 | File | `/admin/email_setup.php` | High
52 | File | `/admin/employee/index.php` | High
53 | File | `/admin/expense_report.php` | High
54 | File | `/admin/index.php` | High
55 | File | `/admin/insert-product.php` | High
56 | File | `/Admin/login.php` | High
57 | File | `/admin/login.php` | High
58 | File | `/admin/manage-incomingvehicle.php` | High
59 | File | `/Admin/match.php` | High
60 | File | `/admin/modules/instructor/index.php` | High
61 | File | `/Admin/News.php` | High
62 | File | `/admin/operations/booking.php` | High
63 | File | `/admin/operations/expense_category.php` | High
64 | File | `/admin/positions.php` | High
65 | File | `/admin/positions_add.php` | High
66 | File | `/admin/profit_report.php` | High
67 | File | `/admin/room.php` | High
68 | File | `/admin/searchview.php` | High
69 | File | `/admin/services/manage_service.php` | High
70 | File | `/admin/service_requests/manage_inventory.php` | High
71 | File | `/admin/settings/users/edit/` | High
72 | File | `/admin/student_action.php` | High
73 | File | `/admin/suppliercontroller.php` | High
74 | File | `/admin/sys_sql_query.php` | High
75 | File | `/admin/update_s1.php` | High
76 | File | `/admin/user/manage_user.php` | High
77 | File | `/admin/view-appointment.php?viewid=11` | High
78 | File | `/adminac.php` | Medium
79 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
80 | File | `/admin_class.php?action=login` | High
81 | File | `/admin_route/inc_service_credits.php` | High
82 | File | `/ajax.php` | Medium
83 | File | `/alunos/search_autocomplete` | High
84 | File | `/api/dept/build` | High
85 | File | `/api/files/recipepictures/` | High
86 | File | `/api/settings` | High
87 | File | `/api/v1/convert/html/pdf` | High
88 | File | `/api/v1/getbaseconfig` | High
89 | File | `/api/wizard/getLanguage` | High
90 | File | `/api/wizard/setLanguage` | High
91 | File | `/app-api/infra/file/upload` | High
92 | File | `/app/admin/controller/Images.php` | High
93 | File | `/app/Http/Controllers/ImageController.php` | High
94 | File | `/application/pay/controller/Index.php` | High
95 | File | `/appy.cgi` | Medium
96 | File | `/APR/login.php` | High
97 | File | `/arp_sys.asp` | Medium
98 | File | `/attribute/queryAll` | High
99 | File | `/auth/info` | Medium
100 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
101 | File | `/bin/boa` | Medium
102 | File | `/boafrm/formDMZ` | High
103 | File | `/boafrm/formIPv6Addr` | High
104 | File | `/boafrm/formSysCmd` | High
105 | ... | ... | ...

There are 926 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/cuba-ransomware/110533/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-335a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
