# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | - | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | - | High
3 | [24.88.87.29](https://vuldb.com/?ip.24.88.87.29) | syn-024-088-087-029.res.spectrum.com | - | High
4 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | - | High
5 | [32.143.50.222](https://vuldb.com/?ip.32.143.50.222) | - | - | High
6 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | - | High
7 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | - | High
8 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | - | High
9 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | - | High
10 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | - | High
11 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | - | High
12 | [68.76.150.97](https://vuldb.com/?ip.68.76.150.97) | 68-76-150-97.lightspeed.hstntx.sbcglobal.net | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pawn Storm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=route_ispinfo_export_save` | High
2 | File | `/a/sys/user/save` | High
3 | File | `/aboutus.php` | Medium
4 | File | `/acceptoffres.php` | High
5 | File | `/account/_settings` | High
6 | File | `/add-pass.php` | High
7 | File | `/addcategory.php` | High
8 | File | `/addfriend.php` | High
9 | File | `/adding-exec.php` | High
10 | File | `/addproduct.php` | High
11 | File | `/add_contestant.php` | High
12 | File | `/add_judge.php` | High
13 | File | `/add_librarian.php` | High
14 | File | `/admin-api/mp/material/upload-permanent` | High
15 | File | `/admin.php` | Medium
16 | File | `/admin/actions/check-attendance.php` | High
17 | File | `/admin/actions/delete-equipment.php` | High
18 | File | `/admin/actions/delete-member.php` | High
19 | File | `/admin/actions/remove-announcement.php` | High
20 | File | `/admin/add_account.php` | High
21 | File | `/admin/add_candidate_modal.php.` | High
22 | File | `/admin/admin.php` | High
23 | File | `/admin/adminprofile.php` | High
24 | File | `/admin/admin_football.php` | High
25 | File | `/admin/admin_index.php` | High
26 | File | `/admin/admin_product.ph` | High
27 | File | `/admin/ajax.php` | High
28 | File | `/admin/announcement/index.php?view=add` | High
29 | File | `/admin/application-bwdates-reports-details.php` | High
30 | File | `/admin/archives_add.php` | High
31 | File | `/admin/articles/add` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
34 | File | `/admin/backup/backups.php` | High
35 | File | `/admin/category.php` | High
36 | File | `/admin/class.php?dowhat=modifyclass` | High
37 | File | `/admin/clientview.php` | High
38 | File | `/admin/content/book` | High
39 | File | `/admin/deleteitem.php` | High
40 | File | `/admin/department/add` | High
41 | File | `/admin/edit-art-product-detail.php?editid=2` | High
42 | File | `/admin/edit-class.php?cid=1` | High
43 | File | `/admin/edit-equipmentform.php` | High
44 | File | `/admin/edit-user.php` | High
45 | File | `/admin/edit_product.php` | High
46 | File | `/admin/edit_title.php?id=1` | High
47 | File | `/admin/employee/index.php?view=edit` | High
48 | File | `/admin/fields/manage_field.php` | High
49 | File | `/admin/forgot-password.php` | High
50 | File | `/admin/freelist_main.php` | High
51 | File | `/admin/index.php` | High
52 | File | `/admin/index.php?add_product` | High
53 | File | `/admin/login.php` | High
54 | File | `/admin/manage-services.php` | High
55 | File | `/admin/manage-users.php` | High
56 | File | `/admin/member_save.php` | High
57 | File | `/admin/menu.php` | High
58 | File | `/admin/normal-bwdates-reports-details.php` | High
59 | File | `/admin/offenses/view_details.php` | High
60 | File | `/admin/readenq.php` | High
61 | File | `/admin/regester.php` | High
62 | File | `/admin/registration.php` | High
63 | File | `/admin/roomdel.php` | High
64 | File | `/admin/search-appointment.php` | High
65 | File | `/admin/services/view_service.php` | High
66 | File | `/admin/spec_add.php` | High
67 | File | `/admin/student-history.php` | High
68 | File | `/admin/transaction/deposit` | High
69 | File | `/admin/update-profile.php` | High
70 | File | `/admin/update-progress.php` | High
71 | File | `/admin/update_user.php` | High
72 | File | `/admin/user-payment.php` | High
73 | File | `/admin/user-profile.php` | High
74 | File | `/admin/user.php` | High
75 | File | `/admin/usersetting.php` | High
76 | File | `/administrator/remove.php` | High
77 | File | `/admin_class.php` | High
78 | File | `/Admin_dashboard/edit_profile` | High
79 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
80 | File | `/ajax.php?action=delete_payroll` | High
81 | File | `/ajax.php?action=login` | High
82 | File | `/ajax.php?action=read_msg` | High
83 | File | `/ajax/action.php` | High
84 | File | `/all-orders.php` | High
85 | File | `/api/config/list` | High
86 | File | `/api/deploy/upload` | High
87 | File | `/api/deploy/upload /api/database/upload` | High
88 | File | `/api/file/upload` | High
89 | File | `/api/login/auth` | High
90 | File | `/api/process.php` | High
91 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
92 | ... | ... | ...

There are 812 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
