# Cobalt Group - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Group](https://vuldb.com/?actor.cobalt_group). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_group](https://vuldb.com/?actor.cobalt_group)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Group:

* [ES](https://vuldb.com/?country.es)
* [PL](https://vuldb.com/?country.pl)
* [AR](https://vuldb.com/?country.ar)
* ...

There are 8 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Group. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin.php/Label/js_del` | High
3 | File | `/admin.php/news/admin/topic/save` | High
4 | File | `/admin/comn/service/update.json` | High
5 | File | `/admin/general.cgi` | High
6 | File | `/admin/inc/include.php` | High
7 | File | `/admin/reports.php` | High
8 | File | `/admin/service/stop/` | High
9 | File | `/admin/usermanagement.php` | High
10 | File | `/app/options.py` | High
11 | File | `/bcms/admin/courts/view_court.php` | High
12 | File | `/category.php` | High
13 | File | `/ci_spms/admin/search/searching/` | High
14 | File | `/config` | Low
15 | File | `/domains/index.fts` | High
16 | File | `/filemanager/upload/drop` | High
17 | File | `/freelance/resume_list` | High
18 | File | `/goform/aspForm` | High
19 | File | `/goform/saveParentControlInfo` | High
20 | File | `/goform/SetClientState` | High
21 | File | `/home/jobfairol/resumelist` | High
22 | File | `/hprms/admin/rooms/view_room.php` | High
23 | File | `/hprms/classes/Master.php?f=delete_message` | High
24 | File | `/images/background/1.php` | High
25 | File | `/ip/car-rental-management-system/admin/ajax.php?action=login` | High
26 | File | `/lists/admin/` | High
27 | File | `/modules/mindmap/index.php` | High
28 | File | `/modules/tasks/gantt.php` | High
29 | File | `/ocwbs/admin/?page=bookings/view_details` | High
30 | File | `/ocwbs/admin/?page=user/manage_user` | High
31 | File | `/ocwbs/admin/services/manage_service.php` | High
32 | File | `/ocwbs/classes/Master.php?f=delete_booking` | High
33 | File | `/ocwbs/classes/Master.php?f=delete_vehicle` | High
34 | File | `/odfs/classes/Master.php?f=save_category` | High
35 | File | `/officials/officials.php` | High
36 | File | `/ofrs/admin/?page=user/manage_user` | High
37 | File | `/ordering/admin/stockin/index.php?view=edit` | High
38 | File | `/php_action/createUser.php` | High
39 | File | `/pms/admin/inmates/manage_privilege.php` | High
40 | ... | ... | ...

There are 340 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
