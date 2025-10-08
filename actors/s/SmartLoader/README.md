# SmartLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SmartLoader](https://vuldb.com/?actor.smartloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.smartloader](https://vuldb.com/?actor.smartloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmartLoader:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SmartLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [77.105.164.40](https://vuldb.com/?ip.77.105.164.40) | 2366squidsbased.example.com | - | High
2 | [77.105.164.59](https://vuldb.com/?ip.77.105.164.59) | - | - | High
3 | [77.105.164.65](https://vuldb.com/?ip.77.105.164.65) | - | - | High
4 | [77.105.164.178](https://vuldb.com/?ip.77.105.164.178) | 3292squidsbased.example.com | - | High
5 | [80.66.81.11](https://vuldb.com/?ip.80.66.81.11) | zaroshiico.com | - | High
6 | [80.66.81.134](https://vuldb.com/?ip.80.66.81.134) | argentajagneaux2.serv.host | - | High
7 | [80.66.85.195](https://vuldb.com/?ip.80.66.85.195) | plokas.serv.host | - | High
8 | [80.66.89.146](https://vuldb.com/?ip.80.66.89.146) | argentajagneaux.serv.host | - | High
9 | [80.66.89.161](https://vuldb.com/?ip.80.66.89.161) | mudriedmouse604.serv.host | - | High
10 | [80.66.89.165](https://vuldb.com/?ip.80.66.89.165) | mudriedmouse6041.serv.host | - | High
11 | [87.120.36.50](https://vuldb.com/?ip.87.120.36.50) | - | - | High
12 | [89.169.12.42](https://vuldb.com/?ip.89.169.12.42) | apicuke5917.serv.host | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SmartLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SmartLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/action.php` | Medium
3 | File | `/Actions.php` | Medium
4 | File | `/activation.php` | High
5 | File | `/actuator` | Medium
6 | File | `/ad-list` | Medium
7 | File | `/adaddmed.php` | High
8 | File | `/addCatController.php` | High
9 | File | `/addcategory.php` | High
10 | File | `/addclient1.php` | High
11 | File | `/addelidetails.php` | High
12 | File | `/addelivery.php` | High
13 | File | `/addstock.php` | High
14 | File | `/add_achievement_details.php` | High
15 | File | `/admin#article/edit?id=2` | High
16 | File | `/admin#themes` | High
17 | File | `/admin-dashboard` | High
18 | File | `/admin-inbox.php` | High
19 | File | `/admin-page.php` | High
20 | File | `/admin-profile.php` | High
21 | File | `/admin.php` | Medium
22 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
23 | File | `/admin/?page=system_info` | High
24 | File | `/admin/about-us.php` | High
25 | File | `/Admin/add-admin.php` | High
26 | File | `/admin/add-admin.php` | High
27 | File | `/admin/add-boat.php` | High
28 | File | `/admin/add-customer-services.php` | High
29 | File | `/admin/add-propertytype.php` | High
30 | File | `/admin/add-services.php` | High
31 | File | `/admin/adminprofile.php` | High
32 | File | `/admin/ajax.php?action=login` | High
33 | File | `/admin/allemployees.php` | High
34 | File | `/admin/approve_user.php` | High
35 | File | `/admin/booking_report.php` | High
36 | File | `/admin/borrow_add.php` | High
37 | File | `/admin/bwdates-reports-details.php` | High
38 | File | `/admin/candidates_add.php` | High
39 | File | `/admin/categories/save` | High
40 | File | `/admin/comment/list` | High
41 | File | `/admin/config/express` | High
42 | File | `/admin/doctor-specilization.php` | High
43 | File | `/admin/edit-nurse.php` | High
44 | File | `/admin/edit-propertytype.php` | High
45 | File | `/admin/email_setup.php` | High
46 | File | `/admin/index.php` | High
47 | File | `/admin/index.php/web/ajax_all_lists` | High
48 | File | `/admin/insert-product.php` | High
49 | File | `/admin/manage-directory.php` | High
50 | File | `/admin/manage_complaint.php` | High
51 | File | `/admin/network/ajax_getChannelList` | High
52 | File | `/admin/network/diag_iperf` | High
53 | File | `/admin/network/diag_nslookup` | High
54 | File | `/admin/network/diag_traceroute6` | High
55 | File | `/admin/operations/booking.php` | High
56 | File | `/admin/operations/expense_category.php` | High
57 | File | `/admin/operations/packages.php` | High
58 | File | `/admin/operations/payment.php` | High
59 | File | `/admin/operations/travellers.php` | High
60 | File | `/admin/page-login.php` | High
61 | File | `/admin/password-recovery.php` | High
62 | File | `/admin/print1.php` | High
63 | File | `/admin/products.php` | High
64 | File | `/admin/profile.php` | High
65 | File | `/admin/regester.php` | High
66 | File | `/Admin/registration.php` | High
67 | File | `/admin/reset-password.php` | High
68 | File | `/admin/save_airlines.php` | High
69 | File | `/admin/search-directory.php` | High
70 | File | `/admin/search-invoices.php` | High
71 | File | `/admin/search-maid.php` | High
72 | File | `/admin/search.php` | High
73 | File | `/admin/session.php` | High
74 | File | `/admin/sms_setting.php` | High
75 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
76 | File | `/admin/tag/save` | High
77 | File | `/admin/team_save.php` | High
78 | File | `/admin/topic/list` | High
79 | File | `/admin/update_room.php` | High
80 | File | `/admin/update_s8.php` | High
81 | File | `/admin/user-search.php` | High
82 | File | `/admin/user/manage_user.php` | High
83 | File | `/admin/users.php` | High
84 | File | `/admin/view-appointment.php` | High
85 | File | `/admin?do=admin:user:editPost` | High
86 | File | `/adphar.php` | Medium
87 | File | `/adposition/queryAll` | High
88 | File | `/ajax.php?action=delete_allowances` | High
89 | File | `/ajax.php?action=delete_user` | High
90 | File | `/api/account` | Medium
91 | File | `/api/role` | Medium
92 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
93 | File | `/api/upload` | Medium
94 | File | `/api/wechat/app_auth` | High
95 | File | `/app/api/controller/Site.php` | High
96 | File | `/app/control/byt_cv_manager` | High
97 | File | `/backend/register.php` | High
98 | File | `/bank/mnotice.php` | High
99 | File | `/bank/statements.php` | High
100 | File | `/bank/transfer.php` | High
101 | File | `/boafrm/formFilter` | High
102 | File | `/boafrm/formMultiAPVLAN` | High
103 | File | `/book-appointment.php` | High
104 | File | `/book_car.php` | High
105 | File | `/browsemdcn.php` | High
106 | File | `/bsc_lan.php` | Medium
107 | File | `/bwdates-report-result.php` | High
108 | File | `/cardo/api` | Medium
109 | File | `/cart_add.php` | High
110 | File | `/cart_remove.php` | High
111 | File | `/cgi-bin/Config.cgi?action=set` | High
112 | File | `/cgi-bin/cstecgi.cgi` | High
113 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
114 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
115 | File | `/cgi-bin/webdav_mgr.cgi` | High
116 | File | `/cgi-bin/widget_api.cgi` | High
117 | File | `/chat/group/send` | High
118 | File | `/clients` | Medium
119 | ... | ... | ...

There are 1054 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/7ce0eb95-f936-4d8a-bae2-50a51c741b98
* https://app.any.run/tasks/f08ed7f8-f60c-4ad9-8f7d-7dc0125f5a86
* https://asec.ahnlab.com/en/89551/
* https://bazaar.abuse.ch/sample/4833e3f6c520312f6cc2716fb89a31c86e143e410305ffdff072786bce948e0c/
* https://bazaar.abuse.ch/sample/27817cb00db5746496c10138655beddb88f5733866452be4bbd51481dbb4a08d/
* https://bazaar.abuse.ch/sample/ac8e9c3db9933684515f091b2637bce105febd069ab8fe6fb0e0ac3caba1ee8b/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
