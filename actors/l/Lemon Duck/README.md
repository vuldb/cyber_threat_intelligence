# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lemon Duck.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.202.15.246](https://vuldb.com/?ip.1.202.15.246) | 246.15.202.1.static.bjtelecom.net | - | High
2 | [27.195.157.70](https://vuldb.com/?ip.27.195.157.70) | - | - | High
3 | [36.48.94.254](https://vuldb.com/?ip.36.48.94.254) | - | - | High
4 | [36.110.1.222](https://vuldb.com/?ip.36.110.1.222) | 222.1.110.36.static.bjtelecom.net | - | High
5 | [40.68.42.171](https://vuldb.com/?ip.40.68.42.171) | - | - | High
6 | [42.7.4.88](https://vuldb.com/?ip.42.7.4.88) | - | - | High
7 | [42.7.31.243](https://vuldb.com/?ip.42.7.31.243) | - | - | High
8 | [42.176.133.183](https://vuldb.com/?ip.42.176.133.183) | - | - | High
9 | [49.71.208.124](https://vuldb.com/?ip.49.71.208.124) | - | - | High
10 | [49.147.72.67](https://vuldb.com/?ip.49.147.72.67) | dsl.49.148.72.67.pldt.net | - | High
11 | [51.36.170.221](https://vuldb.com/?ip.51.36.170.221) | - | - | High
12 | [58.56.135.198](https://vuldb.com/?ip.58.56.135.198) | - | - | High
13 | [58.62.125.245](https://vuldb.com/?ip.58.62.125.245) | - | - | High
14 | [58.221.24.178](https://vuldb.com/?ip.58.221.24.178) | - | - | High
15 | [58.251.2.115](https://vuldb.com/?ip.58.251.2.115) | reverse.gdsz.cncnet.net | - | High
16 | [59.111.181.116](https://vuldb.com/?ip.59.111.181.116) | - | - | High
17 | [59.175.154.97](https://vuldb.com/?ip.59.175.154.97) | - | - | High
18 | [60.10.56.169](https://vuldb.com/?ip.60.10.56.169) | hebei.10.60.in-addr.arpa | - | High
19 | [60.10.134.93](https://vuldb.com/?ip.60.10.134.93) | hebei.10.60.in-addr.arpa | - | High
20 | [60.19.236.50](https://vuldb.com/?ip.60.19.236.50) | - | - | High
21 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lemon Duck_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=route_ispinfo_export_save` | High
2 | File | `/a/sys/user/save` | High
3 | File | `/aboutus.php` | Medium
4 | File | `/acceptoffres.php` | High
5 | File | `/account/_settings` | High
6 | File | `/add-pass.php` | High
7 | File | `/addcategory.php` | High
8 | File | `/addcompany.php` | High
9 | File | `/addfriend.php` | High
10 | File | `/adding-exec.php` | High
11 | File | `/addproduct.php` | High
12 | File | `/add_contestant.php` | High
13 | File | `/add_judge.php` | High
14 | File | `/add_librarian.php` | High
15 | File | `/admin-api/mp/material/upload-permanent` | High
16 | File | `/admin.php` | Medium
17 | File | `/admin/` | Low
18 | File | `/admin/?page=return/view_return` | High
19 | File | `/admin/actions/check-attendance.php` | High
20 | File | `/admin/actions/delete-equipment.php` | High
21 | File | `/admin/actions/delete-member.php` | High
22 | File | `/admin/actions/remove-announcement.php` | High
23 | File | `/admin/add_account.php` | High
24 | File | `/admin/add_candidate_modal.php.` | High
25 | File | `/admin/admin.php` | High
26 | File | `/admin/adminprofile.php` | High
27 | File | `/admin/admin_football.php` | High
28 | File | `/admin/admin_index.php` | High
29 | File | `/admin/admin_product.ph` | High
30 | File | `/admin/announcement/index.php?view=add` | High
31 | File | `/admin/application-bwdates-reports-details.php` | High
32 | File | `/admin/archives_add.php` | High
33 | File | `/admin/articles/add` | High
34 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
35 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
36 | File | `/admin/backup/backups.php` | High
37 | File | `/admin/category.php` | High
38 | File | `/admin/class.php?dowhat=modifyclass` | High
39 | File | `/admin/clientview.php` | High
40 | File | `/admin/content/book` | High
41 | File | `/admin/deleteitem.php` | High
42 | File | `/admin/department/add` | High
43 | File | `/admin/edit-art-product-detail.php?editid=2` | High
44 | File | `/admin/edit-equipmentform.php` | High
45 | File | `/admin/edit-user.php` | High
46 | File | `/admin/edit_product.php` | High
47 | File | `/admin/edit_title.php?id=1` | High
48 | File | `/admin/employee/index.php?view=edit` | High
49 | File | `/admin/employee_edit.php` | High
50 | File | `/admin/fields/manage_field.php` | High
51 | File | `/admin/forgot-password.php` | High
52 | File | `/admin/freelist_main.php` | High
53 | File | `/admin/index.php` | High
54 | File | `/admin/index.php?add_product` | High
55 | File | `/admin/login.php` | High
56 | File | `/admin/manage-services.php` | High
57 | File | `/admin/manage-users.php` | High
58 | File | `/admin/manage_user.php` | High
59 | File | `/admin/menu.php` | High
60 | File | `/admin/normal-bwdates-reports-details.php` | High
61 | File | `/admin/offenses/view_details.php` | High
62 | File | `/admin/readenq.php` | High
63 | File | `/admin/regester.php` | High
64 | File | `/admin/registration.php` | High
65 | File | `/admin/roomdel.php` | High
66 | File | `/admin/search-appointment.php` | High
67 | File | `/admin/services/view_service.php` | High
68 | File | `/admin/spec_add.php` | High
69 | File | `/admin/student-history.php` | High
70 | File | `/admin/transaction/deposit` | High
71 | File | `/admin/update-profile.php` | High
72 | File | `/admin/update-progress.php` | High
73 | File | `/admin/update_user.php` | High
74 | File | `/admin/user-payment.php` | High
75 | File | `/admin/user-profile.php` | High
76 | File | `/admin/user.php` | High
77 | File | `/admin/usersetting.php` | High
78 | File | `/administrator/remove.php` | High
79 | File | `/admin_class.php` | High
80 | File | `/Admin_dashboard/edit_profile` | High
81 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
82 | File | `/admin_members.php?ac=editsave` | High
83 | File | `/ajax.php?action=delete_payroll` | High
84 | File | `/ajax.php?action=login` | High
85 | File | `/ajax.php?action=read_msg` | High
86 | File | `/ajax/action.php` | High
87 | File | `/all-orders.php` | High
88 | File | `/api/config/list` | High
89 | File | `/api/deploy/upload` | High
90 | File | `/api/deploy/upload /api/database/upload` | High
91 | File | `/api/file/upload` | High
92 | File | `/api/login/auth` | High
93 | File | `/api/process.php` | High
94 | ... | ... | ...

There are 828 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/10/lemon-duck-brings-cryptocurrency-miners.html
* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
