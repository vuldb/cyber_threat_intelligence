# PowerShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PowerShell](https://vuldb.com/?actor.powershell). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powershell](https://vuldb.com/?actor.powershell)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PowerShell:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PowerShell.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.18.46](https://vuldb.com/?ip.5.8.18.46) | vm19313.hyper.hosting | - | High
2 | [5.8.19.43](https://vuldb.com/?ip.5.8.19.43) | vm19315.hyper.hosting | - | High
3 | [5.101.85.24](https://vuldb.com/?ip.5.101.85.24) | vm19311.hyper.hosting | - | High
4 | [43.153.201.105](https://vuldb.com/?ip.43.153.201.105) | - | - | High
5 | [43.156.137.45](https://vuldb.com/?ip.43.156.137.45) | - | - | High
6 | [45.74.10.38](https://vuldb.com/?ip.45.74.10.38) | - | - | High
7 | [45.76.53.253](https://vuldb.com/?ip.45.76.53.253) | 45.76.53.253.vultrusercontent.com | - | Medium
8 | [45.144.212.54](https://vuldb.com/?ip.45.144.212.54) | - | - | High
9 | [46.62.175.51](https://vuldb.com/?ip.46.62.175.51) | yandexcontext.live | - | High
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PowerShell_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PowerShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
3 | File | `/admin/blog/comment/create` | High
4 | File | `/admin/login-back.php` | High
5 | File | `/admin/member_save.php` | High
6 | File | `/admin/quesadd.php` | High
7 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
8 | File | `/backend/admin/his_admin_register_patient.php` | High
9 | File | `/be/erpc.php` | Medium
10 | File | `/be/rpc.php` | Medium
11 | File | `/cgi-bin/luci/admin/network/wireless/config/` | High
12 | File | `/complainer_page.php` | High
13 | File | `/database?action=GetDatabaseAccess` | High
14 | File | `/download.php` | High
15 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
16 | File | `/forum/away.php` | High
17 | File | `/function/login.php` | High
18 | File | `/goform/AdvSetWrlsafeset` | High
19 | File | `/goform/Fast_wireless_conf` | High
20 | File | `/HNAP1` | Low
21 | File | `/inc/HTTPClient.php` | High
22 | File | `/index.php` | Medium
23 | File | `/index.php?m=editor&f=edit&filePath=cGhhcjovLy9ldGMvcGFzc3dk&action=edit` | High
24 | File | `/index.php?q=single-item` | High
25 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
26 | File | `/mc-admin/post-edit.php` | High
27 | File | `/membership_profile.php` | High
28 | File | `/minicms/mc-admin/page.php` | High
29 | File | `/modules/profile/index.php` | High
30 | File | `/modules/tasks/summary.inc.php` | High
31 | File | `/multi-vendor-shopping-script/product-list.php` | High
32 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
33 | File | `/new_grade.php` | High
34 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
35 | File | `/out.php` | Medium
36 | File | `/patient/booking.php` | High
37 | File | `/portal/__ajax_exporer.sgi` | High
38 | File | `/Service/ImageStationDataService.asmx` | High
39 | File | `/shw_war/fileupload` | High
40 | File | `/spip.php` | Medium
41 | File | `/src/models/embed.py` | High
42 | File | `/student/project_selection/move_up_project.php` | High
43 | File | `/uncpath/` | Medium
44 | File | `/users` | Low
45 | ... | ... | ...

There are 387 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.cyble.com/2022/06/03/cve-2022-30190-actively-exploited-in-the-wild/
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://community.blueliv.com/#!/s/6192412f82df413eb2354f9a
* https://urlhaus.abuse.ch/url/3524502/
* https://urlhaus.abuse.ch/url/3567832/
* https://urlhaus.abuse.ch/url/3569952/
* https://urlhaus.abuse.ch/url/3599447/
* https://urlhaus.abuse.ch/url/3599644/
* https://urlhaus.abuse.ch/url/3609961/
* https://urlhaus.abuse.ch/url/3610665/
* https://urlhaus.abuse.ch/url/3611366/
* https://urlhaus.abuse.ch/url/3611800/
* https://urlhaus.abuse.ch/url/3615937/
* https://urlhaus.abuse.ch/url/3616524/
* https://urlhaus.abuse.ch/url/3616526/
* https://urlhaus.abuse.ch/url/3626882/
* https://urlhaus.abuse.ch/url/3631737/
* https://urlhaus.abuse.ch/url/3634931/
* https://urlhaus.abuse.ch/url/3646386/
* https://urlhaus.abuse.ch/url/3662661/
* https://urlhaus.abuse.ch/url/3667202/
* https://urlhaus.abuse.ch/url/3682323/
* https://urlhaus.abuse.ch/url/3682727/
* https://urlhaus.abuse.ch/url/3683249/
* https://urlhaus.abuse.ch/url/3684667/
* https://urlhaus.abuse.ch/url/3684822/
* https://urlhaus.abuse.ch/url/3695595/
* https://urlhaus.abuse.ch/url/3710980/
* https://urlhaus.abuse.ch/url/3713982/
* https://urlhaus.abuse.ch/url/3724206/
* https://urlhaus.abuse.ch/url/3729323/
* https://urlhaus.abuse.ch/url/3729354/
* https://urlhaus.abuse.ch/url/3730390/
* https://urlhaus.abuse.ch/url/3730914/
* https://urlhaus.abuse.ch/url/3733972/
* https://urlhaus.abuse.ch/url/3734653/
* https://urlhaus.abuse.ch/url/3736690/
* https://urlhaus.abuse.ch/url/3740904/
* https://urlhaus.abuse.ch/url/3741045/
* https://urlhaus.abuse.ch/url/3741406/
* https://urlhaus.abuse.ch/url/3747726/
* https://urlhaus.abuse.ch/url/3749517/
* https://urlhaus.abuse.ch/url/3757522/
* https://urlhaus.abuse.ch/url/3758276/
* https://urlhaus.abuse.ch/url/3759043/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
