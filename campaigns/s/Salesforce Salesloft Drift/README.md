# Salesforce Salesloft Drift - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Salesforce Salesloft Drift_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Salesforce Salesloft Drift:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Salesforce Salesloft Drift or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [UNC6395](https://vuldb.com/?actor.unc6395) | High
2 | [GRUB1](https://vuldb.com/?actor.grub1) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Salesforce Salesloft Drift.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [44.215.108.109](https://vuldb.com/?ip.44.215.108.109) | ec2-44-215-108-109.compute-1.amazonaws.com | [UNC6395](https://vuldb.com/?actor.unc6395) | Medium
2 | [154.41.95.2](https://vuldb.com/?ip.154.41.95.2) | - | [UNC6395](https://vuldb.com/?actor.unc6395) | High
3 | [176.65.149.100](https://vuldb.com/?ip.176.65.149.100) | hosted-by.pfcloud.io | [UNC6395](https://vuldb.com/?actor.unc6395) | High
4 | [179.43.159.198](https://vuldb.com/?ip.179.43.159.198) | hostedby.privatelayer.com | [UNC6395](https://vuldb.com/?actor.unc6395) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Salesforce Salesloft Drift. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-83 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Salesforce Salesloft Drift. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/a/sys/area/save` | High
4 | File | `/add-lockertype.php` | High
5 | File | `/add-normal-ticket.php` | High
6 | File | `/add-product.php` | High
7 | File | `/adm/index.php` | High
8 | File | `/admin#themes` | High
9 | File | `/admin.php?mod=brand&act=del` | High
10 | File | `/admin/?page=categories/view_category` | High
11 | File | `/admin/?page=state` | High
12 | File | `/admin/?page=zone` | High
13 | File | `/admin/accepted-appointment.php` | High
14 | File | `/admin/add-ambulance.php` | High
15 | File | `/admin/add-art-product.php` | High
16 | File | `/admin/add-artist.php` | High
17 | File | `/admin/addroom.php` | High
18 | File | `/admin/add_category.php` | High
19 | File | `/admin/add_unit.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/admin/save` | High
22 | File | `/admin/admin_football.php` | High
23 | File | `/admin/assign_save.php` | High
24 | File | `/admin/attendance_row.php` | High
25 | File | `/admin/auth/roles` | High
26 | File | `/admin/bookdate.php` | High
27 | File | `/admin/booking-bwdates-reports-details.php` | High
28 | File | `/admin/booktime.php` | High
29 | File | `/admin/bwdates-reports-details.php` | High
30 | File | `/admin/candidates_add.php` | High
31 | File | `/admin/candidates_delete.php` | High
32 | File | `/Admin/changepassword.php` | High
33 | File | `/admin/complaint-search.php` | High
34 | File | `/admin/completed-requests.php` | High
35 | File | `/Admin/Controller/CustomController.class.php` | High
36 | File | `/admin/course.php` | High
37 | File | `/admin/delete_user.php` | High
38 | File | `/admin/doctor-specilization.php` | High
39 | File | `/admin/edit-admin.php` | High
40 | File | `/admin/edit-art-product-detail.php?editid=2` | High
41 | File | `/admin/edit-guard-detail.php` | High
42 | File | `/admin/edit-user.php` | High
43 | File | `/admin/editposts.php` | High
44 | File | `/admin/edit_activity.php` | High
45 | File | `/admin/edit_admin_details.php?id=admin` | High
46 | File | `/admin/edit_admin_query.php` | High
47 | File | `/admin/edit_expenses_query.php` | High
48 | File | `/admin/edit_query_account.php` | High
49 | File | `/admin/edit_student_query.php` | High
50 | File | `/admin/forget-password.php` | High
51 | File | `/admin/getmanagerregion.php` | High
52 | File | `/admin/group/edit.do` | High
53 | File | `/admin/ImgUpdaPost.php` | High
54 | File | `/admin/includes/edit_post.php` | High
55 | File | `/admin/index.php` | High
56 | File | `/admin/index.php?page=user-profile` | High
57 | File | `/admin/lab.php` | High
58 | File | `/admin/login-back.php` | High
59 | File | `/admin/login.php` | High
60 | File | `/admin/manage-notices.php` | High
61 | File | `/admin/manage-tickets.php` | High
62 | File | `/admin/manage_user.php` | High
63 | File | `/admin/member_save.php` | High
64 | File | `/admin/message/search.php` | High
65 | File | `/admin/new-autoortaxi-entry-form.php` | High
66 | File | `/admin/operation/user.php` | High
67 | File | `/admin/operations/expense.php` | High
68 | File | `/admin/property.php` | High
69 | File | `/admin/request-received-bydonar.php` | High
70 | File | `/admin/search-directory.php` | High
71 | File | `/admin/search-invoices.php` | High
72 | File | `/admin/storage/delete` | High
73 | File | `/admin/subject/controller.php` | High
74 | File | `/admin/suppliercontroller.php` | High
75 | File | `/admin/system/variableList.do` | High
76 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
77 | File | `/admin/user.php` | High
78 | File | `/admin/user/edit.do` | High
79 | File | `/admin/user/index.php?view=edit` | High
80 | File | `/admin/v1/blog/edit` | High
81 | File | `/admin/view-user-queries.php` | High
82 | File | `/admin/View_user.php` | High
83 | File | `/admin/voters_delete.php` | High
84 | File | `/admin/voters_row.php` | High
85 | File | `/admin/wangkan_list.php` | High
86 | File | `/adminapi/system/file/openfile` | High
87 | File | `/administrator/addcategory.php` | High
88 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
89 | File | `/Administrator/PHP/AdminAddCategory.php` | High
90 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
91 | File | `/Administrator/PHP/AdminEditCategory.php` | High
92 | File | `/Administrator/PHP/AdminReply.php` | High
93 | File | `/Administrator/PHP/AdminUpdateCategory.php` | High
94 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
95 | File | `/admin_link.php?action=delall` | High
96 | File | `/admin_pic.php` | High
97 | File | `/adv_mac_filter.php` | High
98 | File | `/aim/storage/query.py` | High
99 | File | `/airag/knowledge/doc/edit` | High
100 | File | `/ajax.php?action=calculate_payroll` | High
101 | File | `/ajax.php?action=delete_allowances` | High
102 | File | `/ajax.php?action=delete_package` | High
103 | File | `/ajax.php?action=delete_trainer` | High
104 | File | `/ajax.php?action=delete_user` | High
105 | File | `/ajax.php?action=end_membership` | High
106 | File | `/ajax.php?action=save_membership` | High
107 | File | `/ajax.php?action=save_payroll` | High
108 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
109 | File | `/api/database/testConnect` | High
110 | File | `/api/File/downloadFile` | High
111 | File | `/api/file/downloadUrl` | High
112 | File | `/api/info/long_task` | High
113 | File | `/api/sys/login` | High
114 | File | `/api/undo/` | Medium
115 | File | `/api/wizard/getssidname` | High
116 | File | `/api/wizard/setLanguage` | High
117 | File | `/app/api/controller/collect.php` | High
118 | File | `/app/register.php?action=reg` | High
119 | File | `/app/sms.php` | Medium
120 | File | `/app/sys1.php` | High
121 | File | `/appDetail.jsp` | High
122 | File | `/application/pay/controller/Index.php` | High
123 | File | `/appointment-history.php` | High
124 | File | `/apps/meteor/app/irc/server/servers/RFC2813/parseMessage.js` | High
125 | File | `/arp_sys.asp` | Medium
126 | File | `/assetsGroupReport/assetsService.j%73p` | High
127 | ... | ... | ...

There are 1126 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.cloudflare.com/response-to-salesloft-drift-incident/
* https://cloud.google.com/blog/topics/threat-intelligence/data-theft-salesforce-instances-via-salesloft-drift/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
