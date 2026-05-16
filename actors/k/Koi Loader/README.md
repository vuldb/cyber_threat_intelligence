# Koi Loader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Koi Loader](https://vuldb.com/?actor.koi_loader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.koi_loader](https://vuldb.com/?actor.koi_loader)

## Campaigns

The following _campaigns_ are known and can be associated with Koi Loader:

* Koi Stealer

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Koi Loader:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Koi Loader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.15.233](https://vuldb.com/?ip.2.58.15.233) | - | - | High
2 | [5.101.84.22](https://vuldb.com/?ip.5.101.84.22) | vm20964.hyper.hosting | - | High
3 | [37.49.226.113](https://vuldb.com/?ip.37.49.226.113) | - | - | High
4 | [45.14.227.125](https://vuldb.com/?ip.45.14.227.125) | static.pwxs.net | - | High
5 | [45.90.58.1](https://vuldb.com/?ip.45.90.58.1) | vds1337517.hosted-by-itldc.com | Koi Stealer | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Koi Loader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Koi Loader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
3 | File | `.authlie` | Medium
4 | File | `.htaccess` | Medium
5 | File | `/+CSCOE+/logon.html` | High
6 | File | `/?p=products` | Medium
7 | File | `/add_contestant.php` | High
8 | File | `/admin/admin_feature.php` | High
9 | File | `/admin/goods/update` | High
10 | File | `/admin/role` | Medium
11 | File | `/admin/settings/sites/new` | High
12 | File | `/admin/user-bookings.php` | High
13 | File | `/advanced/adv_dns.xgi` | High
14 | File | `/ajax.php?action=save_station` | High
15 | File | `/alphaware/details.php` | High
16 | File | `/api/system/cluster_config/` | High
17 | File | `/api /v3/auth` | High
18 | File | `/boafrm/formTracerouteDiagnosticRun` | High
19 | File | `/common/info.cgi` | High
20 | File | `/conv/community` | High
21 | File | `/customer_support/ajax.php?action=save_ticket` | High
22 | File | `/del.php` | Medium
23 | File | `/delete.php` | Medium
24 | File | `/editAgent.php` | High
25 | File | `/editar-cliente.php` | High
26 | File | `/folder/list` | Medium
27 | File | `/forms/nslookupHandler` | High
28 | File | `/forum/away.php` | High
29 | File | `/goform/formAutoDetecWAN_wizard4` | High
30 | File | `/goform/GetNewDir` | High
31 | File | `/goform/right_now_d` | High
32 | File | `/goform/RP_checkFWByBBS` | High
33 | File | `/goform/setAdPushInfo` | High
34 | File | `/group/comment` | High
35 | File | `/home/home_parent.xgi` | High
36 | File | `/html/matPat/adicionar_tipoEntrada.php` | High
37 | File | `/index.php?menu=asterisk_cli` | High
38 | File | `/index.php?r=admin/database/index/updatesurveylocalesettings_generalsettings` | High
39 | File | `/index/ajax/lang` | High
40 | File | `/kmf/folder.jsp` | High
41 | File | `/lookin/info` | Medium
42 | File | `/manage_inv.php` | High
43 | File | `/monitoring` | Medium
44 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
45 | File | `/php_action/editUser.php` | High
46 | ... | ... | ...

There are 402 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/09ef17dc4284a8d1a8b937354bd8137aa9c0d98bffb897bd891ccff854484e43/
* https://bazaar.abuse.ch/sample/7d7319a069e4ce6453f554bd52c6103db586c3615e8f1bbc59748b11b2c9a926/
* https://bazaar.abuse.ch/sample/80ee52a320d812693f2e3ba097f80ad08544cd6db17f33c25848cc15550d4d3d/
* https://bazaar.abuse.ch/sample/311d17e119c43e123a8dc7178ec01366835e6b59300ac1c72b7dd2b5e7aaa9c0/
* https://bazaar.abuse.ch/sample/dd56d8d92b125dc1cbd12a164274adf032f2053bfa5ac48c39e645fa1b61400f/
* https://github.com/esThreatIntelligence/iocs/blob/main/Koi/iocs_4-4-2024.txt
* https://malware-traffic-analysis.net/2025/01/23/index.html
* https://threatfox.abuse.ch
* https://tria.ge/240901-w33m7aygje
* https://www.malware-traffic-analysis.net/2024/04/04/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
