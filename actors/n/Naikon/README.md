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
1 | T1006 | CWE-22, CWE-23, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abonados/public/janto/main.php` | High
2 | File | `/addcustind.php` | High
3 | File | `/addstock.php` | High
4 | File | `/admin#article/edit?id=2` | High
5 | File | `/admin#permissions` | High
6 | File | `/admin.php?page=album` | High
7 | File | `/admin/?page=products/view_product` | High
8 | File | `/admin/?page=system_info/contact_info` | High
9 | File | `/Admin/adminlogin.php` | High
10 | File | `/admin/ajax_product.php` | High
11 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
12 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
13 | File | `/admin/blood/update/B-.php` | High
14 | File | `/admin/edit-card-detail.php` | High
15 | File | `/admin/edit_fuel.php` | High
16 | File | `/admin/File/fileUpload` | High
17 | File | `/admin/index.php` | High
18 | File | `/admin/overtime_row.php` | High
19 | File | `/admin/password-recovery.php` | High
20 | File | `/admin/search-medicalcard.php` | High
21 | File | `/admin/sou.php` | High
22 | File | `/admin/view-card-detail.php` | High
23 | File | `/admin/wifi/wlan1` | High
24 | File | `/ajax.php?action=delete_tenant` | High
25 | File | `/animalsupdate.php` | High
26 | File | `/api/config/list` | High
27 | File | `/ar/config/configuation/` | High
28 | File | `/cgi-bin/settings-firewall.cgi` | High
29 | File | `/com/esafenet/servlet/ajax/NetSecPolicyAjax.java` | High
30 | File | `/com/esafenet/servlet/netSec/NetSecConfigService.java` | High
31 | File | `/com/esafenet/servlet/policy/HookService.java` | High
32 | File | `/com/esafenet/servlet/system/PolicyActionService.java` | High
33 | File | `/com/esafenet/servlet/user/ReUserOrganiseService.java` | High
34 | File | `/cov/triggerEnvCov` | High
35 | File | `/curd/table/list` | High
36 | File | `/dev/mem` | Medium
37 | File | `/edit-pig.php` | High
38 | File | `/edit-profile.php` | High
39 | File | `/etc/shadow` | Medium
40 | File | `/file/infoAdd.php` | High
41 | File | `/filemanager/upload` | High
42 | File | `/goform/ate` | Medium
43 | File | `/goform/formResetStatistic` | High
44 | File | `/goform/formSetMuti` | High
45 | File | `/goform/formSetPortTr` | High
46 | File | `/goform/formSetWizardSelectMode` | High
47 | File | `/goform/formVirtualServ` | High
48 | File | `/goform/GetIPTV?fgHPOST/goform/SysToo` | High
49 | File | `/goform/saveParentControlInfo` | High
50 | File | `/goform/SetNetControlList` | High
51 | File | `/goform/SetOnlineDevName` | High
52 | File | `/goform/WriteFacMac` | High
53 | File | `/index.php` | Medium
54 | File | `/manage_invoice.php` | High
55 | ... | ... | ...

There are 475 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
