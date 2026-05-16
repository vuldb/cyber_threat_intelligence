# XtremeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XtremeRAT](https://vuldb.com/?actor.xtremerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xtremerat](https://vuldb.com/?actor.xtremerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XtremeRAT:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [UA](https://vuldb.com/?country.ua)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XtremeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.81.154.116](https://vuldb.com/?ip.2.81.154.116) | bl20-154-116.dsl.telepac.pt | - | High
2 | [5.79.71.205](https://vuldb.com/?ip.5.79.71.205) | - | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
5 | [20.72.235.82](https://vuldb.com/?ip.20.72.235.82) | - | - | High
6 | [23.7.178.157](https://vuldb.com/?ip.23.7.178.157) | a23-7-178-157.deploy.static.akamaitechnologies.com | - | High
7 | [23.32.81.118](https://vuldb.com/?ip.23.32.81.118) | a23-32-81-118.deploy.static.akamaitechnologies.com | - | High
8 | [23.62.7.138](https://vuldb.com/?ip.23.62.7.138) | a23-62-7-138.deploy.static.akamaitechnologies.com | - | High
9 | [23.62.230.159](https://vuldb.com/?ip.23.62.230.159) | a23-62-230-159.deploy.static.akamaitechnologies.com | - | High
10 | [23.202.2.105](https://vuldb.com/?ip.23.202.2.105) | a23-202-2-105.deploy.static.akamaitechnologies.com | - | High
11 | [23.202.81.150](https://vuldb.com/?ip.23.202.81.150) | a23-202-81-150.deploy.static.akamaitechnologies.com | - | High
12 | [52.8.126.80](https://vuldb.com/?ip.52.8.126.80) | ec2-52-8-126-80.us-west-1.compute.amazonaws.com | - | Medium
13 | [62.90.21.54](https://vuldb.com/?ip.62.90.21.54) | 62-90-21-54.barak.net.il | - | High
14 | [64.29.151.221](https://vuldb.com/?ip.64.29.151.221) | hostedc40.carrierzone.com | - | High
15 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
16 | ... | ... | ... | ...

There are 61 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XtremeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XtremeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/?page=reserve` | High
3 | File | `/?_route=settings/users-view/` | High
4 | File | `/account/_settings` | High
5 | File | `/ad/queryAll` | Medium
6 | File | `/addCandidate.php` | High
7 | File | `/addproduct.php` | High
8 | File | `/add_contestant.php` | High
9 | File | `/admin-profile.php` | High
10 | File | `/admin.php` | Medium
11 | File | `/admin.php?id=inbox` | High
12 | File | `/admin/?page=reports` | High
13 | File | `/admin/aboutus.php` | High
14 | File | `/admin/action/add_con.php` | High
15 | File | `/admin/action/new-feed.php` | High
16 | File | `/admin/actions/check-attendance.php` | High
17 | File | `/admin/add-directory.php` | High
18 | File | `/admin/add-module.php` | High
19 | File | `/admin/add_account.php` | High
20 | File | `/admin/add_expenses.php` | High
21 | File | `/admin/add_room.php` | High
22 | File | `/admin/add_subject.php` | High
23 | File | `/admin/admin_product.ph` | High
24 | File | `/admin/all-applied-leave.php` | High
25 | File | `/admin/api/theme-edit/` | High
26 | File | `/admin/app/login_crud.php` | High
27 | File | `/admin/archives_add.php` | High
28 | File | `/admin/article.php?action=upload_cover` | High
29 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
30 | File | `/admin/bookings/manage_booking.php` | High
31 | File | `/admin/budget/manage_budget.php` | High
32 | File | `/admin/categories/view_category.php` | High
33 | File | `/admin/category.php` | High
34 | File | `/admin/changeimage.php` | High
35 | File | `/admin/check_admin.php` | High
36 | File | `/admin/class.php?dowhat=modifyclass` | High
37 | File | `/admin/clientview.php` | High
38 | File | `/admin/contactus.php` | High
39 | File | `/admin/customer-list.php` | High
40 | File | `/admin/customermanagementframework/customers/list` | High
41 | File | `/admin/deleteitem.php` | High
42 | File | `/admin/edit-category.php` | High
43 | File | `/admin/edit.php` | High
44 | File | `/admin/edit_subject.php` | High
45 | File | `/admin/employee/controller.php` | High
46 | File | `/admin/fetch_product_details.php` | High
47 | File | `/admin/forget-password.php` | High
48 | File | `/admin/forgot-password.php` | High
49 | File | `/admin/freelist_main.php` | High
50 | File | `/admin/index.php` | High
51 | File | `/admin/index.php/datafile/delfile` | High
52 | File | `/admin/inquiries/view_inquiry.php` | High
53 | File | `/admin/lab.php` | High
54 | File | `/admin/login.php` | High
55 | File | `/admin/manage-art-medium.php` | High
56 | File | `/admin/manage-students.php` | High
57 | File | `/admin/manage_station.php` | High
58 | File | `/admin/menu_save.php` | High
59 | File | `/admin/modules/lesson/index.php` | High
60 | File | `/admin/modules/product/controller.php?action=add` | High
61 | File | `/admin/modules/room/index.php` | High
62 | File | `/admin/newsletterdel.php` | High
63 | File | `/admin/room.php` | High
64 | File | `/admin/roombook.php` | High
65 | File | `/admin/roomdel.php` | High
66 | File | `/admin/sales-reports-detail.php` | High
67 | File | `/admin/search-appointment.php` | High
68 | File | `/admin/search-invoices.php` | High
69 | File | `/admin/store/edit/` | High
70 | File | `/admin/teachers.php` | High
71 | File | `/admin/update-profile.php` | High
72 | File | `/admin/update-progress.php` | High
73 | File | `/admin/update_student.php` | High
74 | File | `/admin/update_user.php` | High
75 | File | `/admin/user-payment.php` | High
76 | File | `/admin/user.php` | High
77 | File | `/admin/user/manage_user.php` | High
78 | File | `/admin/users.php` | High
79 | File | `/admin/view-progress-report.php` | High
80 | File | `/Adminadd.php` | High
81 | File | `/adminapi/product/product` | High
82 | File | `/Administrator/PHP/AdminAddCategory.php` | High
83 | File | `/Administrator/PHP/AdminEditCategory.php` | High
84 | File | `/adminLogin.php` | High
85 | File | `/admin_class.php` | High
86 | File | `/ajax.php` | Medium
87 | File | `/ajax.php?action=delete_borrower` | High
88 | File | `/ajax.php?action=delete_course` | High
89 | File | `/ajax.php?action=delete_supplier` | High
90 | File | `/ajax.php?action=delete_user` | High
91 | File | `/api/course/enroll-course` | High
92 | File | `/api/file/upload` | High
93 | File | `/api/public/signup` | High
94 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
95 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
96 | File | `/application/index/common.php` | High
97 | File | `/application/index/controller/Icon.php` | High
98 | File | `/artist-display.php` | High
99 | File | `/assets/editNotes.php` | High
100 | File | `/assets/uploadNotes.php` | High
101 | File | `/auth/userkey/logout.php` | High
102 | File | `/b2c/package-information` | High
103 | File | `/bin/httpd` | Medium
104 | File | `/boafrm/formFilter` | High
105 | File | `/boafrm/formFirewallAdv` | High
106 | File | `/boafrm/formIpQoS` | High
107 | File | `/boafrm/formVlan` | High
108 | File | `/boafrm/formWanConfigSetup` | High
109 | File | `/c6/Jhsoft.Web.projectmanage/TaskManage/AddTask.aspx/?Type=add` | High
110 | File | `/cart.php` | Medium
111 | File | `/category.php` | High
112 | File | `/category/list?limit=10&offset=0&order=desc` | High
113 | File | `/cgi-bin/api.values.post` | High
114 | File | `/cgi-bin/cstecgi.cg` | High
115 | File | `/cgi-bin/cstecgi.cgi` | High
116 | File | `/cgi-bin/firewall.cgi` | High
117 | File | `/cgi-bin/lighttpd.cgi` | High
118 | File | `/cgi-bin/wireless.cgi` | High
119 | ... | ... | ...

There are 1054 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/07/threat-roundup-0712-0719.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0719-0726.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0424-0501.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0225-0304.html
* https://blog.talosintelligence.com/2022/05/threat-roundup-0429-0506.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0819-0826.html
* https://blog.talosintelligence.com/threat-roundup-0127-0203/
* https://blog.talosintelligence.com/threat-roundup-0407-0414/
* https://blog.talosintelligence.com/threat-roundup-0428-0505/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
