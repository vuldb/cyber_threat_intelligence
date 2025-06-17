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
1 | [45.90.58.1](https://vuldb.com/?ip.45.90.58.1) | vds1337517.hosted-by-itldc.com | Koi Stealer | High
2 | [78.142.29.118](https://vuldb.com/?ip.78.142.29.118) | - | - | High
3 | [79.124.78.148](https://vuldb.com/?ip.79.124.78.148) | xqn1.jellycat.online | - | High
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

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

There are 21 more TTP items available. Please use our online service to access the data.

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
7 | File | `/admin/settings/sites/new` | High
8 | File | `/admin_giant/` | High
9 | File | `/advanced/adv_dns.xgi` | High
10 | File | `/api/system/cluster_config/` | High
11 | File | `/api /v3/auth` | High
12 | File | `/common/info.cgi` | High
13 | File | `/customer_support/ajax.php?action=save_ticket` | High
14 | File | `/editar-cliente.php` | High
15 | File | `/folder/list` | Medium
16 | File | `/forms/nslookupHandler` | High
17 | File | `/forum/away.php` | High
18 | File | `/goform/GetNewDir` | High
19 | File | `/goform/right_now_d` | High
20 | File | `/group/comment` | High
21 | File | `/home/home_parent.xgi` | High
22 | File | `/index.php?r=admin/database/index/updatesurveylocalesettings_generalsettings` | High
23 | File | `/index/ajax/lang` | High
24 | File | `/lookin/info` | Medium
25 | File | `/manage_inv.php` | High
26 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
27 | File | `/plugins/servlet/jira-blockers/` | High
28 | File | `/register.php` | High
29 | File | `/request.php` | Medium
30 | File | `/sessions/sess_<sessionid>` | High
31 | File | `/status/status_log.sys` | High
32 | File | `/themes/<php_file_name>` | High
33 | File | `/tmp` | Low
34 | File | `/uncpath/` | Medium
35 | File | `/upload` | Low
36 | File | `/usr/bin/shutter` | High
37 | File | `/zm/index.php` | High
38 | File | `adclick.php` | Medium
39 | File | `addtocart.asp` | High
40 | File | `admin-ajax.php` | High
41 | File | `admin.php` | Medium
42 | ... | ... | ...

There are 358 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/09ef17dc4284a8d1a8b937354bd8137aa9c0d98bffb897bd891ccff854484e43/
* https://bazaar.abuse.ch/sample/7d7319a069e4ce6453f554bd52c6103db586c3615e8f1bbc59748b11b2c9a926/
* https://bazaar.abuse.ch/sample/311d17e119c43e123a8dc7178ec01366835e6b59300ac1c72b7dd2b5e7aaa9c0/
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

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
