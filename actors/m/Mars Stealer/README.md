# Mars Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mars Stealer](https://vuldb.com/?actor.mars_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mars_stealer](https://vuldb.com/?actor.mars_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mars Stealer:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mars Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.84.214](https://vuldb.com/?ip.5.45.84.214) | - | - | High
2 | [5.63.155.126](https://vuldb.com/?ip.5.63.155.126) | 5-63-155-126.cloudvps.regruhosting.ru | - | High
3 | [5.181.80.130](https://vuldb.com/?ip.5.181.80.130) | ip-80-130-bullethost.net | - | High
4 | [13.58.70.215](https://vuldb.com/?ip.13.58.70.215) | ec2-13-58-70-215.us-east-2.compute.amazonaws.com | - | Medium
5 | [20.185.186.224](https://vuldb.com/?ip.20.185.186.224) | - | - | High
6 | [23.239.9.184](https://vuldb.com/?ip.23.239.9.184) | 23-239-9-184.ip.linodeusercontent.com | - | High
7 | [45.9.20.31](https://vuldb.com/?ip.45.9.20.31) | - | - | High
8 | [45.67.230.47](https://vuldb.com/?ip.45.67.230.47) | vm718000.stark-industries.solutions | - | High
9 | [45.77.112.250](https://vuldb.com/?ip.45.77.112.250) | 45.77.112.250.vultrusercontent.com | - | Medium
10 | [45.140.147.99](https://vuldb.com/?ip.45.140.147.99) | vm716958.stark-industries.solutions | - | High
11 | [62.3.12.9](https://vuldb.com/?ip.62.3.12.9) | zserg.ch | - | High
12 | [62.113.99.76](https://vuldb.com/?ip.62.113.99.76) | - | - | High
13 | [62.204.41.69](https://vuldb.com/?ip.62.204.41.69) | - | - | High
14 | [62.204.41.70](https://vuldb.com/?ip.62.204.41.70) | - | - | High
15 | ... | ... | ... | ...

There are 57 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mars Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mars Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/academy/home/courses` | High
3 | File | `/ad-list` | Medium
4 | File | `/add_new_invoice.php` | High
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/adduser.php` | High
7 | File | `/admin/ajax.php?action=login` | High
8 | File | `/admin/api/theme-edit/` | High
9 | File | `/admin/book-details.php` | High
10 | File | `/admin/client_user` | High
11 | File | `/admin/cmsVote/save` | High
12 | File | `/admin/communitymanagement.php` | High
13 | File | `/admin/court-type` | High
14 | File | `/admin/edit-category.php` | High
15 | File | `/admin/generalsettings.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/index.php?page=categories` | High
18 | File | `/admin/inquiries/view_inquiry.php` | High
19 | File | `/admin/login.php` | High
20 | File | `/admin/payment.php` | High
21 | File | `/admin/receipt.php` | High
22 | File | `/admin/transactions/update_status.php` | High
23 | File | `/admin?page=media` | High
24 | File | `/ajax.php?action=login` | High
25 | File | `/ajax/checkin.php` | High
26 | File | `/api/controllers/admin/app/ComboController.php` | High
27 | File | `/api/user/password/sent-reset-email` | High
28 | File | `/application/plugins/controller/Upload.php` | High
29 | File | `/aqpg/users/login.php` | High
30 | File | `/bsms_ci/index.php/user/edit_user/` | High
31 | File | `/cgi-bin/cstecgi.cgi` | High
32 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
33 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/cgi-bin/webfile_mgr.cgi` | High
37 | File | `/cgi-bin/wlogin.cgi` | High
38 | File | `/classes/Master.php?f=save_inquiry` | High
39 | File | `/classes/SystemSettings.php?f=update_settings` | High
40 | File | `/com/esafenet/servlet/policy/HookWhiteListService.java` | High
41 | File | `/control/register_case.php` | High
42 | File | `/controllers/control.php` | High
43 | File | `/covidtms/registered-user-testing.php` | High
44 | File | `/cstecgi.cgi` | Medium
45 | File | `/dashboard/add-service.php` | High
46 | File | `/dashboard/updatelogo.php` | High
47 | File | `/Default/Bd` | Medium
48 | File | `/download` | Medium
49 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
50 | File | `/event/admin/?page=user/list` | High
51 | File | `/face-recognition-php/facepay-master/camera.php` | High
52 | File | `/filemanager/upload/drop` | High
53 | File | `/forum/away.php` | High
54 | File | `/forum/PostPrivateMessage` | High
55 | File | `/function/login.php` | High
56 | File | `/getcfg.php` | Medium
57 | File | `/goform/aspForm` | High
58 | File | `/goform/RouteStatic` | High
59 | File | `/goform/SafeEmailFilter` | High
60 | File | `/goform/SetOnlineDevName` | High
61 | File | `/home/masterConsole` | High
62 | File | `/hrm/employeeadd.php` | High
63 | File | `/hrm/employeeview.php` | High
64 | ... | ... | ...

There are 562 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.morphisec.com/threat-research-mars-stealer
* https://cert.gov.ua/article/38606
* https://community.blueliv.com/#!/s/628bf72a82df417b9232fc80
* https://gist.github.com/viriback/362a91ed9601ba906d8a17c8102a68bb
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/marsstealer/mars_stealer_iocs_20220407.csv
* https://isc.sans.edu/forums/diary/Arkei+Variants+From+Vidar+to+Mars+Stealer/28468/
* https://tracker.viriback.com/index.php?q=91.92.246.39
* https://tracker.viriback.com/index.php?q=91.92.250.149
* https://tracker.viriback.com/index.php?q=91.92.254.204
* https://tracker.viriback.com/index.php?q=94.232.249.206
* https://tracker.viriback.com/index.php?q=95.164.47.211
* https://tracker.viriback.com/index.php?q=152.89.218.27
* https://tracker.viriback.com/index.php?q=152.89.218.84
* https://tracker.viriback.com/index.php?q=152.89.218.97
* https://tracker.viriback.com/index.php?q=152.89.218.100
* https://tracker.viriback.com/index.php?q=152.89.218.174
* https://tracker.viriback.com/index.php?q=178.208.92.138
* https://www.virustotal.com/gui/file/69779c8531872ce18a47e818dea9e838f240cd9c38781880ef322a447cfd7d83/relations

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
