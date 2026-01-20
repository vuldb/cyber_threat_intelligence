# BlackWater - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BlackWater_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackWater:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [ES](https://vuldb.com/?country.es)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BlackWater or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Blackwater](https://vuldb.com/?actor.blackwater) | High
2 | [MuddyWater](https://vuldb.com/?actor.muddywater) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackWater.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [38.132.99.167](https://vuldb.com/?ip.38.132.99.167) | - | [MuddyWater](https://vuldb.com/?actor.muddywater) | High
2 | [82.102.8.101](https://vuldb.com/?ip.82.102.8.101) | h82-102-8-101.host.redstation.co.uk | [MuddyWater](https://vuldb.com/?actor.muddywater) | High
3 | [94.23.148.194](https://vuldb.com/?ip.94.23.148.194) | ip194.ip-94-23-148.eu | [MuddyWater](https://vuldb.com/?actor.muddywater) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BlackWater. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BlackWater. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\MyQ\PHP\Sessions\` | High
2 | File | `/.flatpak-info` | High
3 | File | `/Account/login.php` | High
4 | File | `/Actions.php?a=login` | High
5 | File | `/actuator` | Medium
6 | File | `/addelidetails.php` | High
7 | File | `/addProduct.php` | High
8 | File | `/add_new_invoice.php` | High
9 | File | `/add_new_supplier.php` | High
10 | File | `/admin/` | Low
11 | File | `/admin/?page=user` | High
12 | File | `/admin/add-module.php` | High
13 | File | `/admin/app/login_crud.php` | High
14 | File | `/admin/app/product.php` | High
15 | File | `/admin/app/service_crud.php` | High
16 | File | `/admin/archives_add.php` | High
17 | File | `/admin/blood/update/o-.php` | High
18 | File | `/admin/category/view_category.php` | High
19 | File | `/admin/Create_product.php` | High
20 | File | `/admin/delete.php` | High
21 | File | `/admin/delete_user.php` | High
22 | File | `/admin/edit-category.php` | High
23 | File | `/admin/edit.php` | High
24 | File | `/admin/edit_posts.php` | High
25 | File | `/admin/edit_tax.php` | High
26 | File | `/admin/googleads.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/list_ipAddressPolicy.php` | High
29 | File | `/admin/login.php` | High
30 | File | `/Admin/login.php` | High
31 | File | `/admin/massage.php` | High
32 | File | `/admin/menu_save.php` | High
33 | File | `/admin/pages/update_go.php` | High
34 | File | `/admin/profile.php` | High
35 | File | `/admin/quesadd.php` | High
36 | File | `/admin/reg.php` | High
37 | File | `/admin/renewaldue.php` | High
38 | File | `/admin/search.php` | High
39 | File | `/admin/system/variableList.do` | High
40 | File | `/admin/update_s8.php` | High
41 | File | `/admin/update_user.php` | High
42 | File | `/administrator/bidlist.php` | High
43 | File | `/Administrator/PHP/AdminAddUser.php` | High
44 | File | `/Administrator/PHP/AdminViewSongs.php` | High
45 | File | `/adminpanel/admin/query/deleteQuestionExe.php` | High
46 | File | `/ajax` | Low
47 | File | `/analysisProject/pagingQueryData` | High
48 | File | `/api/jobs` | Medium
49 | File | `/api/sys/login` | High
50 | File | `/app/ajax/search_sales_report.php` | High
51 | File | `/app/checkout/update.php` | High
52 | File | `/app/middleware/TokenVerify.php` | High
53 | File | `/app/register.php?action=reg` | High
54 | File | `/application/admin/logic/FilemanagerLogic.php` | High
55 | File | `/application/index/controller/Databasesource.php` | High
56 | File | `/application/index/controller/Screen.php` | High
57 | File | `/assetsGroupReport/assetsService.j%73p` | High
58 | File | `/base/safe_setting/` | High
59 | File | `/bin/boa` | Medium
60 | File | `/binutils/debug.c` | High
61 | File | `/boafrm/formLtefotaUpgradeFibocom` | High
62 | File | `/boafrm/formSysCmd` | High
63 | File | `/boafrm/formWsc` | High
64 | File | `/booking/show_bookings/` | High
65 | File | `/cancel.php` | Medium
66 | File | `/cgi-bin/adm.cgi` | High
67 | File | `/cgi-bin/cstecgi.cgi` | High
68 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
69 | File | `/cgi-bin/myMusic.cgi` | High
70 | File | `/cgi-bin/settings-firewall.cgi` | High
71 | File | `/classes/Users.php?f=save` | High
72 | File | `/collection/all` | High
73 | ... | ... | ...

There are 639 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2019/05/recent-muddywater-associated-blackwater.html
* https://blog.talosintelligence.com/2019/05/recent-muddywater-associated-blackwater.html?m=1

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
