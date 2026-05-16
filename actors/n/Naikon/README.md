# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Naikon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [47.241.127.190](https://vuldb.com/?ip.47.241.127.190) | - | - | High
2 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | Camerashy | High
3 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | Camerashy | High
4 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | Camerashy | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Naikon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-267, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 26 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.seam` | Low
2 | File | `/?explorer/index/zip` | High
3 | File | `/account/change_password` | High
4 | File | `/addProduct.php` | High
5 | File | `/admin/add_activity.php` | High
6 | File | `/admin/add_distributor.php` | High
7 | File | `/admin/add_expenses.php` | High
8 | File | `/admin/admin_running.php` | High
9 | File | `/admin/delete_activity.php` | High
10 | File | `/admin/Delete_product.php` | High
11 | File | `/admin/edit-student-profile.php` | High
12 | File | `/admin/manage-nurse.php` | High
13 | File | `/admin/manage-users.php` | High
14 | File | `/admin/reset-password.php` | High
15 | File | `/admin/stateadd.php` | High
16 | File | `/admin/system/variableList.do` | High
17 | File | `/admin/users.php` | High
18 | File | `/admin/view-appointment.php` | High
19 | File | `/adminapi/export/product_list` | High
20 | File | `/adminapi/product/product_export` | High
21 | File | `/Administrator/PHP/AdminDeleteCategory.php` | High
22 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
23 | File | `/Administrator/PHP/AdminUpdateCategory.php` | High
24 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
25 | File | `/Administrator/PHP/AdminViewSongs.php` | High
26 | File | `/admin_pic.php` | High
27 | File | `/aioseo/v1/ai/credits` | High
28 | File | `/ajax.php?action=login` | High
29 | File | `/api/chat` | Medium
30 | File | `/api/convos/fork` | High
31 | File | `/api/login` | Medium
32 | File | `/api/public/slack/install` | High
33 | File | `/api/settings` | High
34 | File | `/api/undo/` | Medium
35 | File | `/api/v1/contacts/{id}/notes` | High
36 | File | `/app/register.php?action=reg` | High
37 | File | `/assetsGroupReport/fixedAssetsList.j%73p` | High
38 | File | `/blog/bContent/save` | High
39 | File | `/boafrm/formFilter` | High
40 | File | `/boafrm/formLtefotaUpgradeFibocom` | High
41 | File | `/boafrm/formLtefotaUpgradeQuectel` | High
42 | File | `/boafrm/formUSSDSetup` | High
43 | File | `/borrowed_book_search.php` | High
44 | File | `/cgi-bin/cstecgi.cgi` | High
45 | File | `/cgi-bin/pl_web.cgi/util_configlogin_act` | High
46 | File | `/cgi/timepro.cgi` | High
47 | File | `/check_user.php` | High
48 | File | `/console/api/system-features` | High
49 | File | `/controller/api/Room.php` | High
50 | File | `/customer_register.php` | High
51 | File | `/dashboard/userprofile.php` | High
52 | File | `/data/pagesdata.txt` | High
53 | File | `/delete_post.php` | High
54 | File | `/ecodesource/search_list.php` | High
55 | File | `/editeddonor.php` | High
56 | File | `/editotheraccount.php` | High
57 | File | `/element-indexes/get-elements` | High
58 | File | `/etc_ro/shadow` | High
59 | File | `/Forms/admin_access_1` | High
60 | ... | ... | ...

There are 527 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf
* https://1275.ru/ioc/164/lotus-panda-apt-iocs/
* https://research.checkpoint.com/2020/naikon-apt-cyber-espionage-reloaded/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.04.23(1)/NAIKON.pdf
* https://www.threatminer.org/report.php?q=TheNaikonAPT-MsnMM1.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
