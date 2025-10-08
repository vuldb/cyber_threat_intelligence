# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27, CWE-35 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/99/ImportSQLTable` | High
2 | File | `/add-lockertype.php` | High
3 | File | `/add-teacher.php` | High
4 | File | `/addelidetails.php` | High
5 | File | `/addelivery.php` | High
6 | File | `/add_dealerrequest.php` | High
7 | File | `/add_reserve.php` | High
8 | File | `/adicionar-cliente.php` | High
9 | File | `/admin` | Low
10 | File | `/admin#themes` | High
11 | File | `/admin/add-category.php` | High
12 | File | `/admin/add-customer.php` | High
13 | File | `/admin/add-foreigner-ticket.php` | High
14 | File | `/admin/add-foreigners-ticket.php` | High
15 | File | `/admin/add_city.php` | High
16 | File | `/admin/add_subject.php` | High
17 | File | `/admin/admin-profile.php` | High
18 | File | `/admin/admin_forum/search_result.php` | High
19 | File | `/admin/ajax.php?action=confirm_order` | High
20 | File | `/admin/ajax.php?action=save_vacancy` | High
21 | File | `/admin/ajax_represent.php` | High
22 | File | `/admin/api/workspace/default/tool/debug` | High
23 | File | `/admin/article.php` | High
24 | File | `/admin/article/list` | High
25 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
26 | File | `/admin/auto-taxi-entry-detail.php` | High
27 | File | `/admin/bwdates-reports-details.php` | High
28 | File | `/admin/category-list.php` | High
29 | File | `/admin/category_save.php` | High
30 | File | `/admin/class.php` | High
31 | File | `/admin/clients/manage.php` | High
32 | File | `/admin/content/editor` | High
33 | File | `/admin/controller/faculty_controller.php` | High
34 | File | `/admin/disapprove_user.php` | High
35 | File | `/admin/doctor-specilization.php` | High
36 | File | `/admin/edit-art-medium-detail.php` | High
37 | File | `/admin/edit-customer-detailed.php` | High
38 | File | `/admin/edit-doctor-specialization.php` | High
39 | File | `/admin/edit-doctor.php` | High
40 | File | `/admin/edit-services.php` | High
41 | File | `/admin/edit-user-profile.php` | High
42 | File | `/admin/edit_product.php` | High
43 | File | `/admin/edit_tax.php` | High
44 | File | `/admin/expense_report.php` | High
45 | File | `/admin/fetch_product_details.php` | High
46 | File | `/admin/forgot-password.php` | High
47 | File | `/admin/home/index.html` | High
48 | File | `/admin/ImgAddPost.php` | High
49 | File | `/admin/index.php` | High
50 | File | `/admin/index.php/news/edit` | High
51 | File | `/admin/inv-print.php` | High
52 | File | `/admin/list_onlineuser.php` | High
53 | File | `/admin/login` | Medium
54 | File | `/admin/login-back.php` | High
55 | File | `/admin/login.php` | High
56 | File | `/admin/manage-art-medium.php` | High
57 | File | `/admin/manage-directory.php` | High
58 | File | `/admin/manage-foreigners-ticket.php` | High
59 | File | `/admin/manage-incomingvehicle.php` | High
60 | File | `/admin/manage-outgoingvehicle.php` | High
61 | File | `/admin/manage_user.php` | High
62 | File | `/admin/menu_save.php` | High
63 | File | `/admin/modal_add_product.php` | High
64 | File | `/admin/modules/department/index.php` | High
65 | File | `/admin/modules/instructor/index.php` | High
66 | File | `/admin/modules/subject/index.php` | High
67 | File | `/admin/new-autoortaxi-entry-form.php` | High
68 | File | `/admin/normal-bwdates-reports-details.php` | High
69 | File | `/admin/operations/booking.php` | High
70 | File | `/admin/operations/currency.php` | High
71 | File | `/admin/operations/expense.php` | High
72 | File | `/admin/operations/payment.php` | High
73 | File | `/admin/operations/travellers.php` | High
74 | File | `/admin/order.php` | High
75 | File | `/admin/photo.php` | High
76 | File | `/admin/print-payment.php` | High
77 | File | `/admin/productadd_back.php` | High
78 | File | `/admin/profile.php` | High
79 | File | `/admin/reg-users.php` | High
80 | File | `/Admin/registration.php` | High
81 | File | `/admin/save_airlines.php` | High
82 | File | `/admin/search-appointment.php` | High
83 | File | `/admin/search.php` | High
84 | File | `/admin/sign/out` | High
85 | File | `/admin/slide.php` | High
86 | File | `/admin/sms_setting.php` | High
87 | File | `/admin/storage/delete` | High
88 | File | `/admin/subscriber-csv.php` | High
89 | File | `/admin/tag.php` | High
90 | File | `/admin/tags/save` | High
91 | File | `/admin/theme-edit.php` | High
92 | File | `/admin/topic/list` | High
93 | File | `/Admin/tournament_details.php` | High
94 | File | `/admin/update_s3.php` | High
95 | File | `/admin/user-search.php` | High
96 | File | `/admin/view-enquiry.php` | High
97 | File | `/adminFile/upload` | High
98 | File | `/administrator/bidupdate.php` | High
99 | File | `/administrator/remove.php` | High
100 | File | `/administrator/wew.php` | High
101 | File | `/administrator/weweee.php` | High
102 | File | `/adminlogin.php` | High
103 | File | `/adminprofile.php` | High
104 | File | `/adphar.php` | Medium
105 | File | `/adplanet/PlanetCommentList` | High
106 | File | `/AGE0000700/GetHorariosDoDia?idespec=0&idproced=1103&data=2025-02-25+19%3A25&agserv=0&convenio=1&localatend=1&idplano=5&pesfis=01&idprofissional=0&target=.horarios--dia--d0&_=1739371223797` | High
107 | File | `/ajax.php` | Medium
108 | File | `/ajax.php?action=delete_supplier` | High
109 | File | `/ajax.php?action=login` | High
110 | File | `/ajax.php?action=save_product` | High
111 | File | `/alunos/search_autocomplete` | High
112 | File | `/animalsadd.php` | High
113 | File | `/api.php` | Medium
114 | File | `/api/deploy/upload` | High
115 | File | `/api/deploy/upload /api/database/upload` | High
116 | File | `/Api/FileUploadApi.ashx` | High
117 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
118 | File | `/api/v1/admin/` | High
119 | File | `/api/v1/getbaseconfig` | High
120 | File | `/api/wechat/app_auth` | High
121 | File | `/api/wizard/getBasicInfo` | High
122 | ... | ... | ...

There are 1085 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
