# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-25, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/aboutus.php` | High
4 | File | `/admin/admin_log.php?clear=1` | High
5 | File | `/admin/admin_widgets.php?action=install/widget=akismet` | High
6 | File | `/admin/config_time_sync.php` | High
7 | File | `/admin/contacts/organizations/edit/2` | High
8 | File | `/admin/dialog/select_images_post.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/modules/product/controller.php?action=add` | High
11 | File | `/admin/robot.php` | High
12 | File | `/admin/system.php` | High
13 | File | `/admins/{adminId}` | High
14 | File | `/api/swaggerui/static` | High
15 | File | `/api/sys/set_passwd` | High
16 | File | `/boafrm/formSystemCheck` | High
17 | File | `/buscar_integrada.php` | High
18 | File | `/cgi-bin/alexserv` | High
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/hd_config.cgi` | High
21 | File | `/cgi-bin/photocenter_mgr.cgi` | High
22 | File | `/cgi-bin/tosei_kikai.php` | High
23 | File | `/cgi-bin/webfile_mgr.cgi` | High
24 | File | `/classes/Master.php` | High
25 | File | `/classes/Master.php?f=save_package` | High
26 | File | `/contact.php` | Medium
27 | File | `/controllers/add_user.php` | High
28 | File | `/core/config-revisions` | High
29 | File | `/core/tools/delete_place.php` | High
30 | File | `/dcim/power-ports/add/` | High
31 | File | `/debug/pprof` | Medium
32 | File | `/DXR.axd` | Medium
33 | File | `/ecommerce/admin/login.php` | High
34 | File | `/edit/server` | Medium
35 | File | `/endpoint/add-calorie.php` | High
36 | File | `/endpoint/delete-account.php` | High
37 | File | `/endpoint/delete-todo.php` | High
38 | File | `/endpoint/update.php` | High
39 | File | `/etc/passwd` | Medium
40 | File | `/files/` | Low
41 | File | `/film-rating.php` | High
42 | File | `/forum/away.php` | High
43 | File | `/goform/formSetDomainFilter` | High
44 | File | `/goform/formSetQoS` | High
45 | File | `/goform/formSetWanPPPoE` | High
46 | File | `/goform/qossetting` | High
47 | File | `/goform/setDeviceSettings` | High
48 | ... | ... | ...

There are 414 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
