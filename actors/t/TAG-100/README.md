# TAG-100 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TAG-100](https://vuldb.com/?actor.tag-100). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tag-100](https://vuldb.com/?actor.tag-100)

## Campaigns

The following _campaigns_ are known and can be associated with TAG-100:

* Tajikistan

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TAG-100:

* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TAG-100.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [38.54.15.164](https://vuldb.com/?ip.38.54.15.164) | - | - | High
2 | [38.54.115.34](https://vuldb.com/?ip.38.54.115.34) | - | - | High
3 | [38.180.206.61](https://vuldb.com/?ip.38.180.206.61) | - | Tajikistan | High
4 | [104.244.79.119](https://vuldb.com/?ip.104.244.79.119) | - | - | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TAG-100_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TAG-100. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/?page=user` | Medium
3 | File | `/aboutedit.php` | High
4 | File | `/add-normal-ticket.php` | High
5 | File | `/add-pig.php` | Medium
6 | File | `/addcompany.php` | High
7 | File | `/addpayment.php` | High
8 | File | `/admin#themes` | High
9 | File | `/admin.php?id=posts&action=display&value=1&postid=` | High
10 | File | `/admin/?page=inventory/view_inventory&id=2` | High
11 | File | `/Admin/add-admin.php` | High
12 | File | `/admin/add-services.php` | High
13 | File | `/admin/assets/` | High
14 | File | `/admin/assign/assign.php` | High
15 | File | `/admin/auto-taxi-entry-detail.php` | High
16 | File | `/admin/bwdates-reports-details.php` | High
17 | File | `/admin/case-status` | High
18 | File | `/admin/category_save.php` | High
19 | File | `/admin/check_admin.php` | High
20 | File | `/admin/config_time_sync.php` | High
21 | File | `/admin/core/new_user` | High
22 | File | `/admin/deletedoctorclinic.php` | High
23 | File | `/admin/edit-artist-detail.php?editid=1` | High
24 | File | `/admin/edit-category.php` | High
25 | File | `/admin/edit-doctor-specialization.php` | High
26 | File | `/admin/edit-guard-detail.php` | High
27 | File | `/admin/edit_subject.php` | High
28 | File | `/admin/eligibility.php` | High
29 | File | `/admin/expense-type` | High
30 | File | `/admin/group/edit.do` | High
31 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
32 | File | `/admin/inbox.php&action=read` | High
33 | File | `/admin/index.php` | High
34 | File | `/admin/index.php?add_product` | High
35 | File | `/admin/login.php` | High
36 | File | `/admin/member_save.php` | High
37 | File | `/Admin/News.php` | High
38 | File | `/admin/payment_save.php` | High
39 | File | `/admin/process_category_add.php` | High
40 | File | `/Admin/registration.php` | High
41 | File | `/admin/save_student.php` | High
42 | File | `/admin/service` | High
43 | File | `/admin/system.html` | High
44 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
45 | File | `/admin/team_update.php` | High
46 | File | `/admin/vacancy/index.php` | High
47 | File | `/admin/view-user-queries.php` | High
48 | File | `/admin/voters_add.php` | High
49 | File | `/admin/voters_row.php` | High
50 | File | `/administrator` | High
51 | File | `/admin_class.php` | High
52 | File | `/adplanet/PlanetUser` | High
53 | File | `/ajax.php?action=delete_trainer` | High
54 | File | `/ajax/myshop` | Medium
55 | File | `/alphaware/summary.php` | High
56 | File | `/api/deploy/upload` | High
57 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
58 | File | `/api/runscript` | High
59 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
60 | File | `/api/v2/maps` | Medium
61 | File | `/api/wizard/getDualbandSync` | High
62 | File | `/api/wizard/getNetworkStatus` | High
63 | File | `/app/platform/controllers/ResetpwdController.php` | High
64 | File | `/assets/php/upload.php` | High
65 | File | `/assetsGroupReport/assetsService.j%73p` | High
66 | File | `/astre/iodasweb/app.jsp` | High
67 | File | `/auth.asp` | Medium
68 | File | `/boafrm/formMapReboot` | High
69 | File | `/boafrm/formParentControl` | High
70 | File | `/boafrm/formTracerouteDiagnosticRun` | High
71 | File | `/boafrm/formWlanRedirect` | High
72 | File | `/boat-details.php` | High
73 | File | `/book-appointment.php` | High
74 | File | `/buscar_integrada.php` | High
75 | File | `/campaign.php` | High
76 | File | `/category.php` | High
77 | File | `/cfgFile/fileContent` | High
78 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
79 | File | `/cgi-bin/cstecgi.cgi` | High
80 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
81 | File | `/cgi-bin/downloadFile.cgi` | High
82 | File | `/cgi-bin/hd_config.cgi` | High
83 | File | `/cgi-bin/nas_sharing.cgi` | High
84 | File | `/cgi-bin/system_mgr.cgi` | High
85 | ... | ... | ...

There are 752 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/UNC****/TAG-*/TAG-100%20Uses%20Open-Source%20Tools%20in%20Suspected%20Global%20Espionage%20Campaign.pdf
* https://www.recordedfuture.com/research/russia-aligned-tag-110-targets-tajikistan-with-macro-enabled

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
