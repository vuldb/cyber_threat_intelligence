# WannaCryptor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WannaCryptor](https://vuldb.com/?actor.wannacryptor). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wannacryptor](https://vuldb.com/?actor.wannacryptor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WannaCryptor:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WannaCryptor.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.224.174.212](https://vuldb.com/?ip.14.224.174.212) | static.vnpt.vn | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WannaCryptor_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-35, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WannaCryptor. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/admin/aboutus.php` | High
3 | File | `/admin/admin_cl.php?mudi=revPwd` | High
4 | File | `/admin/admin_log.php?clear=1` | High
5 | File | `/admin/admin_widgets.php?action=install/widget=akismet` | High
6 | File | `/admin/config_time_sync.php` | High
7 | File | `/admin/contacts/organizations/edit/2` | High
8 | File | `/admin/dialog/select_images_post.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/robot.php` | High
11 | File | `/admin/system.php` | High
12 | File | `/admin/template/edit` | High
13 | File | `/admins/{adminId}` | High
14 | File | `/api/swaggerui/static` | High
15 | File | `/api/sys/set_passwd` | High
16 | File | `/articles/welcome-to-your-site#comments-head` | High
17 | File | `/bloodrequest.php` | High
18 | File | `/boafrm/formSystemCheck` | High
19 | File | `/buscar_integrada.php` | High
20 | File | `/cgi-bin/alexserv` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/hd_config.cgi` | High
23 | File | `/cgi-bin/photocenter_mgr.cgi` | High
24 | File | `/cgi-bin/tosei_kikai.php` | High
25 | File | `/cgi-bin/webfile_mgr.cgi` | High
26 | File | `/cgi-bin/wlogin.cgi` | High
27 | File | `/classes/Master.php` | High
28 | File | `/classes/Master.php?f=save_package` | High
29 | File | `/contact.php` | Medium
30 | File | `/controllers/add_user.php` | High
31 | File | `/core/config-revisions` | High
32 | File | `/core/tools/delete_place.php` | High
33 | File | `/dcim/power-ports/add/` | High
34 | File | `/debug/pprof` | Medium
35 | File | `/DXR.axd` | Medium
36 | File | `/ecommerce/admin/login.php` | High
37 | File | `/ejbca/ra/cert` | High
38 | File | `/endpoint/add-calorie.php` | High
39 | File | `/endpoint/delete-account.php` | High
40 | File | `/endpoint/update.php` | High
41 | File | `/etc/passwd` | Medium
42 | File | `/files/` | Low
43 | File | `/film-rating.php` | High
44 | File | `/forum/away.php` | High
45 | File | `/goform/formEasySetTimezone` | High
46 | File | `/goform/formSetDomainFilter` | High
47 | File | `/goform/formSetQoS` | High
48 | File | `/goform/formSetWanPPPoE` | High
49 | ... | ... | ...

There are 421 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
