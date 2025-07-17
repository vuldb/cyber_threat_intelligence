# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 1 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
3 | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\1E\Client\Tachyon.Performance.Metrics.exe` | High
2 | File | `/account/delivery` | High
3 | File | `/adama/adama/downloadService` | High
4 | File | `/add-customer.php` | High
5 | File | `/add-notes.php` | High
6 | File | `/addCatController.php` | High
7 | File | `/adds.php` | Medium
8 | File | `/addstock.php` | High
9 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
10 | File | `/admin/` | Low
11 | File | `/admin/?/layout/edit/1` | High
12 | File | `/admin/?/page/delete/10` | High
13 | File | `/admin/?/snippet/delete/3` | High
14 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
15 | File | `/admin/?page=products/view_product` | High
16 | File | `/admin/?page=user/manage` | High
17 | File | `/admin/about-us.php` | High
18 | File | `/admin/aboutPost.php` | High
19 | File | `/admin/aboutus.php` | High
20 | File | `/Admin/add-admin.php` | High
21 | File | `/admin/add-art-medium.php` | High
22 | File | `/admin/add-art-type.php` | High
23 | File | `/admin/add-customer.php` | High
24 | File | `/admin/add_cars.php` | High
25 | File | `/admin/adminprofile.php` | High
26 | File | `/admin/ajax.php` | High
27 | File | `/admin/allemployees.php` | High
28 | File | `/admin/api/admin/v2_products` | High
29 | File | `/admin/article.php?action=upload_cover` | High
30 | File | `/admin/backup/backups.php` | High
31 | File | `/admin/bwdates-report-details.php` | High
32 | File | `/admin/categories/manage_category.php` | High
33 | File | `/admin/change-password.php` | High
34 | File | `/admin/contact-us.php` | High
35 | File | `/admin/core/update_student.php` | High
36 | File | `/admin/delete-row.php` | High
37 | File | `/admin/delete-session.php` | High
38 | File | `/admin/deleteBooking.php` | High
39 | File | `/admin/edit-category.php` | High
40 | File | `/admin/edit-guard-detail.php` | High
41 | File | `/admin/edit-pass-detail.php` | High
42 | File | `/admin/edit-subadmin.php` | High
43 | File | `/Admin/EditCity.php` | High
44 | File | `/admin/edit_categories.php` | High
45 | File | `/admin/edit_manufacturer.php` | High
46 | File | `/admin/edit_product.php` | High
47 | File | `/admin/edit_user.php` | High
48 | File | `/admin/forms/option_lists/edit.php` | High
49 | File | `/admin/home.php?con=add` | High
50 | File | `/admin/index.php` | High
51 | File | `/admin/login.php` | High
52 | File | `/admin/manage_model.php` | High
53 | File | `/admin/overtime_add.php` | High
54 | File | `/admin/plugin.php` | High
55 | File | `/admin/profile.php` | High
56 | File | `/admin/reservation_view.php` | High
57 | File | `/admin/save.php` | High
58 | File | `/admin/search-maid.php` | High
59 | File | `/admin/users.php` | High
60 | File | `/admin/users_photo.php` | High
61 | File | `/admin/view_reserved.php` | High
62 | File | `/admin/view_sendlist.php` | High
63 | File | `/admin/visitor-details.php` | High
64 | File | `/ajax.php?action=read_msg` | High
65 | File | `/ajax.php?action=save_package` | High
66 | File | `/ajax.php?action=save_quiz` | High
67 | File | `/api/client/article/list` | High
68 | File | `/api/database/testConnect` | High
69 | File | `/api/user` | Medium
70 | File | `/api/v1/attack/token` | High
71 | File | `/api/wizard/setLanguage` | High
72 | File | `/app/admin/controller/Upload.php` | High
73 | File | `/appinfo/save` | High
74 | File | `/b2b-supermarket/shopping-cart` | High
75 | File | `/billing/pms_check.php` | High
76 | File | `/bin/httpd` | Medium
77 | File | `/birthing_pending.php` | High
78 | File | `/blog` | Low
79 | File | `/boafrm/formDosCfg` | High
80 | File | `/boafrm/formMultiAP` | High
81 | File | `/boafrm/formRoute` | High
82 | File | `/boafrm/formSysLog` | High
83 | File | `/boafrm/formWlSiteSurvey` | High
84 | File | `/boafrm/formWsc` | High
85 | File | `/catalog/all-products` | High
86 | File | `/cfgFile/1/download` | High
87 | File | `/cgi-bin/cstecgi.cgi` | High
88 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
89 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
90 | ... | ... | ...

There are 794 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
