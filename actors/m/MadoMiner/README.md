# MadoMiner - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MadoMiner](https://vuldb.com/?actor.madominer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.madominer](https://vuldb.com/?actor.madominer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MadoMiner:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MadoMiner.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [61.130.31.174](https://vuldb.com/?ip.61.130.31.174) | - | - | High
2 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MadoMiner_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MadoMiner. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\1E\Client\Tachyon.Performance.Metrics.exe` | High
2 | File | `/a/sys/user/save` | High
3 | File | `/Account/login.php` | High
4 | File | `/add.php` | Medium
5 | File | `/addstock.php` | High
6 | File | `/add_members.php` | High
7 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
8 | File | `/admin/` | Low
9 | File | `/admin/?page=back_order/view_bo` | High
10 | File | `/admin/?page=inventory/view_inventory&id=2` | High
11 | File | `/admin/?page=user/list` | High
12 | File | `/admin/about-us.php` | High
13 | File | `/admin/aboutus.php` | High
14 | File | `/Admin/add-admin.php` | High
15 | File | `/admin/addgiving.php` | High
16 | File | `/admin/admin-profile.php` | High
17 | File | `/admin/ajax.php?action=save_settings` | High
18 | File | `/admin/all-requests.php` | High
19 | File | `/admin/app/profile_crud.php` | High
20 | File | `/admin/approve.php` | High
21 | File | `/admin/backup/backups.php` | High
22 | File | `/admin/book_add.php` | High
23 | File | `/admin/bwdates-report-details.php` | High
24 | File | `/admin/change-password.php` | High
25 | File | `/admin/changeimage1.php` | High
26 | File | `/admin/chip/add.do` | High
27 | File | `/admin/cms_admin.php` | High
28 | File | `/admin/contact-us.php` | High
29 | File | `/admin/delete-appointment.php` | High
30 | File | `/admin/delete-row.php` | High
31 | File | `/admin/delete-session.php` | High
32 | File | `/admin/deleteroom.php` | High
33 | File | `/admin/edit-accepted-appointment.php` | High
34 | File | `/admin/edit-art-medium-detail.php` | High
35 | File | `/admin/edit-card-detail.php` | High
36 | File | `/admin/edit-guard-detail.php` | High
37 | File | `/admin/edit-pass-detail.php` | High
38 | File | `/admin/edit-subadmin.php` | High
39 | File | `/admin/editempeducation.php` | High
40 | File | `/admin/edit_product.php` | High
41 | File | `/admin/edit_user.php` | High
42 | File | `/admin/general-setting` | High
43 | File | `/admin/index.php` | High
44 | File | `/admin/manage-teams.php` | High
45 | File | `/admin/manage_movie.php` | High
46 | File | `/admin/manage_seat.php` | High
47 | File | `/admin/network/diag_traceroute6` | High
48 | File | `/admin/normal-bwdates-reports-details.php` | High
49 | File | `/admin/overtime_add.php` | High
50 | File | `/admin/plugin.php` | High
51 | File | `/admin/post/edit/` | High
52 | File | `/admin/process_category_edit.php` | High
53 | File | `/admin/product-update.php` | High
54 | File | `/admin/profile.php` | High
55 | File | `/admin/room.php` | High
56 | File | `/admin/search-maid.php` | High
57 | File | `/admin/search-report-details.php` | High
58 | File | `/admin/sou.php` | High
59 | File | `/admin/student-history.php` | High
60 | File | `/admin/student.php` | High
61 | File | `/admin/students/manage.php` | High
62 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
63 | File | `/admin/update_room.php` | High
64 | File | `/admin/update_s8.php` | High
65 | File | `/admin/upload/img` | High
66 | File | `/admin/users_photo.php` | High
67 | File | `/admin/view_reserved.php` | High
68 | File | `/admin/View_user.php` | High
69 | File | `/adminPage/main/upload` | High
70 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
71 | File | `/admin_info.php` | High
72 | File | `/ajax.php?action=delete_allowances` | High
73 | File | `/ajax.php?action=login` | High
74 | File | `/ajax.php?action=save_package` | High
75 | File | `/all_student.php` | High
76 | File | `/alphaware/summary.php` | High
77 | File | `/api/database/testConnect` | High
78 | File | `/api/process.php` | High
79 | File | `/api/request-token` | High
80 | File | `/api/role` | Medium
81 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
82 | File | `/api/system/dept/update` | High
83 | File | `/api/v1/attack/token` | High
84 | File | `/app/admin/controller/Upload.php` | High
85 | File | `/app/Http/Controllers/ImageController.php` | High
86 | File | `/application/controller/Transaki.php` | High
87 | File | `/application/index/controller/Unity.php` | High
88 | File | `/Applications/Content%20Manager/Execute.aspx?cmd=convert&mode=HTML` | High
89 | File | `/apps/system/api/user.go` | High
90 | File | `/author/list?limit=10&offset=0&order=desc` | High
91 | File | `/b2b-supermarket/shopping-cart` | High
92 | File | `/backend/doc/his_doc_update-account.php` | High
93 | File | `/birthing_pending.php` | High
94 | File | `/boafrm/formFilter` | High
95 | File | `/boafrm/formRoute` | High
96 | File | `/boafrm/formStaticDHCP` | High
97 | File | `/boafrm/formSysLog` | High
98 | File | `/boafrm/formWsc` | High
99 | File | `/booking/show_bookings/` | High
100 | File | `/cancelbookingpatient.php` | High
101 | File | `/Car_Rental/booking.php` | High
102 | File | `/cbi_addcert.htm` | High
103 | File | `/cfgFile/1/download` | High
104 | File | `/cgAutoListController.do?datagrid` | High
105 | File | `/cgi-bin/cstecgi.cgi` | High
106 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
107 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
108 | File | `/cgi-bin/ExportLogs.sh` | High
109 | File | `/cgi-bin/luci/admin/opsw/Dual_freq_un_apple` | High
110 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
111 | File | `/cgi-bin/nas_sharing.cgi` | High
112 | ... | ... | ...

There are 990 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
