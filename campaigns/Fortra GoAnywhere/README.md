# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/?actor.clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/?actor.clop) | Medium
2 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/?actor.clop) | High
3 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/?actor.clop) | High
4 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | [Clop](https://vuldb.com/?actor.clop) | High
5 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/?actor.clop) | High
6 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/?actor.clop) | High
7 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/?actor.clop) | High
8 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | [Clop](https://vuldb.com/?actor.clop) | High
9 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/?actor.clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?p=products` | Medium
3 | File | `/Account/login.php` | High
4 | File | `/accounts_con/register_account` | High
5 | File | `/actuator/heapdump` | High
6 | File | `/addbill.php` | Medium
7 | File | `/add_classes.php` | High
8 | File | `/add_members.php` | High
9 | File | `/admin` | Low
10 | File | `/admin-api/upload_image` | High
11 | File | `/admin-manage-user.php` | High
12 | File | `/admin.php?p=/Area/index#tab=t2` | High
13 | File | `/admin/` | Low
14 | File | `/admin/?page=borrow/view_borrow` | High
15 | File | `/admin/?page=user/list` | High
16 | File | `/admin/action/delete-vaccine.php` | High
17 | File | `/admin/action/edit_chicken.php` | High
18 | File | `/admin/add-ambulance.php` | High
19 | File | `/admin/add_postlogin.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/admin_user.php` | High
22 | File | `/admin/applicants/index.php` | High
23 | File | `/admin/booktime.php` | High
24 | File | `/admin/book_add.php` | High
25 | File | `/admin/borrow_add.php` | High
26 | File | `/admin/bwdates-report-details.php` | High
27 | File | `/admin/category_row.php` | High
28 | File | `/admin/clientview.php` | High
29 | File | `/admin/client_user` | High
30 | File | `/admin/content` | High
31 | File | `/admin/court` | Medium
32 | File | `/admin/doctors.php` | High
33 | File | `/Admin/edit-photo.php` | High
34 | File | `/admin/edit-services.php` | High
35 | File | `/admin/edit_categories.php` | High
36 | File | `/admin/edit_supplier.php` | High
37 | File | `/admin/employee/index.php` | High
38 | File | `/admin/expense-type` | High
39 | File | `/admin/foreigner-bwdates-reports-details.php` | High
40 | File | `/admin/foreigner-search.php` | High
41 | File | `/admin/forgot-password.php` | High
42 | File | `/admin/index.php` | High
43 | File | `/admin/ind_backstage.php` | High
44 | File | `/admin/judge` | Medium
45 | File | `/admin/list_crl_conf` | High
46 | File | `/admin/list_ipAddressPolicy.php` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/maintenance/manage_brand.php` | High
49 | File | `/admin/manage-ambulance.php` | High
50 | File | `/admin/manage-students.php` | High
51 | File | `/admin/menu/toEdit` | High
52 | File | `/admin/normal-bwdates-reports-details.php` | High
53 | File | `/admin/normal-search.php` | High
54 | File | `/admin/options-theme.php` | High
55 | File | `/admin/pages/edit_chicken.php` | High
56 | File | `/admin/pages/update_go.php` | High
57 | File | `/admin/receipt.php` | High
58 | File | `/admin/regester.php` | High
59 | File | `/admin/request-received-bydonar.php` | High
60 | File | `/admin/return_add.php` | High
61 | File | `/admin/role` | Medium
62 | File | `/admin/rooms.php` | High
63 | File | `/admin/singlelogin.php?submit=1` | High
64 | File | `/admin/subject.php` | High
65 | File | `/admin/tag.php` | High
66 | File | `/admin/tasks` | Medium
67 | File | `/admin/tax` | Medium
68 | File | `/admin/template` | High
69 | File | `/admin/twitter.php` | High
70 | File | `/admin/update-rooms.php` | High
71 | File | `/admin/update-users.php` | High
72 | File | `/admin/upload/img` | High
73 | File | `/admin/uploads/` | High
74 | File | `/Admin/user-record.php` | High
75 | File | `/admin/user/index.php` | High
76 | File | `/admin/users.php` | High
77 | File | `/admin/vacancy/index.php` | High
78 | File | `/admin/vendor` | High
79 | File | `/adminapi/system/file/openfile` | High
80 | File | `/adminPage/conf/reload` | High
81 | File | `/adminPage/conf/saveCmd` | High
82 | File | `/adminPage/main/upload` | High
83 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
84 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
85 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
86 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
87 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
88 | File | `/adminpanel/admin/query/loginExe.php` | High
89 | File | `/admin_route/dec_service_credits.php` | High
90 | File | `/adplanet/PlanetCommentList` | High
91 | File | `/ajax-api.php` | High
92 | File | `/ajax.php` | Medium
93 | File | `/ample/app/action/edit_product.php` | High
94 | File | `/api/controllers/admin/app/AppController.php` | High
95 | File | `/api/controllers/merchant/app/ComboController.php` | High
96 | File | `/api/controllers/merchant/design/MaterialController.php` | High
97 | File | `/api/log/killJob` | High
98 | File | `/app/ajax/search_sales_report.php` | High
99 | File | `/app/Http/Controllers/ImageController.php` | High
100 | File | `/application/index/controller/Datament.php` | High
101 | File | `/application/index/controller/File.php` | High
102 | File | `/application/index/controller/Icon.php` | High
103 | File | `/application/index/controller/Screen.php` | High
104 | File | `/application/index/controller/Unity.php` | High
105 | File | `/application/pay/controller/Api.php` | High
106 | File | `/application/plugins/controller/Upload.php` | High
107 | File | `/application/websocket/controller/Setting.php` | High
108 | File | `/apply/index.php` | High
109 | File | `/apps/login_auth.php` | High
110 | ... | ... | ...

There are 975 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
