# Cisco - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cisco_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cisco:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cisco or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cisco.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.43.231](https://vuldb.com/?ip.5.61.43.231) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [5.165.200.7](https://vuldb.com/?ip.5.165.200.7) | 5x165x200x7.dynamic.saratov.ertelecom.ru | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [5.183.253.129](https://vuldb.com/?ip.5.183.253.129) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [24.6.144.43](https://vuldb.com/?ip.24.6.144.43) | c-24-6-144-43.hsd1.ca.comcast.net | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [31.184.236.63](https://vuldb.com/?ip.31.184.236.63) | zemal.kiprises.net | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [31.184.236.71](https://vuldb.com/?ip.31.184.236.71) | miseria.independentbookstores.net | [Unknown](https://vuldb.com/?actor.unknown) | High
7 | [31.184.236.79](https://vuldb.com/?ip.31.184.236.79) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
8 | [45.32.141.138](https://vuldb.com/?ip.45.32.141.138) | 45.32.141.138.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
9 | [45.32.228.189](https://vuldb.com/?ip.45.32.228.189) | 45.32.228.189.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
10 | [45.32.228.190](https://vuldb.com/?ip.45.32.228.190) | 45.32.228.190.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
11 | [45.55.36.143](https://vuldb.com/?ip.45.55.36.143) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
12 | [45.61.136.5](https://vuldb.com/?ip.45.61.136.5) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
13 | [45.61.136.83](https://vuldb.com/?ip.45.61.136.83) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
14 | [45.61.136.207](https://vuldb.com/?ip.45.61.136.207) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
15 | [45.66.209.122](https://vuldb.com/?ip.45.66.209.122) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
16 | [45.80.107.220](https://vuldb.com/?ip.45.80.107.220) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
17 | [45.145.67.170](https://vuldb.com/?ip.45.145.67.170) | sirio.rhinorepublic.xyz | [Unknown](https://vuldb.com/?actor.unknown) | High
18 | [45.227.252.237](https://vuldb.com/?ip.45.227.252.237) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
19 | [45.227.255.51](https://vuldb.com/?ip.45.227.255.51) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
20 | [45.227.255.215](https://vuldb.com/?ip.45.227.255.215) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
21 | [46.161.27.117](https://vuldb.com/?ip.46.161.27.117) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
22 | [46.161.27.123](https://vuldb.com/?ip.46.161.27.123) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
23 | [52.154.0.241](https://vuldb.com/?ip.52.154.0.241) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
24 | ... | ... | ... | ...

There are 90 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cisco. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cisco. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `-X/path/to/wwwroot/file.php.` | High
2 | File | `/?explorer/upload/serverDownload` | High
3 | File | `/Actions.php` | Medium
4 | File | `/admin#themes` | High
5 | File | `/admin-cp/media` | High
6 | File | `/admin/?page=return/view_return` | High
7 | File | `/admin/action/update-deworm.php` | High
8 | File | `/admin/add-subadmin.php` | High
9 | File | `/admin/add_cars.php` | High
10 | File | `/admin/admin_class.php` | High
11 | File | `/admin/admin_index.php` | High
12 | File | `/admin/all-applications.php` | High
13 | File | `/admin/approve_user.php` | High
14 | File | `/admin/bwdates-request-report-details.php` | High
15 | File | `/admin/category/add.do` | High
16 | File | `/admin/changeimage.php` | High
17 | File | `/admin/controller/faculty_controller.php` | High
18 | File | `/admin/delete-doctor.php` | High
19 | File | `/admin/delete_log.php` | High
20 | File | `/admin/delete_pending.php` | High
21 | File | `/admin/disapprove_user.php` | High
22 | File | `/admin/edit-admin.php` | High
23 | File | `/admin/edit-animal-details.php` | High
24 | File | `/admin/edit-guard-detail.php` | High
25 | File | `/admin/edit-products.php` | High
26 | File | `/admin/edituser.php` | High
27 | File | `/admin/edit_role.php` | High
28 | File | `/admin/edit_tax.php` | High
29 | File | `/admin/enrollment-details.php` | High
30 | File | `/admin/faculty_action.php` | High
31 | File | `/admin/forms/option_lists/edit.php` | High
32 | File | `/admin/index2.html` | High
33 | File | `/admin/login` | Medium
34 | File | `/admin/login.php` | High
35 | File | `/Admin/login.php` | High
36 | File | `/admin/manage-pages.php` | High
37 | File | `/admin/manage_complaint.php` | High
38 | File | `/admin/manage_user.php` | High
39 | File | `/admin/member_save.php` | High
40 | File | `/admin/modules/instructor/index.php` | High
41 | File | `/admin/operations/booking.php` | High
42 | File | `/admin/operations/travellers.php` | High
43 | File | `/admin/search-property.php` | High
44 | File | `/admin/seo_setting.php` | High
45 | File | `/Admin/sports.php` | High
46 | File | `/admin/userlist.php` | High
47 | File | `/admin/view-appointment.php?viewid=11` | High
48 | File | `/admin/view-enquiry.php` | High
49 | File | `/admin/view-patient.php` | High
50 | File | `/adpweb/a/base/barcodeDetail/` | High
51 | File | `/ajax.php` | Medium
52 | File | `/ajax.php?action=delete_borrower` | High
53 | File | `/ajax.php?action=delete_plan` | High
54 | File | `/ajax.php?action=delete_sales` | High
55 | File | `/ajax.php?action=login` | High
56 | File | `/ajax.php?action=save_customer` | High
57 | File | `/ajax.php?action=save_package` | High
58 | File | `/ajax.php?action=save_receiving` | High
59 | File | `/ajax.php?action=save_supplier` | High
60 | File | `/api/` | Low
61 | File | `/api/advanced-search` | High
62 | File | `/api/blade-user/export-user` | High
63 | File | `/api/docs/index.php` | High
64 | File | `/api/plugin/uninstall` | High
65 | File | `/app/controller/Api.php` | High
66 | File | `/app/Http/Controllers/ImageController.php` | High
67 | File | `/application/controllers/Marks.php` | High
68 | File | `/attribute/queryAll` | High
69 | File | `/auth/orderQuery` | High
70 | File | `/backend/admin/his_admin_register_patient.php` | High
71 | File | `/backend/register.php` | High
72 | File | `/bic/ssoService/v1/applyCT` | High
73 | File | `/bin/httpd` | Medium
74 | File | `/blog` | Low
75 | File | `/blog/comment` | High
76 | File | `/boafrm/formFilter` | High
77 | File | `/boafrm/formParentControl` | High
78 | File | `/boafrm/formSaveConfig` | High
79 | File | `/boafrm/formWlSiteSurvey` | High
80 | File | `/booklist.php` | High
81 | File | `/branch/addbranch.php` | High
82 | File | `/browsemdcn.php` | High
83 | File | `/BRS_top.html` | High
84 | ... | ... | ...

There are 740 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2022/08/recent-cyber-attack.html
* https://www.rapid7.com/blog/post/2023/08/29/under-siege-rapid7-observed-exploitation-of-cisco-asa-ssl-vpns/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
