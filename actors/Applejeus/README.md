# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Applejeus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | - | High
2 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | - | High
3 | [95.213.232.170](https://vuldb.com/?ip.95.213.232.170) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Applejeus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-29 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/actuator/heapdump` | High
3 | File | `/Admin/add-admin.php` | High
4 | File | `/admin/addgiving.php` | High
5 | File | `/admin/addTithes.php` | High
6 | File | `/admin/add_ikev2.php` | High
7 | File | `/admin/add_postlogin.php` | High
8 | File | `/admin/add_sundaysch.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/admin.php` | High
11 | File | `/admin/adminHome.php` | High
12 | File | `/admin/admin_cl.php?mudi=revPwd` | High
13 | File | `/admin/admin_user.php` | High
14 | File | `/admin/applicants/controller.php` | High
15 | File | `/admin/applicants/index.php` | High
16 | File | `/admin/application-bwdates-reports-details.php` | High
17 | File | `/admin/bookdate.php` | High
18 | File | `/admin/booking-bwdates-reports-details.php` | High
19 | File | `/admin/booking-search.php` | High
20 | File | `/admin/booktime.php` | High
21 | File | `/admin/category/controller.php` | High
22 | File | `/admin/company/controller.php` | High
23 | File | `/admin/company/index.php` | High
24 | File | `/admin/config_Anticrack.php` | High
25 | File | `/admin/config_ISCGroupNoCache.php` | High
26 | File | `/admin/contact-us.php` | High
27 | File | `/admin/delete_log.php` | High
28 | File | `/admin/div_data/delete?divId=9` | High
29 | File | `/Admin/edit-photo.php` | High
30 | File | `/admin/edit-post.php` | High
31 | File | `/admin/edit-services.php` | High
32 | File | `/Admin/edit_profile.php` | High
33 | File | `/admin/employee/controller.php` | High
34 | File | `/admin/employee/index.php` | High
35 | File | `/admin/forgot-password.php` | High
36 | File | `/admin/index.php` | High
37 | File | `/admin/list_crl_conf` | High
38 | File | `/admin/list_ipAddressPolicy.php` | High
39 | File | `/admin/login.php` | High
40 | File | `/admin/manage-ambulance.php` | High
41 | File | `/admin/manage-students.php` | High
42 | File | `/admin/menu/toEdit` | High
43 | File | `/admin/receipt.php` | High
44 | File | `/admin/rooms.php` | High
45 | File | `/admin/search.php` | High
46 | File | `/admin/update-rooms.php` | High
47 | File | `/admin/update-users.php` | High
48 | File | `/admin/user-search.php` | High
49 | File | `/admin/user/controller.php` | High
50 | File | `/admin/user/index.php` | High
51 | File | `/admin/users.php` | High
52 | File | `/admin/users_photo.php` | High
53 | File | `/admin/vacancy/controller.php` | High
54 | File | `/admin/vacancy/index.php` | High
55 | File | `/admin/view_sendlist.php` | High
56 | File | `/adminPage/conf/reload` | High
57 | File | `/adminPage/main/upload` | High
58 | File | `/adminPage/www/addOver` | High
59 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
60 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
61 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
62 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
63 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
64 | File | `/adminpanel/admin/query/loginExe.php` | High
65 | File | `/api/blade-user/export-user` | High
66 | File | `/api/client/editemedia.php` | High
67 | ... | ... | ...

There are 588 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
