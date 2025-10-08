# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

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
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/account.php?q=quiz&step=2` | High
3 | File | `/account/forgotpassword` | High
4 | File | `/action.php` | Medium
5 | File | `/add-subadmin.php` | High
6 | File | `/add_dealerrequest.php` | High
7 | File | `/add_members.php` | High
8 | File | `/adm/index.php` | High
9 | File | `/admin-api/upload_image` | High
10 | File | `/admin-cp/permalinks` | High
11 | File | `/admin-cp/theme/editor/default` | High
12 | File | `/admin.php/addon/index` | High
13 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
14 | File | `/admin/?/user/add` | High
15 | File | `/admin/?page=inmates/view_inmate` | High
16 | File | `/admin/add_user_modal.php` | High
17 | File | `/admin/admin-add-employee.php` | High
18 | File | `/admin/admin.php` | High
19 | File | `/admin/admin_class.php` | High
20 | File | `/admin/admin_content_tag.php?action=save_content` | High
21 | File | `/admin/ajax.php?action=delete_user` | High
22 | File | `/admin/ajax.php?action=login` | High
23 | File | `/admin/all-request.php` | High
24 | File | `/admin/approve.php` | High
25 | File | `/admin/article/article-edit-run.php` | High
26 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
27 | File | `/admin/between-date-complaintreport.php` | High
28 | File | `/admin/bwdates-report-result.php` | High
29 | File | `/admin/campsdetails.php` | High
30 | File | `/admin/category-list.php` | High
31 | File | `/admin/category/cate-edit-run.php` | High
32 | File | `/admin/category/view_category.php` | High
33 | File | `/admin/change-image.php` | High
34 | File | `/admin/change-password.php` | High
35 | File | `/admin/check_availability.php` | High
36 | File | `/admin/clientview.php` | High
37 | File | `/admin/content/editor` | High
38 | File | `/admin/core/update_student.php` | High
39 | File | `/admin/countrymanagement.php` | High
40 | File | `/admin/create-package.php` | High
41 | File | `/admin/curriculum/view_curriculum.php` | High
42 | File | `/admin/deleteroom.php` | High
43 | File | `/Admin/detail.php` | High
44 | File | `/admin/edit-art-product-detail.php?editid=2` | High
45 | File | `/admin/edit-category-detail.php` | High
46 | File | `/admin/edit-team.php` | High
47 | File | `/admin/editempexp.php` | High
48 | File | `/admin/expense-type` | High
49 | File | `/admin/home.php?con=add` | High
50 | File | `/admin/home/index.html` | High
51 | File | `/admin/index.php` | High
52 | File | `/admin/index.php?page=manage_product` | High
53 | File | `/admin/index.php?r=user%2Fcreate` | High
54 | File | `/Admin/InsertCategory.php` | High
55 | File | `/Admin/InsertState.php` | High
56 | File | `/admin/login-back.php` | High
57 | File | `/admin/manage-outgoingvehicle.php` | High
58 | File | `/admin/manage-users.php` | High
59 | File | `/admin/manage_station.php` | High
60 | File | `/admin/member_save.php` | High
61 | File | `/admin/modules/product/controller.php?action=add` | High
62 | File | `/admin/new-requests.php` | High
63 | File | `/admin/Operations/Role.php` | High
64 | File | `/admin/order.php` | High
65 | File | `/admin/orders/view_order.php` | High
66 | File | `/admin/pages/subjects.php` | High
67 | File | `/admin/pages/yearlevel.php` | High
68 | File | `/admin/positions_edit.php` | High
69 | File | `/admin/positions_row.php` | High
70 | File | `/admin/profile.php` | High
71 | File | `/admin/search-appointment.php` | High
72 | File | `/admin/search-directory.php` | High
73 | File | `/admin/search.php` | High
74 | File | `/admin/settings/index.php?page=accounts` | High
75 | File | `/admin/system.html` | High
76 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
77 | File | `/admin/template/update` | High
78 | File | `/admin/unreadenq.php` | High
79 | File | `/admin/update_room.php` | High
80 | File | `/adms/admin/?page=vehicles/view_transaction` | High
81 | File | `/alphaware/summary.php` | High
82 | File | `/api/controllers/merchant/design/MaterialController.php` | High
83 | File | `/api/deploy/upload` | High
84 | File | `/api/deploy/upload /api/database/upload` | High
85 | File | `/api/v1/attack` | High
86 | File | `/api/v2/open/rowsInfo` | High
87 | File | `/app/index/controller/Common.php` | High
88 | File | `/art-enquiry.php` | High
89 | File | `/astre/iodasweb/app.jsp` | High
90 | File | `/auth/user/all.api` | High
91 | File | `/autheditpwd.php` | High
92 | File | `/bbdms/admin/update-contactinfo.php` | High
93 | File | `/boafrm/formStaticDHCP` | High
94 | File | `/boafrm/formStats` | High
95 | File | `/boafrm/formWsc` | High
96 | File | `/book_edit_do.html` | High
97 | File | `/business/common/sms/sendsms.jsp` | High
98 | File | `/cap.js` | Low
99 | ... | ... | ...

There are 878 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/10/lemon-duck-brings-cryptocurrency-miners.html
* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
