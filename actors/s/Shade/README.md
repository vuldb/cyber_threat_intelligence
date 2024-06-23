# Shade - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shade](https://vuldb.com/?actor.shade). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shade](https://vuldb.com/?actor.shade)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shade:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shade.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.66](https://vuldb.com/?ip.5.9.116.66) | static.66.116.9.5.clients.your-server.de | - | High
2 | [5.9.158.75](https://vuldb.com/?ip.5.9.158.75) | static.75.158.9.5.clients.your-server.de | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.6.22.189](https://vuldb.com/?ip.23.6.22.189) | a23-6-22-189.deploy.static.akamaitechnologies.com | - | High
5 | [37.157.254.113](https://vuldb.com/?ip.37.157.254.113) | rs004106.root.server-hosting.expert | - | High
6 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | - | High
7 | [46.166.182.20](https://vuldb.com/?ip.46.166.182.20) | - | - | High
8 | [47.101.49.13](https://vuldb.com/?ip.47.101.49.13) | - | - | High
9 | [51.68.204.139](https://vuldb.com/?ip.51.68.204.139) | ns3127231.ip-51-68-204.eu | - | High
10 | [51.68.206.28](https://vuldb.com/?ip.51.68.206.28) | ns3128207.ip-51-68-206.eu | - | High
11 | [62.151.180.62](https://vuldb.com/?ip.62.151.180.62) | mx18062.brandengager.info | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shade_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shade. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?g=net_pro_keyword_import_save` | High
3 | File | `/actuator/heapdump` | High
4 | File | `/admin` | Low
5 | File | `/Admin/add-admin.php` | High
6 | File | `/admin/addgiving.php` | High
7 | File | `/admin/addTithes.php` | High
8 | File | `/admin/add_ikev2.php` | High
9 | File | `/admin/add_postlogin.php` | High
10 | File | `/admin/add_sundaysch.php` | High
11 | File | `/admin/admin-profile.php` | High
12 | File | `/admin/admin.php` | High
13 | File | `/admin/adminHome.php` | High
14 | File | `/admin/admin_cl.php?mudi=revPwd` | High
15 | File | `/admin/admin_user.php` | High
16 | File | `/admin/applicants/controller.php` | High
17 | File | `/admin/applicants/index.php` | High
18 | File | `/admin/application-bwdates-reports-details.php` | High
19 | File | `/admin/bookdate.php` | High
20 | File | `/admin/booking-bwdates-reports-details.php` | High
21 | File | `/admin/booking-search.php` | High
22 | File | `/admin/booktime.php` | High
23 | File | `/admin/category/controller.php` | High
24 | File | `/admin/company/controller.php` | High
25 | File | `/admin/company/index.php` | High
26 | File | `/admin/config_Anticrack.php` | High
27 | File | `/admin/config_ISCGroupNoCache.php` | High
28 | File | `/admin/config_MT.php?action=delete` | High
29 | File | `/admin/contact-us.php` | High
30 | File | `/admin/delete_log.php` | High
31 | File | `/admin/div_data/delete?divId=9` | High
32 | File | `/Admin/edit-photo.php` | High
33 | File | `/admin/edit-post.php` | High
34 | File | `/admin/edit-services.php` | High
35 | File | `/Admin/edit_profile.php` | High
36 | File | `/admin/employee/controller.php` | High
37 | File | `/admin/employee/index.php` | High
38 | File | `/admin/forgot-password.php` | High
39 | File | `/admin/general-setting` | High
40 | File | `/admin/index.php` | High
41 | File | `/admin/list_crl_conf` | High
42 | File | `/admin/login.php` | High
43 | File | `/admin/maintenance/manage_brand.php` | High
44 | File | `/admin/makehtml_freelist_action.php` | High
45 | File | `/admin/manage-ambulance.php` | High
46 | File | `/admin/manage-students.php` | High
47 | File | `/admin/menu/toEdit` | High
48 | File | `/Admin/News.php` | High
49 | File | `/admin/normal-bwdates-reports-details.php` | High
50 | File | `/admin/receipt.php` | High
51 | File | `/admin/rooms.php` | High
52 | File | `/admin/search.php` | High
53 | File | `/admin/update-rooms.php` | High
54 | File | `/admin/update-users.php` | High
55 | File | `/admin/update_s6.php` | High
56 | File | `/admin/user-search.php` | High
57 | File | `/admin/user/controller.php` | High
58 | File | `/admin/user/index.php` | High
59 | File | `/admin/users.php` | High
60 | File | `/admin/users_photo.php` | High
61 | File | `/admin/vacancy/controller.php` | High
62 | File | `/admin/vacancy/index.php` | High
63 | File | `/admin/view_sendlist.php` | High
64 | File | `/adminPage/conf/reload` | High
65 | File | `/adminPage/main/upload` | High
66 | File | `/adminPage/www/addOver` | High
67 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
68 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
69 | File | `/adminpanel/admin/query/addCourseExe.php` | High
70 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
71 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
72 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
73 | File | `/adminpanel/admin/query/loginExe.php` | High
74 | File | `/admin_class.php` | High
75 | File | `/ad_js.php` | Medium
76 | File | `/api.php` | Medium
77 | File | `/api/blade-user/export-user` | High
78 | File | `/api/client/editemedia.php` | High
79 | File | `/api/controllers/admin/app/AppController.php` | High
80 | File | `/api/controllers/admin/app/ComboController.php` | High
81 | File | `/api/controllers/common/UploadsController.php` | High
82 | File | `/api/controllers/merchant/app/ComboController.php` | High
83 | File | `/api/controllers/merchant/design/MaterialController.php` | High
84 | File | `/api/controllers/merchant/shop/PosterController.php` | High
85 | File | `/api/process.php` | High
86 | File | `/api/v1/toolbox/device/update/swap` | High
87 | File | `/app/admin/controller/Upload.php` | High
88 | ... | ... | ...

There are 780 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0906-0913.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0920-0927.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1025-1101.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
