# AMOS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [AMOS](https://vuldb.com/?actor.amos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.amos](https://vuldb.com/?actor.amos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AMOS:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AMOS.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.64.45](https://vuldb.com/?ip.5.42.64.45) | - | - | High
2 | [5.42.64.83](https://vuldb.com/?ip.5.42.64.83) | - | - | High
3 | [5.42.65.55](https://vuldb.com/?ip.5.42.65.55) | - | - | High
4 | [5.42.65.102](https://vuldb.com/?ip.5.42.65.102) | - | - | High
5 | [5.42.65.106](https://vuldb.com/?ip.5.42.65.106) | - | - | High
6 | [5.42.65.107](https://vuldb.com/?ip.5.42.65.107) | - | - | High
7 | [5.42.65.108](https://vuldb.com/?ip.5.42.65.108) | - | - | High
8 | [5.42.66.22](https://vuldb.com/?ip.5.42.66.22) | - | - | High
9 | [5.42.67.1](https://vuldb.com/?ip.5.42.67.1) | - | - | High
10 | [5.42.96.124](https://vuldb.com/?ip.5.42.96.124) | - | - | High
11 | [5.42.96.184](https://vuldb.com/?ip.5.42.96.184) | - | - | High
12 | [5.182.86.8](https://vuldb.com/?ip.5.182.86.8) | frequent-minute.aeza.network | - | High
13 | [5.182.86.95](https://vuldb.com/?ip.5.182.86.95) | heavy-look.aeza.network | - | High
14 | [5.199.166.102](https://vuldb.com/?ip.5.199.166.102) | ip-5-199-166-102.003.ptr.cherryservers.net | - | High
15 | [5.255.107.149](https://vuldb.com/?ip.5.255.107.149) | - | - | High
16 | [31.31.196.161](https://vuldb.com/?ip.31.31.196.161) | server159.hosting.reg.ru | - | High
17 | [31.31.196.178](https://vuldb.com/?ip.31.31.196.178) | server195.hosting.reg.ru | - | High
18 | [36.255.98.252](https://vuldb.com/?ip.36.255.98.252) | - | - | High
19 | [37.220.87.16](https://vuldb.com/?ip.37.220.87.16) | ipn-37-220-87-16.artem-catv.ru | - | High
20 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _AMOS_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-41, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by AMOS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/upload_file` | High
2 | File | `/actuator` | Medium
3 | File | `/addelivery.php` | High
4 | File | `/adding-exec.php` | High
5 | File | `/addmem.php` | Medium
6 | File | `/addstock.php` | High
7 | File | `/add_librarian.php` | High
8 | File | `/admin#article/edit?id=2` | High
9 | File | `/admin#themes` | High
10 | File | `/admin-inbox.php` | High
11 | File | `/admin.php` | Medium
12 | File | `/admin/` | Low
13 | File | `/admin/?page=state` | High
14 | File | `/admin/?page=system_info` | High
15 | File | `/admin/about-us.php` | High
16 | File | `/admin/aboutus.php` | High
17 | File | `/admin/adminprofile.php` | High
18 | File | `/admin/admin_members.php?ac=search` | High
19 | File | `/admin/ajax.php?action=save_settings` | High
20 | File | `/admin/app/profile_crud.php` | High
21 | File | `/admin/approve_user.php` | High
22 | File | `/admin/attendance_row.php` | High
23 | File | `/admin/blogger.php?action=update_avatar` | High
24 | File | `/admin/book_row.php` | High
25 | File | `/admin/bwdates-reports-details.php` | High
26 | File | `/admin/bwdates-request-report-details.php` | High
27 | File | `/Admin/changepassword.php` | High
28 | File | `/admin/checklogin.php` | High
29 | File | `/admin/check_admin_login.php` | High
30 | File | `/admin/class.php` | High
31 | File | `/admin/class.php?dowhat=modifyclass` | High
32 | File | `/admin/contactus.php` | High
33 | File | `/admin/deleteuser.php` | High
34 | File | `/admin/delete_student.php` | High
35 | File | `/admin/delete_user.php` | High
36 | File | `/admin/edit-category-detail.php` | High
37 | File | `/admin/edit-customer-detailed.php` | High
38 | File | `/admin/edit-subadmin.php` | High
39 | File | `/admin/edit-teacher-detail.php` | High
40 | File | `/admin/edit-user.php` | High
41 | File | `/admin/edit_class.php` | High
42 | File | `/admin/edit_fuel.php` | High
43 | File | `/admin/inquiries/view_details.php` | High
44 | File | `/admin/login.php` | High
45 | File | `/admin/maintenance/view_designation.php` | High
46 | File | `/admin/manage-normal-ticket.php` | High
47 | File | `/admin/manage_theater.php` | High
48 | File | `/Admin/mode.php` | High
49 | File | `/admin/network/diag_nslookup` | High
50 | File | `/admin/network/diag_pinginterface` | High
51 | File | `/admin/new-content` | High
52 | File | `/admin/normal-search.php` | High
53 | File | `/admin/options-theme.php` | High
54 | File | `/admin/pages/student-print.php` | High
55 | File | `/admin/pass-bwdates-report.php` | High
56 | File | `/admin/password-recovery.php` | High
57 | File | `/admin/php/crud.php` | High
58 | File | `/admin/print_barcode.php` | High
59 | File | `/admin/products/index.php?view=add` | High
60 | File | `/Admin/Proses_Edit_Akun.php` | High
61 | File | `/admin/regester.php` | High
62 | File | `/admin/search-booking-request.php` | High
63 | File | `/admin/search-pass.php` | High
64 | File | `/admin/search1.php` | High
65 | File | `/Admin/sporttype.php` | High
66 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
67 | File | `/admin/update_user.php` | High
68 | File | `/admin/upload/authorImg/` | High
69 | File | `/admin/v1/blog/edit` | High
70 | File | `/admin/view-appointment.php` | High
71 | File | `/admin/view-foreigner-ticket.php` | High
72 | File | `/admin/voters_row.php` | High
73 | File | `/admin_class.php?action=login` | High
74 | File | `/admin_delete.php` | High
75 | File | `/admin_topic.php?action=delall` | High
76 | File | `/ajax.php?action=delete_loan` | High
77 | File | `/ajax.php?action=login` | High
78 | File | `/ajax.php?action=save_course` | High
79 | File | `/api/admin/question/edit` | High
80 | File | `/api/admin/update_account/` | High
81 | File | `/api/backend/v1/user/create` | High
82 | File | `/api/controllers/common/UploadsController.php` | High
83 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
84 | File | `/api/system/sendWebSocketMsg` | High
85 | File | `/api/v1/settings` | High
86 | File | `/api/wizard/networkSetup` | High
87 | File | `/app-api/v1/members/openid/` | High
88 | File | `/app-api/v1/orders/` | High
89 | File | `/app/ajax/search_sales_report.php` | High
90 | File | `/app/ConfirmSmsCode` | High
91 | File | `/application/models/ApplicationDataObject.class.php` | High
92 | File | `/auth/user/all.api` | High
93 | File | `/authentication/` | High
94 | File | `/bank/statements.php` | High
95 | File | `/bank/transfer.php` | High
96 | File | `/bin/httpd` | Medium
97 | File | `/biurl_grou` | Medium
98 | File | `/boafrm/formDebugDiagnosticRun` | High
99 | File | `/boafrm/formFilter` | High
100 | File | `/boafrm/formVpnConfigSetup` | High
101 | File | `/boafrm/formWsc` | High
102 | File | `/bolt/editcontent/showcases` | High
103 | ... | ... | ...

There are 908 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/4b351c938aa176e1c6e46949e6e409179f5e4b4ed593de46da1071f728290495/
* https://bazaar.abuse.ch/sample/7b8835e99a82a9d5002ca637a4db41031477e261fa0fb16aebbb571129051d8c/
* https://bazaar.abuse.ch/sample/97c57caae35331f00e2d51b1f09c0b62518c0ebde6e3e35c79205c30f957ecfc/
* https://bazaar.abuse.ch/sample/b9f0b6d6d0e3310fdc7f2a269db7bfd9d168fa8817774a1e701c3ecd5a287804/
* https://moonlock.com/amos-backdoor-persistent-access#indicators-of-compromise-iocs
* https://search.censys.io/hosts/5.42.65.55
* https://search.censys.io/hosts/5.199.166.102
* https://search.censys.io/hosts/36.255.98.252
* https://search.censys.io/hosts/62.60.131.230
* https://search.censys.io/hosts/62.60.131.249
* https://search.censys.io/hosts/62.60.131.250
* https://search.censys.io/hosts/79.137.198.170
* https://search.censys.io/hosts/88.214.50.3
* https://search.censys.io/hosts/89.208.105.191
* https://search.censys.io/hosts/185.93.89.63
* https://search.censys.io/hosts/185.147.124.212
* https://search.censys.io/hosts/185.172.128.31/
* https://search.censys.io/hosts/185.172.128.163
* https://search.censys.io/hosts/185.215.113.71/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=5.182.86.8
* https://tria.ge/240131-bq8nfsghb7/behavioral1
* https://tria.ge/240204-mqbt9sfdg3
* https://tria.ge/240310-nyz3hacd2y/behavioral1
* https://tria.ge/240319-ld769sgb35/behavioral1
* https://tria.ge/240319-mgpd1ahe93/behavioral1
* https://tria.ge/240319-mpvwrahh42/behavioral1
* https://tria.ge/240410-n1cd8aef57/behavioral1
* https://tria.ge/240417-dt3mqadg4x/behavioral1
* https://tria.ge/240501-c1bl5sdh6w/behavioral1
* https://tria.ge/240507-l4a98aeb53/behavioral1
* https://tria.ge/240507-mg4hxscb3w/behavioral1
* https://tria.ge/240513-c6wt9scd97/behavioral1
* https://tria.ge/240519-mzd1zseg72/behavioral1
* https://tria.ge/240519-p9jqbshh53/behavioral1
* https://tria.ge/240519-pfn3ysgg7z/behavioral1
* https://tria.ge/240524-fl1jhaec5t/behavioral1
* https://tria.ge/240525-m61tbseb9z/behavioral1
* https://tria.ge/240527-l4le7afh91/behavioral1
* https://tria.ge/240530-lf792sea64/behavioral1
* https://tria.ge/240531-lt84hadh41/behavioral1
* https://tria.ge/240603-tdf2sabe7y
* https://tria.ge/240614-r43blavelg/behavioral1
* https://tria.ge/240618-mnmhzstfkp/behavioral1
* https://tria.ge/240716-lvpfgswfrj/behavioral1
* https://tria.ge/240720-lll9rszejc/behavioral1
* https://tria.ge/240728-fxbphszdkq/behavioral3
* https://tria.ge/240803-m8swhawdjc/behavioral1
* https://tria.ge/240806-sahwjasark/behavioral1
* https://tria.ge/240810-q2exvawdjb/behavioral1
* https://tria.ge/240811-l2tnsavdkk/behavioral1
* https://twitter.com/phd_phuc/status/1651002681798926337
* https://urlhaus.abuse.ch/url/3743664/
* https://urlscan.io/result/0199f345-0702-7429-9407-28bfe6e42797/
* https://www.huntress.com/blog/amos-stealer-chatgpt-grok-ai-trust
* https://www.infosecurity-magazine.com/news/russian-legitimate-services/
* https://www.malwarebytes.com/blog/threat-intelligence/2024/01/atomic-stealer-rings-in-the-new-year-with-updated-version
* https://www.recordedfuture.com/cybercriminal-campaign-spreads-infostealers-highlighting-risks-to-web3-gaming
* https://www.trendmicro.com/en_us/research/25/i/an-mdr-analysis-of-the-amos-stealer-campaign.html
* https://x.com/500mk500/status/1980565541468463288
* https://x.com/suyog41/status/1878707544576974922

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
