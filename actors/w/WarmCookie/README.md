# WarmCookie - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WarmCookie](https://vuldb.com/?actor.warmcookie). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.warmcookie](https://vuldb.com/?actor.warmcookie)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WarmCookie:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WarmCookie.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [38.180.91.117](https://vuldb.com/?ip.38.180.91.117) | - | - | High
2 | [45.9.74.135](https://vuldb.com/?ip.45.9.74.135) | - | - | High
3 | [45.11.59.230](https://vuldb.com/?ip.45.11.59.230) | mail1.yhszxddb.com | - | High
4 | [45.11.59.231](https://vuldb.com/?ip.45.11.59.231) | mail-bin-f985.stepupmarketting.com | - | High
5 | [45.11.59.247](https://vuldb.com/?ip.45.11.59.247) | dedicated.sollutium.com | - | High
6 | [45.155.249.102](https://vuldb.com/?ip.45.155.249.102) | - | - | High
7 | [62.60.238.115](https://vuldb.com/?ip.62.60.238.115) | jacketkangaroo.aeza.network | - | High
8 | [65.38.120.80](https://vuldb.com/?ip.65.38.120.80) | - | - | High
9 | [72.5.42.224](https://vuldb.com/?ip.72.5.42.224) | - | - | High
10 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WarmCookie_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WarmCookie. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/?import` | Medium
3 | File | `/admin/app/product.php` | High
4 | File | `/admin/create_product.php` | High
5 | File | `/admin/edit_supplier.php` | High
6 | File | `/admin/emp-profile-avatar.php` | High
7 | File | `/admin/process_category_edit.php` | High
8 | File | `/api/swaggerui/static` | High
9 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
10 | File | `/boafrm/formMapDelDevice` | High
11 | File | `/cgi-bin/hd_config.cgi` | High
12 | File | `/cgi-bin/nas_sharing.cgi` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/client-data/<client_id>/collections/##/usermgmt.xml` | High
15 | File | `/common/info.cgi` | High
16 | File | `/dataSet/testTransform;swagger-ui` | High
17 | File | `/debug/pprof` | Medium
18 | File | `/dental_form.php` | High
19 | File | `/edit-computer-detail.php` | High
20 | File | `/expedit.php` | Medium
21 | File | `/export` | Low
22 | File | `/goform/SetSpeedWan` | High
23 | File | `/hedwig.cgi` | Medium
24 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
25 | File | `/interceptor/OutgoingChainInterceptor.java` | High
26 | File | `/Interface/DevManage/EC.php?cmd=upload` | High
27 | ... | ... | ...

There are 224 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/Cisco-Talos/IOCs/blob/main/2024/10/warmcookie-analysis.txt
* https://search.censys.io/hosts/72.5.42.224
* https://threatfox.abuse.ch
* https://www.darkreading.com/cyberattacks-data-breaches/warmcookie-cyberattackers-backdoor-initial-access

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
