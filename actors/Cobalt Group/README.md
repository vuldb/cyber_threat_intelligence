# Cobalt Group - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Group](https://vuldb.com/?actor.cobalt_group). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_group](https://vuldb.com/?actor.cobalt_group)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Group:

* [PL](https://vuldb.com/?country.pl)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Group.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.66.161](https://vuldb.com/?ip.5.45.66.161) | - | - | High
2 | [5.135.237.216](https://vuldb.com/?ip.5.135.237.216) | - | - | High
3 | [23.152.0.210](https://vuldb.com/?ip.23.152.0.210) | nordns.crowncloud.net | - | High
4 | [23.249.164.26](https://vuldb.com/?ip.23.249.164.26) | - | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cobalt Group_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Group. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academy/home/courses` | High
2 | File | `/action/import_https_cert_file/` | High
3 | File | `/admin` | Low
4 | File | `/admin/?page=user/manage_user` | High
5 | File | `/admin/contacts/organizations/edit/2` | High
6 | File | `/admin/curriculum/view_curriculum.php` | High
7 | File | `/Admin/dashboard.php` | High
8 | File | `/admin/edit-accepted-appointment.php` | High
9 | File | `/admin/edit.php` | High
10 | File | `/admin/edit_category.php` | High
11 | File | `/admin/edit_subject.php` | High
12 | File | `/admin/modal_add_product.php` | High
13 | File | `/admin/sales/view_details.php` | High
14 | File | `/admin/service.php` | High
15 | File | `/admin/sign/out` | High
16 | File | `/admin/test_status.php` | High
17 | File | `/api/common/ping` | High
18 | File | `/api/v2/open/tablesInfo` | High
19 | File | `/api/wechat/app_auth` | High
20 | File | `/asms/classes/Master.php?f=delete_img` | High
21 | File | `/catcompany.php` | High
22 | File | `/classes/Master.php?f=delete_appointment` | High
23 | File | `/classes/Master.php?f=save_item` | High
24 | File | `/classes/Users.php` | High
25 | File | `/cms/notify` | Medium
26 | File | `/depotHead/list` | High
27 | File | `/device/signin` | High
28 | File | `/fusiondirectory/index.php` | High
29 | File | `/general/ipanel/menu_code.php?MENU_TYPE=FAV` | High
30 | File | `/goform/addressNat` | High
31 | File | `/goform/RGFirewallEL` | High
32 | File | `/goform/WifiBasicSet` | High
33 | File | `/h/` | Low
34 | File | `/HNAP1` | Low
35 | File | `/hslist` | Low
36 | File | `/importexport.php` | High
37 | File | `/include/dialog/select_templets_post.php` | High
38 | File | `/index.php/sysmanage/Login/login_auth/` | High
39 | File | `/index.php?page=member` | High
40 | File | `/js/player/dmplayer/dmku/index.php` | High
41 | File | `/lists/admin/` | High
42 | File | `/log/decodmail.php` | High
43 | File | `/login/index.php` | High
44 | File | `/multi-vendor-shopping-script/product-list.php` | High
45 | File | `/myAccount` | Medium
46 | File | `/note/index/delete` | High
47 | File | `/operations/travellers.php` | High
48 | File | `/patient/appointment.php` | High
49 | File | `/paysystem/datatable.php` | High
50 | ... | ... | ...

There are 438 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/07/multiple-cobalt-personality-disorder.html
* https://www.proofpoint.com/us/threat-insight/post/microsoft-word-intruder-integrates-cve-2017-0199-utilized-cobalt-group-target
* https://www.ptsecurity.com/upload/corporate/ww-en/analytics/Cobalt-Snatch-eng.pdf
* https://www.riskiq.com/blog/labs/cobalt-group-spear-phishing-russian-banks/
* https://www.riskiq.com/blog/labs/cobalt-strike/
* https://www.trendmicro.com/en_us/research/17/k/cobalt-spam-runs-use-macros-cve-2017-8759-exploit.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
