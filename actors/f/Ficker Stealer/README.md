# Ficker Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ficker Stealer](https://vuldb.com/?actor.ficker_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ficker_stealer](https://vuldb.com/?actor.ficker_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ficker Stealer:

* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ficker Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.212.247](https://vuldb.com/?ip.2.56.212.247) | - | - | High
2 | [5.178.2.214](https://vuldb.com/?ip.5.178.2.214) | - | - | High
3 | [8.208.86.224](https://vuldb.com/?ip.8.208.86.224) | - | - | High
4 | [8.209.71.17](https://vuldb.com/?ip.8.209.71.17) | - | - | High
5 | [8.211.195.96](https://vuldb.com/?ip.8.211.195.96) | - | - | High
6 | [34.65.142.243](https://vuldb.com/?ip.34.65.142.243) | 243.142.65.34.bc.googleusercontent.com | - | Medium
7 | [34.90.166.4](https://vuldb.com/?ip.34.90.166.4) | 4.166.90.34.bc.googleusercontent.com | - | Medium
8 | [34.91.253.186](https://vuldb.com/?ip.34.91.253.186) | 186.253.91.34.bc.googleusercontent.com | - | Medium
9 | [34.94.171.115](https://vuldb.com/?ip.34.94.171.115) | 115.171.94.34.bc.googleusercontent.com | - | Medium
10 | [34.106.112.240](https://vuldb.com/?ip.34.106.112.240) | 240.112.106.34.bc.googleusercontent.com | - | Medium
11 | [35.203.73.169](https://vuldb.com/?ip.35.203.73.169) | 169.73.203.35.bc.googleusercontent.com | - | Medium
12 | [35.228.242.21](https://vuldb.com/?ip.35.228.242.21) | 21.242.228.35.bc.googleusercontent.com | - | Medium
13 | [37.0.8.225](https://vuldb.com/?ip.37.0.8.225) | avilalee.cartierevannucci.com | - | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ficker Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ficker Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adicionar-cliente.php` | High
2 | File | `/admin/` | Low
3 | File | `/admin/?page=products/view_product` | High
4 | File | `/admin/?page=system_info` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/add-doctor.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/admin-update-employee.php` | High
10 | File | `/admin/admin.php` | High
11 | File | `/admin/ajax.php?action=confirm_order` | High
12 | File | `/admin/ajax.php?action=login` | High
13 | File | `/admin/ajax.php?action=save_settings` | High
14 | File | `/admin/app/profile_crud.php` | High
15 | File | `/admin/article/article-add.php` | High
16 | File | `/admin/booking-search.php` | High
17 | File | `/admin/booktime.php` | High
18 | File | `/admin/campsdetails.php` | High
19 | File | `/admin/candidates_row.php` | High
20 | File | `/admin/casedetails.php` | High
21 | File | `/admin/cashadvance_row.php` | High
22 | File | `/admin/category/controller.php` | High
23 | File | `/admin/company/index.php` | High
24 | File | `/admin/config_save.php` | High
25 | File | `/admin/contact-us.php` | High
26 | File | `/admin/content` | High
27 | File | `/admin/div_data/delete?divId=9` | High
28 | File | `/admin/edit-customer-detailed.php` | High
29 | File | `/Admin/edit-photo.php` | High
30 | File | `/admin/edit_categories.php` | High
31 | File | `/admin/edit_category.php` | High
32 | File | `/admin/edit_teacher.php` | High
33 | File | `/admin/forms/option_lists/edit.php` | High
34 | File | `/admin/googleads.php` | High
35 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
36 | File | `/admin/index.php` | High
37 | File | `/admin/inquiries/view_inquiry.php` | High
38 | File | `/admin/judge` | Medium
39 | File | `/admin/leancloud.php` | High
40 | File | `/Admin/login.php` | High
41 | File | `/admin/maintenance/manage_brand.php` | High
42 | File | `/admin/maintenance/manage_department.php` | High
43 | File | `/admin/manage-students.php` | High
44 | File | `/admin/manage-users.php` | High
45 | File | `/admin/manage_model.php` | High
46 | File | `/admin/menu/toEdit` | High
47 | File | `/admin/operations/expense_category.php` | High
48 | File | `/admin/order.php` | High
49 | File | `/admin/pages/` | High
50 | File | `/admin/pages/student-print.php` | High
51 | File | `/admin/products/manage_product.php` | High
52 | File | `/admin/request-received-bydonar.php` | High
53 | File | `/admin/sales/view_details.php` | High
54 | File | `/admin/search-appointment.php` | High
55 | File | `/admin/students.php` | High
56 | File | `/admin/system.php` | High
57 | File | `/admin/test_status.php` | High
58 | File | `/admin/update-clients.php` | High
59 | File | `/admin/uploads/` | High
60 | File | `/admin/user-search.php` | High
61 | File | `/admin/user/index.php` | High
62 | File | `/admin/user/manage_user.php` | High
63 | File | `/admin/users.php` | High
64 | File | `/admin/view-enquiry.php` | High
65 | File | `/adminapi/system/crud` | High
66 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
67 | File | `/admin_class.php` | High
68 | File | `/ajax.php?action=save_establishment` | High
69 | File | `/ajax/getBasicInfo.php` | High
70 | File | `/animalsadd.php` | High
71 | File | `/animalsupdate.php` | High
72 | File | `/api/controllers/admin/app/ComboController.php` | High
73 | File | `/api/DataDictionary/GetItemList` | High
74 | File | `/api/sys/set_passwd` | High
75 | File | `/api/v1/toolbox/device/update/swap` | High
76 | File | `/app/controller/Setup.php` | High
77 | File | `/App/Core/Extend/Function/ydLib.php` | High
78 | File | `/app/uploading/upload-mp3.php` | High
79 | File | `/application/index/controller/File.php` | High
80 | File | `/application/index/controller/Unity.php` | High
81 | File | `/apps/login_auth.php` | High
82 | File | `/artist-display.php` | High
83 | File | `/bin/httpd` | Medium
84 | File | `/bolt/editcontent/showcases` | High
85 | File | `/cas/logout` | Medium
86 | File | `/category.php` | High
87 | File | `/cgi-bin/cstecgi.cgi` | High
88 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
89 | File | `/cgi-bin/hd_config.cgi` | High
90 | File | `/cgi-bin/photocenter_mgr.cgi` | High
91 | File | `/cgi-bin/tosei_kikai.php` | High
92 | ... | ... | ...

There are 811 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/53eb34b5a1decc113a67803db9a49cc844958fe9d33b645183b870f5d1ac7901/
* https://threatfox.abuse.ch
* https://twitter.com/0xrb/status/1627623872832086016?s=20
* https://urlhaus.abuse.ch/url/918649/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
