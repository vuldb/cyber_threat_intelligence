# XtremeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XtremeRAT](https://vuldb.com/?actor.xtremerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xtremerat](https://vuldb.com/?actor.xtremerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XtremeRAT:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XtremeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.81.154.116](https://vuldb.com/?ip.2.81.154.116) | bl20-154-116.dsl.telepac.pt | - | High
2 | [5.79.71.205](https://vuldb.com/?ip.5.79.71.205) | - | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
5 | [20.72.235.82](https://vuldb.com/?ip.20.72.235.82) | - | - | High
6 | [23.7.178.157](https://vuldb.com/?ip.23.7.178.157) | a23-7-178-157.deploy.static.akamaitechnologies.com | - | High
7 | [23.32.81.118](https://vuldb.com/?ip.23.32.81.118) | a23-32-81-118.deploy.static.akamaitechnologies.com | - | High
8 | [23.62.7.138](https://vuldb.com/?ip.23.62.7.138) | a23-62-7-138.deploy.static.akamaitechnologies.com | - | High
9 | [23.62.230.159](https://vuldb.com/?ip.23.62.230.159) | a23-62-230-159.deploy.static.akamaitechnologies.com | - | High
10 | [23.202.2.105](https://vuldb.com/?ip.23.202.2.105) | a23-202-2-105.deploy.static.akamaitechnologies.com | - | High
11 | [23.202.81.150](https://vuldb.com/?ip.23.202.81.150) | a23-202-81-150.deploy.static.akamaitechnologies.com | - | High
12 | [52.8.126.80](https://vuldb.com/?ip.52.8.126.80) | ec2-52-8-126-80.us-west-1.compute.amazonaws.com | - | Medium
13 | [62.90.21.54](https://vuldb.com/?ip.62.90.21.54) | 62-90-21-54.barak.net.il | - | High
14 | [64.29.151.221](https://vuldb.com/?ip.64.29.151.221) | hostedc40.carrierzone.com | - | High
15 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
16 | ... | ... | ... | ...

There are 61 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XtremeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XtremeRAT. This data is unique as it uses our predictive model for actor profiling.

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
50 | File | `/admin/post/edit/` | High
51 | File | `/admin/process_category_edit.php` | High
52 | File | `/admin/product-update.php` | High
53 | File | `/admin/profile.php` | High
54 | File | `/admin/room.php` | High
55 | File | `/admin/search-maid.php` | High
56 | File | `/admin/search-report-details.php` | High
57 | File | `/admin/sou.php` | High
58 | File | `/admin/student-history.php` | High
59 | File | `/admin/student.php` | High
60 | File | `/admin/students/manage.php` | High
61 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
62 | File | `/admin/update_room.php` | High
63 | File | `/admin/update_s8.php` | High
64 | File | `/admin/upload/img` | High
65 | File | `/admin/users_photo.php` | High
66 | File | `/admin/view_reserved.php` | High
67 | File | `/admin/View_user.php` | High
68 | File | `/adminPage/main/upload` | High
69 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
70 | File | `/admin_info.php` | High
71 | File | `/ajax.php?action=delete_allowances` | High
72 | File | `/ajax.php?action=login` | High
73 | File | `/ajax.php?action=save_package` | High
74 | File | `/all_student.php` | High
75 | File | `/alphaware/summary.php` | High
76 | File | `/api/database/testConnect` | High
77 | File | `/api/process.php` | High
78 | File | `/api/request-token` | High
79 | File | `/api/role` | Medium
80 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
81 | File | `/api/system/dept/update` | High
82 | File | `/api/v1/attack/token` | High
83 | File | `/app/admin/controller/Upload.php` | High
84 | File | `/app/Http/Controllers/ImageController.php` | High
85 | File | `/application/controller/Transaki.php` | High
86 | File | `/application/index/controller/Unity.php` | High
87 | File | `/Applications/Content%20Manager/Execute.aspx?cmd=convert&mode=HTML` | High
88 | File | `/apps/system/api/user.go` | High
89 | File | `/author/list?limit=10&offset=0&order=desc` | High
90 | File | `/b2b-supermarket/shopping-cart` | High
91 | File | `/backend/doc/his_doc_update-account.php` | High
92 | File | `/boafrm/formFilter` | High
93 | File | `/boafrm/formRoute` | High
94 | File | `/boafrm/formStaticDHCP` | High
95 | File | `/boafrm/formSysLog` | High
96 | File | `/boafrm/formWsc` | High
97 | File | `/booking/show_bookings/` | High
98 | File | `/cancelbookingpatient.php` | High
99 | File | `/Car_Rental/booking.php` | High
100 | File | `/cbi_addcert.htm` | High
101 | File | `/cfgFile/1/download` | High
102 | File | `/cgAutoListController.do?datagrid` | High
103 | File | `/cgi-bin/cstecgi.cgi` | High
104 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
105 | File | `/cgi-bin/ExportLogs.sh` | High
106 | File | `/cgi-bin/luci/admin/opsw/Dual_freq_un_apple` | High
107 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
108 | File | `/cgi-bin/nas_sharing.cgi` | High
109 | File | `/cgi-bin/photocenter_mgr.cgi` | High
110 | File | `/cgi-bin/touchlist_sync.cgi` | High
111 | ... | ... | ...

There are 987 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/07/threat-roundup-0712-0719.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0719-0726.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0424-0501.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0225-0304.html
* https://blog.talosintelligence.com/2022/05/threat-roundup-0429-0506.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0819-0826.html
* https://blog.talosintelligence.com/threat-roundup-0127-0203/
* https://blog.talosintelligence.com/threat-roundup-0407-0414/
* https://blog.talosintelligence.com/threat-roundup-0428-0505/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
