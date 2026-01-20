# xmrig - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xmrig](https://vuldb.com/?actor.xmrig). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xmrig](https://vuldb.com/?actor.xmrig)

## Campaigns

The following _campaigns_ are known and can be associated with xmrig:

* CVE-2021-44228
* CVE-2025-31324
* SeleniumGreed

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xmrig:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [SH](https://vuldb.com/?country.sh)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xmrig.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [18.230.118.147](https://vuldb.com/?ip.18.230.118.147) | ec2-18-230-118-147.sa-east-1.compute.amazonaws.com | - | Medium
2 | [23.95.123.5](https://vuldb.com/?ip.23.95.123.5) | 23-95-123-5-host.colocrossing.com | CVE-2025-31324 | High
3 | [23.132.164.155](https://vuldb.com/?ip.23.132.164.155) | - | - | High
4 | [27.36.82.56](https://vuldb.com/?ip.27.36.82.56) | - | - | High
5 | [37.114.37.82](https://vuldb.com/?ip.37.114.37.82) | 82.37.114.37.in-addr.arpa | - | High
6 | [43.163.195.252](https://vuldb.com/?ip.43.163.195.252) | - | - | High
7 | [45.86.86.221](https://vuldb.com/?ip.45.86.86.221) | shbzt | - | High
8 | [45.95.147.236](https://vuldb.com/?ip.45.95.147.236) | protect.privacy | - | High
9 | [45.138.16.193](https://vuldb.com/?ip.45.138.16.193) | - | - | High
10 | [45.204.197.103](https://vuldb.com/?ip.45.204.197.103) | - | - | High
11 | [45.204.214.219](https://vuldb.com/?ip.45.204.214.219) | - | - | High
12 | [47.105.158.116](https://vuldb.com/?ip.47.105.158.116) | - | - | High
13 | [47.109.69.229](https://vuldb.com/?ip.47.109.69.229) | - | - | High
14 | [51.195.211.231](https://vuldb.com/?ip.51.195.211.231) | ip231.ip-51-195-211.eu | - | High
15 | [59.36.188.253](https://vuldb.com/?ip.59.36.188.253) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xmrig_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xmrig. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/action.php` | Medium
4 | File | `/action/upload_file` | High
5 | File | `/actuator` | Medium
6 | File | `/add-notes.php` | High
7 | File | `/add-phlebotomist.php` | High
8 | File | `/addcategory.php` | High
9 | File | `/addelivery.php` | High
10 | File | `/adding-exec.php` | High
11 | File | `/addmem.php` | Medium
12 | File | `/addstock.php` | High
13 | File | `/add_achievement_details.php` | High
14 | File | `/admin#article/edit?id=2` | High
15 | File | `/admin#themes` | High
16 | File | `/admin-inbox.php` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?page=categories/view_category` | High
19 | File | `/admin/?page=state` | High
20 | File | `/admin/about-us.php` | High
21 | File | `/admin/aboutus.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/adminprofile.php` | High
24 | File | `/admin/admin_action.php` | High
25 | File | `/admin/admin_members.php?ac=search` | High
26 | File | `/admin/admin_running.php` | High
27 | File | `/admin/ajax.php?action=login` | High
28 | File | `/admin/ajax.php?action=save_settings` | High
29 | File | `/admin/app/product.php` | High
30 | File | `/admin/app/profile_crud.php` | High
31 | File | `/admin/approve_user.php` | High
32 | File | `/admin/article/article-edit-run.php` | High
33 | File | `/admin/attendance_row.php` | High
34 | File | `/admin/auth/roles` | High
35 | File | `/admin/blogger.php?action=update_avatar` | High
36 | File | `/admin/book_row.php` | High
37 | File | `/admin/bwdates-reports-details.php` | High
38 | File | `/admin/bwdates-request-report-details.php` | High
39 | File | `/admin/checklogin.php` | High
40 | File | `/admin/check_admin_login.php` | High
41 | File | `/admin/class.php` | High
42 | File | `/admin/class.php?dowhat=modifyclass` | High
43 | File | `/admin/contactus.php` | High
44 | File | `/admin/create_product.php` | High
45 | File | `/admin/deleteuser.php` | High
46 | File | `/admin/delete_student.php` | High
47 | File | `/admin/edit-category-detail.php` | High
48 | File | `/admin/edit-customer-detailed.php` | High
49 | File | `/admin/edit-subadmin.php` | High
50 | File | `/admin/edit-teacher-detail.php` | High
51 | File | `/admin/edit-user.php` | High
52 | File | `/admin/edit_account.php` | High
53 | File | `/admin/edit_class.php` | High
54 | File | `/admin/edit_fuel.php` | High
55 | File | `/admin/edit_product.php` | High
56 | File | `/admin/edit_user.php` | High
57 | File | `/admin/index.php` | High
58 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
59 | File | `/admin/inquiries/view_details.php` | High
60 | File | `/admin/lab.php` | High
61 | File | `/admin/login.php` | High
62 | File | `/admin/maintenance/view_designation.php` | High
63 | File | `/admin/manage-normal-ticket.php` | High
64 | File | `/Admin/mode.php` | High
65 | File | `/admin/network/diag_nslookup` | High
66 | File | `/admin/network/diag_pinginterface` | High
67 | File | `/admin/normal-search.php` | High
68 | File | `/admin/operations/expense.php` | High
69 | File | `/admin/options-theme.php` | High
70 | File | `/admin/pages/student-print.php` | High
71 | File | `/admin/pass-bwdates-report.php` | High
72 | File | `/admin/password-recovery.php` | High
73 | File | `/admin/php/crud.php` | High
74 | File | `/admin/positions_row.php` | High
75 | File | `/admin/print_barcode.php` | High
76 | File | `/Admin/Proses_Edit_Akun.php` | High
77 | File | `/admin/regester.php` | High
78 | File | `/admin/request-received-bydonar.php` | High
79 | File | `/admin/robot.php` | High
80 | File | `/admin/search-booking-request.php` | High
81 | File | `/admin/search-pass.php` | High
82 | File | `/admin/search-vehicle.php` | High
83 | File | `/Admin/sporttype.php` | High
84 | File | `/admin/update-progress.php` | High
85 | File | `/admin/update-users.php` | High
86 | File | `/admin/update_s8.php` | High
87 | File | `/admin/update_user.php` | High
88 | File | `/admin/upload/authorImg/` | High
89 | File | `/Admin/user-record.php` | High
90 | File | `/admin/user.php` | High
91 | File | `/admin/v1/blog/edit` | High
92 | File | `/admin/view-appointment.php` | High
93 | File | `/admin/view-foreigner-ticket.php` | High
94 | File | `/admin/voters_row.php` | High
95 | File | `/admin/wangkan_list.php` | High
96 | File | `/admin?do=admin:user:editPost` | High
97 | File | `/admin_class.php?action=login` | High
98 | File | `/admin_topic.php?action=delall` | High
99 | File | `/ajax.php?action=delete_loan` | High
100 | File | `/ajax.php?action=save_plan` | High
101 | File | `/ajax.php?action=save_supplier` | High
102 | File | `/ajax/action.php` | High
103 | File | `/api/admin/question/edit` | High
104 | File | `/api/backend/v1/user/create` | High
105 | File | `/api/controllers/common/UploadsController.php` | High
106 | File | `/api/file/downloadUrl` | High
107 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
108 | File | `/api/system/sendWebSocketMsg` | High
109 | File | `/api/v1/login` | High
110 | File | `/api/v1/settings` | High
111 | File | `/api/wizard/networkSetup` | High
112 | File | `/app-api/v1/members/openid/` | High
113 | File | `/app/ajax/search_sales_report.php` | High
114 | File | `/app/ConfirmSmsCode` | High
115 | File | `/application/models/ApplicationDataObject.class.php` | High
116 | File | `/Applications/Steal/main.cpp` | High
117 | File | `/Auth.php` | Medium
118 | File | `/auth/user/all.api` | High
119 | File | `/backend/admin/his_admin_register_patient.php` | High
120 | File | `/bank/statements.php` | High
121 | File | `/bank/transfer.php` | High
122 | File | `/bin/httpd` | Medium
123 | File | `/biurl_grou` | Medium
124 | File | `/boafrm/formFilter` | High
125 | File | `/boafrm/formOneKeyAccessButton` | High
126 | File | `/boafrm/formParentControl` | High
127 | File | `/boafrm/formRoute` | High
128 | ... | ... | ...

There are 1132 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/5fec2efb82df413ea934b2d1
* https://cybersecuritynews.com/sysrv-botnet-google-xmrig-spreader/
* https://en.fofa.info/result?qbase64=Ym9keT0iWE1SaWciICYmIHRpdGxlPT0iSW5kZXggb2YgLyI%3D&page=2&page_size=10
* https://search.censys.io/hosts/45.138.16.193
* https://search.censys.io/hosts/45.204.197.103
* https://search.censys.io/hosts/45.204.214.219
* https://search.censys.io/hosts/65.49.232.44
* https://search.censys.io/hosts/89.221.225.7
* https://search.censys.io/hosts/104.233.210.195
* https://search.censys.io/hosts/107.172.86.208
* https://search.censys.io/hosts/115.190.22.7
* https://search.censys.io/hosts/140.112.62.119
* https://search.censys.io/hosts/144.172.104.87
* https://search.censys.io/hosts/172.84.76.231
* https://search.censys.io/hosts/179.61.147.132
* https://search.censys.io/hosts/196.251.70.216
* https://search.censys.io/hosts/196.251.86.71
* https://search.censys.io/hosts/213.192.33.143
* https://threatfox.abuse.ch
* https://tria.ge/230707-zfx1zacf4s/behavioral1
* https://tria.ge/231117-r45rqabb9y
* https://urlhaus.abuse.ch/host/89.125.209.139/
* https://urlhaus.abuse.ch/url/3186497/
* https://urlhaus.abuse.ch/url/3522756/
* https://urlhaus.abuse.ch/url/3547058/
* https://urlhaus.abuse.ch/url/3551023/
* https://urlhaus.abuse.ch/url/3555257/
* https://urlhaus.abuse.ch/url/3555767/
* https://urlhaus.abuse.ch/url/3569048/
* https://urlhaus.abuse.ch/url/3620889/
* https://urlhaus.abuse.ch/url/3661061/
* https://urlhaus.abuse.ch/url/3661062/
* https://urlhaus.abuse.ch/url/3661068/
* https://urlhaus.abuse.ch/url/3666830/
* https://urlhaus.abuse.ch/url/3713106/
* https://urlhaus.abuse.ch/url/3739048/
* https://urlhaus.abuse.ch/url/3739076/
* https://urlhaus.abuse.ch/url/3747270/
* https://urlhaus.abuse.ch/url/3749342/
* https://urlhaus.abuse.ch/url/3749344/
* https://www.cadosecurity.com/containerised-clicks-malicious-use-of-9hits-on-vulnerable-docker-hosts/
* https://www.cyber45.com
* https://www.darktrace.com/blog/tracking-cve-2025-31324-darktraces-detection-of-sap-netweaver-exploitation-before-and-after-disclosure
* https://www.shodan.io/host/195.201.139.229
* https://www.uptycs.com/blog/log4j-campaign-xmrig-malware
* https://www.virustotal.com/gui/file/7f98872e415358424986167baac5c0bf3e729207b6a3562187ee89892f5a7fbc/relations
* https://www.virustotal.com/gui/file/261e97590d9dcfa3d19750e9a0fc306f37b07ca01ddd20cd13a6eaae70fc1d57
* https://www.virustotal.com/gui/file/a1c362d25595658214ba3fbf5547a1edbf5d8eda55c0d204ef4f85a834b926a0/behavior
* https://www.virustotal.com/gui/file/b362af32333b72f5b4f9dcc233c290ec5ca0957378646a361d258bd13ed64c8f
* https://www.wiz.io/blog/seleniumgreed-cryptomining-exploit-attack-flow-remediation-steps
* https://www.wiz.io/blog/wiz-research-identifies-exploitation-in-the-wild-of-aviatrix-cve-2024-50603
* https://x.com/orlof_v/status/1906650981674127671

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
