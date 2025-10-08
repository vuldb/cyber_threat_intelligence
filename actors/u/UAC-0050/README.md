# UAC-0050 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0050](https://vuldb.com/?actor.uac-0050). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0050](https://vuldb.com/?actor.uac-0050)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-0050:

* Remcos

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0050:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0050.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.92.30](https://vuldb.com/?ip.5.42.92.30) | hosted-by.saltu-cloud.pro | - | High
2 | [5.42.92.31](https://vuldb.com/?ip.5.42.92.31) | hosted-by.saltu-cloud.pro | - | High
3 | [5.42.92.32](https://vuldb.com/?ip.5.42.92.32) | hosted-by.yeezyhost.net | - | High
4 | [5.42.92.37](https://vuldb.com/?ip.5.42.92.37) | hosted-by.yeezyhost.net | - | High
5 | [5.42.92.44](https://vuldb.com/?ip.5.42.92.44) | hosted-by.yeezyhost.net | - | High
6 | [31.214.157.49](https://vuldb.com/?ip.31.214.157.49) | expand.wolfleet.com | - | High
7 | [45.10.245.245](https://vuldb.com/?ip.45.10.245.245) | - | - | High
8 | [45.87.154.153](https://vuldb.com/?ip.45.87.154.153) | net-group.net | - | High
9 | [45.87.155.41](https://vuldb.com/?ip.45.87.155.41) | trustvs.com | - | High
10 | [45.143.166.100](https://vuldb.com/?ip.45.143.166.100) | - | - | High
11 | [46.249.58.40](https://vuldb.com/?ip.46.249.58.40) | yufrt.g5.housinglandshares.info | Remcos | High
12 | [65.21.245.7](https://vuldb.com/?ip.65.21.245.7) | static.7.245.21.65.clients.your-server.de | - | High
13 | [77.105.132.70](https://vuldb.com/?ip.77.105.132.70) | - | - | High
14 | [77.105.132.124](https://vuldb.com/?ip.77.105.132.124) | - | - | High
15 | [77.105.161.194](https://vuldb.com/?ip.77.105.161.194) | - | - | High
16 | [79.137.205.201](https://vuldb.com/?ip.79.137.205.201) | awesome-dime.aeza.network | - | High
17 | [80.78.254.28](https://vuldb.com/?ip.80.78.254.28) | 80-78-254-28.cloudvps.regruhosting.ru | - | High
18 | [81.19.149.130](https://vuldb.com/?ip.81.19.149.130) | mx20lb.world4you.com | - | High
19 | [89.23.98.22](https://vuldb.com/?ip.89.23.98.22) | - | - | High
20 | [91.240.86.200](https://vuldb.com/?ip.91.240.86.200) | den.aria.fvds.ru | - | High
21 | [94.131.99.56](https://vuldb.com/?ip.94.131.99.56) | vm2202770.stark-industries.solutions | - | High
22 | [94.131.99.89](https://vuldb.com/?ip.94.131.99.89) | vm2030942.stark-industries.solutions | - | High
23 | [94.131.99.153](https://vuldb.com/?ip.94.131.99.153) | vm2051611.stark-industries.solutions | - | High
24 | ... | ... | ... | ...

There are 91 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0050_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-44, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0050. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `-X/path/to/wwwroot/file.php.` | High
2 | File | `.travis.yml` | Medium
3 | File | `/Actions.php` | Medium
4 | File | `/add_deductions.php` | High
5 | File | `/adfs/ls` | Medium
6 | File | `/admin-cp/media` | High
7 | File | `/admin/?page=return/view_return` | High
8 | File | `/admin/add-subadmin.php` | High
9 | File | `/admin/add_cars.php` | High
10 | File | `/admin/admin_action.php` | High
11 | File | `/admin/admin_index.php` | High
12 | File | `/admin/ajax.php?action=save_user` | High
13 | File | `/admin/all-applications.php` | High
14 | File | `/admin/approve_user.php` | High
15 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
16 | File | `/admin/bookList?page=1&limit=10` | High
17 | File | `/admin/bwdates-report-details.php` | High
18 | File | `/admin/bwdates-request-report-details.php` | High
19 | File | `/admin/category/add.do` | High
20 | File | `/admin/changeimage.php` | High
21 | File | `/admin/chatroom.php` | High
22 | File | `/admin/delete-doctor.php` | High
23 | File | `/admin/delete_log.php` | High
24 | File | `/admin/disapprove_user.php` | High
25 | File | `/admin/edit-admin.php` | High
26 | File | `/admin/edit-guard-detail.php` | High
27 | File | `/admin/edit-products.php` | High
28 | File | `/admin/enrollment-details.php` | High
29 | File | `/admin/faculty_action.php` | High
30 | File | `/admin/forms/option_lists/edit.php` | High
31 | File | `/admin/getallarticleinfo` | High
32 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
33 | File | `/admin/index.php` | High
34 | File | `/admin/index2.html` | High
35 | File | `/admin/login.php` | High
36 | File | `/Admin/login.php` | High
37 | File | `/admin/manage-pages.php` | High
38 | File | `/admin/manage_user.php` | High
39 | File | `/admin/new-content` | High
40 | File | `/admin/operations/booking.php` | High
41 | File | `/admin/operations/currency.php` | High
42 | File | `/admin/operations/travellers.php` | High
43 | File | `/Admin/sports.php` | High
44 | File | `/admin/template/update` | High
45 | File | `/admin/user-search.php` | High
46 | File | `/admin/view-patient.php` | High
47 | File | `/admin/voters_add.php` | High
48 | File | `/admin/voters_delete.php` | High
49 | File | `/adminPage/main/upload` | High
50 | File | `/admin_topic.php?action=delall` | High
51 | File | `/adpweb/a/base/barcodeDetail/` | High
52 | File | `/ajax.php?action=save_package` | High
53 | File | `/api/` | Low
54 | File | `/api/docs/index.php` | High
55 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
56 | File | `/api/role` | Medium
57 | File | `/api/sys/set_passwd` | High
58 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
59 | File | `/api/v1/settings` | High
60 | File | `/api/wizard/setsyncpppoecfg` | High
61 | File | `/app/controller/Api.php` | High
62 | File | `/application/controller/Pengeluaran.php` | High
63 | File | `/auth.asp` | Medium
64 | File | `/authentication/logout.php` | High
65 | File | `/backend/register.php` | High
66 | File | `/bic/ssoService/v1/applyCT` | High
67 | File | `/bin/httpd` | Medium
68 | File | `/bitrix/admin/ldap_server_edit.php` | High
69 | File | `/blog/comment` | High
70 | File | `/boafrm/formFilter` | High
71 | File | `/boafrm/formSaveConfig` | High
72 | File | `/boafrm/formWlSiteSurvey` | High
73 | File | `/BRS_top.html` | High
74 | File | `/cashconfirm.php` | High
75 | File | `/catalog/compare` | High
76 | File | `/cgi-bin/Config.cgi?action=set` | High
77 | File | `/cgi-bin/cstecgi.cgi` | High
78 | File | `/cgi-bin/editBookmark` | High
79 | File | `/cgi-bin/ExportIbmsConfig.sh` | High
80 | File | `/cgi-bin/hd_config.cgi` | High
81 | ... | ... | ...

There are 717 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/3804703
* https://cert.gov.ua/article/6276351
* https://cert.gov.ua/article/6276567
* https://cert.gov.ua/article/6276652
* https://cert.gov.ua/article/6276824
* https://cert.gov.ua/article/6277063
* https://cert.gov.ua/article/6277285
* https://cert.gov.ua/article/6281009
* https://cert.gov.ua/article/6281202
* https://www.uptycs.com/blog/remcos-rat-uac-0500-pipe-method

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
