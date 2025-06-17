# xStart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xStart](https://vuldb.com/?actor.xstart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xstart](https://vuldb.com/?actor.xstart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xStart:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [AL](https://vuldb.com/?country.al)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xStart.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.210.23.243](https://vuldb.com/?ip.8.210.23.243) | - | - | High
2 | [8.210.29.183](https://vuldb.com/?ip.8.210.29.183) | - | - | High
3 | [8.210.43.38](https://vuldb.com/?ip.8.210.43.38) | - | - | High
4 | [8.210.66.64](https://vuldb.com/?ip.8.210.66.64) | - | - | High
5 | [8.210.74.149](https://vuldb.com/?ip.8.210.74.149) | - | - | High
6 | [8.210.120.8](https://vuldb.com/?ip.8.210.120.8) | - | - | High
7 | [8.210.130.151](https://vuldb.com/?ip.8.210.130.151) | - | - | High
8 | [34.92.61.61](https://vuldb.com/?ip.34.92.61.61) | 61.61.92.34.bc.googleusercontent.com | - | Medium
9 | [36.99.196.223](https://vuldb.com/?ip.36.99.196.223) | - | - | High
10 | [39.99.245.93](https://vuldb.com/?ip.39.99.245.93) | - | - | High
11 | [39.102.48.190](https://vuldb.com/?ip.39.102.48.190) | - | - | High
12 | [42.48.120.127](https://vuldb.com/?ip.42.48.120.127) | - | - | High
13 | ... | ... | ... | ...

There are 47 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xStart_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xStart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/admin-manage-user.php` | High
3 | File | `/admin/?setting-base.htm` | High
4 | File | `/admin/add-category.php` | High
5 | File | `/admin/edit-admin.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/list_resource_icon.php?action=delete` | High
8 | File | `/admin/singlelogin.php` | High
9 | File | `/admin/update_s6.php` | High
10 | File | `/admin/view-patient.php` | High
11 | File | `/ajax/check_medicine_name.php` | High
12 | File | `/api/blade-user/export-user` | High
13 | File | `/api/geojson` | Medium
14 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
15 | File | `/api/sys/login` | High
16 | File | `/bcms/admin/?page=user/manage_user` | High
17 | File | `/book_list.php` | High
18 | File | `/cgi-bin/ExportAllSettings.sh` | High
19 | File | `/cgi-bin/kerbynet` | High
20 | File | `/cgi-bin/nas_sharing.cgi` | High
21 | File | `/cgi-bin/webviewer_login_page` | High
22 | File | `/cgi/networkDiag.cgi` | High
23 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
24 | File | `/cms/category/list` | High
25 | File | `/cms/classes/Users.php?f=delete_client` | High
26 | File | `/com/esafenet/servlet/policy/HookService.java` | High
27 | File | `/controller/OnlinePreviewController.java` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/designer/add/layout` | High
30 | File | `/em/console/logon/logon` | High
31 | File | `/env` | Low
32 | File | `/file` | Low
33 | File | `/forum/away.php` | High
34 | File | `/general/email/inbox/delete_webmail.php` | High
35 | File | `/goform/SetNetControlList` | High
36 | File | `/inc/jquery/uploadify/uploadify.php` | High
37 | File | `/list` | Low
38 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
39 | File | `/net/sched/cls_fw.c` | High
40 | File | `/nidp/idff/sso` | High
41 | File | `/oews/admin/` | Medium
42 | File | `/patient/appointment.php` | High
43 | ... | ... | ...

There are 367 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/PwCUK-CTO/SANSCTISummit2021-xStart/blob/main/indicators/Indicators_IPs.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
