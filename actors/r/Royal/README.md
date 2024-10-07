# Royal - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Royal](https://vuldb.com/?actor.royal). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.royal](https://vuldb.com/?actor.royal)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Royal:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Royal.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.44.42.20](https://vuldb.com/?ip.5.44.42.20) | 4SER-1678212226.ip-ptr.tech | - | High
2 | [5.181.234.58](https://vuldb.com/?ip.5.181.234.58) | - | - | High
3 | [5.188.86.195](https://vuldb.com/?ip.5.188.86.195) | - | - | High
4 | [23.111.114.52](https://vuldb.com/?ip.23.111.114.52) | - | - | High
5 | [41.97.65.51](https://vuldb.com/?ip.41.97.65.51) | - | - | High
6 | [41.100.55.97](https://vuldb.com/?ip.41.100.55.97) | - | - | High
7 | [41.107.77.67](https://vuldb.com/?ip.41.107.77.67) | - | - | High
8 | [41.109.11.80](https://vuldb.com/?ip.41.109.11.80) | - | - | High
9 | [41.251.121.35](https://vuldb.com/?ip.41.251.121.35) | - | - | High
10 | [42.189.12.36](https://vuldb.com/?ip.42.189.12.36) | - | - | High
11 | [45.8.158.104](https://vuldb.com/?ip.45.8.158.104) | - | - | High
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Royal_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-25, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Royal. This data is unique as it uses our predictive model for actor profiling.

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
13 | File | `/api/v2/maps` | Medium
14 | File | `/boafrm/formSystemCheck` | High
15 | File | `/buscar_integrada.php` | High
16 | File | `/cgi-bin/alexserv` | High
17 | File | `/cgi-bin/apkg_mgr.cgi` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/hd_config.cgi` | High
20 | File | `/cgi-bin/photocenter_mgr.cgi` | High
21 | File | `/cgi-bin/tosei_kikai.php` | High
22 | File | `/cgi-bin/webfile_mgr.cgi` | High
23 | File | `/classes/Master.php` | High
24 | File | `/classes/Master.php?f=delete_record` | High
25 | File | `/classes/Master.php?f=save_package` | High
26 | File | `/classes/SystemSettings.php?f=update_settings` | High
27 | File | `/contact.php` | Medium
28 | File | `/controllers/add_user.php` | High
29 | File | `/core/config-revisions` | High
30 | File | `/core/tools/delete_place.php` | High
31 | File | `/dcim/power-ports/add/` | High
32 | File | `/debug/pprof` | Medium
33 | File | `/dtale/chart-data/1` | High
34 | File | `/DXR.axd` | Medium
35 | File | `/ecommerce/admin/login.php` | High
36 | File | `/edit/server` | Medium
37 | File | `/endpoint/add-calorie.php` | High
38 | File | `/endpoint/delete-account.php` | High
39 | File | `/endpoint/delete-todo.php` | High
40 | File | `/endpoint/update.php` | High
41 | File | `/etc/passwd` | Medium
42 | File | `/etc/shadow.sample` | High
43 | File | `/film-rating.php` | High
44 | File | `/foms/routers/place-order.php` | High
45 | File | `/formSysLog` | Medium
46 | File | `/forum/away.php` | High
47 | File | `/goform/qossetting` | High
48 | ... | ... | ...

There are 414 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-061a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
