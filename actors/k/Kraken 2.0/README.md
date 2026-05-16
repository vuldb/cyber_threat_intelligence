# Kraken 2.0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kraken 2.0](https://vuldb.com/?actor.kraken_2.0). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kraken_2.0](https://vuldb.com/?actor.kraken_2.0)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kraken 2.0:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kraken 2.0.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kraken 2.0_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kraken 2.0. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=route_ispinfo_export_save` | High
2 | File | `/action/upload_file` | High
3 | File | `/add-notes.php` | High
4 | File | `/addcategory.php` | High
5 | File | `/addelivery.php` | High
6 | File | `/add_contestant.php` | High
7 | File | `/add_judge.php` | High
8 | File | `/admin-api/bpm/model/deploy` | High
9 | File | `/admin-profile.php` | High
10 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
11 | File | `/admin.php?p=/Area/index#tab=t2` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=establishment` | High
14 | File | `/admin/?page=inventory/view_inventory&id=2` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/about_edit.php?action=modify` | High
17 | File | `/admin/add-customer.php` | High
18 | File | `/admin/add-services.php` | High
19 | File | `/Admin/add-student.php` | High
20 | File | `/admin/add-subadmin.php` | High
21 | File | `/admin/add_account.php` | High
22 | File | `/admin/add_admin.php` | High
23 | File | `/admin/add_content.php` | High
24 | File | `/admin/add_room.php` | High
25 | File | `/admin/admin-profile.php` | High
26 | File | `/admin/admin.php` | High
27 | File | `/admin/admin_user.php` | High
28 | File | `/admin/ajax.php?action=save_settings` | High
29 | File | `/admin/app/login_crud.php` | High
30 | File | `/admin/apply.php` | High
31 | File | `/admin/archives_add.php` | High
32 | File | `/admin/assets/` | High
33 | File | `/admin/blood/update/o-.php` | High
34 | File | `/admin/category.php` | High
35 | File | `/admin/category_update.php` | High
36 | File | `/admin/chatroom.php` | High
37 | File | `/admin/class.php?dowhat=modifyclass` | High
38 | File | `/admin/clientview.php` | High
39 | File | `/admin/company/index.php` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/content/filemanager/uploads` | High
42 | File | `/admin/delete_s7.php` | High
43 | File | `/admin/delete_user.php` | High
44 | File | `/admin/disapprove_user.php` | High
45 | File | `/admin/edit-boat.php` | High
46 | File | `/admin/edit-category.php` | High
47 | File | `/admin/edit-customer-detailed.php` | High
48 | File | `/admin/edit-post.php` | High
49 | File | `/admin/edit-subcategory.php` | High
50 | File | `/admin/edit_admin_details.php?id=admin` | High
51 | File | `/admin/edit_class.php` | High
52 | File | `/admin/edit_room.php` | High
53 | File | `/admin/equipment-entry.php` | High
54 | File | `/admin/expense_report.php` | High
55 | File | `/admin/fields/manage_field.php` | High
56 | File | `/admin/forgot-password.php` | High
57 | File | `/admin/freelist_main.php` | High
58 | File | `/admin/index.php` | High
59 | File | `/admin/inquiries/view_inquiry.php` | High
60 | File | `/admin/maintenance/view_designation.php` | High
61 | File | `/admin/manage-category.php` | High
62 | File | `/admin/manage-scdetails.php` | High
63 | File | `/admin/manage-services.php` | High
64 | File | `/admin/modules/class/index.php` | High
65 | File | `/admin/newsletter.php` | High
66 | File | `/admin/newsletterdel.php` | High
67 | File | `/admin/options-theme.php` | High
68 | File | `/admin/pages/list` | High
69 | File | `/admin/pass-bwdates-report.php` | High
70 | File | `/admin/photo.php` | High
71 | File | `/admin/php/crud.php` | High
72 | File | `/admin/profile.php` | High
73 | File | `/admin/room.php` | High
74 | File | `/admin/roombook.php` | High
75 | File | `/admin/roomdel.php` | High
76 | File | `/admin/salary_slip.php` | High
77 | File | `/admin/sales-reports-detail.php` | High
78 | File | `/admin/session.php` | High
79 | File | `/admin/slideupdate.php` | High
80 | File | `/admin/store/edit/` | High
81 | File | `/admin/templets_one_edit.php` | High
82 | File | `/admin/transaction/deposit` | High
83 | File | `/admin/update-profile.php` | High
84 | File | `/admin/update_user.php` | High
85 | File | `/admin/upload/authorImg/` | High
86 | File | `/admin/users-applications.php` | High
87 | File | `/admin/view-enquiry.php` | High
88 | File | `/admin/view-member-report.php` | High
89 | File | `/admin/view-progress-report.php` | High
90 | File | `/admin?do=admin:user:editPost` | High
91 | File | `/admin_class.php` | High
92 | File | `/ajax.php` | Medium
93 | File | `/ajax.php?action=login` | High
94 | File | `/ajax.php?action=save_payment` | High
95 | File | `/ajax.php?action=save_student` | High
96 | File | `/ajax.php?action=save_supplier` | High
97 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
98 | File | `/api/backend/core/web-file-upload/upload` | High
99 | File | `/api/backend/v1/user/create` | High
100 | File | `/api/config/list` | High
101 | File | `/api/es/admin/v3/security/user/1` | High
102 | File | `/api/esps` | Medium
103 | File | `/api/file/downloadfile` | High
104 | File | `/api/file/s3/get-presigned-get-url-proxy` | High
105 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
106 | File | `/api/v1/initialization/embedding/test` | High
107 | File | `/api/wechat/app_auth` | High
108 | File | `/api/wizard/getDualbandSync` | High
109 | File | `/app-api/infra/file/upload` | High
110 | File | `/app/admin/controller/Upload.php` | High
111 | File | `/app/platform/controllers/ResetpwdController.php` | High
112 | File | `/application/common.php` | High
113 | File | `/art-enquiry.php` | High
114 | File | `/author/list?limit=10&offset=0&order=desc` | High
115 | File | `/backend/doc/his_doc_update-account.php` | High
116 | ... | ... | ...

There are 1024 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
