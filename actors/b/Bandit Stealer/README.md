# Bandit Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bandit Stealer](https://vuldb.com/?actor.bandit_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bandit_stealer](https://vuldb.com/?actor.bandit_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bandit Stealer:

* [US](https://vuldb.com/?country.us)
* [SH](https://vuldb.com/?country.sh)
* [IT](https://vuldb.com/?country.it)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bandit Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.92.209.204](https://vuldb.com/?ip.3.92.209.204) | ec2-3-92-209-204.compute-1.amazonaws.com | - | Medium
2 | [20.102.80.176](https://vuldb.com/?ip.20.102.80.176) | - | - | High
3 | [20.150.218.195](https://vuldb.com/?ip.20.150.218.195) | - | - | High
4 | [24.199.107.85](https://vuldb.com/?ip.24.199.107.85) | - | - | High
5 | [41.216.183.23](https://vuldb.com/?ip.41.216.183.23) | - | - | High
6 | [41.216.183.94](https://vuldb.com/?ip.41.216.183.94) | - | - | High
7 | [45.42.45.10](https://vuldb.com/?ip.45.42.45.10) | web9-redirect.me | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bandit Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandit Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/99/ImportSQLTable` | High
2 | File | `/account.php` | Medium
3 | File | `/action.php` | Medium
4 | File | `/add.home.php` | High
5 | File | `/addCandidate.php` | High
6 | File | `/addmem.php` | Medium
7 | File | `/addtime.php` | Medium
8 | File | `/add_book.php` | High
9 | File | `/add_librarian.php` | High
10 | File | `/add_member.php` | High
11 | File | `/add_query_reserve.php` | High
12 | File | `/add_to_cart` | Medium
13 | File | `/admin.php` | Medium
14 | File | `/admin/?page=city` | High
15 | File | `/admin/?page=establishment` | High
16 | File | `/admin/?page=people` | High
17 | File | `/admin/?page=state` | High
18 | File | `/admin/?page=system_info/contact_info` | High
19 | File | `/admin/about.php` | High
20 | File | `/admin/add-artist.php` | High
21 | File | `/admin/add-customer.php` | High
22 | File | `/admin/add-property.php` | High
23 | File | `/admin/addpackage.php` | High
24 | File | `/admin/add_content.php` | High
25 | File | `/admin/add_product.php` | High
26 | File | `/admin/add_unit.php` | High
27 | File | `/admin/admin_action.php` | High
28 | File | `/admin/admin_forum/search_result.php` | High
29 | File | `/admin/admin_login.php` | High
30 | File | `/admin/admin_members.php?ac=search` | High
31 | File | `/admin/admin_product.ph` | High
32 | File | `/admin/admin_running.php` | High
33 | File | `/admin/ajax_represent.php` | High
34 | File | `/admin/all-applied-leave.php` | High
35 | File | `/admin/api/workspace/default/tool/debug` | High
36 | File | `/admin/article.php` | High
37 | File | `/admin/article.php?a=mod` | High
38 | File | `/admin/article.php?action=upload_cover` | High
39 | File | `/admin/articles/create` | High
40 | File | `/admin/bwdates-reports-details.php` | High
41 | File | `/admin/candidates_edit.php` | High
42 | File | `/Admin/changepassword.php` | High
43 | File | `/admin/chatroom.php` | High
44 | File | `/admin/checklogin.php` | High
45 | File | `/admin/cms/material/add` | High
46 | File | `/admin/config_ISCGroupNoCache.php` | High
47 | File | `/admin/content/book` | High
48 | File | `/admin/content/editor` | High
49 | File | `/admin/controller/faculty_controller.php` | High
50 | File | `/admin/customer-list.php` | High
51 | File | `/admin/customermanagementframework/customers/list` | High
52 | File | `/admin/deleteBooking.php` | High
53 | File | `/admin/deletemanager.php` | High
54 | File | `/admin/delete_s1.php` | High
55 | File | `/admin/delete_user.php` | High
56 | File | `/admin/department.php` | High
57 | File | `/admin/de_activate.php` | High
58 | File | `/admin/edit-category.php` | High
59 | File | `/admin/edit-teacher-detail.php` | High
60 | File | `/admin/edit_account.php` | High
61 | File | `/admin/edit_class.php` | High
62 | File | `/admin/edit_member.php` | High
63 | File | `/admin/edit_product.php` | High
64 | File | `/admin/edit_student.php` | High
65 | File | `/admin/edit_student_query.php` | High
66 | File | `/admin/edit_teacher.php` | High
67 | File | `/admin/edit_user.php` | High
68 | File | `/admin/fetch_product_details.php` | High
69 | File | `/admin/index.php` | High
70 | File | `/admin/inv-print.php` | High
71 | File | `/admin/login.php` | High
72 | File | `/admin/manage-foreigners-ticket.php` | High
73 | File | `/admin/manage_movie.php` | High
74 | File | `/admin/modules/class/index.php` | High
75 | File | `/admin/newsletter.php` | High
76 | File | `/admin/operation/user.php` | High
77 | File | `/admin/positions.php` | High
78 | File | `/admin/print-payment.php` | High
79 | File | `/admin/print.php` | High
80 | File | `/admin/print1.php` | High
81 | File | `/admin/print_inv.php` | High
82 | File | `/admin/product.php` | High
83 | File | `/admin/products.php` | High
84 | File | `/admin/products/index.php?view=edit` | High
85 | File | `/admin/profile.php` | High
86 | File | `/admin/receipt.php` | High
87 | File | `/admin/registration.php` | High
88 | File | `/Admin/registration.php` | High
89 | File | `/admin/reset-password.php` | High
90 | File | `/admin/sales/manage_sale.php` | High
91 | File | `/admin/save_user.php` | High
92 | File | `/admin/search-booking-request.php` | High
93 | File | `/admin/search-maid.php` | High
94 | File | `/admin/search-property.php` | High
95 | File | `/admin/show.php` | High
96 | File | `/admin/teachers.php` | High
97 | File | `/admin/twitter.php` | High
98 | File | `/admin/update-progress.php` | High
99 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
100 | File | `/admin/update_room.php` | High
101 | File | `/admin/update_s3.php` | High
102 | File | `/admin/update_s7.php` | High
103 | File | `/admin/update_student.php` | High
104 | File | `/admin/user/index.php?view=edit` | High
105 | File | `/admin/users.php` | High
106 | ... | ... | ...

There are 939 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/41.216.183.23
* https://search.censys.io/hosts/41.216.183.94
* https://search.censys.io/hosts/45.42.45.10
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
