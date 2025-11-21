# CoralRaider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CoralRaider](https://vuldb.com/?actor.coralraider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.coralraider](https://vuldb.com/?actor.coralraider)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CoralRaider:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CoralRaider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.225.210.97](https://vuldb.com/?ip.14.225.210.97) | static.vnpt.vn | - | High
2 | [14.225.210.98](https://vuldb.com/?ip.14.225.210.98) | static.vnpt.vn | - | High
3 | [14.225.210.209](https://vuldb.com/?ip.14.225.210.209) | static.vnpt.vn | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CoralRaider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CoralRaider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/about.php` | Medium
4 | File | `/Actions.php?a=login` | High
5 | File | `/addcategory.php` | High
6 | File | `/addelidetails.php` | High
7 | File | `/add_classes.php` | High
8 | File | `/admin.php/addon/index` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=maintenance/brand` | High
11 | File | `/admin/aboutus.php` | High
12 | File | `/admin/add_postlogin.php` | High
13 | File | `/admin/admin-update-employee.php` | High
14 | File | `/admin/admin_cl.php?mudi=revPwd` | High
15 | File | `/admin/admin_index.php` | High
16 | File | `/admin/admin_user.php` | High
17 | File | `/admin/ajax_products_list.php` | High
18 | File | `/admin/archives_add.php` | High
19 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
20 | File | `/admin/candidates_add.php` | High
21 | File | `/admin/categories/save` | High
22 | File | `/admin/change-password.php` | High
23 | File | `/admin/changepassword.php` | High
24 | File | `/admin/client_user` | High
25 | File | `/admin/cmsVote/save` | High
26 | File | `/admin/edit-brand.php` | High
27 | File | `/admin/edit-category.php` | High
28 | File | `/admin/editempeducation.php` | High
29 | File | `/admin/edit_fuel.php` | High
30 | File | `/admin/get_balance.php` | High
31 | File | `/admin/index.php` | High
32 | File | `/admin/index.php?language=en&nv=upload` | High
33 | File | `/admin/login.php` | High
34 | File | `/admin/new-content` | High
35 | File | `/admin/operations/payment.php` | High
36 | File | `/admin/plan/examExportPDF` | High
37 | File | `/admin/readenq.php` | High
38 | File | `/admin/regester.php` | High
39 | File | `/Admin/registration.php` | High
40 | File | `/admin/search-vehicle.php` | High
41 | File | `/admin/session.php` | High
42 | File | `/admin/sn_package/sn_https` | High
43 | File | `/admin/subject.php` | High
44 | File | `/admin/update-rooms.php` | High
45 | File | `/admin/uploads/` | High
46 | File | `/admin/user-search.php` | High
47 | File | `/admin/user/edit.do` | High
48 | File | `/admin/userlist.php` | High
49 | File | `/admin/userprofile.php` | High
50 | File | `/ajax.php?action=save_payment` | High
51 | File | `/ajax_state.php` | High
52 | File | `/ajx.php` | Medium
53 | File | `/analysisProject/pagingQueryData` | High
54 | File | `/api/` | Low
55 | File | `/api/client/editemedia.php` | High
56 | File | `/api/config/list` | High
57 | File | `/api/objects/recipes` | High
58 | File | `/api/upload` | Medium
59 | File | `/api/v1/toolbox/device/update/swap` | High
60 | File | `/api/wechat/app_auth` | High
61 | File | `/app/ConfirmSmsCode` | High
62 | File | `/applyleave.php` | High
63 | File | `/APR/login.php` | High
64 | File | `/b2c/package-information` | High
65 | File | `/bin/boa` | Medium
66 | File | `/Blood/A+.php` | High
67 | File | `/boafrm/formDosCfg` | High
68 | File | `/boafrm/formParentControl` | High
69 | File | `/boafrm/formPortFw` | High
70 | File | `/boafrm/formSysLog` | High
71 | File | `/cgi-bin/` | Medium
72 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
73 | File | `/cgi-bin/cstecgi.cgi` | High
74 | File | `/cgi-bin/editBookmark` | High
75 | File | `/cgi-bin/ExportSyslog.sh` | High
76 | File | `/cgi-bin/hd_config.cgi` | High
77 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
78 | File | `/cgi-bin/nas_sharing.cgi` | High
79 | File | `/cgi-bin/sysconf.cgi` | High
80 | File | `/cgi-bin/webfile_mgr.cgi` | High
81 | File | `/change-password.php` | High
82 | File | `/changeimage1.php` | High
83 | File | `/chat.php` | Medium
84 | File | `/classes/Master.php?f=save_inquiry` | High
85 | File | `/client/api/json/v2/nfareports/compareReport` | High
86 | File | `/cm/delete` | Medium
87 | ... | ... | ...

There are 767 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/coralraider-targets-socialmedia-accounts/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
