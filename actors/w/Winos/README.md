# Winos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Winos](https://vuldb.com/?actor.winos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.winos](https://vuldb.com/?actor.winos)

## Campaigns

The following _campaigns_ are known and can be associated with Winos:

* Catena
* Taiwanese Organizations

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Winos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Winos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.122.59.71](https://vuldb.com/?ip.27.122.59.71) | - | - | High
2 | [43.226.125.44](https://vuldb.com/?ip.43.226.125.44) | - | - | High
3 | [47.83.184.193](https://vuldb.com/?ip.47.83.184.193) | - | - | High
4 | [47.86.28.28](https://vuldb.com/?ip.47.86.28.28) | - | - | High
5 | [47.238.125.85](https://vuldb.com/?ip.47.238.125.85) | - | - | High
6 | [103.46.185.44](https://vuldb.com/?ip.103.46.185.44) | undefined.hostname.localhost | Catena | High
7 | [103.46.185.73](https://vuldb.com/?ip.103.46.185.73) | undefined.hostname.localhost | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Winos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Winos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `-X/path/to/wwwroot/file.php.` | High
2 | File | `/Actions.php` | Medium
3 | File | `/add_deductions.php` | High
4 | File | `/adfs/ls` | Medium
5 | File | `/admin-cp/media` | High
6 | File | `/admin/?page=return/view_return` | High
7 | File | `/admin/add-subadmin.php` | High
8 | File | `/admin/add_cars.php` | High
9 | File | `/admin/admin_index.php` | High
10 | File | `/admin/all-applications.php` | High
11 | File | `/admin/approve_user.php` | High
12 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
13 | File | `/admin/bookList?page=1&limit=10` | High
14 | File | `/admin/bwdates-report-details.php` | High
15 | File | `/admin/bwdates-request-report-details.php` | High
16 | File | `/admin/category/add.do` | High
17 | File | `/admin/changeimage.php` | High
18 | File | `/admin/chatroom.php` | High
19 | File | `/admin/create_product.php` | High
20 | File | `/admin/delete-doctor.php` | High
21 | File | `/admin/delete_log.php` | High
22 | File | `/admin/disapprove_user.php` | High
23 | File | `/admin/edit-admin.php` | High
24 | File | `/admin/edit-guard-detail.php` | High
25 | File | `/admin/edit-products.php` | High
26 | File | `/admin/enrollment-details.php` | High
27 | File | `/admin/faculty_action.php` | High
28 | File | `/admin/forms/option_lists/edit.php` | High
29 | File | `/admin/getallarticleinfo` | High
30 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
31 | File | `/admin/index.php` | High
32 | File | `/admin/index2.html` | High
33 | File | `/Admin/login.php` | High
34 | File | `/admin/manage-pages.php` | High
35 | File | `/admin/manage_user.php` | High
36 | File | `/admin/normal-search.php` | High
37 | File | `/admin/operations/booking.php` | High
38 | File | `/admin/operations/travellers.php` | High
39 | File | `/admin/salary_slip.php` | High
40 | File | `/Admin/sports.php` | High
41 | File | `/admin/template/update` | High
42 | File | `/admin/user-search.php` | High
43 | File | `/admin/view-patient.php` | High
44 | File | `/adminPage/main/upload` | High
45 | File | `/adminpanel/admin/query/addCourseExe.php` | High
46 | File | `/adpweb/a/base/barcodeDetail/` | High
47 | File | `/ajax.php?action=save_package` | High
48 | File | `/api/` | Low
49 | File | `/api/docs/index.php` | High
50 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
51 | File | `/api/semantic/database/testConnect` | High
52 | File | `/api/sys/set_passwd` | High
53 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
54 | File | `/api/v1/settings` | High
55 | File | `/api/wizard/setsyncpppoecfg` | High
56 | File | `/app/controller/Api.php` | High
57 | File | `/auth.asp` | Medium
58 | File | `/auth/register` | High
59 | File | `/backend/register.php` | High
60 | File | `/bic/ssoService/v1/applyCT` | High
61 | File | `/bin/httpd` | Medium
62 | File | `/blog/comment` | High
63 | File | `/boafrm/formFilter` | High
64 | File | `/boafrm/formSaveConfig` | High
65 | File | `/boafrm/formWlSiteSurvey` | High
66 | File | `/BRS_top.html` | High
67 | File | `/cashconfirm.php` | High
68 | File | `/catalog/compare` | High
69 | File | `/cgi-bin/Config.cgi?action=set` | High
70 | File | `/cgi-bin/cstecgi.cgi` | High
71 | File | `/cgi-bin/editBookmark` | High
72 | File | `/cgi-bin/ExportIbmsConfig.sh` | High
73 | ... | ... | ...

There are 646 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/rapid7/Rapid7-Labs/blob/main/IOCs/nsis-abuse-srdi-winos4/iocs.txt
* https://www.fortinet.com/blog/threat-research/threat-group-targets-companies-in-taiwan
* https://www.rapid7.com/blog/post/2025/05/22/nsis-abuse-and-srdi-shellcode-anatomy-of-the-winos-4-0-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
