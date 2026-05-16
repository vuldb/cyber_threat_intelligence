# WannaCryptor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WannaCryptor](https://vuldb.com/?actor.wannacryptor). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wannacryptor](https://vuldb.com/?actor.wannacryptor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WannaCryptor:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WannaCryptor.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.224.174.212](https://vuldb.com/?ip.14.224.174.212) | static.vnpt.vn | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WannaCryptor_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WannaCryptor. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/99/ImportSQLTable` | High
2 | File | `/?g=route_ispinfo_export_save` | High
3 | File | `/Account/EditProfile` | High
4 | File | `/account/_settings` | High
5 | File | `/add-courier.php` | High
6 | File | `/add-notes.php` | High
7 | File | `/addcategory.php` | High
8 | File | `/addproduct.php` | High
9 | File | `/admin#themes` | High
10 | File | `/admin-api/bpm/model/deploy` | High
11 | File | `/admin-api/mp/material/upload-permanent` | High
12 | File | `/admin.php` | Medium
13 | File | `/admin/` | Low
14 | File | `/admin/?page=back_order/view_bo` | High
15 | File | `/admin/actions/check-attendance.php` | High
16 | File | `/admin/actions/delete-equipment.php` | High
17 | File | `/admin/actions/remove-announcement.php` | High
18 | File | `/admin/add-admin.php` | High
19 | File | `/admin/add-boat.php` | High
20 | File | `/admin/add-directory.php` | High
21 | File | `/admin/add_account.php` | High
22 | File | `/admin/add_postlogin.php` | High
23 | File | `/admin/add_trainers.php` | High
24 | File | `/admin/admin.php` | High
25 | File | `/admin/adminprofile.php` | High
26 | File | `/admin/admin_football.php` | High
27 | File | `/admin/admin_index.php` | High
28 | File | `/admin/admin_login.php` | High
29 | File | `/admin/admin_user.php` | High
30 | File | `/admin/ajax.php` | High
31 | File | `/admin/ajax.php?action=save_area` | High
32 | File | `/admin/all-applied-leave.php` | High
33 | File | `/admin/announcement/index.php?view=add` | High
34 | File | `/admin/api/theme-edit/` | High
35 | File | `/admin/application-bwdates-reports-details.php` | High
36 | File | `/admin/archives_add.php` | High
37 | File | `/admin/articles/add` | High
38 | File | `/admin/attendance_row.php` | High
39 | File | `/admin/backup/backups.php` | High
40 | File | `/admin/ballot_up.php` | High
41 | File | `/admin/changeimage.php` | High
42 | File | `/admin/class.php?dowhat=modifyclass` | High
43 | File | `/admin/clientview.php` | High
44 | File | `/admin/content/book` | High
45 | File | `/admin/deleteitem.php` | High
46 | File | `/admin/delete_s2.php` | High
47 | File | `/admin/edit-art-product-detail.php?editid=2` | High
48 | File | `/admin/edit-class.php?cid=1` | High
49 | File | `/admin/edit-user.php` | High
50 | File | `/admin/edit_state.php` | High
51 | File | `/admin/fields/manage_field.php` | High
52 | File | `/admin/images/add` | High
53 | File | `/admin/index.php` | High
54 | File | `/admin/index.php/news/edit` | High
55 | File | `/admin/indexConfigs/save` | High
56 | File | `/admin/list_localuser.php` | High
57 | File | `/admin/login.php` | High
58 | File | `/admin/manage-notices.php` | High
59 | File | `/admin/manage-tickets.php` | High
60 | File | `/admin/member_save.php` | High
61 | File | `/admin/offenses/view_details.php` | High
62 | File | `/admin/operations/travellers.php` | High
63 | File | `/admin/posts.php?source=add_post` | High
64 | File | `/admin/print-payment.php` | High
65 | File | `/admin/print.php` | High
66 | File | `/admin/registration.php` | High
67 | File | `/Admin/resultdetails.php` | High
68 | File | `/admin/return_add.php` | High
69 | File | `/admin/sales/manage_sale.php` | High
70 | File | `/admin/save_student.php` | High
71 | File | `/admin/search-appointment.php` | High
72 | File | `/admin/search-directory.php` | High
73 | File | `/admin/services/manage.php` | High
74 | File | `/admin/services/manage_service.php` | High
75 | File | `/admin/services/view_service.php` | High
76 | File | `/admin/spec_add.php` | High
77 | File | `/admin/sys/menu/list` | High
78 | File | `/admin/test_status.php` | High
79 | File | `/admin/transaction/deposit` | High
80 | File | `/admin/user.php` | High
81 | File | `/admin/user/user-move-run.php` | High
82 | File | `/admin/usersetting.php` | High
83 | File | `/adminprofile.php` | High
84 | File | `/admin_class.php` | High
85 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
86 | File | `/agent/profile/edit` | High
87 | File | `/ajax.php` | Medium
88 | File | `/ajax.php?action=read_msg` | High
89 | File | `/ajax.php?action=save_product` | High
90 | File | `/ajax.php?action=save_student` | High
91 | File | `/all-orders.php` | High
92 | File | `/api/blade-system/menu/list?updatexml` | High
93 | File | `/api/blade-user/export-user` | High
94 | File | `/api/config/list` | High
95 | File | `/api/deploy/upload` | High
96 | File | `/api/deploy/upload /api/database/upload` | High
97 | File | `/api/login/auth` | High
98 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
99 | File | `/api/v1/challenges//solves` | High
100 | File | `/app-api/v1/members/openid/` | High
101 | File | `/app/checkout/delete.php` | High
102 | File | `/app/register.php?action=reg` | High
103 | File | `/application/models/ApplicationDataObject.class.php` | High
104 | File | `/apply.cgi` | Medium
105 | File | `/applyleave.php` | High
106 | ... | ... | ...

There are 937 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
