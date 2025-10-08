# Kraken 2.0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kraken 2.0](https://vuldb.com/?actor.kraken_2.0). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kraken_2.0](https://vuldb.com/?actor.kraken_2.0)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kraken 2.0:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kraken 2.0.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kraken 2.0_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kraken 2.0. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\1E\Client\Tachyon.Performance.Metrics.exe` | High
2 | File | `/a/sys/user/save` | High
3 | File | `/Account/login.php` | High
4 | File | `/add.php` | Medium
5 | File | `/add_members.php` | High
6 | File | `/admin/?page=back_order/view_bo` | High
7 | File | `/admin/?page=inventory/view_inventory&id=2` | High
8 | File | `/admin/?page=user/list` | High
9 | File | `/admin/about-us.php` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/admin/addgiving.php` | High
12 | File | `/admin/admin-profile.php` | High
13 | File | `/admin/ajax.php?action=save_settings` | High
14 | File | `/admin/all-requests.php` | High
15 | File | `/admin/app/profile_crud.php` | High
16 | File | `/admin/approve.php` | High
17 | File | `/admin/book_add.php` | High
18 | File | `/admin/bwdates-passreports-details.php` | High
19 | File | `/admin/bwdates-report-details.php` | High
20 | File | `/admin/changeimage1.php` | High
21 | File | `/admin/chip/add.do` | High
22 | File | `/admin/cms_admin.php` | High
23 | File | `/admin/delete-appointment.php` | High
24 | File | `/admin/delete-session.php` | High
25 | File | `/admin/deleteroom.php` | High
26 | File | `/admin/edit-accepted-appointment.php` | High
27 | File | `/admin/edit-art-medium-detail.php` | High
28 | File | `/admin/edit-card-detail.php` | High
29 | File | `/admin/edit-guard-detail.php` | High
30 | File | `/admin/edit-subadmin.php` | High
31 | File | `/admin/editempeducation.php` | High
32 | File | `/admin/edit_product.php` | High
33 | File | `/admin/edit_user.php` | High
34 | File | `/admin/general-setting` | High
35 | File | `/admin/index.php` | High
36 | File | `/admin/manage-teams.php` | High
37 | File | `/admin/manage_movie.php` | High
38 | File | `/admin/manage_seat.php` | High
39 | File | `/admin/network/diag_traceroute6` | High
40 | File | `/admin/normal-bwdates-reports-details.php` | High
41 | File | `/admin/post/edit/` | High
42 | File | `/admin/process_category_edit.php` | High
43 | File | `/admin/product-update.php` | High
44 | File | `/admin/profile.php` | High
45 | File | `/admin/room.php` | High
46 | File | `/admin/search-report-details.php` | High
47 | File | `/admin/sou.php` | High
48 | File | `/admin/student-history.php` | High
49 | File | `/admin/student.php` | High
50 | File | `/admin/students/manage.php` | High
51 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
52 | File | `/admin/update_room.php` | High
53 | File | `/admin/update_s8.php` | High
54 | File | `/admin/upload/img` | High
55 | File | `/admin/view_reserved.php` | High
56 | File | `/admin/View_user.php` | High
57 | File | `/adminPage/main/upload` | High
58 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
59 | File | `/admin_info.php` | High
60 | File | `/admin_system/api.php` | High
61 | File | `/ajax.php?action=delete_allowances` | High
62 | File | `/ajax.php?action=login` | High
63 | File | `/all_student.php` | High
64 | File | `/alphaware/summary.php` | High
65 | File | `/api/process.php` | High
66 | File | `/api/request-token` | High
67 | File | `/api/role` | Medium
68 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
69 | File | `/api/system/dept/update` | High
70 | File | `/api/v1/attack/token` | High
71 | File | `/app/Http/Controllers/ImageController.php` | High
72 | File | `/application/controller/Transaki.php` | High
73 | File | `/application/index/controller/Unity.php` | High
74 | File | `/Applications/Content%20Manager/Execute.aspx?cmd=convert&mode=HTML` | High
75 | File | `/apps/system/api/user.go` | High
76 | File | `/author/list?limit=10&offset=0&order=desc` | High
77 | File | `/b2b-supermarket/shopping-cart` | High
78 | File | `/backend/doc/his_doc_update-account.php` | High
79 | File | `/boafrm/formFilter` | High
80 | File | `/boafrm/formRoute` | High
81 | File | `/boafrm/formStaticDHCP` | High
82 | File | `/boafrm/formSysLog` | High
83 | File | `/booking/show_bookings/` | High
84 | File | `/cancelbookingpatient.php` | High
85 | File | `/Car_Rental/booking.php` | High
86 | File | `/categoryvalue.php` | High
87 | File | `/cbi_addcert.htm` | High
88 | File | `/cgAutoListController.do?datagrid` | High
89 | File | `/cgi-bin/cstecgi.cgi` | High
90 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
91 | File | `/cgi-bin/ExportLogs.sh` | High
92 | File | `/cgi-bin/luci/admin/opsw/Dual_freq_un_apple` | High
93 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
94 | File | `/cgi-bin/nas_sharing.cgi` | High
95 | File | `/cgi-bin/nightled.cgi` | High
96 | File | `/cgi-bin/touchlist_sync.cgi` | High
97 | File | `/cgi-bin/wlogin.cgi` | High
98 | File | `/changeUsername.php` | High
99 | File | `/classes/Master.php?f=delete_schedule` | High
100 | File | `/classes/Master.php?f=save_inquiry` | High
101 | ... | ... | ...

There are 891 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
