# UNC6395 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UNC6395](https://vuldb.com/?actor.unc6395). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.unc6395](https://vuldb.com/?actor.unc6395)

## Campaigns

The following _campaigns_ are known and can be associated with UNC6395:

* Salesforce Salesloft Drift

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNC6395:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNC6395.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [44.215.108.109](https://vuldb.com/?ip.44.215.108.109) | ec2-44-215-108-109.compute-1.amazonaws.com | Salesforce Salesloft Drift | Medium
2 | [154.41.95.2](https://vuldb.com/?ip.154.41.95.2) | - | Salesforce Salesloft Drift | High
3 | [176.65.149.100](https://vuldb.com/?ip.176.65.149.100) | hosted-by.pfcloud.io | Salesforce Salesloft Drift | High
4 | [179.43.159.198](https://vuldb.com/?ip.179.43.159.198) | hostedby.privatelayer.com | Salesforce Salesloft Drift | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UNC6395_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-83 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UNC6395. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/a/sys/area/save` | High
4 | File | `/academic-calendar` | High
5 | File | `/add-lockertype.php` | High
6 | File | `/add-normal-ticket.php` | High
7 | File | `/add-product.php` | High
8 | File | `/adding-exec.php` | High
9 | File | `/addproduct.php` | High
10 | File | `/add_query_reserve.php` | High
11 | File | `/adm/index.php` | High
12 | File | `/admin#themes` | High
13 | File | `/admin.php?mod=brand&act=del` | High
14 | File | `/admin/?page=categories/view_category` | High
15 | File | `/admin/?page=state` | High
16 | File | `/admin/?page=zone` | High
17 | File | `/admin/aboutus.php` | High
18 | File | `/admin/accepted-appointment.php` | High
19 | File | `/admin/actions/check-attendance.php` | High
20 | File | `/admin/add-ambulance.php` | High
21 | File | `/admin/add-art-product.php` | High
22 | File | `/admin/add-artist.php` | High
23 | File | `/admin/addroom.php` | High
24 | File | `/admin/add_category.php` | High
25 | File | `/admin/add_course.php` | High
26 | File | `/admin/add_student.php` | High
27 | File | `/admin/add_unit.php` | High
28 | File | `/admin/admin-profile.php` | High
29 | File | `/admin/admin_football.php` | High
30 | File | `/admin/assign_save.php` | High
31 | File | `/admin/auth/roles` | High
32 | File | `/admin/bookdate.php` | High
33 | File | `/admin/booking-bwdates-reports-details.php` | High
34 | File | `/admin/booktime.php` | High
35 | File | `/admin/bwdates-reports-details.php` | High
36 | File | `/admin/candidates_add.php` | High
37 | File | `/Admin/changepassword.php` | High
38 | File | `/admin/completed-requests.php` | High
39 | File | `/Admin/Controller/CustomController.class.php` | High
40 | File | `/admin/course.php` | High
41 | File | `/Admin/CustomerReport.php` | High
42 | File | `/admin/deleteitem.php` | High
43 | File | `/admin/delete_user.php` | High
44 | File | `/admin/doctor-specilization.php` | High
45 | File | `/admin/edit-admin.php` | High
46 | File | `/admin/edit-art-product-detail.php?editid=2` | High
47 | File | `/admin/edit-guard-detail.php` | High
48 | File | `/admin/edit-user.php` | High
49 | File | `/admin/editposts.php` | High
50 | File | `/admin/edit_admin_details.php?id=admin` | High
51 | File | `/admin/edit_admin_query.php` | High
52 | File | `/admin/edit_expenses_query.php` | High
53 | File | `/admin/edit_members.php` | High
54 | File | `/admin/edit_query_account.php` | High
55 | File | `/admin/edit_room.php` | High
56 | File | `/admin/edit_student_query.php` | High
57 | File | `/admin/forget-password.php` | High
58 | File | `/admin/group/edit.do` | High
59 | File | `/admin/images/add` | High
60 | File | `/admin/ImgUpdaPost.php` | High
61 | File | `/admin/includes/edit_post.php` | High
62 | File | `/admin/index.php` | High
63 | File | `/admin/index.php?page=user-profile` | High
64 | File | `/admin/lab.php` | High
65 | File | `/admin/login-back.php` | High
66 | File | `/admin/login.php` | High
67 | File | `/admin/manage-notices.php` | High
68 | File | `/admin/manage-tickets.php` | High
69 | File | `/admin/member_save.php` | High
70 | File | `/admin/operation/user.php` | High
71 | File | `/admin/operations/expense.php` | High
72 | File | `/admin/property.php` | High
73 | File | `/admin/request-received-bydonar.php` | High
74 | File | `/admin/search-directory.php` | High
75 | File | `/admin/search-invoices.php` | High
76 | File | `/admin/storage/delete` | High
77 | File | `/admin/subject/controller.php` | High
78 | File | `/admin/suppliercontroller.php` | High
79 | File | `/admin/system/variableList.do` | High
80 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
81 | File | `/admin/user-bookings.php` | High
82 | File | `/admin/user.php` | High
83 | File | `/admin/user/edit.do` | High
84 | File | `/admin/user/index.php?view=edit` | High
85 | File | `/admin/v1/blog/edit` | High
86 | File | `/admin/view-user-queries.php` | High
87 | File | `/admin/View_user.php` | High
88 | File | `/admin/voters_delete.php` | High
89 | File | `/admin/voters_row.php` | High
90 | File | `/admin/wangkan_list.php` | High
91 | File | `/adminapi/system/file/openfile` | High
92 | File | `/administrator/addcategory.php` | High
93 | File | `/Administrator/PHP/AdminAddCategory.php` | High
94 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
95 | File | `/Administrator/PHP/AdminReply.php` | High
96 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
97 | File | `/admin_link.php?action=delall` | High
98 | File | `/admin_pic.php` | High
99 | File | `/aim/storage/query.py` | High
100 | File | `/ajax.php?action=delete_allowances` | High
101 | File | `/ajax.php?action=delete_package` | High
102 | File | `/ajax.php?action=delete_payment` | High
103 | File | `/ajax.php?action=delete_trainer` | High
104 | File | `/ajax.php?action=delete_user` | High
105 | File | `/ajax.php?action=end_membership` | High
106 | File | `/ajax.php?action=save_membership` | High
107 | File | `/ajax.php?action=save_payroll` | High
108 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
109 | File | `/alphaware/summary.php` | High
110 | File | `/api/File/downloadFile` | High
111 | File | `/api/file/downloadUrl` | High
112 | File | `/api/sys/login` | High
113 | File | `/api/users/updateEmail/` | High
114 | File | `/api/wizard/setLanguage` | High
115 | File | `/app/api/controller/collect.php` | High
116 | File | `/app/register.php?action=reg` | High
117 | File | `/app/sms.php` | Medium
118 | File | `/app/sys1.php` | High
119 | File | `/appDetail.jsp` | High
120 | File | `/application/pay/controller/Index.php` | High
121 | File | `/appointment-history.php` | High
122 | File | `/apps/meteor/app/irc/server/servers/RFC2813/parseMessage.js` | High
123 | File | `/arp_sys.asp` | Medium
124 | File | `/assetsGroupReport/assetsService.j%73p` | High
125 | ... | ... | ...

There are 1112 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloud.google.com/blog/topics/threat-intelligence/data-theft-salesforce-instances-via-salesloft-drift/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
