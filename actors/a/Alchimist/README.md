# Alchimist - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Alchimist](https://vuldb.com/?actor.alchimist). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.alchimist](https://vuldb.com/?actor.alchimist)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Alchimist.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.86.255.8](https://vuldb.com/?ip.3.86.255.8) | ec2-3-86-255-8.compute-1.amazonaws.com | - | Medium
2 | [3.86.255.88](https://vuldb.com/?ip.3.86.255.88) | ec2-3-86-255-88.compute-1.amazonaws.com | - | Medium
3 | [45.32.132.166](https://vuldb.com/?ip.45.32.132.166) | - | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Alchimist_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Alchimist. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/99/ImportSQLTable` | High
2 | File | `/Actions.php` | Medium
3 | File | `/actuator` | Medium
4 | File | `/ad/queryAll` | Medium
5 | File | `/add-book.php` | High
6 | File | `/add-teacher.php` | High
7 | File | `/add.home.php` | High
8 | File | `/addcategory.php` | High
9 | File | `/addclient1.php` | High
10 | File | `/addcompany.php` | High
11 | File | `/addelidetails.php` | High
12 | File | `/addelivery.php` | High
13 | File | `/addmem.php` | Medium
14 | File | `/addtime.php` | Medium
15 | File | `/addvehicle.php` | High
16 | File | `/add_student_grade.php` | High
17 | File | `/adm/index.php` | High
18 | File | `/admin-control.php` | High
19 | File | `/admin-cp/file-manager/upload` | High
20 | File | `/admin-profile.php` | High
21 | File | `/admin.php` | Medium
22 | File | `/admin.php/addon/index` | High
23 | File | `/admin/` | Low
24 | File | `/admin/add-animals.php` | High
25 | File | `/admin/add-customer-services.php` | High
26 | File | `/admin/add-directory.php` | High
27 | File | `/admin/add-foreigner-ticket.php` | High
28 | File | `/admin/add-subadmin.php` | High
29 | File | `/admin/add-table.php` | High
30 | File | `/admin/adddoctorclinic.php` | High
31 | File | `/admin/add_cars.php` | High
32 | File | `/admin/add_query_account.php` | High
33 | File | `/admin/add_student.php` | High
34 | File | `/admin/add_subject.php` | High
35 | File | `/admin/add_teacher.php` | High
36 | File | `/admin/add_title.php` | High
37 | File | `/admin/ajax.php?action=login` | High
38 | File | `/admin/ajax.php?action=save_application` | High
39 | File | `/admin/approve_user.php` | High
40 | File | `/admin/betweendates-detailsreports.php` | High
41 | File | `/admin/blogger.php?action=update_avatar` | High
42 | File | `/admin/booking_report.php` | High
43 | File | `/admin/bwdates-reports-details.php` | High
44 | File | `/admin/calendar_of_events.php` | High
45 | File | `/admin/candidates_add.php` | High
46 | File | `/admin/change-emailid.php` | High
47 | File | `/admin/changepassword.php` | High
48 | File | `/admin/checklogin.php` | High
49 | File | `/admin/class.php` | High
50 | File | `/admin/comment/list` | High
51 | File | `/admin/completed-requests.php` | High
52 | File | `/admin/config/express` | High
53 | File | `/admin/contact-us.php` | High
54 | File | `/admin/controller/delete_group_student.php` | High
55 | File | `/admin/core/new_user` | High
56 | File | `/admin/deletedoctor.php` | High
57 | File | `/admin/deletegallery.php` | High
58 | File | `/admin/deleteroom.php` | High
59 | File | `/admin/delete_member.php` | High
60 | File | `/admin/delete_s4.php` | High
61 | File | `/admin/delete_s5.php` | High
62 | File | `/admin/delete_s6.php` | High
63 | File | `/admin/delete_s7.php` | High
64 | File | `/admin/delete_s8.php` | High
65 | File | `/admin/delete_user.php` | High
66 | File | `/admin/doctor-specilization.php` | High
67 | File | `/admin/edit-services.php` | High
68 | File | `/admin/edit_class.php` | High
69 | File | `/admin/edit_product.php` | High
70 | File | `/admin/edit_room.php` | High
71 | File | `/admin/edit_teacher.php` | High
72 | File | `/admin/edit_title.php?id=1` | High
73 | File | `/admin/email_setup.php` | High
74 | File | `/admin/execeditroom.php` | High
75 | File | `/Admin/facilitator.php` | High
76 | File | `/Admin/gametype.php` | High
77 | File | `/admin/getmanagerregion.php` | High
78 | File | `/admin/index.php` | High
79 | File | `/admin/lastsevendays-reg-users.php` | High
80 | File | `/admin/login` | Medium
81 | File | `/admin/login-back.php` | High
82 | File | `/admin/login.php` | High
83 | File | `/admin/manage-foreigners-ticket.php` | High
84 | File | `/admin/manage-outgoingvehicle.php` | High
85 | File | `/admin/manage-students.php` | High
86 | File | `/admin/manage-subadmins.php` | High
87 | File | `/admin/manage_seat.php` | High
88 | File | `/Admin/match.php` | High
89 | File | `/admin/media.php?action=upload&sid=0` | High
90 | File | `/Admin/mode.php` | High
91 | File | `/admin/modules/course/index.php` | High
92 | File | `/admin/modules/student/index.php` | High
93 | File | `/admin/modules/subject/index.php` | High
94 | File | `/admin/new-requests.php` | High
95 | File | `/Admin/NewsReport.php` | High
96 | File | `/admin/operation/paid.php` | High
97 | File | `/admin/operation/user.php` | High
98 | File | `/admin/operations/booking.php` | High
99 | File | `/admin/operations/currency.php` | High
100 | File | `/admin/operations/packages.php` | High
101 | File | `/admin/operations/payment.php` | High
102 | File | `/admin/operations/tax.php` | High
103 | File | `/admin/operations/travellers.php` | High
104 | File | `/admin/options/update` | High
105 | File | `/admin/page-login.php` | High
106 | File | `/admin/patient-search.php` | High
107 | File | `/admin/positions.php` | High
108 | File | `/admin/product.php` | High
109 | File | `/admin/product/edit/` | High
110 | File | `/admin/productadd_back.php` | High
111 | File | `/admin/profit_report.php` | High
112 | File | `/admin/reg-users.php` | High
113 | File | `/Admin/resultdetails.php` | High
114 | File | `/admin/role/list` | High
115 | File | `/admin/save_airlines.php` | High
116 | File | `/admin/search-appointment.php` | High
117 | File | `/admin/sensitive_word/list` | High
118 | File | `/admin/services/manage.php` | High
119 | File | `/admin/session.php` | High
120 | File | `/admin/slide.php` | High
121 | File | `/Admin/sporttype.php` | High
122 | File | `/admin/storage/delete` | High
123 | File | `/admin/store/edit/` | High
124 | File | `/admin/student-history.php` | High
125 | File | `/admin/student-registration.php` | High
126 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
127 | File | `/admin/topic/list` | High
128 | File | `/Admin/tournament_details.php` | High
129 | File | `/admin/update_s1.php` | High
130 | File | `/admin/update_s2.php` | High
131 | File | `/admin/update_s3.php` | High
132 | File | `/admin/update_s7.php` | High
133 | File | `/Admin/User.php` | High
134 | File | `/admin/user/list` | High
135 | File | `/admin/userlist.php` | High
136 | File | `/admin/view_all_posts.php` | High
137 | File | `/admin/violation_add.php?id=2` | High
138 | File | `/admin/voters_add.php` | High
139 | File | `/admin/voters_delete.php` | High
140 | File | `/administrator/wew.php` | High
141 | File | `/adminlogin.php` | High
142 | File | `/admin_members.php?ac=editsave` | High
143 | File | `/adposition/queryAll` | High
144 | File | `/advancesearch.php` | High
145 | File | `/ajax.php` | Medium
146 | File | `/ajax.php?action=calculate_payroll` | High
147 | File | `/ajax.php?action=delete_borrower` | High
148 | File | `/ajax.php?action=delete_plan` | High
149 | File | `/ajax.php?action=save_borrower` | High
150 | File | `/ajax.php?action=save_loan_type` | High
151 | File | `/ajax.php?action=save_payment` | High
152 | File | `/ajax.php?action=save_plan` | High
153 | File | `/ajax/updateProfile.php` | High
154 | File | `/ajx.php` | Medium
155 | File | `/allocated_rooms.php` | High
156 | File | `/Android/data/com.myairtelapp/files/` | High
157 | ... | ... | ...

There are 1395 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/alchimist-offensive-framework/
* https://gblogs.cisco.com/jp/2022/10/talos-alchimist-offensive-framework/
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/10/alchimist-offensive-framework.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
