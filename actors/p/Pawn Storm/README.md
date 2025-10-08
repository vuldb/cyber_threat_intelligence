# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)

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
1 | T1006 | CWE-21, CWE-22, CWE-27 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/account.php?q=quiz&step=2` | High
3 | File | `/action.php` | Medium
4 | File | `/add-normal-ticket.php` | High
5 | File | `/add-subadmin.php` | High
6 | File | `/add-teacher.php` | High
7 | File | `/add_dealerrequest.php` | High
8 | File | `/add_members.php` | High
9 | File | `/adm/index.php` | High
10 | File | `/admin-api/upload_image` | High
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
37 | File | `/admin/contact-list.php` | High
38 | File | `/admin/content/editor` | High
39 | File | `/admin/core/update_student.php` | High
40 | File | `/admin/countrymanagement.php` | High
41 | File | `/admin/create-package.php` | High
42 | File | `/admin/curriculum/view_curriculum.php` | High
43 | File | `/admin/deleteroom.php` | High
44 | File | `/admin/delete_file.php` | High
45 | File | `/Admin/detail.php` | High
46 | File | `/admin/edit-category-detail.php` | High
47 | File | `/admin/edit-subadmin.php` | High
48 | File | `/admin/edit-team.php` | High
49 | File | `/admin/editempexp.php` | High
50 | File | `/admin/expense-type` | High
51 | File | `/admin/home.php?con=add` | High
52 | File | `/admin/home/index.html` | High
53 | File | `/admin/index.php?page=manage_product` | High
54 | File | `/admin/index.php?r=user%2Fcreate` | High
55 | File | `/Admin/InsertCategory.php` | High
56 | File | `/admin/login-back.php` | High
57 | File | `/admin/manage-users.php` | High
58 | File | `/admin/manage_station.php` | High
59 | File | `/admin/media_folders` | High
60 | File | `/admin/member_save.php` | High
61 | File | `/admin/modules/product/controller.php?action=add` | High
62 | File | `/admin/new-requests.php` | High
63 | File | `/admin/Operations/Role.php` | High
64 | File | `/admin/order.php` | High
65 | File | `/admin/pages/subjects.php` | High
66 | File | `/admin/pages/update_go.php` | High
67 | File | `/admin/pages/yearlevel.php` | High
68 | File | `/admin/positions_edit.php` | High
69 | File | `/admin/positions_row.php` | High
70 | File | `/admin/profile.php` | High
71 | File | `/admin/search-appointment.php` | High
72 | File | `/admin/search-directory.php` | High
73 | File | `/admin/search.php` | High
74 | File | `/admin/settings/index.php?page=accounts` | High
75 | File | `/admin/students/manage_academic.php` | High
76 | File | `/admin/system.html` | High
77 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
78 | File | `/admin/template/update` | High
79 | File | `/admin/unreadenq.php` | High
80 | File | `/admin/update_room.php` | High
81 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
82 | File | `/adms/admin/?page=vehicles/view_transaction` | High
83 | File | `/api/deploy/upload` | High
84 | File | `/api/deploy/upload /api/database/upload` | High
85 | File | `/api/v1/attack` | High
86 | File | `/api/v2/open/rowsInfo` | High
87 | File | `/app/index/controller/Common.php` | High
88 | File | `/art-enquiry.php` | High
89 | File | `/astre/iodasweb/app.jsp` | High
90 | File | `/auth.asp` | Medium
91 | File | `/auth/user/all.api` | High
92 | File | `/autheditpwd.php` | High
93 | File | `/bbdms/admin/update-contactinfo.php` | High
94 | File | `/bilal final/edit_stud.php` | High
95 | File | `/bishe/register` | High
96 | File | `/boafrm/formStaticDHCP` | High
97 | File | `/boafrm/formStats` | High
98 | File | `/book_edit_do.html` | High
99 | File | `/BRS_top.html` | High
100 | ... | ... | ...

There are 888 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
