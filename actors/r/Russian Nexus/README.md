# Russian Nexus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Russian Nexus](https://vuldb.com/?actor.russian_nexus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.russian_nexus](https://vuldb.com/?actor.russian_nexus)

## Campaigns

The following _campaigns_ are known and can be associated with Russian Nexus:

* Sitting Ducks

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Russian Nexus:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Russian Nexus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.136.49.35](https://vuldb.com/?ip.45.136.49.35) | - | Sitting Ducks | High
2 | [80.255.12.237](https://vuldb.com/?ip.80.255.12.237) | - | - | High
3 | [81.19.135.241](https://vuldb.com/?ip.81.19.135.241) | undefined.hostname.localhost | Sitting Ducks | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Russian Nexus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-268, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Russian Nexus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `-X/path/to/wwwroot/file.php.` | High
2 | File | `/Actions.php` | Medium
3 | File | `/add_deductions.php` | High
4 | File | `/admin#themes` | High
5 | File | `/admin-cp/media` | High
6 | File | `/admin/?page=return/view_return` | High
7 | File | `/admin/add-subadmin.php` | High
8 | File | `/admin/add_cars.php` | High
9 | File | `/admin/admin_class.php` | High
10 | File | `/admin/admin_index.php` | High
11 | File | `/admin/all-applications.php` | High
12 | File | `/admin/approve_user.php` | High
13 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
14 | File | `/admin/bookList?page=1&limit=10` | High
15 | File | `/admin/bwdates-request-report-details.php` | High
16 | File | `/admin/category/add.do` | High
17 | File | `/admin/changeimage.php` | High
18 | File | `/admin/delete-doctor.php` | High
19 | File | `/admin/delete_log.php` | High
20 | File | `/admin/disapprove_user.php` | High
21 | File | `/admin/edit-admin.php` | High
22 | File | `/admin/edit-guard-detail.php` | High
23 | File | `/admin/edit-products.php` | High
24 | File | `/admin/edituser.php` | High
25 | File | `/admin/enrollment-details.php` | High
26 | File | `/admin/faculty_action.php` | High
27 | File | `/admin/forms/option_lists/edit.php` | High
28 | File | `/admin/getallarticleinfo` | High
29 | File | `/admin/index.php` | High
30 | File | `/admin/index2.html` | High
31 | File | `/admin/login` | Medium
32 | File | `/admin/login.php` | High
33 | File | `/Admin/login.php` | High
34 | File | `/admin/manage-pages.php` | High
35 | File | `/admin/manage_user.php` | High
36 | File | `/admin/modules/instructor/index.php` | High
37 | File | `/admin/operations/booking.php` | High
38 | File | `/admin/operations/travellers.php` | High
39 | File | `/Admin/sports.php` | High
40 | File | `/admin/user-search.php` | High
41 | File | `/admin/userlist.php` | High
42 | File | `/admin/view-patient.php` | High
43 | File | `/adpweb/a/base/barcodeDetail/` | High
44 | File | `/ajax.php` | Medium
45 | File | `/ajax.php?action=delete_borrower` | High
46 | File | `/ajax.php?action=delete_plan` | High
47 | File | `/ajax.php?action=delete_sales` | High
48 | File | `/ajax.php?action=login` | High
49 | File | `/ajax.php?action=save_package` | High
50 | File | `/ajax.php?action=save_receiving` | High
51 | File | `/api/` | Low
52 | File | `/api/docs/index.php` | High
53 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
54 | File | `/api/plugin/uninstall` | High
55 | File | `/api/sys/set_passwd` | High
56 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
57 | File | `/api/wizard/setsyncpppoecfg` | High
58 | File | `/app/controller/Api.php` | High
59 | File | `/auth.asp` | Medium
60 | File | `/backend/admin/his_admin_register_patient.php` | High
61 | File | `/backend/register.php` | High
62 | File | `/bic/ssoService/v1/applyCT` | High
63 | File | `/bin/httpd` | Medium
64 | File | `/blog/comment` | High
65 | File | `/boafrm/formFilter` | High
66 | File | `/boafrm/formParentControl` | High
67 | File | `/boafrm/formSaveConfig` | High
68 | File | `/boafrm/formWlSiteSurvey` | High
69 | File | `/booklist.php` | High
70 | File | `/branch/addbranch.php` | High
71 | File | `/browsemdcn.php` | High
72 | File | `/BRS_top.html` | High
73 | File | `/cashconfirm.php` | High
74 | File | `/cgi-bin/Config.cgi?action=set` | High
75 | File | `/cgi-bin/cstecgi.cgi` | High
76 | File | `/cgi-bin/editBookmark` | High
77 | File | `/cgi-bin/ExportIbmsConfig.sh` | High
78 | File | `/cgi-bin/hd_config.cgi` | High
79 | File | `/cgi-bin/login.cgi` | High
80 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
81 | ... | ... | ...

There are 710 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.infoblox.com/threat-intelligence/who-knew-domain-hijacking-is-so-easy/
* https://citizenlab.ca/2017/05/tainted-leaks-disinformation-phish/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
