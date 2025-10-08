# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
3 | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/account.php?q=quiz&step=2` | High
3 | File | `/Account/EditProfile` | High
4 | File | `/activation.php` | High
5 | File | `/add-phlebotomist.php` | High
6 | File | `/add-table.php` | High
7 | File | `/addbill.php` | Medium
8 | File | `/addproduct.php` | High
9 | File | `/adicionar-cliente.php` | High
10 | File | `/admin#themes` | High
11 | File | `/admin-inbox.php` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=system_info` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/about_edit.php?action=modify` | High
16 | File | `/admin/add-customer.php` | High
17 | File | `/admin/add-foreigner-ticket.php` | High
18 | File | `/admin/add-propertytype.php` | High
19 | File | `/admin/add_cars.php` | High
20 | File | `/admin/add_subject.php` | High
21 | File | `/admin/add_vehicles.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/adminprofile.php` | High
24 | File | `/admin/ajax.php?action=login` | High
25 | File | `/admin/ajax_product.php` | High
26 | File | `/admin/app/product.php` | High
27 | File | `/admin/booktime.php` | High
28 | File | `/admin/candidates_add.php` | High
29 | File | `/admin/chatroom.php` | High
30 | File | `/admin/cmsTagType/save` | High
31 | File | `/admin/complaint-search.php` | High
32 | File | `/admin/contactus.php` | High
33 | File | `/admin/core/update_student.php` | High
34 | File | `/admin/course_action.php` | High
35 | File | `/admin/delete-user.php` | High
36 | File | `/admin/disapprove_user.php` | High
37 | File | `/admin/doctor-specilization.php` | High
38 | File | `/admin/edit-doctor.php` | High
39 | File | `/admin/edit-nurse.php` | High
40 | File | `/admin/edit-services.php` | High
41 | File | `/admin/edit-teacher-detail.php` | High
42 | File | `/admin/editempeducation.php` | High
43 | File | `/admin/edit_room.php` | High
44 | File | `/admin/email_setup.php` | High
45 | File | `/admin/expense_report.php` | High
46 | File | `/admin/getallarticleinfo` | High
47 | File | `/admin/index.php` | High
48 | File | `/admin/insert-product.php` | High
49 | File | `/admin/link.php` | High
50 | File | `/admin/login.php` | High
51 | File | `/admin/manage-foreigners-ticket.php` | High
52 | File | `/admin/manage-services.php` | High
53 | File | `/admin/network/ajax_getChannelList` | High
54 | File | `/admin/network/wifi_schedule` | High
55 | File | `/admin/newsletter.php` | High
56 | File | `/admin/operations/expense_category.php` | High
57 | File | `/admin/operations/tax.php` | High
58 | File | `/admin/options/update` | High
59 | File | `/admin/orders/update_status.php` | High
60 | File | `/admin/page-login.php` | High
61 | File | `/admin/pages/student-print.php` | High
62 | File | `/admin/pass-bwdates-report.php` | High
63 | File | `/admin/print1.php` | High
64 | File | `/admin/profile.php` | High
65 | File | `/admin/request-received-bydonar.php` | High
66 | File | `/admin/role/list` | High
67 | File | `/admin/search-appointment.php` | High
68 | File | `/admin/search-directory.php` | High
69 | File | `/admin/search-invoices.php` | High
70 | File | `/admin/sign/out` | High
71 | File | `/admin/store.php` | High
72 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
73 | File | `/admin/tags/save` | High
74 | File | `/admin/update_room.php` | High
75 | File | `/admin/update_s7.php` | High
76 | File | `/admin/user/list` | High
77 | File | `/admin/userlist.php` | High
78 | File | `/admin/view-foreigner-ticket.php` | High
79 | File | `/admin/view-normal-ticket.php` | High
80 | File | `/adms/admin/?page=user/manage_user` | High
81 | File | `/adms/admin/?page=vehicles/view_transaction` | High
82 | File | `/ajax.php?action=save_category` | High
83 | File | `/alunos/search_autocomplete` | High
84 | File | `/api/admin/system/store/order/list` | High
85 | File | `/api/article/del` | High
86 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
87 | File | `/api/upload` | Medium
88 | File | `/api/user` | Medium
89 | File | `/api/v1/attack/token` | High
90 | File | `/Applications/Endurance.app/Contents/Library/LaunchServices/com.MagnetismStudios.endurance.helper` | High
91 | File | `/Applications/Steal/main.cpp` | High
92 | File | `/apps/meteor/app/irc/server/servers/RFC2813/parseMessage.js` | High
93 | File | `/App_Resource/UEditor/server/upload.aspx` | High
94 | File | `/auth/info` | Medium
95 | File | `/auth/list_projects` | High
96 | File | `/BBfile/Blood/o+.php` | High
97 | File | `/bill/add_bill.php` | High
98 | File | `/boafrm/formMapDel` | High
99 | File | `/boafrm/formMapDelDevice` | High
100 | File | `/boafrm/formNtp` | High
101 | File | `/boafrm/formTmultiAP` | High
102 | File | `/boat/login.php` | High
103 | File | `/booking/show_bookings/` | High
104 | File | `/bookingconfirm.php` | High
105 | File | `/book_car.php` | High
106 | File | `/bsc_lan.php` | Medium
107 | File | `/bwdates-report-result.php` | High
108 | File | `/cancelbookingpatient.php` | High
109 | File | `/cart/index.php` | High
110 | File | `/cgi-bin/cstecgi.cgi` | High
111 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
112 | File | `/cgi-bin/nas_sharing.cgi` | High
113 | File | `/cgi-bin/wireless.cgi` | High
114 | File | `/change-password.php` | High
115 | File | `/check_availability.php` | High
116 | File | `/classes/Master.php?f=delete_category` | High
117 | File | `/classes/Master.php?f=delete_reminder` | High
118 | File | `/classes/Master.php? f=save_medicine` | High
119 | File | `/classes/Master.php?f=save_sub_category` | High
120 | File | `/clients` | Medium
121 | ... | ... | ...

There are 1075 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
