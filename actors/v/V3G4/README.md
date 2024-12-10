# V3G4 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [V3G4](https://vuldb.com/?actor.v3g4). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.v3g4](https://vuldb.com/?actor.v3g4)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with V3G4:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [ES](https://vuldb.com/?country.es)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of V3G4.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [104.244.72.64](https://vuldb.com/?ip.104.244.72.64) | winging.co.uk | - | High
2 | [176.123.9.238](https://vuldb.com/?ip.176.123.9.238) | - | - | High
3 | [198.98.49.79](https://vuldb.com/?ip.198.98.49.79) | - | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _V3G4_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-27 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by V3G4. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%APPDATA%\Securepoint SSL VPN` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/action/iperf` | High
4 | File | `/admin.php/admin/plog/index.html` | High
5 | File | `/admin.php/singer/admin/singer/del` | High
6 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
7 | File | `/admin/?page=inventory/view_inventory&id=2` | High
8 | File | `/admin/?page=orders/view_order` | High
9 | File | `/admin/comn/service/update.json` | High
10 | File | `/admin/create-package.php` | High
11 | File | `/admin/mod_room/controller.php?action=add` | High
12 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
13 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
14 | File | `/admin/template/edit` | High
15 | File | `/admin/transactions/update_status.php` | High
16 | File | `/admin/uesrs.php&action=display&value=Hide` | High
17 | File | `/administrator/components/menu/` | High
18 | File | `/api/deploy/upload` | High
19 | File | `/api/deploy/upload /api/database/upload` | High
20 | File | `/assets/php/upload.php` | High
21 | File | `/auparse/auparse.c` | High
22 | File | `/back/index.php/user/User/?1` | High
23 | File | `/backups/` | Medium
24 | File | `/cgi-bin/cstecgi.cgi` | High
25 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
26 | File | `/cgi-bin/logs.ha` | High
27 | File | `/cgi-bin/s3.cgi` | High
28 | File | `/claire_blake` | High
29 | File | `/classes/Master.php?f=delete_service` | High
30 | File | `/classes/SystemSettings.php?f=update_settings` | High
31 | File | `/common/info.cgi` | High
32 | File | `/core/table/query` | High
33 | File | `/cupseasylive/costcentercreate.php` | High
34 | File | `/damicms-master/admin.php?s=/Article/doedit` | High
35 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
36 | File | `/doctor/view-appointment-detail.php` | High
37 | File | `/endpoint/delete-account.php` | High
38 | File | `/feedback/post/` | High
39 | File | `/gaia-job-admin/user/add` | High
40 | File | `/goform/formVirtualServ` | High
41 | File | `/goform/login` | High
42 | File | `/goform/SetInternetLanInfo` | High
43 | File | `/goform/SetPptpServerCfg` | High
44 | ... | ... | ...

There are 382 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/mirai-variant-v3g4/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
