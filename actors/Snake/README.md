# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | - | High
2 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
3 | [8.0.1.0](https://vuldb.com/?ip.8.0.1.0) | - | - | High
4 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | Snake | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snake_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/home/courses` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/addproduct.php` | High
8 | File | `/admin/ajax.php?action=confirm_order` | High
9 | File | `/admin/article/article-edit-run.php` | High
10 | File | `/admin/bookings/manage_booking.php` | High
11 | File | `/admin/bookings/view_booking.php` | High
12 | File | `/admin/budget/manage_budget.php` | High
13 | File | `/admin/cashadvance_row.php` | High
14 | File | `/admin/cms_admin.php` | High
15 | File | `/admin/contacts/organizations/edit/2` | High
16 | File | `/admin/curriculum/view_curriculum.php` | High
17 | File | `/admin/deduction_row.php` | High
18 | File | `/admin/departments/view_department.php` | High
19 | File | `/admin/edit_product.php` | High
20 | File | `/admin/edit_subject.php` | High
21 | File | `/admin/employee_row.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
24 | File | `/admin/inquiries/view_inquiry.php` | High
25 | File | `/admin/leancloud.php` | High
26 | File | `/admin/login.php` | High
27 | File | `/admin/maintenance/manage_category.php` | High
28 | File | `/admin/maintenance/view_designation.php` | High
29 | File | `/admin/mechanics/manage_mechanic.php` | High
30 | File | `/admin/modal_add_product.php` | High
31 | File | `/admin/offenses/view_details.php` | High
32 | File | `/admin/orders/update_status.php` | High
33 | File | `/admin/products/manage_product.php` | High
34 | File | `/admin/products/view_product.php` | High
35 | File | `/admin/project/update/2` | High
36 | File | `/admin/read.php?mudi=getSignal` | High
37 | File | `/admin/reg.php` | High
38 | File | `/admin/reminders/manage_reminder.php` | High
39 | File | `/admin/report/index.php` | High
40 | File | `/admin/service.php` | High
41 | File | `/admin/services/manage_service.php` | High
42 | File | `/admin/services/view_service.php` | High
43 | File | `/admin/service_requests/manage_inventory.php` | High
44 | File | `/admin/sys_sql_query.php` | High
45 | File | `/admin/test_status.php` | High
46 | File | `/admin/upload.php` | High
47 | File | `/admin/user/manage_user.php` | High
48 | File | `/admin/userprofile.php` | High
49 | File | `/admin/vote_edit.php` | High
50 | File | `/ajax.php?action=read_msg` | High
51 | File | `/api/stl/actions/search` | High
52 | File | `/api/sys/login` | High
53 | File | `/apply.cgi` | Medium
54 | File | `/App_Resource/UEditor/server/upload.aspx` | High
55 | File | `/autheditpwd.php` | High
56 | File | `/author_posts.php` | High
57 | File | `/bin/ate` | Medium
58 | File | `/blog` | Low
59 | File | `/blog-single.php` | High
60 | File | `/booking/show_bookings/` | High
61 | File | `/browse` | Low
62 | File | `/bsms_ci/index.php/book` | High
63 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
64 | File | `/cgi-bin/ping.cgi` | High
65 | File | `/chaincity/user/ticket/create` | High
66 | File | `/changeimage.php` | High
67 | File | `/classes/Login.php` | High
68 | File | `/classes/Master.php` | High
69 | File | `/classes/Master.php?f=delete_category` | High
70 | File | `/classes/Master.php?f=delete_inquiry` | High
71 | File | `/classes/Master.php?f=delete_item` | High
72 | File | `/classes/Master.php?f=delete_service` | High
73 | File | `/classes/Master.php?f=delete_sub_category` | High
74 | File | `/classes/Master.php?f=save_course` | High
75 | File | `/classes/Master.php?f=save_inquiry` | High
76 | File | `/classes/Master.php?f=save_item` | High
77 | File | `/classes/Master.php?f=save_service` | High
78 | File | `/classes/Users.php` | High
79 | File | `/classes/Users.php?f=save` | High
80 | File | `/collection/all` | High
81 | File | `/company/store` | High
82 | File | `/config` | Low
83 | ... | ... | ...

There are 728 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.bleepingcomputer.com/news/security/snake-ransomware-is-the-next-threat-targeting-business-networks/
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
