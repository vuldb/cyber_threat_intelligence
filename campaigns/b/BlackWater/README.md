# BlackWater - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BlackWater_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackWater:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)

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
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BlackWater. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/actuator` | Medium
2 | File | `/addelidetails.php` | High
3 | File | `/addProduct.php` | High
4 | File | `/admin/?page=user` | High
5 | File | `/admin/activity.php` | High
6 | File | `/admin/add-module.php` | High
7 | File | `/admin/add-subadmins.php` | High
8 | File | `/admin/archives_add.php` | High
9 | File | `/admin/Create_product.php` | High
10 | File | `/admin/delete.php` | High
11 | File | `/admin/delete_activity.php` | High
12 | File | `/admin/Delete_product.php` | High
13 | File | `/admin/delete_user.php` | High
14 | File | `/admin/edit-category.php` | High
15 | File | `/admin/editsite.php` | High
16 | File | `/admin/edit_activity_query.php` | High
17 | File | `/admin/edit_posts.php` | High
18 | File | `/admin/edit_tax.php` | High
19 | File | `/admin/expenses.php` | High
20 | File | `/admin/login.php` | High
21 | File | `/admin/menu_save.php` | High
22 | File | `/admin/modules/lesson/index.php` | High
23 | File | `/admin/operation/user.php` | High
24 | File | `/admin/quesadd.php` | High
25 | File | `/admin/system/variableList.do` | High
26 | File | `/admin/system/variableSave.do` | High
27 | File | `/admin/update_s8.php` | High
28 | File | `/admin/update_user.php` | High
29 | File | `/administrator/bidlist.php` | High
30 | File | `/Administrator/PHP/AdminAddUser.php` | High
31 | File | `/Administrator/PHP/AdminViewSongs.php` | High
32 | File | `/api/jobs` | Medium
33 | File | `/app/checkout/delete.php` | High
34 | File | `/app/checkout/update.php` | High
35 | File | `/app/complaint.php` | High
36 | File | `/app/Jobs/Util/Import.php` | High
37 | File | `/app/register.php?action=reg` | High
38 | File | `/app/sms.php` | Medium
39 | File | `/application/admin/logic/FilemanagerLogic.php` | High
40 | File | `/assetsGroupReport/assetsService.j%73p` | High
41 | File | `/base/safe_setting/` | High
42 | File | `/binutils/debug.c` | High
43 | File | `/blog/bContent/save` | High
44 | File | `/boafrm/formLtefotaUpgradeFibocom` | High
45 | File | `/boafrm/formNewSchedule` | High
46 | File | `/boafrm/formSysCmd` | High
47 | File | `/boafrm/formWsc` | High
48 | File | `/cgi-bin/cstecgi.cgi` | High
49 | File | `/cgi-bin/imode_alldata.php` | High
50 | File | `/cgi-bin/nas.cgi` | High
51 | File | `/contact_us.php` | High
52 | File | `/controller/api/Room.php` | High
53 | File | `/customer_details.php` | High
54 | File | `/dashboard/Ccustomer/manage_customer` | High
55 | File | `/data/pbootcms.db` | High
56 | ... | ... | ...

There are 490 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
