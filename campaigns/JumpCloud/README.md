# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with JumpCloud or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/?actor.dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JumpCloud.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.29.115.171](https://vuldb.com/?ip.23.29.115.171) | 23-29-115-171.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
2 | [23.95.182.5](https://vuldb.com/?ip.23.95.182.5) | 23-95-182-5-host.colocrossing.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.82.250.186](https://vuldb.com/?ip.45.82.250.186) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [51.254.24.19](https://vuldb.com/?ip.51.254.24.19) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/Account/login.php` | High
3 | File | `/addbill.php` | Medium
4 | File | `/add_members.php` | High
5 | File | `/admin` | Low
6 | File | `/admin-manage-user.php` | High
7 | File | `/admin/` | Low
8 | File | `/admin/action/add_con.php` | High
9 | File | `/admin/action/delete-vaccine.php` | High
10 | File | `/admin/action/edit_chicken.php` | High
11 | File | `/admin/action/new-father.php` | High
12 | File | `/admin/action/new-feed.php` | High
13 | File | `/admin/action/update-deworm.php` | High
14 | File | `/admin/admin_login_process.php` | High
15 | File | `/admin/book_add.php` | High
16 | File | `/admin/book_row.php` | High
17 | File | `/admin/borrow_add.php` | High
18 | File | `/admin/bwdates-report-details.php` | High
19 | File | `/admin/category_row.php` | High
20 | File | `/admin/clientview.php` | High
21 | File | `/admin/courses/manage_course.php` | High
22 | File | `/admin/courses/view_course.php` | High
23 | File | `/admin/departments/manage_department.php` | High
24 | File | `/admin/edit-post.php` | High
25 | File | `/admin/edit_supplier.php` | High
26 | File | `/admin/forgot-password.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/index2.html` | High
29 | File | `/admin/list_addr_fwresource_ip.php` | High
30 | File | `/admin/login.php` | High
31 | File | `/Admin/login.php` | High
32 | File | `/admin/manage-users.php` | High
33 | File | `/admin/order.php` | High
34 | File | `/admin/pages/edit_chicken.php` | High
35 | File | `/admin/pages/student-print.php` | High
36 | File | `/admin/pages/update_go.php` | High
37 | File | `/admin/php/crud.php` | High
38 | File | `/admin/regester.php` | High
39 | File | `/admin/request-received-bydonar.php` | High
40 | File | `/admin/return_add.php` | High
41 | File | `/admin/role` | Medium
42 | File | `/admin/singlelogin.php` | High
43 | File | `/admin/singlelogin.php?submit=1` | High
44 | File | `/admin/students/manage_academic.php` | High
45 | File | `/admin/students/update_status.php` | High
46 | File | `/admin/update-clients.php` | High
47 | File | `/admin/upload/img` | High
48 | File | `/adminPage/conf/saveCmd` | High
49 | File | `/admin_route/dec_service_credits.php` | High
50 | File | `/admin_route/inc_service_credits.php` | High
51 | File | `/ample/app/action/edit_product.php` | High
52 | File | `/api.php` | Medium
53 | File | `/api/` | Low
54 | File | `/app/ajax/sell_return_data.php` | High
55 | File | `/app/index/controller/Common.php` | High
56 | File | `/application/index/common.php` | High
57 | File | `/application/index/controller/Databasesource.php` | High
58 | File | `/application/index/controller/File.php` | High
59 | File | `/application/index/controller/Icon.php` | High
60 | File | `/application/index/controller/Pay.php` | High
61 | File | `/application/index/controller/Screen.php` | High
62 | File | `/application/index/controller/Service.php` | High
63 | File | `/application/index/controller/Unity.php` | High
64 | File | `/application/pay/controller/Api.php` | High
65 | File | `/application/plugins/controller/Upload.php` | High
66 | File | `/application/websocket/controller/Setting.php` | High
67 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
68 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
69 | File | `/applications/nexus/modules/front/store/store.php` | High
70 | File | `/apply/index.php` | High
71 | File | `/apps/login_auth.php` | High
72 | File | `/apps/reg_go.php` | High
73 | File | `/assets/php/upload.php` | High
74 | File | `/assoc_table.php` | High
75 | File | `/auth/auth.php?user=1` | High
76 | File | `/billing/bill/edit/` | High
77 | File | `/bitrix/admin/ldap_server_edit.php` | High
78 | File | `/boaform/getASPdata/formFirewall` | High
79 | File | `/cgi-bin/cstecgi.cgi` | High
80 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
81 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
82 | File | `/cgi-bin/nas_sharing.cgi` | High
83 | File | `/classes/Master.php` | High
84 | File | `/classes/Master.php?f=save_category` | High
85 | File | `/classes/Users.php?f=save` | High
86 | File | `/command_port.ini` | High
87 | File | `/config,admin.jsp` | High
88 | File | `/diag_s.php` | Medium
89 | File | `/edit-computer-detail.php` | High
90 | File | `/edit-task.php` | High
91 | File | `/EXCU_SHELL` | Medium
92 | File | `/fftools/ffmpeg_enc.c` | High
93 | File | `/file-manager/delete.php` | High
94 | File | `/file-manager/upload.php` | High
95 | File | `/forms/doLogin` | High
96 | File | `/forum/away.php` | High
97 | File | `/get.php` | Medium
98 | File | `/goform/AddDnsForward` | High
99 | File | `/goform/addIpMacBind` | High
100 | File | `/goform/addressNat` | High
101 | ... | ... | ...

There are 890 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
