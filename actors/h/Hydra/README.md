# Hydra - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Hydra](https://vuldb.com/?actor.hydra). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hydra](https://vuldb.com/?actor.hydra)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hydra:

* [US](https://vuldb.com/?country.us)
* [AU](https://vuldb.com/?country.au)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Hydra.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.57.149.78](https://vuldb.com/?ip.2.57.149.78) | - | - | High
2 | [31.129.22.96](https://vuldb.com/?ip.31.129.22.96) | Pbl.ip-ptr.tech | - | High
3 | [45.12.253.200](https://vuldb.com/?ip.45.12.253.200) | - | - | High
4 | [45.144.28.231](https://vuldb.com/?ip.45.144.28.231) | - | - | High
5 | [45.150.67.23](https://vuldb.com/?ip.45.150.67.23) | vm307437.pq.hosting | - | High
6 | [62.233.50.185](https://vuldb.com/?ip.62.233.50.185) | - | - | High
7 | [77.73.131.239](https://vuldb.com/?ip.77.73.131.239) | curved-knife.aeza.network | - | High
8 | [77.91.84.249](https://vuldb.com/?ip.77.91.84.249) | victorious-sweater.aeza.network | - | High
9 | [77.91.85.231](https://vuldb.com/?ip.77.91.85.231) | vigorous-finger.aeza.network | - | High
10 | [77.91.86.197](https://vuldb.com/?ip.77.91.86.197) | godly-arm.aeza.network | - | High
11 | [77.91.87.207](https://vuldb.com/?ip.77.91.87.207) | - | - | High
12 | ... | ... | ... | ...

There are 43 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Hydra_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Hydra. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.cfm` | Low
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/.env` | Low
4 | File | `/admin/cms_admin.php` | High
5 | File | `/admin/delete_user.php` | High
6 | File | `/admin/forgot-password.php` | High
7 | File | `/admin/judge` | Medium
8 | File | `/admin/maintenance/view_designation.php` | High
9 | File | `/admin/wlmultipleap.asp` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/be/erpc.php` | Medium
12 | File | `/billing/bill/edit/` | High
13 | File | `/brand.php` | Medium
14 | File | `/cas/logout` | Medium
15 | File | `/category.php` | High
16 | File | `/cgi-bin/` | Medium
17 | File | `/classes/Master.php?f=delete_inquiry` | High
18 | File | `/collection/all` | High
19 | File | `/coreframe/app/member/admin/group.php` | High
20 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
21 | File | `/filemanager/php/connector.php` | High
22 | File | `/filex/read-raw` | High
23 | File | `/forum/away.php` | High
24 | File | `/goform/L7Im` | Medium
25 | File | `/hardware` | Medium
26 | File | `/hospital_activities/birth/form` | High
27 | File | `/hoteldruid/interconnessioni.php` | High
28 | File | `/include/chart_generator.php` | High
29 | File | `/index.php?page=member` | High
30 | File | `/investigation/delete/` | High
31 | File | `/login/index.php` | High
32 | File | `/manager/ipconfig_new.php` | High
33 | File | `/medical/inventories.php` | High
34 | File | `/mgmt/tm/util/bash` | High
35 | File | `/modules/projects/vw_files.php` | High
36 | File | `/owa/auth/logon.aspx` | High
37 | File | `/rest/api/2/user/picker` | High
38 | File | `/school/model/get_events.php` | High
39 | File | `/scripts/cpan_config` | High
40 | File | `/search/index` | High
41 | File | `/secserver` | Medium
42 | File | `/secure/QueryComponent!Default.jspa` | High
43 | File | `/spacecom/login.php` | High
44 | File | `/spip.php` | Medium
45 | File | `/src/admin/content_batchup_action.php` | High
46 | File | `/uncpath/` | Medium
47 | File | `/user/updatePwd` | High
48 | File | `/view/networkConfig/vlan/vlan_add_commit.php` | High
49 | File | `/wp-admin/admin-ajax.php` | High
50 | File | `AbstractController.php` | High
51 | File | `action.php` | Medium
52 | File | `adclick.php` | Medium
53 | File | `add-locker-form.php` | High
54 | File | `addpost_newpoll.php` | High
55 | File | `admin.cgi` | Medium
56 | File | `admin.php` | Medium
57 | ... | ... | ...

There are 499 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=80.82.76.8
* https://tracker.viriback.com/index.php?q=80.82.76.124
* https://tracker.viriback.com/index.php?q=212.113.116.215
* https://twitter.com/500mk500/status/1645680480602279936
* https://twitter.com/500mk500/status/1646474859399004160
* https://twitter.com/500mk500/status/1647323885916893186
* https://twitter.com/500mk500/status/1648583985533014019
* https://twitter.com/josh_penny/status/1642101016270196736
* https://twitter.com/josh_penny/status/1644464243956129793
* https://twitter.com/TLP_R3D/status/1646925457760083971

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
