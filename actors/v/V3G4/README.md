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
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
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
4 | File | `/admin-profile.php` | High
5 | File | `/admin.php/admin/plog/index.html` | High
6 | File | `/admin.php/singer/admin/singer/del` | High
7 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
8 | File | `/admin/?page=inventory/view_inventory&id=2` | High
9 | File | `/admin/?page=orders/view_order` | High
10 | File | `/admin/about_edit.php?action=modify` | High
11 | File | `/admin/add_course.php` | High
12 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
13 | File | `/admin/class.php?dowhat=modifyclass` | High
14 | File | `/admin/comn/service/update.json` | High
15 | File | `/admin/create-package.php` | High
16 | File | `/admin/edit-boat.php` | High
17 | File | `/admin/edit-subadmin.php` | High
18 | File | `/admin/index.php` | High
19 | File | `/admin/mod_room/controller.php?action=add` | High
20 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
21 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
22 | File | `/admin/template/edit` | High
23 | File | `/admin/transactions/update_status.php` | High
24 | File | `/admin/uesrs.php&action=display&value=Hide` | High
25 | File | `/administrator/components/menu/` | High
26 | File | `/api/deploy/upload` | High
27 | File | `/api/deploy/upload /api/database/upload` | High
28 | File | `/assets/php/upload.php` | High
29 | File | `/auparse/auparse.c` | High
30 | File | `/back/index.php/user/User/?1` | High
31 | File | `/backups/` | Medium
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
34 | File | `/cgi-bin/logs.ha` | High
35 | File | `/cgi-bin/s3.cgi` | High
36 | File | `/claire_blake` | High
37 | File | `/classes/Master.php?f=delete_service` | High
38 | File | `/classes/SystemSettings.php?f=update_settings` | High
39 | File | `/CMSInstall/install.aspx` | High
40 | File | `/common/info.cgi` | High
41 | File | `/core/table/query` | High
42 | File | `/crm/inicio.php` | High
43 | File | `/cupseasylive/costcentercreate.php` | High
44 | File | `/damicms-master/admin.php?s=/Article/doedit` | High
45 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
46 | File | `/doctor/view-appointment-detail.php` | High
47 | ... | ... | ...

There are 406 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/mirai-variant-v3g4/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
