# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-25, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/admin/admin_log.php?clear=1` | High
3 | File | `/admin/admin_widgets.php?action=install/widget=akismet` | High
4 | File | `/admin/config_time_sync.php` | High
5 | File | `/admin/contacts/organizations/edit/2` | High
6 | File | `/admin/dialog/select_images_post.php` | High
7 | File | `/admin/login.php` | High
8 | File | `/admin/modules/product/controller.php?action=add` | High
9 | File | `/admin/robot.php` | High
10 | File | `/admin/system.php` | High
11 | File | `/admins/{adminId}` | High
12 | File | `/api/swaggerui/static` | High
13 | File | `/api/sys/set_passwd` | High
14 | File | `/api/v1` | Low
15 | File | `/boafrm/formSystemCheck` | High
16 | File | `/buscar_integrada.php` | High
17 | File | `/cgi-bin/alexserv` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/hd_config.cgi` | High
20 | File | `/cgi-bin/photocenter_mgr.cgi` | High
21 | File | `/cgi-bin/tosei_kikai.php` | High
22 | File | `/cgi-bin/webfile_mgr.cgi` | High
23 | File | `/classes/Master.php` | High
24 | File | `/classes/Master.php?f=save_package` | High
25 | File | `/contact.php` | Medium
26 | File | `/controllers/add_user.php` | High
27 | File | `/core/config-revisions` | High
28 | File | `/core/tools/delete_place.php` | High
29 | File | `/dcim/power-ports/add/` | High
30 | File | `/debug/pprof` | Medium
31 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
32 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
33 | File | `/DXR.axd` | Medium
34 | File | `/ecommerce/admin/login.php` | High
35 | File | `/edit/server` | Medium
36 | File | `/endpoint/add-calorie.php` | High
37 | File | `/endpoint/delete-account.php` | High
38 | File | `/endpoint/delete-todo.php` | High
39 | File | `/endpoint/update.php` | High
40 | File | `/etc/passwd` | Medium
41 | File | `/film-rating.php` | High
42 | File | `/forum/away.php` | High
43 | File | `/goform/qossetting` | High
44 | File | `/guestbook` | Medium
45 | File | `/hardware` | Medium
46 | File | `/ims/login.php` | High
47 | ... | ... | ...

There are 404 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
