# Fallchill - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fallchill_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fallchill:

* [VN](https://vuldb.com/?country.vn)

## Actors

These _actors_ are associated with Fallchill or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fallchill.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.79.99.169](https://vuldb.com/?ip.5.79.99.169) | nsg037-19.divide.nl | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [27.123.221.66](https://vuldb.com/?ip.27.123.221.66) | 66-221.fiber.net.id | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [36.71.90.4](https://vuldb.com/?ip.36.71.90.4) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [41.92.208.194](https://vuldb.com/?ip.41.92.208.194) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [41.92.208.196](https://vuldb.com/?ip.41.92.208.196) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [41.92.208.197](https://vuldb.com/?ip.41.92.208.197) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [50.62.168.157](https://vuldb.com/?ip.50.62.168.157) | p3nwvpweb145.shr.prod.phx3.secureserver.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
8 | [59.90.93.138](https://vuldb.com/?ip.59.90.93.138) | static.bb.knl.59.90.93.138.bsnl.in | [Lazarus](https://vuldb.com/?actor.lazarus) | High
9 | [62.243.45.227](https://vuldb.com/?ip.62.243.45.227) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
10 | [64.29.144.201](https://vuldb.com/?ip.64.29.144.201) | ntfw1c25.carrierzone.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
11 | [66.175.41.191](https://vuldb.com/?ip.66.175.41.191) | winVIPnatfl.hostopia.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
12 | [66.232.121.65](https://vuldb.com/?ip.66.232.121.65) | 66-232-121-65.static.hvvc.us | [Lazarus](https://vuldb.com/?actor.lazarus) | High
13 | [66.242.128.11](https://vuldb.com/?ip.66.242.128.11) | hdflns11.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
14 | [66.242.128.12](https://vuldb.com/?ip.66.242.128.12) | hdflns12.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
15 | [66.242.128.13](https://vuldb.com/?ip.66.242.128.13) | hdflns13.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
16 | [66.242.128.134](https://vuldb.com/?ip.66.242.128.134) | hdflsf03.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
17 | [66.242.128.140](https://vuldb.com/?ip.66.242.128.140) | hdflsf01.fl.hostdepot.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reports` | High
2 | File | `/add-category.php` | High
3 | File | `/add-subadmin.php` | High
4 | File | `/addCatController.php` | High
5 | File | `/addmem.php` | Medium
6 | File | `/admin/` | Low
7 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
8 | File | `/admin/about-us.php` | High
9 | File | `/admin/aboutus.php` | High
10 | File | `/admin/add-ambulance.php` | High
11 | File | `/admin/add-category.php` | High
12 | File | `/admin/add-doctor.php` | High
13 | File | `/admin/add-teacher.php` | High
14 | File | `/admin/add_exercises.php` | High
15 | File | `/admin/ajax.php` | High
16 | File | `/admin/ajax.php?action=login` | High
17 | File | `/admin/app/web_crud.php` | High
18 | File | `/admin/changestock.php` | High
19 | File | `/admin/clients/manage.php` | High
20 | File | `/admin/deleteBooking.php` | High
21 | File | `/admin/doctors.php` | High
22 | File | `/admin/edit-category.php` | High
23 | File | `/admin/edit-customer-detailed.php` | High
24 | File | `/admin/edit-services.php` | High
25 | File | `/admin/edit_category.php` | High
26 | File | `/admin/edit_supplier.php` | High
27 | File | `/admin/group` | Medium
28 | File | `/admin/lab.php` | High
29 | File | `/admin/login.php` | High
30 | File | `/Admin/News.php` | High
31 | File | `/admin/positions_row.php` | High
32 | File | `/admin/reg.php` | High
33 | File | `/admin/search-appointment.php` | High
34 | File | `/admin/search-pass.php` | High
35 | File | `/admin/search.php` | High
36 | File | `/admin/view-user-queries.php` | High
37 | File | `/admin?do=admin:user:editPost` | High
38 | File | `/adminpanel/admin/query/addCourseExe.php` | High
39 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
40 | File | `/adminprofile.php` | High
41 | File | `/admin_class.php` | High
42 | File | `/admin_pay.php` | High
43 | File | `/ample/app/action/edit_product.php` | High
44 | File | `/api/blade-system/menu/list?updatexml` | High
45 | File | `/Api/FileUploadApi.ashx` | High
46 | File | `/api/GylOperator/LoadData` | High
47 | File | `/api/index.php` | High
48 | File | `/api/process.php` | High
49 | File | `/api/v4/users/user-id/mfa` | High
50 | File | `/application/index/controller/Icon.php` | High
51 | File | `/apps/meteor/app/irc/server/servers/RFC2813/parseMessage.js` | High
52 | File | `/atheme/src/crypto-benchmark/main.c` | High
53 | File | `/auth/userkey/logout.php` | High
54 | File | `/aya/module/admin/ust_tab_e.inc.php` | High
55 | File | `/batchGetBlockAttrs` | High
56 | File | `/birthing_record.php` | High
57 | File | `/boafrm/formIpQoS` | High
58 | File | `/boafrm/formReflashClientTbl` | High
59 | File | `/book_car.php` | High
60 | File | `/cart.php` | Medium
61 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
62 | File | `/cgi-bin/cstecgi.cgi` | High
63 | File | `/classes/Master.php?f=save_inquiry` | High
64 | File | `/com/esafenet/servlet/system/SystemEncryptPolicyService.java` | High
65 | File | `/config-manager/save` | High
66 | File | `/control/add_act.php` | High
67 | File | `/dayrui/My/View/main.html` | High
68 | File | `/doctor-panel.php` | High
69 | File | `/doctor/search.php` | High
70 | File | `/download.php?file=author.png` | High
71 | File | `/edit-locker.php?ltid=6` | High
72 | File | `/edit-product.php` | High
73 | File | `/edit-profile.php` | High
74 | ... | ... | ...

There are 647 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/alerts/TA17-318A

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
