# Nova Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nova Stealer](https://vuldb.com/?actor.nova_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nova_stealer](https://vuldb.com/?actor.nova_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nova Stealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nova Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [89.213.140.115](https://vuldb.com/?ip.89.213.140.115) | 89.213.140.115.nerozix.ovh | - | High
2 | [92.249.48.63](https://vuldb.com/?ip.92.249.48.63) | undefined.hostname.localhost | - | High
3 | [92.249.48.64](https://vuldb.com/?ip.92.249.48.64) | undefined.hostname.localhost | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nova Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nova Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `-X/path/to/wwwroot/file.php.` | High
2 | File | `/add_deductions.php` | High
3 | File | `/admin-cp/media` | High
4 | File | `/admin/?page=return/view_return` | High
5 | File | `/admin/add-subadmin.php` | High
6 | File | `/admin/add_cars.php` | High
7 | File | `/admin/admin_index.php` | High
8 | File | `/admin/all-applications.php` | High
9 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
10 | File | `/admin/bookList?page=1&limit=10` | High
11 | File | `/admin/bwdates-report-details.php` | High
12 | File | `/admin/bwdates-request-report-details.php` | High
13 | File | `/admin/category/add.do` | High
14 | File | `/admin/changeimage.php` | High
15 | File | `/admin/chatroom.php` | High
16 | File | `/admin/create_product.php` | High
17 | File | `/admin/delete-doctor.php` | High
18 | File | `/admin/delete_log.php` | High
19 | File | `/admin/edit-admin.php` | High
20 | File | `/admin/edit-guard-detail.php` | High
21 | File | `/admin/edit-products.php` | High
22 | File | `/admin/enrollment-details.php` | High
23 | File | `/admin/faculty_action.php` | High
24 | File | `/admin/forms/option_lists/edit.php` | High
25 | File | `/admin/getallarticleinfo` | High
26 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/index2.html` | High
29 | File | `/Admin/login.php` | High
30 | File | `/admin/manage-pages.php` | High
31 | File | `/admin/manage_user.php` | High
32 | File | `/admin/normal-search.php` | High
33 | File | `/admin/salary_slip.php` | High
34 | File | `/admin/template/update` | High
35 | File | `/admin/user-search.php` | High
36 | File | `/admin/view-patient.php` | High
37 | File | `/adminPage/main/upload` | High
38 | File | `/adminpanel/admin/query/addCourseExe.php` | High
39 | File | `/adpweb/a/base/barcodeDetail/` | High
40 | File | `/ajax.php?action=save_package` | High
41 | File | `/api/` | Low
42 | File | `/api/docs/index.php` | High
43 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
44 | File | `/api/sys/set_passwd` | High
45 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
46 | File | `/api/wizard/setsyncpppoecfg` | High
47 | File | `/app/controller/Api.php` | High
48 | File | `/auth.asp` | Medium
49 | File | `/auth/register` | High
50 | File | `/backend/register.php` | High
51 | File | `/bic/ssoService/v1/applyCT` | High
52 | File | `/bin/httpd` | Medium
53 | File | `/boafrm/formFilter` | High
54 | File | `/boafrm/formSaveConfig` | High
55 | File | `/boafrm/formWlSiteSurvey` | High
56 | File | `/BRS_top.html` | High
57 | File | `/cashconfirm.php` | High
58 | File | `/catalog/compare` | High
59 | File | `/cgi-bin/Config.cgi?action=set` | High
60 | File | `/cgi-bin/cstecgi.cgi` | High
61 | File | `/cgi-bin/editBookmark` | High
62 | File | `/cgi-bin/ExportIbmsConfig.sh` | High
63 | File | `/cgi-bin/hd_config.cgi` | High
64 | File | `/cgi-bin/login.cgi` | High
65 | File | `/cgi-bin/mainfunction.cgi` | High
66 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
67 | File | `/change-password.php` | High
68 | ... | ... | ...

There are 594 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://x.com/NDA0E/status/1828045352785838172

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
