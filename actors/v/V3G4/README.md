# V3G4 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [V3G4](https://vuldb.com/?actor.v3g4). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.v3g4](https://vuldb.com/?actor.v3g4)

## Campaigns

The following _campaigns_ are known and can be associated with V3G4:

* Industrial Routers
* Mirai

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
1 | [64.225.49.218](https://vuldb.com/?ip.64.225.49.218) | - | Industrial Routers | High
2 | [103.149.93.224](https://vuldb.com/?ip.103.149.93.224) | - | Mirai | High
3 | [104.244.72.64](https://vuldb.com/?ip.104.244.72.64) | winging.co.uk | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _V3G4_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-27 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by V3G4. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/action/iperf` | High
3 | File | `/admin-profile.php` | High
4 | File | `/admin.php/addon/index` | High
5 | File | `/admin.php/admin/plog/index.html` | High
6 | File | `/admin.php/singer/admin/singer/del` | High
7 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
8 | File | `/admin/?page=inventory/view_inventory&id=2` | High
9 | File | `/admin/?page=orders/view_order` | High
10 | File | `/admin/about_edit.php?action=modify` | High
11 | File | `/admin/add_course.php` | High
12 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
13 | File | `/admin/assign_save.php` | High
14 | File | `/admin/between-date-complaintreport.php` | High
15 | File | `/admin/class.php?dowhat=modifyclass` | High
16 | File | `/admin/comn/service/update.json` | High
17 | File | `/admin/controller/faculty_controller.php` | High
18 | File | `/admin/create-package.php` | High
19 | File | `/admin/delete_pending.php` | High
20 | File | `/admin/doctor-specilization.php` | High
21 | File | `/admin/edit-boat.php` | High
22 | File | `/admin/edit-category.php` | High
23 | File | `/admin/edit-subadmin.php` | High
24 | File | `/admin/edit_product.php` | High
25 | File | `/admin/index.php` | High
26 | File | `/admin/login.php` | High
27 | File | `/admin/model/addOrUpdate` | High
28 | File | `/admin/mod_room/controller.php?action=add` | High
29 | File | `/admin/page-login.php` | High
30 | File | `/admin/profile.php` | High
31 | File | `/admin/registration.php` | High
32 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
33 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
34 | File | `/admin/template/edit` | High
35 | File | `/admin/transactions/update_status.php` | High
36 | File | `/admin/uesrs.php&action=display&value=Hide` | High
37 | File | `/administrator/components/menu/` | High
38 | File | `/ajax.php?action=login` | High
39 | File | `/alphaware/summary.php` | High
40 | File | `/api/controllers/merchant/app/ComboController.php` | High
41 | File | `/api/deploy/upload` | High
42 | File | `/api/deploy/upload /api/database/upload` | High
43 | File | `/api/employees` | High
44 | File | `/application/user/controller/Index.php` | High
45 | File | `/Applications/Endurance.app/Contents/Library/LaunchServices/com.MagnetismStudios.endurance.helper` | High
46 | File | `/assets/php/upload.php` | High
47 | File | `/auparse/auparse.c` | High
48 | File | `/auth/delete_project/` | High
49 | File | `/back/index.php/user/User/?1` | High
50 | File | `/boafrm/formFilter` | High
51 | File | `/boafrm/formWlwds` | High
52 | File | `/boafrm/formWsc` | High
53 | File | `/cancelbookingpatient.php` | High
54 | File | `/cgi-bin/cstecgi.cgi` | High
55 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
56 | File | `/cgi-bin/logs.ha` | High
57 | File | `/cgi-bin/s3.cgi` | High
58 | ... | ... | ...

There are 506 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/v3g4-mirai-botnet-evolves/
* https://unit42.paloaltonetworks.com/mirai-variant-v3g4/
* https://www.forescout.com/blog/ot-network-security-threats-industrial-routers-under-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
