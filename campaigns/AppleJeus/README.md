# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

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
23 | File | `/admin/case-type` | High
24 | File | `/admin/category/controller.php` | High
25 | File | `/admin/company/controller.php` | High
26 | File | `/admin/company/index.php` | High
27 | File | `/admin/config_Anticrack.php` | High
28 | File | `/admin/config_ISCGroupNoCache.php` | High
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
42 | File | `/admin/list_ipAddressPolicy.php` | High
43 | File | `/admin/login.php` | High
44 | File | `/admin/maintenance/manage_brand.php` | High
45 | File | `/admin/manage-ambulance.php` | High
46 | File | `/admin/manage-students.php` | High
47 | File | `/admin/menu/toEdit` | High
48 | File | `/admin/receipt.php` | High
49 | File | `/admin/rooms.php` | High
50 | File | `/admin/search.php` | High
51 | File | `/admin/update-rooms.php` | High
52 | File | `/admin/update-users.php` | High
53 | File | `/admin/user-search.php` | High
54 | File | `/admin/user/controller.php` | High
55 | File | `/admin/user/index.php` | High
56 | File | `/admin/users.php` | High
57 | File | `/admin/users_photo.php` | High
58 | File | `/admin/vacancy/controller.php` | High
59 | File | `/admin/vacancy/index.php` | High
60 | File | `/admin/view_sendlist.php` | High
61 | File | `/adminPage/conf/reload` | High
62 | File | `/adminPage/main/upload` | High
63 | File | `/adminPage/www/addOver` | High
64 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
65 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
66 | File | `/adminpanel/admin/query/addCourseExe.php` | High
67 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
68 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
69 | ... | ... | ...

There are 606 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
