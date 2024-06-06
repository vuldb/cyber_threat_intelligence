# TeamTNT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TeamTNT](https://vuldb.com/?actor.teamtnt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.teamtnt](https://vuldb.com/?actor.teamtnt)

## Campaigns

The following _campaigns_ are known and can be associated with TeamTNT:

* Amazon Web Services
* Cryptomining
* Hildegard

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TeamTNT:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TeamTNT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.125.10.23](https://vuldb.com/?ip.3.125.10.23) | ec2-3-125-10-23.eu-central-1.compute.amazonaws.com | Amazon Web Services | Medium
2 | [13.245.9.147](https://vuldb.com/?ip.13.245.9.147) | ec2-13-245-9-147.af-south-1.compute.amazonaws.com | Hildegard | Medium
3 | [15.236.100.141](https://vuldb.com/?ip.15.236.100.141) | ec2-15-236-100-141.eu-west-3.compute.amazonaws.com | Amazon Web Services | Medium
4 | [39.100.33.209](https://vuldb.com/?ip.39.100.33.209) | - | - | High
5 | [45.9.148.35](https://vuldb.com/?ip.45.9.148.35) | - | - | High
6 | [45.9.148.37](https://vuldb.com/?ip.45.9.148.37) | - | - | High
7 | [45.9.148.108](https://vuldb.com/?ip.45.9.148.108) | mx1.dendrite.network | Hildegard | High
8 | [45.9.148.182](https://vuldb.com/?ip.45.9.148.182) | - | Cryptomining | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TeamTNT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-27, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TeamTNT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin.php/appcenter/local.html?type=addon` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/assign/assign.php` | High
6 | File | `/admin/config_save.php` | High
7 | File | `/admin/contacts/organizations/edit/2` | High
8 | File | `/admin/curriculum/view_curriculum.php` | High
9 | File | `/admin/employee_row.php` | High
10 | File | `/admin/login.php` | High
11 | File | `/admin/mechanics/manage_mechanic.php` | High
12 | File | `/admin/report/index.php` | High
13 | File | `/admin/robot/approval/list` | High
14 | File | `/admin/sales/index.php` | High
15 | File | `/admin/sales/view_details.php` | High
16 | File | `/admin/sys_sql_query.php` | High
17 | File | `/admin/transactions/track_shipment.php` | High
18 | File | `/ajax.php?action=read_msg` | High
19 | File | `/api/browserextension/UpdatePassword/` | High
20 | File | `/assets/components/gallery/connector.php` | High
21 | File | `/bin/boa` | Medium
22 | File | `/change_password_process` | High
23 | File | `/churchcrm/v2/family/not-found` | High
24 | File | `/classes/Login.php` | High
25 | File | `/classes/Master.php` | High
26 | File | `/classes/Master.php?f=update_order_status` | High
27 | File | `/client/manage/ourphp_out.php` | High
28 | File | `/config/api/v1/reboot` | High
29 | File | `/debug/pprof` | Medium
30 | File | `/designer/add/layout` | High
31 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
32 | File | `/dotrace.asp` | Medium
33 | File | `/ecrire` | Low
34 | File | `/env` | Low
35 | File | `/etc/shadow.sample` | High
36 | File | `/forum/away.php` | High
37 | File | `/goform/SetNetControlList` | High
38 | File | `/goform/SetStaticRouteCfg` | High
39 | File | `/goform/SysToolRestoreSet` | High
40 | File | `/goform/WifiBasicSet` | High
41 | File | `/HNAP1/SetAccessPointMode` | High
42 | File | `/index.php?page=category_list` | High
43 | File | `/omos/admin/?page=user/list` | High
44 | File | `/openvpn/pageswitch.htm` | High
45 | File | `/operations/ecma-function-object.c` | High
46 | ... | ... | ...

There are 398 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/04/teamtnt-targeting-aws-alibaba.html
* https://securitylabs.datadoghq.com/articles/analysis-of-teamtnt-doppelganger/
* https://unit42.paloaltonetworks.com/hildegard-malware-teamtnt/
* https://unit42.paloaltonetworks.com/teamtnt-cryptojacking-watchdog-operations/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.02.03/Hildegard.pdf
* https://www.trendmicro.com/en_us/research/21/k/compromised-docker-hub-accounts-abused-for-cryptomining-linked-t.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
