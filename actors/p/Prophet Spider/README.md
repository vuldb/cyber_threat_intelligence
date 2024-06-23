# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node&OBJ=/System/AdvancedSettings/DeviceSettings/MiscSettings` | High
2 | File | `/actuator/heapdump` | High
3 | File | `/admin` | Low
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/action/new-father.php` | High
7 | File | `/Admin/add-admin.php` | High
8 | File | `/admin/add-ambulance.php` | High
9 | File | `/admin/add_ikev2.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/applicants/controller.php` | High
12 | File | `/admin/applicants/index.php` | High
13 | File | `/admin/application-bwdates-reports-details.php` | High
14 | File | `/admin/booking-bwdates-reports-details.php` | High
15 | File | `/admin/category/controller.php` | High
16 | File | `/Admin/changepassword.php` | High
17 | File | `/admin/clients` | High
18 | File | `/admin/company/controller.php` | High
19 | File | `/admin/company/index.php` | High
20 | File | `/admin/config_ISCGroupNoCache.php` | High
21 | File | `/admin/config_MT.php?action=delete` | High
22 | File | `/admin/content` | High
23 | File | `/admin/court` | Medium
24 | File | `/admin/court-type` | High
25 | File | `/admin/div_data/delete?divId=9` | High
26 | File | `/admin/employee/controller.php` | High
27 | File | `/admin/employee/index.php` | High
28 | File | `/admin/expense-type` | High
29 | File | `/admin/foreigner-bwdates-reports-details.php` | High
30 | File | `/admin/foreigner-search.php` | High
31 | File | `/admin/forgot-password.php` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/index.php?page=categories` | High
34 | File | `/admin/index.php?page=manage_product` | High
35 | File | `/admin/list_crl_conf` | High
36 | File | `/admin/list_localuser.php` | High
37 | File | `/admin/login.php` | High
38 | File | `/admin/maintenance/manage_brand.php` | High
39 | File | `/admin/modules/product/controller.php?action=add` | High
40 | File | `/admin/mod_room/controller.php?action=add` | High
41 | File | `/admin/normal-bwdates-reports-details.php` | High
42 | File | `/admin/normal-search.php` | High
43 | File | `/admin/role` | Medium
44 | File | `/admin/search-directory.php.` | High
45 | File | `/admin/search.php` | High
46 | File | `/admin/tasks` | Medium
47 | File | `/admin/tax` | Medium
48 | File | `/admin/template` | High
49 | File | `/admin/twitter.php` | High
50 | File | `/admin/update-users.php` | High
51 | File | `/Admin/user-record.php` | High
52 | File | `/admin/user-search.php` | High
53 | File | `/admin/user/controller.php` | High
54 | File | `/admin/users.php` | High
55 | File | `/admin/vacancy/index.php` | High
56 | File | `/admin/vendor` | High
57 | File | `/adminPage/conf/reload` | High
58 | File | `/adminPage/conf/saveCmd` | High
59 | File | `/adminPage/main/upload` | High
60 | File | `/adminPage/www/addOver` | High
61 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
62 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
63 | File | `/adminpanel/admin/query/loginExe.php` | High
64 | File | `/admin_class.php` | High
65 | File | `/api/client/editemedia.php` | High
66 | File | `/api/v1/policies/validation/condition/` | High
67 | File | `/api/v2/maps` | Medium
68 | File | `/application/controller/Pelanggan.php` | High
69 | File | `/application/controller/Pengeluaran.php` | High
70 | File | `/apply/index.php` | High
71 | File | `/apps/system/api/user.go` | High
72 | File | `/apps/system/router/upload.go` | High
73 | File | `/apps/system/services/role_menu.go` | High
74 | File | `/assoc_table.php` | High
75 | File | `/backend/register.php` | High
76 | File | `/boafrm/formFilter` | High
77 | File | `/book-services.php` | High
78 | File | `/cancel.php` | Medium
79 | File | `/catalog/all-products` | High
80 | File | `/cgi-bin/cstecgi.cgi` | High
81 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
82 | File | `/cgi-bin/nas_sharing.cgi` | High
83 | File | `/classes/Master.php?f=load_registration` | High
84 | File | `/classes/Master.php?f=log_employee` | High
85 | File | `/classes/Master.php?f=log_visitor` | High
86 | File | `/classes/SystemSettings.php?f=update_settings` | High
87 | File | `/classes/Users.php?f=delete` | High
88 | File | `/classes/Users.php?f=save` | High
89 | File | `/conf/app.conf` | High
90 | File | `/control/addcase_stage.php` | High
91 | File | `/control/deactivate_case.php` | High
92 | File | `/control/register_case.php` | High
93 | File | `/controller/company/Index.php#sendCompanyLogo` | High
94 | File | `/dataSet/testTransform;swagger-ui` | High
95 | File | `/deletefile.php` | High
96 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
97 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
98 | File | `/doctor/view-appointment-detail.php` | High
99 | ... | ... | ...

There are 873 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
