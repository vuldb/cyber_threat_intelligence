# Chaos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chaos](https://vuldb.com/?actor.chaos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chaos](https://vuldb.com/?actor.chaos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chaos:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chaos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.82.253.69](https://vuldb.com/?ip.1.82.253.69) | - | - | High
2 | [3.120.164.69](https://vuldb.com/?ip.3.120.164.69) | chaos.fk0.name | - | High
3 | [5.180.44.53](https://vuldb.com/?ip.5.180.44.53) | 53.44-180-5.rdns.scalabledns.com | - | High
4 | [8.134.85.229](https://vuldb.com/?ip.8.134.85.229) | - | - | High
5 | [8.134.88.86](https://vuldb.com/?ip.8.134.88.86) | - | - | High
6 | [8.138.47.191](https://vuldb.com/?ip.8.138.47.191) | - | - | High
7 | [8.139.6.64](https://vuldb.com/?ip.8.139.6.64) | - | - | High
8 | [8.140.20.239](https://vuldb.com/?ip.8.140.20.239) | - | - | High
9 | [8.141.114.161](https://vuldb.com/?ip.8.141.114.161) | - | - | High
10 | [8.141.114.174](https://vuldb.com/?ip.8.141.114.174) | - | - | High
11 | [8.141.115.230](https://vuldb.com/?ip.8.141.115.230) | - | - | High
12 | [8.156.73.92](https://vuldb.com/?ip.8.156.73.92) | - | - | High
13 | [14.241.100.39](https://vuldb.com/?ip.14.241.100.39) | static.vnpt.vn | - | High
14 | [20.90.110.121](https://vuldb.com/?ip.20.90.110.121) | - | - | High
15 | [20.187.95.103](https://vuldb.com/?ip.20.187.95.103) | - | - | High
16 | [23.88.62.122](https://vuldb.com/?ip.23.88.62.122) | static.122.62.88.23.clients.your-server.de | - | High
17 | [23.224.132.58](https://vuldb.com/?ip.23.224.132.58) | - | - | High
18 | [23.225.194.65](https://vuldb.com/?ip.23.225.194.65) | - | - | High
19 | [23.226.76.122](https://vuldb.com/?ip.23.226.76.122) | we.love.servers.at.ioflood.net | - | High
20 | [34.58.136.79](https://vuldb.com/?ip.34.58.136.79) | 79.136.58.34.bc.googleusercontent.com | - | Medium
21 | [34.64.111.49](https://vuldb.com/?ip.34.64.111.49) | 49.111.64.34.bc.googleusercontent.com | - | Medium
22 | [34.79.229.30](https://vuldb.com/?ip.34.79.229.30) | 30.229.79.34.bc.googleusercontent.com | - | Medium
23 | [34.141.142.28](https://vuldb.com/?ip.34.141.142.28) | 28.142.141.34.bc.googleusercontent.com | - | Medium
24 | [38.55.138.146](https://vuldb.com/?ip.38.55.138.146) | - | - | High
25 | [38.180.142.165](https://vuldb.com/?ip.38.180.142.165) | - | - | High
26 | ... | ... | ... | ...

There are 99 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chaos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chaos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/abs.php` | Medium
3 | File | `/Account/login.php` | High
4 | File | `/adding-exec.php` | High
5 | File | `/admin#permissions` | High
6 | File | `/admin-api/mp/material/upload-permanent` | High
7 | File | `/admin-manage-user.php` | High
8 | File | `/admin/` | Low
9 | File | `/admin/aboutPost.php` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/admin/action/edit_chicken.php` | High
12 | File | `/admin/add-admin.php` | High
13 | File | `/admin/add-art-medium.php` | High
14 | File | `/admin/admin-add-employee.php` | High
15 | File | `/admin/admin-profile.php` | High
16 | File | `/admin/ajax.php?action=login` | High
17 | File | `/admin/ajax.php?action=save_settings` | High
18 | File | `/admin/appointment.php` | High
19 | File | `/admin/approve.php` | High
20 | File | `/admin/archives/edit` | High
21 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
22 | File | `/admin/attendance_action.php` | High
23 | File | `/admin/bwdates-report-details.php` | High
24 | File | `/Admin/Category.php` | High
25 | File | `/admin/category/cate-edit-run.php` | High
26 | File | `/admin/change-image.php` | High
27 | File | `/admin/comment.php` | High
28 | File | `/admin/CopyadminPost.php` | High
29 | File | `/Admin/CustomerReport.php` | High
30 | File | `/admin/delete-appointment.php` | High
31 | File | `/admin/delete_account.php` | High
32 | File | `/admin/del_service.php` | High
33 | File | `/admin/doctor-specilization.php` | High
34 | File | `/admin/edit-boat.php` | High
35 | File | `/admin/edit-brand.php` | High
36 | File | `/admin/edit-card-detail.php` | High
37 | File | `/admin/edit-services.php` | High
38 | File | `/admin/edit-teacher-info.php` | High
39 | File | `/admin/edit_customer.php` | High
40 | File | `/admin/edit_product.php` | High
41 | File | `/admin/edit_state.php` | High
42 | File | `/admin/edit_subject.php` | High
43 | File | `/admin/File/pictureUpload` | High
44 | File | `/admin/general-setting` | High
45 | File | `/admin/index.php` | High
46 | File | `/admin/index.php/news/edit` | High
47 | File | `/admin/list_localuser.php` | High
48 | File | `/Admin/login.php` | High
49 | File | `/admin/login.php` | High
50 | File | `/admin/manage-art-medium.php` | High
51 | File | `/admin/manage-services.php` | High
52 | File | `/admin/manage-students.php` | High
53 | File | `/admin/member_save.php` | High
54 | File | `/admin/pages/` | High
55 | File | `/admin/sales-reports-detail.php` | High
56 | File | `/admin/search-maid.php` | High
57 | File | `/admin/students/view_student.php` | High
58 | File | `/admin/sys_sql_query.php` | High
59 | File | `/admin/tag.php` | High
60 | File | `/admin/update-rooms.php` | High
61 | File | `/admin/updateorder.php` | High
62 | File | `/admin/view-request.php` | High
63 | File | `/admin/view-user-queries.php` | High
64 | File | `/admin/voters_row.php` | High
65 | File | `/AGE0000700/GetHorariosDoDia?idespec=0&idproced=1103&data=2025-02-25+19%3A25&agserv=0&convenio=1&localatend=1&idplano=5&pesfis=01&idprofissional=0&target=.horarios--dia--d0&_=1739371223797` | High
66 | File | `/ajax.php?action=delete_member` | High
67 | File | `/ajax.php?action=login` | High
68 | File | `/ajax.php?action=save_category` | High
69 | File | `/ajax.php?action=save_member` | High
70 | File | `/allocate_room.php` | High
71 | File | `/api.php` | Medium
72 | File | `/api/blade-system/menu/list?updatexml` | High
73 | File | `/api/blade-user/submit` | High
74 | File | `/api/DataDictionary/GetItemList` | High
75 | File | `/api/user` | Medium
76 | File | `/api/user/update` | High
77 | File | `/api/v2/open/tablesInfo` | High
78 | File | `/api/wizard/setLanguage` | High
79 | File | `/App/Core/Extend/Function/ydLib.php` | High
80 | File | `/application/index/controller/File.php` | High
81 | File | `/appointment-history.php` | High
82 | File | `/att_add.php` | Medium
83 | File | `/auth.asp` | Medium
84 | File | `/backend/doc/his_doc_update-account.php` | High
85 | File | `/backups/` | Medium
86 | File | `/bilal final/edit_stud.php` | High
87 | File | `/birthing_print.php` | High
88 | File | `/blog` | Low
89 | File | `/Bloodgroop_process.php` | High
90 | File | `/boafrm/formDMZ` | High
91 | File | `/boafrm/formFilter` | High
92 | File | `/boafrm/formIpQoS` | High
93 | File | `/boafrm/formMultiAP` | High
94 | File | `/boafrm/formPortFw` | High
95 | File | `/boafrm/formSetLg` | High
96 | File | `/boafrm/formStats` | High
97 | File | `/boafrm/formSysCmd` | High
98 | File | `/boafrm/formSysLog` | High
99 | File | `/boafrm/formTmultiAP` | High
100 | File | `/boafrm/formWirelessTbl` | High
101 | File | `/boat-details.php` | High
102 | File | `/bwdates-report-result.php` | High
103 | File | `/category.php` | High
104 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
105 | ... | ... | ...

There are 929 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloudsecurityalliance.org/blog/2023/06/15/chaos-malware-quietly-evolves-persistence-and-evasion-techniques/
* https://community.blueliv.com/#!/s/63353bd382df413eb5359c9b
* https://search.censys.io/hosts/1.82.253.69
* https://search.censys.io/hosts/3.120.164.69
* https://search.censys.io/hosts/8.134.85.229
* https://search.censys.io/hosts/8.134.88.86
* https://search.censys.io/hosts/8.138.47.191
* https://search.censys.io/hosts/8.139.6.64
* https://search.censys.io/hosts/8.140.20.239
* https://search.censys.io/hosts/8.141.114.161
* https://search.censys.io/hosts/8.141.114.174
* https://search.censys.io/hosts/8.141.115.230
* https://search.censys.io/hosts/8.156.73.92
* https://search.censys.io/hosts/14.241.100.39
* https://search.censys.io/hosts/23.88.62.122
* https://search.censys.io/hosts/34.58.136.79
* https://search.censys.io/hosts/34.64.111.49
* https://search.censys.io/hosts/34.79.229.30
* https://search.censys.io/hosts/34.141.142.28
* https://search.censys.io/hosts/38.55.138.146
* https://search.censys.io/hosts/38.180.142.165
* https://search.censys.io/hosts/39.106.3.184
* https://search.censys.io/hosts/43.131.244.144
* https://search.censys.io/hosts/45.14.185.146
* https://search.censys.io/hosts/45.76.80.199
* https://search.censys.io/hosts/46.10.180.67
* https://search.censys.io/hosts/47.76.24.178
* https://search.censys.io/hosts/47.96.164.62
* https://search.censys.io/hosts/47.97.178.157
* https://search.censys.io/hosts/47.103.98.239
* https://search.censys.io/hosts/47.108.160.69
* https://search.censys.io/hosts/47.108.221.225
* https://search.censys.io/hosts/47.108.249.44
* https://search.censys.io/hosts/47.109.40.109
* https://search.censys.io/hosts/47.110.132.52
* https://search.censys.io/hosts/47.110.144.223
* https://search.censys.io/hosts/47.113.145.151
* https://search.censys.io/hosts/50.193.250.21
* https://search.censys.io/hosts/52.0.83.31
* https://search.censys.io/hosts/52.87.248.40
* https://search.censys.io/hosts/52.221.213.139
* https://search.censys.io/hosts/57.128.76.137
* https://search.censys.io/hosts/58.215.146.108
* https://search.censys.io/hosts/64.227.71.105
* https://search.censys.io/hosts/79.137.51.184
* https://search.censys.io/hosts/81.71.155.224
* https://search.censys.io/hosts/82.180.162.193
* https://search.censys.io/hosts/89.42.88.41
* https://search.censys.io/hosts/93.90.59.79
* https://search.censys.io/hosts/94.21.157.169
* https://search.censys.io/hosts/94.74.106.10
* https://search.censys.io/hosts/94.154.172.175
* https://search.censys.io/hosts/95.216.184.3
* https://search.censys.io/hosts/100.25.226.74
* https://search.censys.io/hosts/101.37.12.180
* https://search.censys.io/hosts/103.56.19.194
* https://search.censys.io/hosts/104.156.255.27
* https://search.censys.io/hosts/107.150.0.237
* https://search.censys.io/hosts/108.181.155.15
* https://search.censys.io/hosts/113.106.204.39
* https://search.censys.io/hosts/113.106.204.68
* https://search.censys.io/hosts/113.106.204.206
* https://search.censys.io/hosts/116.203.230.194
* https://search.censys.io/hosts/117.20.108.15
* https://search.censys.io/hosts/118.184.186.43
* https://search.censys.io/hosts/118.184.187.166
* https://search.censys.io/hosts/118.184.187.167
* https://search.censys.io/hosts/118.184.187.174
* https://search.censys.io/hosts/120.26.48.72
* https://search.censys.io/hosts/121.9.235.20
* https://search.censys.io/hosts/121.9.235.32
* https://search.censys.io/hosts/121.41.30.139
* https://search.censys.io/hosts/122.143.2.28
* https://search.censys.io/hosts/130.61.253.246
* https://search.censys.io/hosts/138.197.229.229
* https://search.censys.io/hosts/141.147.108.142
* https://search.censys.io/hosts/158.255.2.21
* https://search.censys.io/hosts/161.97.117.117
* https://search.censys.io/hosts/168.100.10.177
* https://search.censys.io/hosts/172.105.190.211
* https://search.censys.io/hosts/178.217.98.23
* https://search.censys.io/hosts/185.196.8.218
* https://search.censys.io/hosts/185.234.65.107
* https://search.censys.io/hosts/193.5.65.117
* https://search.censys.io/hosts/209.74.77.200
* https://search.censys.io/hosts/217.154.22.37
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=67.205.163.232
* https://tracker.viriback.com/index.php?q=194.87.216.75
* https://urlscan.io/result/c5c82047-0a7e-48ba-93f3-523f04671fa0

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
