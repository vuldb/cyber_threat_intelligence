# TellYouThePass - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TellYouThePass](https://vuldb.com/?actor.tellyouthepass). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tellyouthepass](https://vuldb.com/?actor.tellyouthepass)

## Campaigns

The following _campaigns_ are known and can be associated with TellYouThePass:

* CVE-2024-4577

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TellYouThePass:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TellYouThePass.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.116.254.172](https://vuldb.com/?ip.14.116.254.172) | - | CVE-2024-4577 | High
2 | [14.225.53.162](https://vuldb.com/?ip.14.225.53.162) | static.vnpt.vn | CVE-2024-4577 | High
3 | [39.97.209.211](https://vuldb.com/?ip.39.97.209.211) | - | CVE-2024-4577 | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TellYouThePass_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TellYouThePass. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?explorer/index/zip` | High
3 | File | `/?p=products` | Medium
4 | File | `/?r=email/api/mark&op=delFromSend` | High
5 | File | `/a/sys/area/save` | High
6 | File | `/a/sys/user/save` | High
7 | File | `/account/_settings` | High
8 | File | `/add-pass.php` | High
9 | File | `/addCandidate.php` | High
10 | File | `/addcategory.php` | High
11 | File | `/addfriend.php` | High
12 | File | `/admin-profile.php` | High
13 | File | `/admin.php` | Medium
14 | File | `/admin/?page=inventory/view_inventory&id=2` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/about_edit.php?action=modify` | High
17 | File | `/admin/action/new-feed.php` | High
18 | File | `/admin/actions/check-attendance.php` | High
19 | File | `/admin/actions/delete-member.php` | High
20 | File | `/admin/actions/remove-announcement.php` | High
21 | File | `/admin/add-subadmins.php` | High
22 | File | `/admin/add_account.php` | High
23 | File | `/admin/add_content.php` | High
24 | File | `/admin/admin_feature.php` | High
25 | File | `/admin/admin_product.ph` | High
26 | File | `/admin/api/theme-edit/` | High
27 | File | `/admin/app/login_crud.php` | High
28 | File | `/admin/archives_add.php` | High
29 | File | `/admin/barcode.php` | High
30 | File | `/admin/category.php` | High
31 | File | `/admin/chatroom.php` | High
32 | File | `/admin/class.php?dowhat=modifyclass` | High
33 | File | `/admin/customer-list.php` | High
34 | File | `/admin/deleteitem.php` | High
35 | File | `/admin/department/add` | High
36 | File | `/admin/departments/manage_department.php` | High
37 | File | `/admin/edit-art-medium-detail.php` | High
38 | File | `/admin/edit-equipmentform.php` | High
39 | File | `/admin/edit-user.php` | High
40 | File | `/admin/edit.php` | High
41 | File | `/admin/edit_room.php` | High
42 | File | `/admin/edit_student.php` | High
43 | File | `/admin/edit_teacher.php` | High
44 | File | `/admin/edit_user.php` | High
45 | File | `/admin/fetch_product_details.php` | High
46 | File | `/admin/fields/manage_field.php` | High
47 | File | `/admin/freelist_main.php` | High
48 | File | `/admin/index.php` | High
49 | File | `/admin/index.php?add_product` | High
50 | File | `/admin/inquiries/view_inquiry.php` | High
51 | File | `/admin/kami_list` | High
52 | File | `/admin/login.php` | High
53 | File | `/admin/manage_user.php` | High
54 | File | `/admin/modules/department/index.php` | High
55 | File | `/admin/modules/room/index.php` | High
56 | File | `/admin/new-appointment.php` | High
57 | File | `/admin/newsletterdel.php` | High
58 | File | `/admin/options-theme.php` | High
59 | File | `/admin/reservation.php` | High
60 | File | `/admin/sales-reports-detail.php` | High
61 | File | `/admin/save_teacher.php` | High
62 | File | `/admin/save_user.php` | High
63 | File | `/admin/search-appointment.php` | High
64 | File | `/admin/search-invoices.php` | High
65 | File | `/admin/search_product.php` | High
66 | File | `/admin/seo_setting.php` | High
67 | File | `/admin/show.php` | High
68 | File | `/admin/spec_add.php` | High
69 | File | `/admin/teachers.php` | High
70 | File | `/admin/transaction/deposit` | High
71 | File | `/admin/update-progress.php` | High
72 | File | `/admin/update_user.php` | High
73 | File | `/admin/upload` | High
74 | File | `/admin/user-payment.php` | High
75 | File | `/admin/usersetting.php` | High
76 | File | `/admin/view-appointment.php` | High
77 | File | `/admin/view-member-report.php` | High
78 | File | `/admin/visitor-details.php` | High
79 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
80 | File | `/Administrator/PHP/AdminAddCategory.php` | High
81 | File | `/Administrator/PHP/AdminDeleteCategory.php` | High
82 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
83 | File | `/admin_class.php` | High
84 | File | `/admin_cron.php` | High
85 | File | `/adv_mac_filter.php` | High
86 | File | `/agents/deploy/initiate.c` | High
87 | File | `/ajax.php` | Medium
88 | File | `/ajax.php?action=delete_course` | High
89 | File | `/ajax.php?action=delete_plan` | High
90 | File | `/ajax.php?action=login` | High
91 | File | `/ajax.php?action=read_msg` | High
92 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
93 | File | `/api/admin/system/store/order/list` | High
94 | File | `/api/config/list` | High
95 | File | `/api/file` | Medium
96 | File | `/api/password/email` | High
97 | File | `/api/users/updateEmail/` | High
98 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
99 | File | `/api/v1/initialization/embedding/test` | High
100 | File | `/appointments.php` | High
101 | File | `/assets/changeSllyabus.php` | High
102 | File | `/assets/editNotes.php` | High
103 | File | `/auth/auth.php?user=1` | High
104 | File | `/b2c/package-information` | High
105 | File | `/bbdms/admin/update-contactinfo.php` | High
106 | File | `/bitrix/admin/ldap_server_edit.php` | High
107 | File | `/boaform/formgponConf` | High
108 | File | `/boafrm/formIpQoS` | High
109 | ... | ... | ...

There are 965 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/cve-2024-4577-ongoing-exploitation-of-a-critical-php-vulnerability/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
