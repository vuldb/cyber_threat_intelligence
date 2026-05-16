# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/a/sys/user/save` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/acceptoffres.php` | High
4 | File | `/add-pass.php` | High
5 | File | `/add-product.php` | High
6 | File | `/addcategory.php` | High
7 | File | `/addcompany.php` | High
8 | File | `/addelidetails.php` | High
9 | File | `/addfriend.php` | High
10 | File | `/adding-exec.php` | High
11 | File | `/addproduct.php` | High
12 | File | `/add_contestant.php` | High
13 | File | `/add_judge.php` | High
14 | File | `/add_librarian.php` | High
15 | File | `/Add_reciver.php` | High
16 | File | `/adicionar-cliente.php` | High
17 | File | `/admin` | Low
18 | File | `/admin-page.php` | High
19 | File | `/admin-profile.php` | High
20 | File | `/admin.php` | Medium
21 | File | `/admin/` | Low
22 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
23 | File | `/admin/?page=return/view_return` | High
24 | File | `/admin/?page=user` | High
25 | File | `/admin/actions/delete-equipment.php` | High
26 | File | `/admin/actions/delete-member.php` | High
27 | File | `/admin/add-category.php` | High
28 | File | `/admin/add_account.php` | High
29 | File | `/admin/add_candidate_modal.php.` | High
30 | File | `/admin/admin.php` | High
31 | File | `/admin/admin_product.ph` | High
32 | File | `/admin/ajax.php?action=login` | High
33 | File | `/admin/ajax.php?action=save_settings` | High
34 | File | `/admin/ajax_product.php` | High
35 | File | `/admin/api/workspace/default/tool/debug` | High
36 | File | `/admin/application-bwdates-reports-details.php` | High
37 | File | `/admin/appointment.php` | High
38 | File | `/admin/approve.php` | High
39 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
40 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
41 | File | `/admin/bwdates-reports-details.php` | High
42 | File | `/admin/categories/view_category.php` | High
43 | File | `/admin/category.php` | High
44 | File | `/admin/class.php?dowhat=modifyclass` | High
45 | File | `/admin/clientview.php` | High
46 | File | `/admin/content/book` | High
47 | File | `/admin/controller/faculty_controller.php` | High
48 | File | `/admin/deleteitem.php` | High
49 | File | `/admin/department/add` | High
50 | File | `/admin/edit-doc.php` | High
51 | File | `/admin/edit-equipmentform.php` | High
52 | File | `/admin/edit-user.php` | High
53 | File | `/admin/edit_product.php` | High
54 | File | `/admin/edit_title.php?id=1` | High
55 | File | `/admin/edit_user.php` | High
56 | File | `/admin/employee/index.php?view=edit` | High
57 | File | `/admin/employee_edit.php` | High
58 | File | `/admin/employee_row.php` | High
59 | File | `/admin/fields/manage_field.php` | High
60 | File | `/admin/forgot-password.php` | High
61 | File | `/admin/freelist_main.php` | High
62 | File | `/admin/index.php` | High
63 | File | `/admin/index.php?add_product` | High
64 | File | `/admin/inquiries/view_inquiry.php` | High
65 | File | `/admin/login.php` | High
66 | File | `/admin/manage-services.php` | High
67 | File | `/admin/manage-users.php` | High
68 | File | `/admin/manage_theater.php` | High
69 | File | `/admin/manage_user.php` | High
70 | File | `/admin/menu.php` | High
71 | File | `/admin/normal-bwdates-reports-details.php` | High
72 | File | `/admin/offenses/view_details.php` | High
73 | File | `/admin/positions_edit.php` | High
74 | File | `/admin/readenq.php` | High
75 | File | `/admin/regester.php` | High
76 | File | `/admin/report/index.php` | High
77 | File | `/admin/roomdel.php` | High
78 | File | `/admin/save.php` | High
79 | File | `/admin/search-appointment.php` | High
80 | File | `/admin/settings/` | High
81 | File | `/admin/student-history.php` | High
82 | File | `/admin/students/view_student.php` | High
83 | File | `/admin/transaction/deposit` | High
84 | File | `/admin/update-profile.php` | High
85 | File | `/admin/update-progress.php` | High
86 | File | `/admin/update_user.php` | High
87 | File | `/admin/user-payment.php` | High
88 | File | `/admin/user-profile.php` | High
89 | File | `/admin/user.php` | High
90 | File | `/admin/user/index.php` | High
91 | File | `/admin/users.php` | High
92 | File | `/administrator/remove.php` | High
93 | File | `/admin_class.php` | High
94 | File | `/Admin_dashboard/edit_profile` | High
95 | File | `/admin_members.php?ac=editsave` | High
96 | File | `/adv_arpspoofing.php` | High
97 | File | `/ajax.php?action=delete_allowances` | High
98 | File | `/ajax.php?action=delete_payroll` | High
99 | File | `/ajax.php?action=login` | High
100 | File | `/ajax.php?action=read_msg` | High
101 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
102 | File | `/ajax/action.php` | High
103 | File | `/analysisProject/pagingQueryData` | High
104 | File | `/api/config/list` | High
105 | File | `/api/file/upload` | High
106 | File | `/Api/FileUploadApi.ashx` | High
107 | File | `/api/process.php` | High
108 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
109 | File | `/appointment.php` | High
110 | File | `/assets/changeSllyabus.php` | High
111 | File | `/assets/createNotice.php` | High
112 | File | `/assets/uploadNotes.php` | High
113 | ... | ... | ...

There are 1000 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
