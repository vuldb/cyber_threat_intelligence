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

There are 19 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TAG-100. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/aboutedit.php` | High
3 | File | `/add-pig.php` | Medium
4 | File | `/addcompany.php` | High
5 | File | `/addpayment.php` | High
6 | File | `/admin/?page=inventory/view_inventory&id=2` | High
7 | File | `/Admin/add-admin.php` | High
8 | File | `/admin/add-services.php` | High
9 | File | `/admin/assets/` | High
10 | File | `/admin/assign/assign.php` | High
11 | File | `/admin/category_save.php` | High
12 | File | `/admin/config_time_sync.php` | High
13 | File | `/admin/edit_subject.php` | High
14 | File | `/admin/eligibility.php` | High
15 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/process_category_add.php` | High
19 | File | `/admin/subnets/ripe-query.php` | High
20 | File | `/admin/system.html` | High
21 | File | `/adplanet/PlanetUser` | High
22 | File | `/ajax/myshop` | Medium
23 | File | `/alphaware/summary.php` | High
24 | File | `/api/deploy/upload` | High
25 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
26 | File | `/api/runscript` | High
27 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
28 | File | `/api/v2/maps` | Medium
29 | File | `/api/wizard/getDualbandSync` | High
30 | File | `/api/wizard/getNetworkStatus` | High
31 | File | `/app/platform/controllers/ResetpwdController.php` | High
32 | File | `/assets/php/upload.php` | High
33 | File | `/baseOpLog.do` | High
34 | File | `/book-appointment.php` | High
35 | File | `/buscar_integrada.php` | High
36 | File | `/campaign.php` | High
37 | File | `/cfgFile/fileContent` | High
38 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
39 | File | `/cgi-bin/cstecgi.cgi` | High
40 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
41 | File | `/cgi-bin/downloadFile.cgi` | High
42 | File | `/cgi-bin/hd_config.cgi` | High
43 | File | `/cgi-bin/system_mgr.cgi` | High
44 | File | `/Cinema-Reservation/booking.php` | High
45 | File | `/classes/Master.php?f=log_employee` | High
46 | File | `/classes/Master.php?f=log_visitor` | High
47 | File | `/classes/Users.php` | High
48 | File | `/classes/Users.php?f=delete` | High
49 | File | `/classes/Users.php?f=save` | High
50 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
51 | File | `/cm/update_rows/page?id=2` | High
52 | File | `/cms/classes/Users.php?f=delete_client` | High
53 | File | `/com/esafenet/servlet/ajax/UsbKeyAjax.java` | High
54 | File | `/com/esafenet/servlet/policy/PrintPolicyService.java` | High
55 | File | `/content_top.jsp` | High
56 | File | `/debug/pprof` | Medium
57 | File | `/deleteAgent.php` | High
58 | File | `/dev-api/cms/file/upload` | High
59 | File | `/Doctor/user_appointment.php` | High
60 | File | `/E-Insurance/` | High
61 | File | `/edit_book.php` | High
62 | ... | ... | ...

There are 544 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/UNC****/TAG-*/TAG-100%20Uses%20Open-Source%20Tools%20in%20Suspected%20Global%20Espionage%20Campaign.pdf
* https://www.recordedfuture.com/research/russia-aligned-tag-110-targets-tajikistan-with-macro-enabled

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
