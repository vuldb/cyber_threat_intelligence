# Alien - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Alien](https://vuldb.com/?actor.alien). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.alien](https://vuldb.com/?actor.alien)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Alien:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Alien.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.75.176.47](https://vuldb.com/?ip.5.75.176.47) | static.47.176.75.5.clients.your-server.de | - | High
2 | [5.78.74.58](https://vuldb.com/?ip.5.78.74.58) | static.58.74.78.5.clients.your-server.de | - | High
3 | [5.78.105.58](https://vuldb.com/?ip.5.78.105.58) | static.58.105.78.5.clients.your-server.de | - | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Alien_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Alien. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\IDriveWindows` | High
2 | File | `/.dbus-keyrings` | High
3 | File | `/.env` | Low
4 | File | `/admin` | Low
5 | File | `/admin.php?controller=admin_commonuser` | High
6 | File | `/admin/?page=inmates/view_inmate` | High
7 | File | `/admin/?page=user/list` | High
8 | File | `/admin/content/index` | High
9 | File | `/admin/convert/export_z3950_new.php` | High
10 | File | `/admin/edit_product.php` | High
11 | File | `/admin/reg.php` | High
12 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
13 | File | `/ajax/update_certificate` | High
14 | File | `/api/admin/system/store/order/list` | High
15 | File | `/api/jmeter/download/files` | High
16 | File | `/cgi-bin/wlogin.cgi` | High
17 | File | `/configs/application.ini` | High
18 | File | `/customs/loan_by_class.php?reportView` | High
19 | File | `/ecommerce/admin/settings/setDiscount.php` | High
20 | File | `/editor/index.php` | High
21 | File | `/forum/away.php` | High
22 | File | `/fos/admin/ajax.php` | High
23 | File | `/goform/WifiBasicSet` | High
24 | File | `/intern/controller.php` | High
25 | File | `/LEPTON_stable_2.2.2/upload/account/logout.php` | High
26 | File | `/master/core/PostHandler.php` | High
27 | ... | ... | ...

There are 230 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
