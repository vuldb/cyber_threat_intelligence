# AISURU - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [AISURU](https://vuldb.com/?actor.aisuru). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.aisuru](https://vuldb.com/?actor.aisuru)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AISURU:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AISURU.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [64.188.68.193](https://vuldb.com/?ip.64.188.68.193) | relay-eu-fra.hotpotatoservices.com | - | High
2 | [78.108.178.100](https://vuldb.com/?ip.78.108.178.100) | - | - | High
3 | [104.171.170.241](https://vuldb.com/?ip.104.171.170.241) | undefined.hostname.localhost | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _AISURU_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by AISURU. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `-X/path/to/wwwroot/file.php.` | High
2 | File | `/?explorer/upload/serverDownload` | High
3 | File | `/Actions.php` | Medium
4 | File | `/admin#themes` | High
5 | File | `/admin-cp/media` | High
6 | File | `/admin/?page=return/view_return` | High
7 | File | `/admin/add-subadmin.php` | High
8 | File | `/admin/add_cars.php` | High
9 | File | `/admin/admin_class.php` | High
10 | File | `/admin/admin_index.php` | High
11 | File | `/admin/all-applications.php` | High
12 | File | `/admin/approve_user.php` | High
13 | File | `/admin/bwdates-request-report-details.php` | High
14 | File | `/admin/category/add.do` | High
15 | File | `/admin/changeimage.php` | High
16 | File | `/admin/controller/faculty_controller.php` | High
17 | File | `/admin/delete-doctor.php` | High
18 | File | `/admin/delete_log.php` | High
19 | File | `/admin/disapprove_user.php` | High
20 | File | `/admin/edit-admin.php` | High
21 | File | `/admin/edit-guard-detail.php` | High
22 | File | `/admin/edit-products.php` | High
23 | File | `/admin/edituser.php` | High
24 | File | `/admin/edit_role.php` | High
25 | File | `/admin/edit_tax.php` | High
26 | File | `/admin/enrollment-details.php` | High
27 | File | `/admin/faculty_action.php` | High
28 | File | `/admin/forms/option_lists/edit.php` | High
29 | File | `/admin/index2.html` | High
30 | File | `/admin/login` | Medium
31 | File | `/admin/login.php` | High
32 | File | `/Admin/login.php` | High
33 | File | `/admin/manage-pages.php` | High
34 | File | `/admin/manage_user.php` | High
35 | File | `/admin/modules/instructor/index.php` | High
36 | File | `/admin/operations/booking.php` | High
37 | File | `/admin/operations/travellers.php` | High
38 | File | `/admin/seo_setting.php` | High
39 | File | `/Admin/sports.php` | High
40 | File | `/admin/userlist.php` | High
41 | File | `/admin/view-enquiry.php` | High
42 | File | `/admin/view-patient.php` | High
43 | File | `/adpweb/a/base/barcodeDetail/` | High
44 | File | `/ajax.php` | Medium
45 | File | `/ajax.php?action=delete_borrower` | High
46 | File | `/ajax.php?action=delete_plan` | High
47 | File | `/ajax.php?action=delete_sales` | High
48 | File | `/ajax.php?action=login` | High
49 | File | `/ajax.php?action=save_customer` | High
50 | File | `/ajax.php?action=save_package` | High
51 | File | `/ajax.php?action=save_receiving` | High
52 | File | `/ajax.php?action=save_supplier` | High
53 | File | `/api/` | Low
54 | File | `/api/advanced-search` | High
55 | File | `/api/areacliente/pessoa/validarCpf` | High
56 | File | `/api/blade-user/export-user` | High
57 | File | `/api/docs/index.php` | High
58 | File | `/api/plugin/uninstall` | High
59 | File | `/api/wizard/setsyncpppoecfg` | High
60 | File | `/app/controller/Api.php` | High
61 | File | `/application/controllers/Marks.php` | High
62 | File | `/attribute/queryAll` | High
63 | File | `/auth.asp` | Medium
64 | File | `/auth/orderQuery` | High
65 | File | `/backend/admin/his_admin_register_patient.php` | High
66 | File | `/backend/register.php` | High
67 | File | `/bic/ssoService/v1/applyCT` | High
68 | File | `/bin/httpd` | Medium
69 | File | `/blog/comment` | High
70 | File | `/boafrm/formFilter` | High
71 | File | `/boafrm/formParentControl` | High
72 | File | `/boafrm/formSaveConfig` | High
73 | File | `/boafrm/formWlSiteSurvey` | High
74 | File | `/booklist.php` | High
75 | File | `/branch/addbranch.php` | High
76 | File | `/browsemdcn.php` | High
77 | File | `/BRS_top.html` | High
78 | File | `/cashconfirm.php` | High
79 | File | `/cgi-bin/Config.cgi?action=set` | High
80 | File | `/cgi-bin/cstecgi.cgi` | High
81 | ... | ... | ...

There are 711 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.xlab.qianxin.com/super-large-scale-botnet-aisuru-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
